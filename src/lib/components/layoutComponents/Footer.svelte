<script>
  import cpromlogo from '$lib/images/logos/cprom-transparent.png';
</script>

<footer class="relative bg-gradient-to-br from-gray-900 to-gray-800 text-white overflow-hidden">
  <!-- Animated background elements -->
  <div class="absolute top-0 left-0 w-full h-full overflow-hidden opacity-20">
    <div class="absolute top-20 left-10 w-32 h-32 bg-blue-500 rounded-full filter blur-3xl animate-float1"></div>
    <div class="absolute top-40 right-20 w-40 h-40 bg-purple-500 rounded-full filter blur-3xl animate-float2"></div>
    <div class="absolute bottom-10 left-1/2 w-48 h-48 bg-cyan-500 rounded-full filter blur-3xl animate-float3"></div>
  </div>

  <!-- Main footer content -->
  <div class="relative max-w-7xl mx-auto px-6 py-16 sm:py-20 lg:px-8">
    <!-- Grid layout -->
    <div class="grid grid-cols-1 md:grid-cols-3  gap-12">
      
      <!-- Logo/Name section with interactive effect -->
      <div class="group">
        <div class="flex items-center space-x-2 mb-6">
          <div class="w-10 h-10 bg-white rounded-lg flex items-center justify-center transform group-hover:rotate-12 transition duration-500">
            <img src={cpromlogo} class="" alt="Cadeaux Prom Logo" />
          </div>
          <h2 class="text-2xl font-bold  text-white">
            Cadeaux Prom
          </h2>
        </div>
        <p class="text-gray-300 mb-6">Cadeaux personnalisés pour toutes vos occasions.</p>
        
        <!-- Social media with hover glow -->
        <div class="flex space-x-4">
          <a href="#" class="w-10 h-10 rounded-full bg-gray-800 flex items-center justify-center hover:bg-blue-500 hover:shadow-lg hover:shadow-blue-500/30 transition-all duration-300">
            <svg class="w-6 h-6 text-white" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="currentColor" viewBox="0 0 24 24">
              <path fill-rule="evenodd" d="M13.135 6H15V3h-1.865a4.147 4.147 0 0 0-4.142 4.142V9H7v3h2v9.938h3V12h2.021l.592-3H12V6.591A.6.6 0 0 1 12.592 6h.543Z" clip-rule="evenodd"/>
            </svg>
          </a>


          <a href="#" class="w-10 h-10 rounded-full bg-gray-800 flex items-center justify-center hover:bg-purple-500 hover:shadow-lg hover:shadow-purple-500/30 transition-all duration-300">
            <svg class="w-6 h-6 text-white" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="none" viewBox="0 0 24 24">
              <path fill="currentColor" fill-rule="evenodd" d="M3 8a5 5 0 0 1 5-5h8a5 5 0 0 1 5 5v8a5 5 0 0 1-5 5H8a5 5 0 0 1-5-5V8Zm5-3a3 3 0 0 0-3 3v8a3 3 0 0 0 3 3h8a3 3 0 0 0 3-3V8a3 3 0 0 0-3-3H8Zm7.597 2.214a1 1 0 0 1 1-1h.01a1 1 0 1 1 0 2h-.01a1 1 0 0 1-1-1ZM12 9a3 3 0 1 0 0 6 3 3 0 0 0 0-6Zm-5 3a5 5 0 1 1 10 0 5 5 0 0 1-10 0Z" clip-rule="evenodd"/>
            </svg>
          </a>
        </div>
      </div>

      <!-- Quick links with hover effect -->
      <div>
        <h3 class="text-lg font-semibold mb-6 relative inline-block">
          <span class="relative z-10">Liens rapides</span>
          <span class="absolute bottom-0 left-0 w-full h-1 bg-blue-500 transform scale-x-0 group-hover:scale-x-100 transition-transform origin-left duration-300"></span>
        </h3>
        <ul class="space-y-3">
          <li><a href="#" class="text-gray-300 hover:text-white hover:pl-2 transition-all duration-300 flex items-center">
            <span class="w-1 h-1 bg-blue-500 rounded-full mr-2 opacity-0 group-hover:opacity-100 transition duration-300"></span>
            Accueil</a></li>
          <li><a href="#" class="text-gray-300 hover:text-white hover:pl-2 transition-all duration-300 flex items-center">
            <span class="w-1 h-1 bg-blue-500 rounded-full mr-2 opacity-0 group-hover:opacity-100 transition duration-300"></span>
            Cadeaux</a></li>
          <li><a href="#" class="text-gray-300 hover:text-white hover:pl-2 transition-all duration-300 flex items-center">
            <span class="w-1 h-1 bg-blue-500 rounded-full mr-2 opacity-0 group-hover:opacity-100 transition duration-300"></span>
            Articles</a></li>
          <li><a href="#" class="text-gray-300 hover:text-white hover:pl-2 transition-all duration-300 flex items-center">
            <span class="w-1 h-1 bg-blue-500 rounded-full mr-2 opacity-0 group-hover:opacity-100 transition duration-300"></span>
            Packs</a></li>
        </ul>
      </div>

      <!-- Contact info with animated icons -->
      <div>
        <h3 class="text-lg font-semibold mb-6">Contactez-nous</h3>
        <ul class="space-y-4">
          <li class="flex items-start">
            <div class="flex-shrink-0 mt-1">
              <div class="w-8 h-8 bg-blue-500/20 rounded-full flex items-center justify-center animate-pulse">
                <svg class="w-4 h-4 text-blue-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path>
                </svg>
              </div>
            </div>
            <div class="ml-3">
              <p class="text-sm text-gray-300">E-mail</p>
              <a href="mailto:cadeauxprom@gmail.com" class="text-white hover:text-blue-400 transition">cadeauxprom@gmail.com</a>
            </div>
          </li>
          <li class="flex items-start">
            <div class="flex-shrink-0 mt-1">
              <div class="w-8 h-8 bg-blue-500/20 rounded-full flex items-center justify-center animate-pulse" style="animation-delay: 0.2s">
                <svg class="w-4 h-4 text-blue-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"></path>
                </svg>
              </div>
            </div>
            <div class="ml-3">
              <p class="text-sm text-gray-300">Téléphone</p>
              <a href="tel:+21698567801" class="text-white hover:text-blue-400 transition">98 567 801</a>
            </div>
          </li>
        </ul>
      </div>

      <!-- Newsletter with floating input -->

    </div>

    <!-- Bottom section with animated copyright -->
    <div class="mt-16 pt-8 border-t border-gray-800 flex flex-col md:flex-row justify-between items-center">
      <p class="text-gray-400 text-sm mb-4 md:mb-0">
        &copy; <span id="year" class="text-blue-400"></span> Cadeaux Prom. Tous droits réservés.
      </p>
      <div class="flex space-x-6">
        <a href="#" class="text-gray-400 hover:text-white transition">Politique de confidentialité</a>
        <a href="#" class="text-gray-400 hover:text-white transition">Conditions d’utilisation</a>
      </div>
    </div>
  </div>

  <!-- Floating orb that follows cursor -->
  <div class="orb absolute w-64 h-64 rounded-full bg-gradient-to-r from-blue-500/10 to-purple-500/10 filter blur-3xl pointer-events-none"></div>

  <style>
    /* Animations */
    @keyframes float1 {
      0%, 100% { transform: translate(0, 0); }
      50% { transform: translate(20px, 20px); }
    }
    @keyframes float2 {
      0%, 100% { transform: translate(0, 0); }
      50% { transform: translate(-15px, 15px); }
    }
    @keyframes float3 {
      0%, 100% { transform: translate(0, 0); }
      50% { transform: translate(0, -20px); }
    }
    .animate-float1 { animation: float1 8s ease-in-out infinite; }
    .animate-float2 { animation: float2 10s ease-in-out infinite; }
    .animate-float3 { animation: float3 12s ease-in-out infinite; }

    /* Orb follow effect */
    .orb {
      transform: translate(-50%, -50%);
      opacity: 0.3;
      transition: transform 0.1s ease-out;
    }
  </style>

  <script>
    // Update copyright year
    document.getElementById('year').textContent = new Date().getFullYear();

    // Mouse follow orb effect
    document.addEventListener('mousemove', (e) => {
      const orb = document.querySelector('.orb');
      orb.style.left = `${e.clientX}px`;
      orb.style.top = `${e.clientY}px`;
    });
  </script>
</footer>