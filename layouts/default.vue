<template>
    <div>
        
            <header class="shadow-sm bg-txtprimary">
                <nav class="text-xl text-secondarycolor font-semibold p-4 flex bg-primarycolor">
                    <ul class="flex gap-4">
                        <li><NuxtLink to="/">Home</NuxtLink></li>
                        <li><NuxtLink to="about">About</NuxtLink></li>
                        <li><NuxtLink to="contact">Contact</NuxtLink></li>
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
</template>


<style scoped>
    .container{
        color: #F1E1AA;
        font-weight: bold;
        font-size: larger;
        /* width:  */
    }
    

</style>