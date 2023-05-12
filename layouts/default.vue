<template>
    <div>
        <header class="shadow-sm bg-gray-400">
            <nav class="container mx-auto p-4 flex justify">
                <ul class="flex gap-4">
                    <li><NuxtLink to="/">Home</NuxtLink></li>
                    <li><NuxtLink to="about">About</NuxtLink></li>
                    <li><NuxtLink to="contact">Contact</NuxtLink></li>
                </ul>
            </nav>
        </header>
        
        <div>
            <slot/>
        </div>

    </div>
</template>

<style scoped>
    .router-link-exacct-active{
        color:beige
    }

</style>