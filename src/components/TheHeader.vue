<template>
  <div class="container py-8">
    <div class="flex flex-row justify-between items-center">
      <div class="flex flex-row">
        <div class="pr-10">
          <IconBesnik color="#000228" />
        </div>
        <TheNav/>
      </div>
      <div class="hidden lg:flex flex-row ">
        <p class="md:px-4 lg:px-6 text-[#0F1B4C]">Sign up</p>
        <p>Login</p>
      </div>
    </div>
  </div>
</template>

<script setup>
import IconBesnik from './icons/IconBesnik.vue'
import TheNav from './TheNav.vue'

</script>

<style lang="scss" scoped>

</style>
