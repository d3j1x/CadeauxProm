<script>
    import setbureau from '$lib/images/articles/set-bureau.jpeg';
    import brossmom from '$lib/images/articles/bross-mom.jpeg';
    import mugmaryem from '$lib/images/articles/mug-maryem.jpeg';
    import cachepassport from '$lib/images/articles/cache-passport.jpeg';
    import pcleflower from '$lib/images/articles/pcle-flower.jpeg';
    import pclemed from '$lib/images/articles/pcle-med.jpeg';
    import pclemaryem from '$lib/images/articles/pcle-maryem.jpeg';
    import supportpcle_classic from '$lib/images/articles/support-pcle.jpeg';
    import supportpcle_modern from '$lib/images/articles/support-pcle-modern.jpeg';
    import notebookmom from '$lib/images/articles/notebook-mom.jpeg';


    
</script>

<!-- Main Product Showcase Section -->
<section class="bg-gray-50 min-h-screen py-16 px-6">
  <!-- Hero -->
  <div class="text-center mb-12">
    <h1 class="text-4xl md:text-5xl font-extrabold text-gray-900">Découvrez nos produits haut de gamme</h1>
    <p class="mt-4 text-lg text-gray-600 max-w-2xl mx-auto">Livraison gratuite.</p>
    <div class="mt-6">
      <button class="bg-black text-white px-6 py-3 rounded-xl hover:bg-gray-800">Achetez maintenant</button>
    </div>
  </div>

  <!-- Category Filters -->
  <div class="flex flex-wrap justify-center gap-4 mb-10">
    <button class="bg-gray-200 text-gray-700 px-4 py-2 rounded-full hover:bg-gray-300">Tous</button>
    <button class="bg-gray-200 text-gray-700 px-4 py-2 rounded-full hover:bg-gray-300">Business</button>
    <button class="bg-gray-200 text-gray-700 px-4 py-2 rounded-full hover:bg-gray-300">Accessories</button>
    <button class="bg-gray-200 text-gray-700 px-4 py-2 rounded-full hover:bg-gray-300">Home</button>
    <button class="bg-gray-200 text-gray-700 px-4 py-2 rounded-full hover:bg-gray-300">Homme</button>
    <button class="bg-gray-200 text-gray-700 px-4 py-2 rounded-full hover:bg-gray-300">Femme</button>
    
  </div>

  <!-- Product Grid -->
  <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8 max-w-7xl mx-auto">
    <!-- Product Card -->
    <div class="bg-white rounded-2xl shadow-lg hover:shadow-2xl transition overflow-hidden group">
      <div class="relative">
        <img src={setbureau} alt="Product Image" class="w-full h-60 object-cover group-hover:scale-105 transition-transform" />
        <span class="absolute top-3 right-3 bg-black text-white text-xs px-2 py-1 rounded">NEW</span>
      </div>
      <div class="p-5">
        <h3 class="text-lg font-bold text-gray-900 mb-1">Set Bureau</h3>
        <p class="text-sm text-gray-500 mb-2">4 · soustasse </p>
        <div class="flex justify-between items-center mt-4">
          <span class="text-lg font-semibold text-green-600">39.00 DT</span>
          <button class="bg-black text-white px-4 py-2 rounded-lg hover:bg-gray-800">Commander</button>
        </div>
      </div>
    </div>

    <!-- Duplicate Product Cards -->
    <div class="bg-white rounded-2xl shadow-lg hover:shadow-2xl transition overflow-hidden group">
      <div class="relative">
        <img src={brossmom} alt="Product Image" class="w-full h-60 object-cover group-hover:scale-105 transition-transform" />
        <span class="absolute top-3 right-3 bg-green-600 text-white text-xs px-2 py-1 rounded">BEST</span>
      </div>
      <div class="p-5">
        <h3 class="text-lg font-bold text-gray-900 mb-1">Bross MoM</h3>
        <p class="text-sm text-gray-500 mb-2">Lightweight · Bois</p>
        <div class="flex justify-between items-center mt-4">
          <span class="text-lg font-semibold text-green-600">20.00 DT</span>
          <button class="bg-black text-white px-4 py-2 rounded-lg hover:bg-gray-800">Commander</button>
        </div>
      </div>
    </div>

    <div class="bg-white rounded-2xl shadow-lg hover:shadow-2xl transition overflow-hidden group">
      <div class="relative">
        <img src={mugmaryem} alt="Product Image" class="w-full h-60 object-cover group-hover:scale-105 transition-transform" />
      </div>
      <div class="p-5">
        <h3 class="text-lg font-bold text-gray-900 mb-1">Mug personalisée</h3>
        <p class="text-sm text-gray-500 mb-2">Enjoy · Your daiy</p>
        <div class="flex justify-between items-center mt-4">
          <span class="text-lg font-semibold text-green-600">25.00 DT</span>
          <button class="bg-black text-white px-4 py-2 rounded-lg hover:bg-gray-800">Commander</button>
        </div>
      </div>
    </div>

    <div class="bg-white rounded-2xl shadow-lg hover:shadow-2xl transition overflow-hidden group">
      <div class="relative">
        <img src={supportpcle_modern} alt="Product Image" class="w-full h-60 object-cover group-hover:scale-105 transition-transform" />
      </div>
      <div class="p-5">
        <h3 class="text-lg font-bold text-gray-900 mb-1">Support PCles Modern</h3>
        <p class="text-sm text-gray-500 mb-2">Help · Daily</p>
        <div class="flex justify-between items-center mt-4">
          <span class="text-lg font-semibold text-green-600">35.00 DT</span>
          <button class="bg-black text-white px-4 py-2 rounded-lg hover:bg-gray-800">Commander</button>
        </div>
      </div>
    </div>

    <div class="bg-white rounded-2xl shadow-lg hover:shadow-2xl transition overflow-hidden group">
      <div class="relative">
        <img src={supportpcle_classic} alt="Product Image" class="w-full h-60 object-cover group-hover:scale-105 transition-transform" />
      </div>
      <div class="p-5">
        <h3 class="text-lg font-bold text-gray-900 mb-1">Support PCles Classic</h3>
        <p class="text-sm text-gray-500 mb-2">Help · Daily</p>
        <div class="flex justify-between items-center mt-4">
          <span class="text-lg font-semibold text-green-600">35.00 DT</span>
          <button class="bg-black text-white px-4 py-2 rounded-lg hover:bg-gray-800">Commander</button>
        </div>
      </div>
    </div>

    <div class="bg-white rounded-2xl shadow-lg hover:shadow-2xl transition overflow-hidden group">
      <div class="relative">
        <img src={notebookmom} alt="Product Image" class="w-full h-60 object-cover group-hover:scale-105 transition-transform" />
      </div>
      <div class="p-5">
        <h3 class="text-lg font-bold text-gray-900 mb-1">Notebook</h3>
        <p class="text-sm text-gray-500 mb-2">Mom · Sondes</p>
        <div class="flex justify-between items-center mt-4">
          <span class="text-lg font-semibold text-green-600">35.00 DT</span>
          <button class="bg-black text-white px-4 py-2 rounded-lg hover:bg-gray-800">Commander</button>
        </div>
      </div>
    </div>
  </div>
</section>