<template>
    <div class="flex p-2 place-content-center">
        <div class="flex">
            <div class="max-w-sm rounded overflow-hidden shadow-lg">
            <img class="w-full" :src="image" />
            <div class="px-6 py-4">
                <div class="font-bold text-xl mb-2">{{ subheading }}</div>
                <p class="text-gray-700 text-base">
                {{ text }}
                </p>
            </div>
            <div class="px-6 pt-4 pb-2">
                <span class="inline-block bg-primarycolor rounded-full px-3 py-1 text-sm font-semibold mr-2 mb-2">{{ tag1 }}</span>
                <span class="inline-block bg-primarycolor rounded-full px-3 py-1 text-sm font-semibold  mr-2 mb-2">{{ tag2 }}</span>
                <span class="inline-block bg-primarycolor rounded-full px-3 py-1 text-sm font-semibold  mr-2 mb-2">{{ tag3 }}</span>
                <slot />
            </div>
                </div>


    </div>
    </div>
        
</template>

<script setup>
    import image from "../assets/img/me.jpg"
    const props = defineProps({
        image: String,
        subheading: String,
        text: String,
        tag1: String,
        tag2: String,
        tag3: String,
    })

</script>