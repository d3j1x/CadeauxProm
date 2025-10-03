<script>
  let logos = [
    "/logos/aramex.webp",
    "/logos/aramex.webp",
    "/logos/aramex.webp",
    "/logos/aramex.webp",
    "/logos/aramex.webp",
    "/logos/aramex.webp",
    "/logos/aramex.webp",
    "/logos/aramex.webp",
    "/logos/aramex.webp",
    "/logos/aramex.webp",
    "/logos/aramex.webp",
    "/logos/aramex.webp",
    "/logos/aramex.webp",
    "/logos/aramex.webp"
  ];
</script>

<style>
  .Marquee-content {
    animation: marquee 40s linear infinite;
  }

  .Marquee-content:hover {
    animation-play-state: paused;
  }

  @keyframes marquee {
    0% {
      transform: translateX(0);
    }
    100% {
      transform: translateX(-50%);
    }
  }
</style>

<div class="text-center">
    <h1 class="text-3xl sm:text-4xl font-bold  mt-10 mb-20">NOS PARTENAIRES</h1>
</div>

<div class="marque-container h-full w-full flex items-center justify-center mb-10">
  <div class="Marquee w-full box-border p-4  font-light flex items-center overflow-hidden ">
    <div class="Marquee-content flex">
      {#each logos as logo}
        <div class="Marquee-tag w-52 mx-10 p-2 inline-flex items-center justify-center transition-all duration-900 ease-in-out hover:scale-110">
          <img src={logo} alt="logo" />
        </div>
      {/each}
    </div>
  </div>
</div>
