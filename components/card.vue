<template>
    <div class="flex p-2 place-content-center">
        <div class="flex-none">
            <div class="max-w-sm rounded overflow-hidden shadow-lg">
            <div class="px-6 py-4">
                <div class="font-bold text-xl mb-2">{{ subheading }}</div>
            </div>
            <div class="px-6 pt-4 pb-2">
                <span class="inline-block bg-primarycolor rounded-full px-3 py-1 text-sm font-semibold mr-2 mb-2">{{ tag }}</span>
                <span class="inline-block bg-primarycolor rounded-full px-3 py-1 text-sm font-semibold  mr-2 mb-2">{{ tag2 }}</span>
                <span class="inline-block bg-primarycolor rounded-full px-3 py-1 text-sm font-semibold  mr-2 mb-2">{{ tag3 }}</span>
                <slot />
            </div>
                </div>


    </div>
    </div>
        
</template>

<script setup>
    const props = defineProps({
        // title: String,
        subheading: String,
        text: String,
        tag: String,
        tag2: String,
        tag3: String,
    })

</script>