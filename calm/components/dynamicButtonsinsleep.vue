<template>
    <!--Dynamic buttons till 425px-->
    <div class="mb-48 flex flex-col gap-3 w-10/12 mx-auto tb:hidden">
            <div class="flex justify-center gap-3">
                <button class="text-gray-950 md:text-lg bg-gray-300 hover:bg-blue-950 hover:text-white p-2 rounded-lg text-sm">Sleep Stories</button>
            </div>
            <div class="flex justify-center gap-3">
                <button class="text-gray-950 md:text-lg  bg-gray-300 hover:bg-blue-950 hover:text-white p-2 rounded-lg text-sm">Sleep Meditations</button>
                <button class="text-gray-950 md:text-lg bg-gray-300 hover:bg-blue-950 hover:text-white p-2 rounded-lg text-sm">Music</button>
            </div>
            <div class="flex justify-center gap-3">
                <button class="text-gray-950 md:text-lg bg-gray-300 hover:bg-blue-950 hover:text-white p-2 rounded-lg text-sm">Soundscapes</button>
                <button class="text-gray-950 md:text-lg bg-gray-300 hover:bg-blue-950 hover:text-white p-2 rounded-lg text-sm">Sleep Tracking</button>
            </div>
            <div class="flex justify-center gap-3">
                <button class="text-gray-950 md:text-lg bg-gray-300 hover:bg-blue-950 hover:text-white p-2 rounded-lg text-sm">For Kids</button>
            </div>
    </div>
<!--For Tablet-->
    <div class="tb:flex mx-auto justify-center w-10/12 gap-5 flex-col sm:hidden md:hidden ">
            <div class="flex gap-5 justify-center lg:hidden">
                <div><button class="text-gray-950 h-10 md:text-lg tb:text-sm  bg-gray-300 hover:bg-blue-950 hover:text-white p-2 rounded-lg text-sm">Sleep Meditations</button></div>
                <div><button class="text-gray-950 h-10 md:text-lg tb:text-sm  bg-gray-300 hover:bg-blue-950 hover:text-white p-2 rounded-lg text-sm">Sleep Meditations</button></div>
                <div><button class="text-gray-950 h-10 md:text-lg tb:text-sm bg-gray-300 hover:bg-blue-950 hover:text-white p-2 rounded-lg text-sm">Music</button></div>
            </div> 
            <div class="flex gap-5 justify-center lg:hidden">
                <div><button class="text-gray-950 h-10 md:text-lg tb:text-sm bg-gray-300 hover:bg-blue-950 hover:text-white p-2 rounded-lg text-sm">Soundscapes</button></div>
                <div> <button class="text-gray-950 h-10 md:text-lg bg-gray-300 hover:bg-blue-950 hover:text-white p-2 rounded-lg text-sm">For Kids</button></div>
                <div><button class="text-gray-950 h-10 md:text-lg bg-gray-300 hover:bg-blue-950 hover:text-white p-2 rounded-lg text-sm">Sleep Tracking</button></div>
            </div>
    </div>
<!--For large and extra large-->
<div class="flex mx-auto justify-center w-10/12 gap-5 sm:hidden md:hidden tb:hidden lg:flex">
                <div><button class="text-gray-950 h-16 w-auto px-5 md:text-lg tb:text-sm  bg-gray-300 hover:bg-blue-950 hover:text-white p-2 rounded-lg text-sm">Sleep Meditations</button></div>
                <div><button class="text-gray-950 h-16 w-auto px-5 md:text-lg tb:text-sm  bg-gray-300 hover:bg-blue-950 hover:text-white p-2 rounded-lg text-sm">Sleep Meditations</button></div>
                <div><button class="text-gray-950 h-16 w-auto px-5 md:text-lg tb:text-sm bg-gray-300 hover:bg-blue-950 hover:text-white p-2 rounded-lg text-sm">Music</button></div>      
                <div><button class="text-gray-950 h-16 w-auto px-5 md:text-lg tb:text-sm bg-gray-300 hover:bg-blue-950 hover:text-white p-2 rounded-lg text-sm">Soundscapes</button></div>
                <div> <button class="text-gray-950 h-16 w-auto px-5 md:text-lg bg-gray-300 hover:bg-blue-950 hover:text-white p-2 rounded-lg text-sm">For Kids</button></div>
                <div><button class="text-gray-950 h-16 w-auto px-5 md:text-lg bg-gray-300 hover:bg-blue-950 hover:text-white p-2 rounded-lg text-sm">Sleep Tracking</button></div>
            
    </div>
</template>