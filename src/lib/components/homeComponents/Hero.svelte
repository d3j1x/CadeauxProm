<section class="relative bg-white dark:bg-gray-900">
  <!-- Background decoration -->
  <div class="absolute inset-0 -z-10">
    <div class="h-full w-full bg-gradient-to-r from-pink-200 via-purple-200 to-blue-200 dark:from-gray-800 dark:via-gray-900 dark:to-black opacity-40"></div>
  </div>

  <div class="max-w-7xl mx-auto px-6 lg:px-12 py-20 flex flex-col lg:flex-row items-center gap-12">
    <!-- Texte -->
    <div class="flex-1 text-center lg:text-left">
      <h1 class="text-4xl sm:text-5xl lg:text-6xl font-extrabold leading-tight text-gray-900 dark:text-white">
        Cadeaux <span class="text-pink-600 dark:text-pink-400">Prom</span>
      </h1>
      <p class="mt-6 text-lg sm:text-xl text-gray-600 dark:text-gray-300 max-w-2xl">
        Spécialiste en <span class="font-semibold">découpe laser</span> et <span class="font-semibold">gravure</span> pour des cadeaux <span class="italic">uniques et personnalisés</span>.  
        Offrez un souvenir qui dure toute une vie.
      </p>

      <!-- CTA -->
      <div class="mt-8 flex flex-wrap justify-center lg:justify-start gap-4">
        <a href="/" 
           class="px-6 py-3 rounded-2xl bg-pink-600 text-white font-semibold shadow-md hover:bg-pink-700 transition">
          Découvrir nos produits
        </a>
        <a href="/contactez-nous" 
           class="px-6 py-3 rounded-2xl border border-gray-300 dark:border-gray-600 text-gray-900 dark:text-white font-semibold hover:bg-gray-100 dark:hover:bg-gray-800 transition">
          Nous contacter
        </a>
      </div>
    </div>

    <!-- Image Hero -->
    <div class="flex-1 flex justify-center">
      <img src="https://cdn-icons-png.flaticon.com/512/3602/3602145.png" 
           alt="Cadeau personnalisé" 
           class="w-72 sm:w-96 drop-shadow-2xl animate-bounce-slow dark:invert">
    </div>
  </div>
</section>

<!-- Animation lente -->
<style>
@keyframes bounce-slow {
  0%, 100% { transform: translateY(0); }
  50% { transform: translateY(-10px); }
}
.animate-bounce-slow {
  animation: bounce-slow 4s infinite;
}
</style>
