<script  lang="ts" setup>
import illustration from '~/assets/images/illustration-hero.svg'
import music from '~/assets/images/icon-music.svg'

</script>

<template>
  <main class="bg-blue-background text-blue-text h-screen flex items-center justify-center">
    <article class="w-100 rounded-3xl bg-white overflow-hidden shadow-xl">
      <img class="w-screen" :src="illustration" alt="">
      <div class='text-center p-8 space-y-4 flex flex-col items-center'>
        <h1 class="capitalize text-3xl font-bold text-blue-title">
          order summary
        </h1>
        <p class="text-[#9498AB] px-4 text-semibold">
          You can now listen to millions of songs, audiobooks, and podcasts on any device anywhere you like!
        </p>
        <section class="flex w-full items-center justify-between bg-blue-section rounded-xl p-4 gap-4">
          <img :src="music" alt="">
          <div class="flex-1 text-left">
            <h1 class="text-blue-title font-semibold">Annual Plan</h1>
            <p class="text-[#9498AB]">$59.99/year</p>
          </div>
          <button class="text-blue-native font-semibold underline hover:(no-underline text-blue-hover) focus:outline-none">Change</button>
        </section>
        <button class="font-semibold bg-blue-native text-white p-4 w-full rounded-xl shadow-xl shadow-blue-native hover:bg-blue-hover focus:outline-none">
          Proceed to Payment
        </button>
        <button class="font-semibold hover:text-blue-title focus:outline-none">
          Cancel Order
        </button>
      </div>
    </article>
  </main>
</template>
