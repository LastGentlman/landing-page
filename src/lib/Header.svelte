<script lang="ts">
  // Simple header for landing page - no authentication needed
  let mobileMenuOpen = false;

  function toggleMobileMenu() {
    mobileMenuOpen = !mobileMenuOpen;
  }
</script>

<header class="sticky top-0 bg-white/80 backdrop-blur-sm border-b border-gray-100 z-50 transition-all duration-300">
  <div class="w-full px-6 py-4">
    <!-- Mobile Layout -->
    <div class="flex items-center justify-between md:hidden">
      <!-- Logo - Left aligned -->
      <div class="text-2xl font-bold tracking-tight">
        <a
          href="https://pedidolist.com"
          class="text-gray-900 hover:text-gray-700 transition-colors duration-300"
        >
          PedidoList
        </a>
      </div>

      <!-- Mobile Menu Button -->
      <button
        on:click={toggleMobileMenu}
        class="text-gray-900 hover:text-gray-700"
        aria-label="Toggle menu"
      >
        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
        </svg>
      </button>
    </div>

    <!-- Desktop Layout -->
    <div class="hidden md:grid grid-cols-3 items-center w-full">
      <!-- Logo - Left aligned -->
      <div class="text-2xl font-bold tracking-tight justify-self-start">
        <a
          href="https://pedidolist.com"
          class="text-gray-900 hover:text-gray-700 transition-colors duration-300"
        >
          PedidoList
        </a>
      </div>

      <!-- Desktop Navigation - Center aligned -->
      <nav class="justify-self-center">
        <div class="flex items-center space-x-8">
          <a
            href="#features"
            class="font-medium text-gray-600 hover:text-gray-900 transition-colors duration-300 py-2 relative group"
          >
            Características
            <span class="absolute bottom-0 left-0 w-0 h-0.5 bg-gray-900 transition-all duration-300 group-hover:w-full"></span>
          </a>

          <a
            href="#pricing"
            class="font-medium text-gray-600 hover:text-gray-900 transition-colors duration-300 py-2 relative group"
          >
            Precios
            <span class="absolute bottom-0 left-0 w-0 h-0.5 bg-gray-900 transition-all duration-300 group-hover:w-full"></span>
          </a>

          <a
            href="#contact"
            class="font-medium text-gray-600 hover:text-gray-900 transition-colors duration-300 py-2 relative group"
          >
            Contacto
            <span class="absolute bottom-0 left-0 w-0 h-0.5 bg-gray-900 transition-all duration-300 group-hover:w-full"></span>
          </a>
        </div>
      </nav>

      <!-- CTA Button - Right aligned -->
      <div class="justify-self-end">
        <a
          href="https://app.pedidolist.com"
          class="inline-flex items-center px-6 py-2 bg-gray-900 text-white font-medium rounded-lg hover:bg-gray-800 transition-all transform hover:scale-105"
        >
          Comenzar
        </a>
      </div>
    </div>
  </div>

  <!-- Mobile Menu Dropdown -->
  {#if mobileMenuOpen}
    <div class="md:hidden border-t border-gray-100 py-4 px-6 space-y-4 bg-white">
      <a
        href="#features"
        class="block font-medium text-gray-600 hover:text-gray-900 transition-colors py-2"
        on:click={toggleMobileMenu}
      >
        Características
      </a>
      <a
        href="#pricing"
        class="block font-medium text-gray-600 hover:text-gray-900 transition-colors py-2"
        on:click={toggleMobileMenu}
      >
        Precios
      </a>
      <a
        href="#contact"
        class="block font-medium text-gray-600 hover:text-gray-900 transition-colors py-2"
        on:click={toggleMobileMenu}
      >
        Contacto
      </a>
      <a
        href="https://app.pedidolist.com"
        class="block w-full text-center px-6 py-2 bg-gray-900 text-white font-medium rounded-lg hover:bg-gray-800 transition-all"
      >
        Comenzar
      </a>
    </div>
  {/if}
</header>
