<script>
  import laserbg from '$lib/images/homeImages/laserbg.webp';
</script>
<section class="">
  <!-- Background decoration -->
   

  <div class="max-w-7xl mx-auto px-6 lg:px-12 py-10 lg:py-20 flex flex-col lg:flex-row items-center gap-12">
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
      <img src={laserbg} 
           alt="Cadeau personnalisé" 
           class="w-72 sm:w-96  drop-shadow-2xl  ">
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
