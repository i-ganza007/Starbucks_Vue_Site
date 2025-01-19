<template>
    <div class="flex pt-10 h-[375px] justify-center">
        <div>
            <img class="w-full h-full" src="../assets/third-ones.jpeg" alt="third-ones">
        </div>
        <TextBox class="h-full w-full" :heading="'Your first taste of Rewards is free'" :description="'Unlock Rewards from the very first sip, starting with a free handcrafted drink when you make a qualifying purchase during your first week as a Starbucks® Rewards member.*'"/>
    </div>
</template>

<script setup>
import TextBox from './TextBox.vue';
</script>