<template>
    <div>
        <div>        
                <header class="shadow-sm bg-txtprimary">

                    <nav class="text-xl text-secondarycolor font-semibold p-4 flex bg-primarycolor content-center">
                        <NuxtLink to="/" class="object-scale-down w-11">
                            <img src="~/assets/img/aboutus.png">
                        </NuxtLink>

                        <ul class="flex gap-4 my-2 mx-5">
                            <li><NuxtLink to="/" class="hover:bg-buttoncolor rounded-md p-1">Home</NuxtLink></li>
                            <li><NuxtLink to="about" class="hover:bg-buttoncolor rounded-md p-1">About</NuxtLink></li>
                            <li><NuxtLink to="contact" class="hover:bg-buttoncolor rounded-md p-1">Contact</NuxtLink></li>
                        </ul>
                    </nav>
                </header>
            
                <slot />
                   
                <div class="flex shadow-xl place-content-center bg-txtbase">
                    <footer class="max-w-sm text-center overflow-hidden font-semibold text-txtprimary">
                <h3 class="">© 2023 Ummi Jumria, Bootcamp Juke Technology. All rights reserved</h3>
                </footer>
                </div>  
        </div>
    </div>
</template>


<style scoped>    

</style>