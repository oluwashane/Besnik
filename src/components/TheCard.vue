<template>
  <div class="grid sm:grid-cols-2 lg:grid-cols-3 gap-x-6">
    <div v-for="item in items" :key="item.id" class="mt-10 mx-auto flex w-96 lg:w-full flex-col justify-center bg-white rounded-2xl shadow-xl shadow-slate-300/60">
      <img class="aspect-video w-full rounded-t-2xl object-cover object-center" :src="getImage(item.image)" alt="image">
      <div class="p-6">
        <h4 class="text-[#000339]">${{item.price}}</h4>
        <p class="pt-2 text-[#A3A6AB]">{{item.description}}</p>
        <div class="flex flex-row justify-between pt-6">
          <div class="flex flex-row items-center">
            <span class="">
              <img src="@/assets/images/bed.svg" alt="">
            </span>
            <p class="ml-2 text-sm text-[#444444]">{{item.beds}} Beds</p>
          </div>
          <div class="flex flex-row items-center">
            <span>
              <img src="@/assets/images/both.svg" alt="">
            </span>
            <p class="ml-2 text-sm text-[#444444]">{{item.both}} both</p>
          </div>
          <div class="flex flex-row items-center">
            <span>
              <img src="@/assets/images/sqft.svg" alt="">
            </span>
            <p class="ml-2 text-sm text-[#444444]">{{item.sqft}} Sqft</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import cardData from '@/utils/data.json'
import { ref } from 'vue'

const items = ref(cardData)

const getImage = (image) => {
  return `src/assets/images/${image}`
}

</script>

<style lang="scss" scoped>

</style>
