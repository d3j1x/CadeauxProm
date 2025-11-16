<script>
    import popular01 from '$lib/images/tableaux/tab01.jpeg';
    import popular02 from '$lib/images/tableaux/tab02.jpeg';
    import limited01 from '$lib/images/tableaux/tabLimited01.jpeg';
    import limited02 from '$lib/images/tableaux/tabLimited02.jpeg';
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
    <button class="bg-gray-200 text-gray-700 px-4 py-2 rounded-full hover:bg-gray-300">Populaire</button>
    <button class="bg-gray-200 text-gray-700 px-4 py-2 rounded-full hover:bg-gray-300">ÉDITION LIMITÉE</button>
    
 
    
  </div>

  <!-- Product Grid -->
  <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8 max-w-7xl mx-auto">
    <!-- Product Card -->
    <div class="bg-white rounded-2xl shadow-lg hover:shadow-2xl transition overflow-hidden group">
      <div class="relative">
        <img src={popular01} alt="Product Image" class="w-full h-60 object-cover group-hover:scale-105 transition-transform" />
        <span class="absolute top-3 right-3 bg-black text-white text-xs px-2 py-1 rounded">NEW</span>
      </div>
      <div class="p-5">
        <h3 class="text-lg font-bold text-gray-900 mb-1">Arabesque PoP 1</h3>
        <p class="text-sm text-gray-500 mb-2"> </p>
        <div class="flex justify-between items-center mt-4">
          <span class="text-lg font-semibold text-green-600">89.00 DT</span>
          <button class="bg-black text-white px-4 py-2 rounded-lg hover:bg-gray-800">Commander</button>
        </div>
      </div>
    </div>

    <!-- Duplicate Product Cards -->
    <div class="bg-white rounded-2xl shadow-lg hover:shadow-2xl transition overflow-hidden group">
      <div class="relative">
        <img src={popular02} alt="Product Image" class="w-full h-60 object-cover group-hover:scale-105 transition-transform" />
        <span class="absolute top-3 right-3 bg-black text-white text-xs px-2 py-1 rounded">NEW</span>
      </div>
      <div class="p-5">
        <h3 class="text-lg font-bold text-gray-900 mb-1">Arabesque PoP 2</h3>
        <p class="text-sm text-gray-500 mb-2"></p>
        <div class="flex justify-between items-center mt-4">
          <span class="text-lg font-semibold text-green-600">89.00 DT</span>
          <button class="bg-black text-white px-4 py-2 rounded-lg hover:bg-gray-800">Commander</button>
        </div>
      </div>
    </div>

        <div class="bg-white rounded-2xl shadow-lg hover:shadow-2xl transition overflow-hidden group">
      <div class="relative">
        <img src={limited01} alt="Product Image" class="w-full h-60 object-cover group-hover:scale-105 transition-transform" />
        <span class="absolute top-3 right-3 bg-black text-white text-xs px-2 py-1 rounded">NEW</span>
      </div>
      <div class="p-5">
        <h3 class="text-lg font-bold text-gray-900 mb-1">Limited 1</h3>
        <p class="text-sm text-gray-500 mb-2"> </p>
        <div class="flex justify-between items-center mt-4">
          <span class="text-lg font-semibold text-green-600">189.00 DT</span>
          <button class="bg-black text-white px-4 py-2 rounded-lg hover:bg-gray-800">Commander</button>
        </div>
      </div>
    </div>

    <!-- Duplicate Product Cards -->
    <div class="bg-white rounded-2xl shadow-lg hover:shadow-2xl transition overflow-hidden group">
      <div class="relative">
        <img src={limited02} alt="Product Image" class="w-full h-60 object-cover group-hover:scale-105 transition-transform" />
        <span class="absolute top-3 right-3 bg-black text-white text-xs px-2 py-1 rounded">NEW</span>
      </div>
      <div class="p-5">
        <h3 class="text-lg font-bold text-gray-900 mb-1">Limited 2</h3>
        <p class="text-sm text-gray-500 mb-2"></p>
        <div class="flex justify-between items-center mt-4">
          <span class="text-lg font-semibold text-green-600">189.00 DT</span>
          <button class="bg-black text-white px-4 py-2 rounded-lg hover:bg-gray-800">Commander</button>
        </div>
      </div>
    </div>
  </div>

  
</section>