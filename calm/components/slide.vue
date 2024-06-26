<template>
    <div class="lg:hidden">
    <div class=" bg-blue-500 m-5 rounded-2xl h-96 " v-if="count == '1'">
        <div class="mt-16 p-5 flex flex-col gap-7">
            <img class="h-10 w-10" src="C:\Users\ADMIN\Desktop\project2\calm\assets\pngwing.com.png" alt="">
            <h1 class="text-white text-xl">When I cannot fall asleep, I turn on this app and am out within 5 mins.</h1>
            <h1 class="text-white">Brandy from Houston</h1>
            <img class=" w-32"src="C:\Users\ADMIN\Desktop\project2\calm\assets\5star.png" alt="">
        </div>
    </div>
    <div class=" bg-blue-500 m-5 rounded-2xl h-96" v-if="count == '2'">
        <div class="mt-16 p-5 flex flex-col gap-7">
            <img class="h-10 w-10" src="C:\Users\ADMIN\Desktop\project2\calm\assets\pngwing.com.png" alt="">
            <h1 class="text-white text-xl">I have a very busy brain and can find it hard to unwind. Now a daily practive is actually so wonderful and healing for me.</h1>
            <h1 class="text-white">John from Chicago</h1>
            <img class=" w-32"src="C:\Users\ADMIN\Desktop\project2\calm\assets\5star.png" alt="">
        </div>
    </div>
    <div class=" bg-blue-500 m-5 rounded-2xl h-96" v-if="count === 3">
        <div class="mt-16 p-5 flex flex-col gap-7">
            <img class="h-10 w-10" src="C:\Users\ADMIN\Desktop\project2\calm\assets\pngwing.com.png" alt="">
            <h1 class="text-white text-xl">Calm has changed my life in immeasurable ways. I am more resilient and feel so much more connected to myself.</h1>
            <h1 class="text-white">Allison from San Jose</h1>
            <img class=" w-32"src="C:\Users\ADMIN\Desktop\project2\calm\assets\5star.png" alt="">
        </div>
    </div>
    <div class=" bg-blue-500 m-5 rounded-2xl h-96" v-if="count == 4">
        <div class="mt-16 p-5 flex flex-col gap-7">
            <img class="h-10 w-10" src="C:\Users\ADMIN\Desktop\project2\calm\assets\pngwing.com.png" alt="">
            <h1 class="text-white text-xl">Whenever I need to unwind from a stressfull work day I meditate with Calm's soundspaces and it automatically sends me to my happy place.</h1>
            <h1 class="text-white">Jasmine from Bend</h1>
            <img class=" w-32"src="C:\Users\ADMIN\Desktop\project2\calm\assets\5star.png" alt="">
        </div>
    </div>
</div>

<div class="lg:grid grid-cols-4 items-center justify-center mt-6 sm:hidden md:hidden tb:hidden ">
    <div class=" bg-blue-500 m-5 rounded-2xl h-96 ">
        <div class="mt-20 p-5 flex flex-col gap-7">
            <img class="h-10 w-10" src="C:\Users\ADMIN\Desktop\project2\calm\assets\pngwing.com.png" alt="">
            <h1 class="text-white text-xl">When I cannot fall asleep, I turn on this app and am out within 5 mins.</h1>
            <h1 class="text-white">Brandy from Houston</h1>
            <img class=" w-32"src="C:\Users\ADMIN\Desktop\project2\calm\assets\5star.png" alt="">
        </div>
    </div>
    <div class=" bg-blue-500 m-5 rounded-2xl h-96">
        <div class="mt-14 p-5 flex flex-col gap-7">
            <img class="h-10 w-10" src="C:\Users\ADMIN\Desktop\project2\calm\assets\pngwing.com.png" alt="">
            <h1 class="text-white text-xl">I have a very busy brain and can find it hard to unwind. Now a daily practive is actually so wonderful and healing for me.</h1>
            <h1 class="text-white">John from Chicago</h1>
            <img class=" w-32"src="C:\Users\ADMIN\Desktop\project2\calm\assets\5star.png" alt="">
        </div>
    </div>
    <div class=" bg-blue-500 m-5 rounded-2xl h-96">
        <div class="mt-14 p-5 flex flex-col gap-7">
            <img class="h-10 w-10" src="C:\Users\ADMIN\Desktop\project2\calm\assets\pngwing.com.png" alt="">
            <h1 class="text-white text-xl">Calm has changed my life in immeasurable ways. I am more resilient and feel so much more connected to myself.</h1>
            <h1 class="text-white">Allison from San Jose</h1>
            <img class=" w-32"src="C:\Users\ADMIN\Desktop\project2\calm\assets\5star.png" alt="">
        </div>
    </div>
    <div class=" bg-blue-500 m-5 rounded-2xl h-96">
        <div class=" p-5 flex flex-col gap-7">
            <img class="h-10 w-10" src="C:\Users\ADMIN\Desktop\project2\calm\assets\pngwing.com.png" alt="">
            <h1 class="text-white text-xl">Whenever I need to unwind from a stressfull work day I meditate with Calm's soundspaces and it automatically sends me to my happy place.</h1>
            <h1 class="text-white">Jasmine from Bend</h1>
            <img class=" w-32"src="C:\Users\ADMIN\Desktop\project2\calm\assets\5star.png" alt="">
        </div>
    </div>
</div>

<div class="flex items-center justify-center mb-16 gap-5 lg:hidden">
    <img class="h-9 bg-slate-500 rounded-3xl p-2"src="assets\left-arrow-backup-2-svgrepo-com.svg" @click="previous" alt="">
    <img class="h-9 bg-slate-500 rounded-3xl p-2"src="assets\right-arrow-svgrepo-com.svg" @click="next" alt="">
    <div>{{ count }}</div>
</div>
</template>

<script setup>
import { ref } from 'vue';
const count = ref(1);
function next() {
        count.value++;
    }

function previous() {
    count.value--;
}


</script>