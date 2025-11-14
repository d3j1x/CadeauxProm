<script>
    import image01 from '$lib/images/ai/1.jpeg';
    import image02 from '$lib/images/ai/2.jpeg';
    import image03 from '$lib/images/ai/3.jpeg';
    import image04 from '$lib/images/ai/4.jpeg';
    import image05 from '$lib/images/ai/5.jpeg';
    import image06 from '$lib/images/ai/6.jpeg';
    import image07 from '$lib/images/ai/7.jpeg';
    import image08 from '$lib/images/ai/8.jpeg';

    import image09 from '$lib/images/ai/9.jpeg';
    import image10 from '$lib/images/ai/10.jpeg';
    import image11 from '$lib/images/ai/11.jpeg';
    import image12 from '$lib/images/ai/12.jpeg';
    import image13 from '$lib/images/ai/13.jpeg';
    import image14 from '$lib/images/ai/14.jpeg';
    import image15 from '$lib/images/ai/15.jpeg';
    import image16 from '$lib/images/ai/16.jpeg';

    let showMore = false;
</script>

<!-- Photo Gallery Section -->
<section class="py-20 bg-white">
  <div class="container mx-auto px-6">
    <div class="text-center mb-16">
      <span class="text-rose-600 font-semibold">⭐ Pourquoi nous choisir ?</span>
      <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mt-4">📸 Qualité Premium</h2>
      <p class="max-w-2xl mx-auto text-gray-600 mt-6 text-lg">Nos produits sont réalisés avec une attention exceptionnelle aux détails. Chaque photo, chaque design et chaque impression reflètent notre engagement envers la qualité.</p>
    </div>

    <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-4">
      <!-- Gallery Item 1 -->
      <div class="group relative overflow-hidden rounded-lg aspect-square">
        <img 
          src={image01} 
          alt="Concert crowd" 
          class="w-full h-full object-cover transform group-hover:scale-110 transition-transform duration-500"
        >
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex items-end p-6">
          <div class="translate-y-4 group-hover:translate-y-0 transition-transform duration-300">
            <h3 class="text-white text-xl font-bold">Cadeaux Prom</h3>
            <p class="text-white/80 mt-1">November 2025</p>
          </div>
        </div>
      </div>

      <!-- Gallery Item 2 -->
      <div class="group relative overflow-hidden rounded-lg aspect-square">
        <img 
          src={image02} 
          alt="Team building" 
          class="w-full h-full object-cover transform group-hover:scale-110 transition-transform duration-500"
        >
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex items-end p-6">
          <div class="translate-y-4 group-hover:translate-y-0 transition-transform duration-300">
            <h3 class="text-white text-xl font-bold">Cadeaux Prom</h3>
            <p class="text-white/80 mt-1">November 2025</p>
          </div>
        </div>
      </div>

      <!-- Gallery Item 3 -->
      <div class="group relative overflow-hidden rounded-lg aspect-square">
        <img 
          src={image03} 
          alt="Office meeting" 
          class="w-full h-full object-cover transform group-hover:scale-110 transition-transform duration-500"
        >
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex items-end p-6">
          <div class="translate-y-4 group-hover:translate-y-0 transition-transform duration-300">
            <h3 class="text-white text-xl font-bold">Cadeaux Prom</h3>
            <p class="text-white/80 mt-1">November 2025</p>
          </div>
        </div>
      </div>

      <!-- Gallery Item 4 -->
      <div class="group relative overflow-hidden rounded-lg aspect-square">
        <img 
          src={image04} 
          alt="Team celebration" 
          class="w-full h-full object-cover transform group-hover:scale-110 transition-transform duration-500"
        >
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex items-end p-6">
          <div class="translate-y-4 group-hover:translate-y-0 transition-transform duration-300">
            <h3 class="text-white text-xl font-bold">Cadeaux Prom</h3>
            <p class="text-white/80 mt-1">November 2025</p>
          </div>
        </div>
      </div>

      <!-- Gallery Item 5 -->
      <div class="group relative overflow-hidden rounded-lg aspect-square">
        <img 
          src={image05} 
          alt="Conference" 
          class="w-full h-full object-cover transform group-hover:scale-110 transition-transform duration-500"
        >
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex items-end p-6">
          <div class="translate-y-4 group-hover:translate-y-0 transition-transform duration-300">
            <h3 class="text-white text-xl font-bold">Cadeaux Prom</h3>
            <p class="text-white/80 mt-1">November 2025</p>
          </div>
        </div>
      </div>

      <!-- Gallery Item 6 -->
      <div class="group relative overflow-hidden rounded-lg aspect-square">
        <img 
          src={image06} 
          alt="Volunteering" 
          class="w-full h-full object-cover transform group-hover:scale-110 transition-transform duration-500"
        >
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex items-end p-6">
          <div class="translate-y-4 group-hover:translate-y-0 transition-transform duration-300">
            <h3 class="text-white text-xl font-bold">Cadeaux Prom</h3>
            <p class="text-white/80 mt-1">November 2025</p>
          </div>
        </div>
      </div>

      <!-- Gallery Item 7 -->
      <div class="group relative overflow-hidden rounded-lg aspect-square">
        <img 
          src={image07} 
          alt="Award ceremony" 
          class="w-full h-full object-cover transform group-hover:scale-110 transition-transform duration-500"
        >
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex items-end p-6">
          <div class="translate-y-4 group-hover:translate-y-0 transition-transform duration-300">
            <h3 class="text-white text-xl font-bold">Cadeaux Prom</h3>
            <p class="text-white/80 mt-1">November 2025</p>
          </div>
        </div>
      </div>

      <!-- Gallery Item 8 -->
      <div class="group relative overflow-hidden rounded-lg aspect-square">
        <img 
          src={image08} 
          alt="Office party" 
          class="w-full h-full object-cover transform group-hover:scale-110 transition-transform duration-500"
        >
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex items-end p-6">
          <div class="translate-y-4 group-hover:translate-y-0 transition-transform duration-300">
            <h3 class="text-white text-xl font-bold">Cadeaux Prom</h3>
            <p class="text-white/80 mt-1">November 2025</p>
          </div>
        </div>
      </div>


      {#if showMore}
        
        


            <!-- Gallery Item 9 -->
      <div class="group relative overflow-hidden rounded-lg aspect-square">
        <img 
          src={image09} 
          alt="Concert crowd" 
          class="w-full h-full object-cover transform group-hover:scale-110 transition-transform duration-500"
        >
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex items-end p-6">
          <div class="translate-y-4 group-hover:translate-y-0 transition-transform duration-300">
            <h3 class="text-white text-xl font-bold">Cadeaux Prom</h3>
            <p class="text-white/80 mt-1">November 2025</p>
          </div>
        </div>
      </div>

      <!-- Gallery Item 10 -->
      <div class="group relative overflow-hidden rounded-lg aspect-square">
        <img 
          src={image10} 
          alt="Team building" 
          class="w-full h-full object-cover transform group-hover:scale-110 transition-transform duration-500"
        >
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex items-end p-6">
          <div class="translate-y-4 group-hover:translate-y-0 transition-transform duration-300">
            <h3 class="text-white text-xl font-bold">Cadeaux Prom</h3>
            <p class="text-white/80 mt-1">November 2025</p>
          </div>
        </div>
      </div>

      <!-- Gallery Item 11 -->
      <div class="group relative overflow-hidden rounded-lg aspect-square">
        <img 
          src={image11} 
          alt="Office meeting" 
          class="w-full h-full object-cover transform group-hover:scale-110 transition-transform duration-500"
        >
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex items-end p-6">
          <div class="translate-y-4 group-hover:translate-y-0 transition-transform duration-300">
            <h3 class="text-white text-xl font-bold">Cadeaux Prom</h3>
            <p class="text-white/80 mt-1">November 2025</p>
          </div>
        </div>
      </div>

      <!-- Gallery Item 12 -->
      <div class="group relative overflow-hidden rounded-lg aspect-square">
        <img 
          src={image12} 
          alt="Team celebration" 
          class="w-full h-full object-cover transform group-hover:scale-110 transition-transform duration-500"
        >
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex items-end p-6">
          <div class="translate-y-4 group-hover:translate-y-0 transition-transform duration-300">
            <h3 class="text-white text-xl font-bold">Cadeaux Prom</h3>
            <p class="text-white/80 mt-1">November 2025</p>
          </div>
        </div>
      </div>

      <!-- Gallery Item 13 -->
      <div class="group relative overflow-hidden rounded-lg aspect-square">
        <img 
          src={image13} 
          alt="Conference" 
          class="w-full h-full object-cover transform group-hover:scale-110 transition-transform duration-500"
        >
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex items-end p-6">
          <div class="translate-y-4 group-hover:translate-y-0 transition-transform duration-300">
            <h3 class="text-white text-xl font-bold">Cadeaux Prom</h3>
            <p class="text-white/80 mt-1">November 2025</p>
          </div>
        </div>
      </div>

      <!-- Gallery Item 14 -->
      <div class="group relative overflow-hidden rounded-lg aspect-square">
        <img 
          src={image14} 
          alt="Volunteering" 
          class="w-full h-full object-cover transform group-hover:scale-110 transition-transform duration-500"
        >
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex items-end p-6">
          <div class="translate-y-4 group-hover:translate-y-0 transition-transform duration-300">
            <h3 class="text-white text-xl font-bold">Cadeaux Prom</h3>
            <p class="text-white/80 mt-1">November 2025</p>
          </div>
        </div>
      </div>

      <!-- Gallery Item 15 -->
      <div class="group relative overflow-hidden rounded-lg aspect-square">
        <img 
          src={image15} 
          alt="Award ceremony" 
          class="w-full h-full object-cover transform group-hover:scale-110 transition-transform duration-500"
        >
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex items-end p-6">
          <div class="translate-y-4 group-hover:translate-y-0 transition-transform duration-300">
            <h3 class="text-white text-xl font-bold">Cadeaux Prom</h3>
            <p class="text-white/80 mt-1">November 2025</p>
          </div>
        </div>
      </div>

      <!-- Gallery Item 16 -->
      <div class="group relative overflow-hidden rounded-lg aspect-square">
        <img 
          src={image16} 
          alt="Office party" 
          class="w-full h-full object-cover transform group-hover:scale-110 transition-transform duration-500"
        >
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex items-end p-6">
          <div class="translate-y-4 group-hover:translate-y-0 transition-transform duration-300">
            <h3 class="text-white text-xl font-bold">Cadeaux Prom</h3>
            <p class="text-white/80 mt-1">November 2025</p>
          </div>
        </div>
      </div>

      {/if}
    </div>

    {#if !showMore}
    <div class="text-center mt-16">
      <button onclick={() => showMore = true} class="px-8 py-3 bg-rose-600 text-white font-medium rounded-lg hover:bg-rose-700 transition-colors shadow-lg">
        Charger plus de photos
      </button>
    </div>
    {/if}
  </div>
</section>