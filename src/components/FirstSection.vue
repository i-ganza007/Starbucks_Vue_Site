<template>
    <!-- eslint-disable vue/no-multiple-template-root -->
    <div class="flex pt-10 h-[556px] justify-center">
      <div class="bg-red-200">
        <img class="w-full h-full mr-0" src="../assets/first-ones.jpeg" alt="Winter menu image" />
      </div>
      <TextBox
        :heading="'The best of winter'"
        :button="'Add to order'"
        :description="'A new winter menu is here, featuring new Cortado alongside Pistachio beverages and Matcha Latte—now customized to your perfect level of sweetness.'"
      />
    </div>
    <!-- eslint-enable vue/no-multiple-template-root -->
  </template>
  
  <script setup>
  import TextBox from './TextBox.vue';
  </script>
  