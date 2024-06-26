<template>
    <div class="lg:hidden">
    <div class=" h-auto p-5 rounded-md tb:w-5/12 tb:mx-auto" v-if="count == '1'">
    <div class="flex justify-center flex-col gap-5">
        <img class="rounded-lg h-60"  src="https://images.squarespace-cdn.com/content/v1/656f4e4dababbd7c042c4946/37f850e0-0003-4c40-8cc7-fdf656fbccb7/PDF+mock-up.jpg?format=1500w" alt="">
        <div class="mx-auto bg-white">
            <p class="text-sm">Meditation & Mindfulness, Mental Health</p>
            <h1 class="text-md font-bold">Empower yourself with the "Pride in Practice" guide for LGBTQ+ individuals by Dr. Moon</h1>
        </div>
    </div>
</div>

<div class=" h-auto p-5 rounded-md tb:w-5/12 tb:mx-auto" v-if="count == '2'">
    <div class="flex justify-center flex-col gap-5">
        <img class="rounded-lg h-60"  src="https://images.squarespace-cdn.com/content/v1/656f4e4dababbd7c042c4946/504dc703-8208-4dfb-9450-4a4d426dda24/CalmConversations_Dr.Moon%26RaymondBraun_1000x656.jpg?format=1500w" alt="">
        <div class="mx-auto bg-white">
            <p class="text-sm">Mental Health</p>
            <h1 class="text-md font-bold">Pride & Resilience: 5 highlights from Dr. Moon & Raymond Braun</h1>
        </div>
    </div>
</div>
<div class=" h-auto p-5 rounded-md tb:w-5/12 tb:mx-auto" v-if="count == '3'">
    <div class="flex justify-center flex-col gap-5">
        <img class="rounded-lg h-60"  src="https://images.squarespace-cdn.com/content/v1/656f4e4dababbd7c042c4946/92b2618f-808f-41b0-9efd-e560f0e6ebff/thc-and-anxiety-3x2.jpg?format=1500w" alt="">
        <div class="mx-auto bg-white">
            <p class="text-sm">Stress & Anxiety</p>
            <h1 class="text-md font-bold">Does THC Cause anxiety? Effects of THC vs CBD on mental health</h1>
        </div>
    </div>
</div>
<div class=" h-auto p-5 rounded-md tb:w-5/12 tb:mx-auto" v-if="count == '4'">
    <div class="flex justify-center flex-col gap-5">
        <img class="rounded-lg h-60"  src="https://images.squarespace-cdn.com/content/v1/656f4e4dababbd7c042c4946/32121605-ba2a-4e19-9497-1e04c1d1a7fb/job-loss-anxiety-3x2.jpg?format=1500w" alt="">
        <div class="mx-auto bg-white">
            <p class="text-sm">Strees & Anxiety, Worksplace wellness</p>
            <h1 class="text-md font-bold">Job loss anxiety: How to handle the stress of losing your job</h1>
        </div>
    </div>
</div>
<div class=" h-auto p-5 rounded-md tb:w-5/12 tb:mx-auto" v-if="count == '5'">
    <div class="flex justify-center flex-col gap-5">
        <img class="rounded-lg h-60"  src="https://images.squarespace-cdn.com/content/v1/656f4e4dababbd7c042c4946/eb2ef480-ae6e-4732-a8a2-c713369da644/fear-of-being-sober-3x2.jpg?format=1500w" alt="">
        <div class="mx-auto bg-white">
            <p class="text-sm">Stress & Anxiety</p>
            <h1 class="text-md font-bold">8 Tips to help your overcome the fear of being sober</h1>
        </div>
    </div>
</div>
<div class=" h-auto p-5 rounded-md tb:w-5/12 tb:mx-auto" v-if="count == '6'">
    <div class="flex justify-center flex-col gap-5">
        <img class="rounded-lg h-60"  src="https://images.squarespace-cdn.com/content/v1/656f4e4dababbd7c042c4946/924d16df-e119-4604-983d-b4bd9e52354a/stress-balls-3x2.jpg?format=1500w" alt="">
        <div class="mx-auto bg-white">
            <p class="text-sm">Stress & Anxiety</p>
            <h1 class="text-md font-bold">What are stress balls (and do they really work)?</h1>
        </div>
    </div>
</div>
</div>


