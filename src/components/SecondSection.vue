<template>
    <div class="flex pt-10 h-[556px] justify-center">
        <div>
            <img class="w-full h-full" src="../assets/second-ones.jpeg" alt="coffee-bag">
        </div>
        <TextBox :heading="'From the birthplace of coffee'" :description="'With distinctive floral, tangerine and lemon balm notes, Single-Origin Ethiopia is a unique global favorite.'" :button="'Add to order'"/>
    </div>
</template>
<script setup>
import TextBox from './TextBox.vue';
</script>