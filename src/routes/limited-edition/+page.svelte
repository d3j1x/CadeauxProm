<svelte:head>
  <script type="module" src="https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.esm.js"></script>
  <script nomodule src="https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.js"></script>
</svelte:head>

<script>
  const phone = "21656165627"; // replace with your number (no + or spaces)
  const message = "Bonjour, je suis intéressé par votre produit Édition Limitée !";

  function openWhatsApp() {
    const url = `https://wa.me/${phone}?text=${encodeURIComponent(message)}`;
    window.open(url, "_blank");
  }
</script>

<div class="w-full h-full  py-16">
  <div class="max-w-6xl mx-auto flex flex-col justify-center items-center">
    <!-- Title -->
    <p class="pb-2 text-lg lg:text-2xl text-rose-600 font-semibold">ÉDITION LIMITÉE</p>
    <h2 class="text-3xl lg:text-5xl text-center  font-semibold mb-12 dark:text-white">
      Choisissez Votre Meilleur ..
    </h2>

    <!-- Cards -->
    <div class="flex flex-wrap gap-8 justify-center items-center">
      <!-- Card 1 -->
      <div
        class="group w-[18rem] sm:w-[20rem] bg-white dark:bg-black rounded-2xl overflow-hidden shadow-lg hover:shadow-2xl transition-all duration-300 transform hover:scale-105">
        <img
          class="w-full h-[14rem] object-cover"
          src="/images/newtableau.webp"
          alt="Sushi"
        />
        <div class="p-5">
          <h2 class="text-2xl font-semibold mb-1 group-hover:text-rose-600 dark:text-white">So trust in God</h2>
          <p class="text-gray-700 dark:text-gray-300 mb-4 font-extrabold">فتوكل على الله</p>
          <div class="flex justify-between items-center mb-4">
      <!-- <div class="flex -space-x-3">
        <img class="w-9 h-9 rounded-full border-2 border-white" src="https://randomuser.me/api/portraits/men/1.jpg" alt="">
        <img class="w-9 h-9 rounded-full border-2 border-white" src="https://randomuser.me/api/portraits/men/2.jpg" alt="">
        <img class="w-9 h-9 rounded-full border-2 border-white" src="https://randomuser.me/api/portraits/men/3.jpg" alt="">
      </div> -->
      <div class="flex -space-x-3">
        <p class="font-semibold">189 DT</p>
      </div>
            <div class="flex items-center text-red-500 text-xl font-bold">
              <ion-icon name="heart"></ion-icon>
              <span class="text-red-500 ml-1">5.0</span>
            </div>
          </div>
          <button onclick={openWhatsApp}
            class="w-full py-2 border border-rose-600 dark:border-gray-500 text-rose-700 dark:text-white rounded-full uppercase font-bold transition duration-300 hover:bg-rose-600 hover:text-white dark:hover:bg-white dark:hover:text-black">
            Commandez
          </button>
        </div>
      </div>

      <!-- Card 2 -->
             <div
        class="group w-[18rem] sm:w-[20rem] bg-white dark:bg-black rounded-2xl overflow-hidden shadow-lg hover:shadow-2xl transition-all duration-300 transform hover:scale-105">
        <img
          class="w-full h-[14rem] object-cover"
          src="/images/newtableau2.webp"
          alt="Sushi"
        />
        <div class="p-5">
          <h2 class="text-2xl font-semibold mb-1 group-hover:text-rose-600 dark:text-white">Praise God</h2>
          <p class="text-gray-700 dark:text-gray-300 mb-4 font-extrabold">سبحان الله</p>
          <div class="flex justify-between items-center mb-4">
      <div class="flex -space-x-3">
        <p class="font-semibold">189 DT</p>
      </div>
            <div class="flex items-center text-yellow-500 text-xl font-bold">
              <ion-icon name="star"></ion-icon>
              <span class="text-yellow-500 ml-1">4.9</span>
            </div>
          </div>
          <button onclick={openWhatsApp}
            class="w-full py-2 border border-rose-600 dark:border-gray-500 text-rose-700 dark:text-white rounded-full uppercase font-bold transition duration-300 hover:bg-rose-600 hover:text-white dark:hover:bg-white dark:hover:text-black">
            Commandez
          </button>
        </div>
      </div>

      <!-- Card 3 -->
             <div
        class="group w-[18rem] sm:w-[20rem] bg-white dark:bg-black rounded-2xl overflow-hidden shadow-lg hover:shadow-2xl transition-all duration-300 transform hover:scale-105">
        <img
          class="w-full h-[14rem] object-cover"
          src="/images/newtableau3.webp"
          alt="Sushi"
        />
        <div class="p-5">
          <h2 class="text-2xl font-semibold mb-1 group-hover:text-rose-600 dark:text-white">God bless</h2>
          <p class="text-gray-700 dark:text-gray-300 mb-4 font-extrabold">ما شاء الله</p>
          <div class="flex justify-between items-center mb-4">
      <div class="flex -space-x-3">
        <p class="font-semibold">189 DT</p>
      </div>
            <div class="flex items-center text-yellow-500 text-xl font-bold">
              <ion-icon name="star"></ion-icon>
              <span class="text-yellow-500 ml-1">4.9</span>
            </div>
          </div>
          <button onclick={openWhatsApp}
            class="w-full py-2 border border-rose-600 dark:border-gray-500 text-rose-700 dark:text-white rounded-full uppercase font-bold transition duration-300 hover:bg-rose-600 hover:text-white dark:hover:bg-white dark:hover:text-black">
            Commandez
          </button>
        </div>
      </div>

      <!-- card 4 -->
             <div
        class="group w-[18rem] sm:w-[20rem] bg-white dark:bg-black rounded-2xl overflow-hidden shadow-lg hover:shadow-2xl transition-all duration-300 transform hover:scale-105">
        <img
          class="w-full h-[14rem] object-cover"
          src="/images/newtableau4.webp"
          alt="Sushi"
        />
        <div class="p-5">
          <h2 class="text-2xl font-semibold mb-1 group-hover:text-rose-600 dark:text-white">The blessing ..
</h2>
          <p class="text-gray-700 dark:text-gray-300 mb-4 font-extrabold">وأما بنعمة ربك فحدث</p>
          <div class="flex justify-between items-center mb-4">
      <div class="flex -space-x-3">
        <p class="font-semibold">189 DT</p>
      </div>
            <div class="flex items-center text-yellow-500 text-xl font-bold">
              <ion-icon name="star"></ion-icon>
              <span class="text-yellow-500 ml-1">4.9</span>
            </div>
          </div>
          <button onclick={openWhatsApp}
            class="w-full py-2 border border-rose-600 dark:border-gray-500 text-rose-700 dark:text-white rounded-full uppercase font-bold transition duration-300 hover:bg-rose-600 hover:text-white dark:hover:bg-white dark:hover:text-black">
            Commandez
          </button>
        </div>
      </div>


    </div>
  </div>
</div>

