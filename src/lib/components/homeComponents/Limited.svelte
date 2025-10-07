<script>
  import { onMount, onDestroy } from 'svelte';

  // Your image list
  const images = [
    '/images/newtableau.webp',
    '/images/newtableau2.webp',
    '/images/newtableau3.webp',
    '/images/newtableau4.webp'
  ];

  let current = 0;
  let interval;

  // Automatically change image every 3 seconds
  onMount(() => {
    interval = setInterval(() => {
      current = (current + 1) % images.length;
    }, 3000);
  });

  onDestroy(() => {
    clearInterval(interval);
  });
</script>

<section class="relative overflow-hidden section-padding">
  <!-- SVG Background Pattern -->
  <div class="absolute inset-0 opacity-10 pointer-events-none">
    <svg width="100%" height="100%" xmlns="http://www.w3.org/2000/svg">
      <defs>
        <pattern id="dotGrid" width="20" height="20" patternUnits="userSpaceOnUse">
          <circle cx="10" cy="10" r="2" fill="currentcolor" />
        </pattern>
      </defs>
      <rect width="100%" height="100%" fill="url(#dotGrid)" />
    </svg>
  </div>

  <!-- Main Content -->
  <div class="container mx-auto px-4 relative z-10 my-20">
    <div class="text-center max-w-3xl mx-auto mb-16">
      <h2 class="text-3xl md:text-4xl font-extrabold mb-6 tracking-wider">
        ÉDITION <span class="text-pink-500">LIMITÉE</span>.
      </h2>
      <p class="text-lg font-extralight">
        Découvrez l'élégance unique de notre tableau Arabesque, une édition limitée
        qui sublime votre intérieur avec couleurs et formes harmonieuses.
      </p>
    </div>

    <div class="max-w-5xl mx-auto">
      <div class="relative rounded-xl overflow-hidden shadow-2xl" id="video-container">
        <!-- Smooth fade transition -->
        <img
          src={images[current]}
          alt="Nouveau Tableau Arabesque"
          class="transition-opacity duration-1000 ease-in-out w-full h-auto"
        />
      </div>
    </div>
    <div class="text-center mt-10">
      <a class="font-semibold hover:underline text-rose-500 text-xl border-2 px-2 rounded " href="/tableaux">Découvrir ..</a>
    </div>
  </div>
</section>

<style>
  /* Optional: add a fade effect manually if you want it smoother */
  img {
    animation: fade 1s ease-in-out;
  }

  @keyframes fade {
    from {
      opacity: 0.4;
    }
    to {
      opacity: 1;
    }
  }
</style>
