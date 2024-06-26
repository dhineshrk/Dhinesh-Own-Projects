<template>
    <div class="absolute top-0 w-screen text-black lg:bg-white font-bold z-20 shadow-md">
        <!--For mobile to tablet-->
        <nav class="h-20 overflow-hidden p-5 flex items-center justify-evenly gap-5 tb:justify-between lg:hidden">
            <img class="h-6" src="assets\calm.png" alt="">
            <div class="flex items-center gap-5 ">
                <button class="text-white bg-blue-950 p-3 rounded-full">Try Calm for Free</button>
                <img @click="sideopen" class="h-5" src="assets\menu.svg" alt="">
            </div>
        </nav>
    
        <!--For Large (1024) -->
        <nav class="h-20 overflow-hidden justify-between px-9 py-5 sm:hidden md:hidden tb:hidden lg:flex xlg:hidden flex items-center">
            <img class="h-20" src="assets\calm2.png" alt="">
            <div class="flex items-center gap-9 ">
                <div class="text-lg">Calm Business</div>
                <div class="text-lg">Calm Health</div>
                <div class="text-lg">Log In</div>
                <button class="text-white bg-black p-5 rounded-full">Try Calm for Free</button>
            </div>
        </nav>
    
        <!--For ExtraLarge (1440) -->
        <nav class="h-28  overflow-hidden justify-between px-9 py-5 sm:hidden md:hidden tb:hidden lg:hidden xlg:flex text-2xl">
            <div class="flex items-center gap-9 ">
                <img class="h-20" src="assets\calm2.png" alt="">
                <NuxtLink to="/sleep" class="text-lg">Sleep</NuxtLink>
                <div class="text-lg">Stress & Anxiety</div>
                <div class="text-lg">Mindfulness</div>
            </div>
            <div class="flex items-center gap-9 ">
                <div class="text-lg">Calm Business</div>
                <div class="text-lg">Calm Health</div>
                <div class="text-lg">Log In</div>
                <button class="text-white bg-black p-5 rounded-full">Try Calm for Free</button>
            </div>
        </nav>
    </div>
    
    <!--Side bar-->
    
    <div v-if="open=='true'" class="absolute top-0 w-full flex flex-col bg-gray-600 h-screen z-30 gap-12  text-lg text-white font-extrabold p-10 ">
        <div class="text-white ml-auto">
            <svg @click="sideclose" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6">
            <path stroke-linecap="round" stroke-linejoin="round" d="M6 18 18 6M6 6l12 12" />
            </svg>
        </div>
        <div  v-for="(item,index) in items" :key="index">
            <NuxtLink :to="item.path"> <span class=" hover:bg-gray-400 rounded-full w-screen p-3">{{ item.title }}</span> </NuxtLink>
        </div>
    </div>
    
    
    </template>
    
    <script setup>
    import { ref } from 'vue';
    
    const items = ref([
        {
            title: "Sleep",
            path: '/sleep',
        }, {
            title: "Stress & Anxiety",
            path: '/stressAnxiety'
        }, {
            title: "Mindfulness",
            path: '/mindfulness'
        }, {
            title: "Calm Business",
            path: '/calmBusiness'
        }, {
            title: "Calm Health",
            path: '/calmHealth'
        }, {
            title: "Log In",
            path: '/logIn'
        }
    ])
    
    
    const open = ref(false);
    
    function sideopen() {
            open.value = 'true';
    }
    function sideclose() {
            open.value = 'false';
    }
    
    </script>