<template>
    <div style="background-color:#cfe6b5" class="flex flex-col justify-center items-center gap-7" >
        <h2 style="color: #1d3c34;" class="text-5xl font-bold tracking-wide w-[280px]">{{heading}}</h2>
        <p style="color: #1d3c34;" class="font-semibold tracking-wider">{{ description }}</p>
        <button style="color: #1d3c34;" class="p-2 border-solid border rounded-full px-3 py-1 border-black font-semibold text-black text-[14px] text-[24px]">{{ button }}</button>
    </div>
</template>
<script setup>
import { defineProps} from 'vue';
defineProps({
    heading:{
        type:String,
        required:true
    },
    description:{
        type:String,
        required:true,
    },
    button:{
        type:String,
        default:'Join Now',
        required:true
    }
})
</script>