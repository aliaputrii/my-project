<script setup>

</script>
<template>

<div id="gallery" class="relative w-full" data-carousel="slide">
    <!-- Carousel wrapper -->
    <div class="relative h-56 overflow-hidden rounded-lg md:h-96 bg-gray-900">
         <!-- Item 1 -->
        <div class="hidden duration-700 ease-in-out" data-carousel-item>
            <img src="https://asset-a.grid.id/crop/0x0:0x0/700x465/photo/2019/02/04/2705763058.jpg" class="absolute block max-w-full h-auto -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2" alt="">
        </div>
        <!-- Item 2 -->
        <div class="hidden duration-700 ease-in-out" data-carousel-item="active">
            <img src="https://mediatani.co/wp-content/uploads/2021/06/Migrasi-paus.png" class="absolute block max-w-full h-auto -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2" alt="">
        </div>
        <!-- Item 3 -->
        <div class="hidden duration-700 ease-in-out" data-carousel-item>
            <img src="https://boombastis.sgp1.digitaloceanspaces.com/wp-content/uploads/2014/10/Penumpang-Kapal-Shock-Melihat-Paus-Lompat-Ini-Karena..-1.jpg" class="absolute block max-w-full h-auto -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2" alt="">
        </div>
        <!-- Item 4 -->
        <div class="hidden duration-700 ease-in-out" data-carousel-item>
            <img src="https://static.promediateknologi.id/crop/0x0:0x0/750x500/webp/photo/2023/05/04/IMG_20230504_125039-3570564192.jpg" class="absolute block max-w-full h-auto -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2" alt="">
        </div>
        <!-- Item 5 -->
        <div class="hidden duration-700 ease-in-out" data-carousel-item>
            <img src="https://asset.kompas.com/crops/YwWEYRVYRhzFqLM79QYBIkOGJcI=/200x53:876x503/780x390/data/photo/2020/09/07/5f561d0e15452.jpg" class="absolute block max-w-full h-auto -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2" alt="">
        </div>
    </div>
    <!-- Slider controls -->
    <button type="button" class="absolute top-0 left-0 z-30 flex items-center justify-center h-full px-4 cursor-pointer group focus:outline-none" data-carousel-prev>
        <span class="inline-flex items-center justify-center w-10 h-10 rounded-full bg-white/30 dark:bg-gray-800/30 group-hover:bg-white/50 dark:group-hover:bg-gray-800/60 group-focus:ring-4 group-focus:ring-white dark:group-focus:ring-gray-800/70 group-focus:outline-none">
            <svg class="w-4 h-4 text-white dark:text-gray-800" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 6 10">
                <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 1 1 5l4 4"/>
            </svg>
            <span class="sr-only">Previous</span>
        </span>
    </button>
    <button type="button" class="absolute top-0 right-0 z-30 flex items-center justify-center h-full px-4 cursor-pointer group focus:outline-none" data-carousel-next>
        <span class="inline-flex items-center justify-center w-10 h-10 rounded-full bg-white/30 dark:bg-gray-800/30 group-hover:bg-white/50 dark:group-hover:bg-gray-800/60 group-focus:ring-4 group-focus:ring-white dark:group-focus:ring-gray-800/70 group-focus:outline-none">
            <svg class="w-4 h-4 text-white dark:text-gray-800" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 6 10">
                <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="m1 9 4-4-4-4"/>
            </svg>
            <span class="sr-only">Next</span>
        </span>
    </button>
</div>

    
<div class="grid grid-cols-2 gap-2 bg-gray-900">
        <div>
            <img class="h-auto max-w-full rounded-lg" src="https://akcdn.detik.net.id/community/media/visual/2021/06/18/paus-biru-pygmy_169.png?w=780&q=90" alt="">
        </div>
        <div>
            <img class="h-auto max-w-full rounded-lg" src="https://cdn2.tstatic.net/travel/foto/bank/images/penampakan-paus-biru-yang-langka-di-sydney.jpg" alt="">
        </div>
        <div>
            <img class="h-auto max-w-full rounded-lg" src="https://img.pikbest.com/origin/09/14/13/05fpIkbEsTF8V.png!w700wp" alt="">
        </div>
        <div>
            <img class="h-auto max-w-full rounded-lg" src="https://awsimages.detik.net.id/community/media/visual/2022/10/29/paus-biru-terdampar-di-raja-ampat-lokasi-dan-kondisi-terkini.jpeg?w=1200" alt="">
        </div>
    </div>

  </template>