<div class="sm:hidden md:hidden tb:hidden lg:grid lg:grid-cols-3">
    <div class=" p-5 rounded-md tb:w-5/12 tb:mx-auto lg:w-auto">
        <div class="flex justify-center flex-col gap-5">
            <img class="rounded-lg h-60"  src="https://images.squarespace-cdn.com/content/v1/656f4e4dababbd7c042c4946/37f850e0-0003-4c40-8cc7-fdf656fbccb7/PDF+mock-up.jpg?format=1500w" alt="">
            <div class="mx-auto bg-white">
                <p class="text-sm">Meditation & Mindfulness, Mental Health</p>
                <h1 class="text-md font-bold">Empower yourself with the "Pride in Practice" guide for LGBTQ+ individuals by Dr. Moon</h1>
            </div>
        </div>
    </div>

    <div class=" h-auto p-5 rounded-md tb:w-5/12 tb:mx-auto lg:w-auto">
        <div class="flex justify-center flex-col gap-5 ">
            <img class="rounded-lg h-60"  src="https://images.squarespace-cdn.com/content/v1/656f4e4dababbd7c042c4946/504dc703-8208-4dfb-9450-4a4d426dda24/CalmConversations_Dr.Moon%26RaymondBraun_1000x656.jpg?format=1500w" alt="">
            <div class="mx-auto bg-white">
                <p class="text-sm">Mental Health</p>
                <h1 class="text-md font-bold">Pride & Resilience: 5 highlights from Dr. Moon & Raymond Braun</h1>
            </div>
        </div>
    </div>
    <div class=" h-auto p-5 rounded-md tb:w-5/12 tb:mx-auto lg:w-auto">
        <div class="flex justify-center flex-col gap-5">
            <img class="rounded-lg h-60"  src="https://images.squarespace-cdn.com/content/v1/656f4e4dababbd7c042c4946/92b2618f-808f-41b0-9efd-e560f0e6ebff/thc-and-anxiety-3x2.jpg?format=1500w" alt="">
            <div class="mx-auto bg-white">
                <p class="text-sm">Stress & Anxiety</p>
                <h1 class="text-md font-bold">Does THC Cause anxiety? Effects of THC vs CBD on mental health</h1>
            </div>
        </div>
    </div>
    <div class=" h-auto p-5 rounded-md tb:w-5/12 tb:mx-auto lg:w-auto">
        <div class="flex justify-center flex-col gap-5">
            <img class="rounded-lg h-60"  src="https://images.squarespace-cdn.com/content/v1/656f4e4dababbd7c042c4946/32121605-ba2a-4e19-9497-1e04c1d1a7fb/job-loss-anxiety-3x2.jpg?format=1500w" alt="">
            <div class="mx-auto bg-white">
                <p class="text-sm">Strees & Anxiety, Worksplace wellness</p>
                <h1 class="text-md font-bold">Job loss anxiety: How to handle the stress of losing your job</h1>
            </div>
        </div>
    </div>
    <div class=" h-auto p-5 rounded-md tb:w-5/12 tb:mx-auto lg:w-auto">
        <div class="flex justify-center flex-col gap-5">
            <img class="rounded-lg h-60"  src="https://images.squarespace-cdn.com/content/v1/656f4e4dababbd7c042c4946/eb2ef480-ae6e-4732-a8a2-c713369da644/fear-of-being-sober-3x2.jpg?format=1500w" alt="">
            <div class="mx-auto bg-white">
                <p class="text-sm">Stress & Anxiety</p>
                <h1 class="text-md font-bold">8 Tips to help your overcome the fear of being sober</h1>
            </div>
        </div>
    </div>
    <div class=" h-auto p-5 rounded-md tb:w-5/12 tb:mx-auto lg:w-auto">
        <div class="flex justify-center flex-col gap-5">
            <img class="rounded-lg h-60"  src="https://images.squarespace-cdn.com/content/v1/656f4e4dababbd7c042c4946/924d16df-e119-4604-983d-b4bd9e52354a/stress-balls-3x2.jpg?format=1500w" alt="">
            <div class="mx-auto bg-white">
                <p class="text-sm">Stress & Anxiety</p>
                <h1 class="text-md font-bold">What are stress balls (and do they really work)?</h1>
            </div>
        </div>
    </div>
</div>




<div class="flex items-center justify-center mb-5 gap-5 lg:hidden">
    <img class="h-9 bg-slate-500 rounded-3xl p-2"src="assets\left-arrow-backup-2-svgrepo-com.svg" @click="previous" alt="">
    <img class="h-9 bg-slate-500 rounded-3xl p-2"src="assets\right-arrow-svgrepo-com.svg" @click="next" alt="">
    
</div>
<div>{{ count }}</div>

</template>

<script setup>
import { ref } from 'vue';
const count = ref(1);
function next() {
        count.value++;
        // if(count.value >= 4){
        //     count == 1;
        // }
    }


function previous() {
    count.value--;
}




</script>