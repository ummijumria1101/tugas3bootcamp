<template>
    <div class="flex p-2 place-content-center">
        <div class="flex">
            <div class="max-w-sm rounded overflow-hidden shadow-lg">
            <img class="w-full" :src="image" />
            <div class="px-6 pt-4">
                <div class="font-bold text-xl mb-2">{{ subheading }}</div>
                <p class="text-gray-700 text-base">
                {{ text }}
                </p>
            </div>
            <div class="px-6 pt-4 pb-2">
                <div class="">
                    <div class="flex">
                        <a href="mailto:ummijumria@gmail.com">
                            <img class="object-none items-center hover:bg-primarycolor rounded-md" src="~/assets/img/iconemail.png">
                        </a>
                        <p class="px-3 text-base font-semibold mb-2">{{ tag1 }}</p>
                    </div>
                    <div class="flex">
                        <a href="https://github.com/ummijumria1101"> <img class="object-none items-center hover:bg-primarycolor rounded-md" src="~/assets/img/icongithub.png"></a>                       
                        <p class="px-3 text-base font-semibold mb-2">{{ tag2 }}</p>

                    </div>
                    <div class="flex align-middle">
                        <a href="https://www.linkedin.com/in/ummi-jumria/">
                            <img class="object-none items-center hover:bg-primarycolor rounded-md" src="~/assets/img/iconlinkedin.png">
                        </a>
                        
                        <p class="px-3 text-base font-semibold mb-2">{{ tag3 }}</p>

                    </div>
                    <div class="flex">
                        <a href="wa.me/+6282124460650">
                            <img class="object-none items-center hover:bg-primarycolor rounded-md" src="~/assets/img/iconwa.png">
                        </a>
                        
                        <p class="px-3 text-base font-semibold mb-2">{{ tag4 }}</p>

                    </div>
                    

                </div>
                <!-- <ol>
                    <li class="px-3 py-1 text-base font-semibold mr-2 mb-2">{{ tag1 }}</li>
                    <li class="px-3 py-1 text-base font-semibold mr-2 mb-2">{{ tag2 }}</li>
                    <li class="px-3 py-1 text-base font-semibold mr-2 mb-2">{{ tag3 }}</li>
                    <li class="px-3 py-1 text-base font-semibold mr-2 mb-2">{{ tag4 }}</li>
                </ol> -->
                <!-- <span class="inline-block bg-primarycolor rounded-full px-3 py-1 text-sm font-semibold mr-2 mb-2">{{ tag1 }}</span>
                <span class="inline-block bg-primarycolor rounded-full px-3 py-1 text-sm font-semibold  mr-2 mb-2">{{ tag2 }}</span>
                <span class="inline-block bg-primarycolor rounded-full px-3 py-1 text-sm font-semibold  mr-2 mb-2">{{ tag3 }}</span> -->
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
        tag4: String,
    })

</script>