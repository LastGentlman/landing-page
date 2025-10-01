<script lang="ts">
  import Header from './lib/Header.svelte'
</script>

<main>
  <Header />

  <!-- Hero Section -->
  <section class="min-h-screen flex items-center justify-center bg-gradient-to-br from-gray-50 to-gray-100">
    <div class="max-w-7xl mx-auto px-6 py-24 text-center">
      <h1 class="text-6xl md:text-7xl font-bold text-gray-900 mb-6 tracking-tight">
        Gestiona tus pedidos
        <span class="block text-transparent bg-clip-text bg-gradient-to-r from-blue-600 to-purple-600">
          de forma simple
        </span>
      </h1>

      <p class="text-xl md:text-2xl text-gray-600 mb-12 max-w-3xl mx-auto">
        La plataforma todo-en-uno para negocios que quieren llevar el control de sus pedidos,
        clientes y productos de manera eficiente.
      </p>

      <div class="flex flex-col sm:flex-row gap-4 justify-center items-center">
        <a
          href="https://app.pedidolist.com"
          class="inline-flex items-center px-8 py-4 bg-gray-900 text-white font-semibold rounded-lg hover:bg-gray-800 transition-all transform hover:scale-105 shadow-lg"
        >
          Comenzar gratis
          <svg class="w-5 h-5 ml-2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 7l5 5m0 0l-5 5m5-5H6" />
          </svg>
        </a>

        <a
          href="#features"
          class="inline-flex items-center px-8 py-4 bg-white text-gray-900 font-semibold rounded-lg hover:bg-gray-50 transition-all border-2 border-gray-200"
        >
          Ver características
        </a>
      </div>

      <p class="mt-8 text-sm text-gray-500">
        Sin tarjeta de crédito requerida • Prueba gratuita de 14 días
      </p>
    </div>
  </section>

  <!-- Features Section -->
  <section id="features" class="py-24 bg-white">
    <div class="max-w-7xl mx-auto px-6">
      <div class="text-center mb-16">
        <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-4">
          Todo lo que necesitas
        </h2>
        <p class="text-xl text-gray-600 max-w-2xl mx-auto">
          Herramientas poderosas diseñadas para hacer crecer tu negocio
        </p>
      </div>

      <div class="grid md:grid-cols-3 gap-12">
        <!-- Feature 1 -->
        <div class="text-center">
          <div class="inline-flex items-center justify-center w-16 h-16 bg-blue-100 rounded-full mb-6">
            <svg class="w-8 h-8 text-blue-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5H7a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2V7a2 2 0 00-2-2h-2M9 5a2 2 0 002 2h2a2 2 0 002-2M9 5a2 2 0 012-2h2a2 2 0 012 2" />
            </svg>
          </div>
          <h3 class="text-2xl font-bold text-gray-900 mb-3">Gestión de Pedidos</h3>
          <p class="text-gray-600">
            Organiza y da seguimiento a todos tus pedidos en un solo lugar. Actualiza estados en tiempo real.
          </p>
        </div>

        <!-- Feature 2 -->
        <div class="text-center">
          <div class="inline-flex items-center justify-center w-16 h-16 bg-purple-100 rounded-full mb-6">
            <svg class="w-8 h-8 text-purple-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0zm6 3a2 2 0 11-4 0 2 2 0 014 0zM7 10a2 2 0 11-4 0 2 2 0 014 0z" />
            </svg>
          </div>
          <h3 class="text-2xl font-bold text-gray-900 mb-3">Control de Clientes</h3>
          <p class="text-gray-600">
            Mantén un registro completo de tus clientes y su historial de compras.
          </p>
        </div>

        <!-- Feature 3 -->
        <div class="text-center">
          <div class="inline-flex items-center justify-center w-16 h-16 bg-green-100 rounded-full mb-6">
            <svg class="w-8 h-8 text-green-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M20 7l-8-4-8 4m16 0l-8 4m8-4v10l-8 4m0-10L4 7m8 4v10M4 7v10l8 4" />
            </svg>
          </div>
          <h3 class="text-2xl font-bold text-gray-900 mb-3">Inventario de Productos</h3>
          <p class="text-gray-600">
            Administra tu catálogo de productos con imágenes, precios y stock actualizado.
          </p>
        </div>
      </div>
    </div>
  </section>

  <!-- Pricing Section -->
  <section id="pricing" class="py-24 bg-gray-50">
    <div class="max-w-7xl mx-auto px-6">
      <div class="text-center mb-16">
        <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-4">
          Precios simples y transparentes
        </h2>
        <p class="text-xl text-gray-600 max-w-2xl mx-auto">
          Comienza gratis y crece a tu ritmo
        </p>
      </div>

      <div class="max-w-lg mx-auto">
        <div class="bg-white rounded-2xl shadow-xl p-8 border-2 border-gray-900">
          <div class="text-center mb-8">
            <h3 class="text-2xl font-bold text-gray-900 mb-2">Plan Profesional</h3>
            <div class="flex items-baseline justify-center">
              <span class="text-5xl font-bold text-gray-900">$29</span>
              <span class="text-gray-600 ml-2">/mes</span>
            </div>
            <p class="text-gray-600 mt-2">14 días de prueba gratuita</p>
          </div>

          <ul class="space-y-4 mb-8">
            <li class="flex items-center">
              <svg class="w-5 h-5 text-green-500 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
              </svg>
              <span class="text-gray-700">Pedidos ilimitados</span>
            </li>
            <li class="flex items-center">
              <svg class="w-5 h-5 text-green-500 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
              </svg>
              <span class="text-gray-700">Clientes ilimitados</span>
            </li>
            <li class="flex items-center">
              <svg class="w-5 h-5 text-green-500 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
              </svg>
              <span class="text-gray-700">Productos ilimitados</span>
            </li>
            <li class="flex items-center">
              <svg class="w-5 h-5 text-green-500 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
              </svg>
              <span class="text-gray-700">Soporte prioritario</span>
            </li>
            <li class="flex items-center">
              <svg class="w-5 h-5 text-green-500 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
              </svg>
              <span class="text-gray-700">Modo offline</span>
            </li>
          </ul>

          <a
            href="https://app.pedidolist.com"
            class="block w-full text-center px-8 py-4 bg-gray-900 text-white font-semibold rounded-lg hover:bg-gray-800 transition-all transform hover:scale-105"
          >
            Comenzar ahora
          </a>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="py-24 bg-white">
    <div class="max-w-4xl mx-auto px-6 text-center">
      <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-6">
        ¿Listo para comenzar?
      </h2>
      <p class="text-xl text-gray-600 mb-8">
        Únete a cientos de negocios que ya confían en PedidoList
      </p>
      <a
        href="https://app.pedidolist.com"
        class="inline-flex items-center px-8 py-4 bg-gray-900 text-white font-semibold rounded-lg hover:bg-gray-800 transition-all transform hover:scale-105 shadow-lg"
      >
        Comenzar gratis
        <svg class="w-5 h-5 ml-2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 7l5 5m0 0l-5 5m5-5H6" />
        </svg>
      </a>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-900 text-white py-12">
    <div class="max-w-7xl mx-auto px-6">
      <div class="grid md:grid-cols-3 gap-8 mb-8">
        <div>
          <h3 class="text-2xl font-bold mb-4">PedidoList</h3>
          <p class="text-gray-400">
            Gestión de pedidos simple y eficiente para tu negocio.
          </p>
        </div>

        <div>
          <h4 class="font-semibold mb-4">Enlaces</h4>
          <ul class="space-y-2 text-gray-400">
            <li><a href="#features" class="hover:text-white transition-colors">Características</a></li>
            <li><a href="#pricing" class="hover:text-white transition-colors">Precios</a></li>
            <li><a href="https://app.pedidolist.com" class="hover:text-white transition-colors">App</a></li>
          </ul>
        </div>

        <div>
          <h4 class="font-semibold mb-4">Contacto</h4>
          <ul class="space-y-2 text-gray-400">
            <li><a href="mailto:soporte@pedidolist.com" class="hover:text-white transition-colors">soporte@pedidolist.com</a></li>
          </ul>
        </div>
      </div>

      <div class="border-t border-gray-800 pt-8 text-center text-gray-400">
        <p>&copy; {new Date().getFullYear()} PedidoList. Todos los derechos reservados.</p>
      </div>
    </div>
  </footer>
</main>

<style>
  :global(html) {
    scroll-behavior: smooth;
  }
</style>
