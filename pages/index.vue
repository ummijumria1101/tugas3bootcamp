<template>
    <div class="opacity-50 h-1/2 w-full mt-1">
        <img src="~/assets/img/test.jpg">
    </div>     
    <div class="flex mt-1">
        <div class="bg-txtprimary"> 

        <h1 class="text-center text-4xl font-semibold text-primarycolor pt-10">Antena Expert <br/> Panduan Lengkap dan Informasi Terkini tentang Antena</h1>
        <!-- <img class="image mx-auto flex item-center m-5" src = "https://i.postimg.cc/G28cdcB5/Suppression-of-Cross-Polarization-of-the-Microstrip-Integrated-Balun-Fed-Printed-Dipole-Antenna.jpg"> -->
        <div class="ml-10 mr-10 inline-block">
            <p class="text-primarycolor text-justify p-4 text-lg font-semibold">Selamat datang di website kami yang penuh dengan pengetahuan menarik seputar dunia antena! Apakah Anda penasaran tentang bagaimana antena dibuat? Atau ingin mengenal berbagai jenis antena yang ada? Di sini, Anda akan menemukan panduan yang lengkap serta jurnal terkait yang akan memperkaya pengetahuan Anda tentang teknologi antena. Bersiaplah untuk menjelajahi dunia yang menarik ini dan temukan potensi tak terbatas dari pembuatan dan penerapan antena.</p>
        </div>
    

        <div class="flex">
            <NuxtLink to="page1">
                <v-card class="flex place-content-center">
                    <div class="shadow-lg p-4 hover:bg-hovercolor rounded-md">
                        <div class="max-w-sm">
                            <img src="~/assets/img/aboutus.png">
                        </div>
                        <div>
                            <p class="text-base text-center">Menjelajahi Jenis-Jenis Antena Mikrostrip</p>
                        </div>
                        
                    </div>            
                </v-card>

            </NuxtLink>
            <NuxtLink to="page2">
                <v-card class="flex place-content-center">
                    <div class="shadow-lg p-4 m-2 hover:bg-hovercolor rounded-md">
                        <div class="max-w-sm">
                            <img src="~/assets/img/aboutus.png">
                        </div>
                        <div>
                            <p class="text-base text-center">Panduan Lengkap Pembuatan Antena</p>
                        </div>
                        
                    </div>            
                </v-card>

            </NuxtLink>
            <NuxtLink to="page3">
                <v-card class="flex place-content-center">
                    <div class="shadow-lg p-4 m-2 hover:bg-hovercolor rounded-md">
                        <div class="max-w-sm">
                            <img src="~/assets/img/aboutus.png">
                        </div>
                        <div>
                            <p class="text-base text-center">Menyelami Dunia Penelitian Terkait Antena</p>
                        </div>
                        
                    </div>            
                </v-card>

            </NuxtLink>
            <NuxtLink to="page4">
                <v-card class="flex place-content-center">
                    <div class="shadow-lg p-4 m-2 hover:bg-hovercolor rounded-md">
                        <div class="max-w-sm">
                            <img src="~/assets/img/aboutus.png">
                        </div>
                        <div>
                            <p class="text-base text-center">Tips dan Trik untuk Meningkatkan Kinerja Antena</p>
                        </div>
                        
                    </div>            
                </v-card>

            </NuxtLink>
        </div>
>
        </div>
        <div class="flex-col bg-txtprimary drop-shadow-xl w-1/2 max-h-50">
            <NuxtLink to="page3">
                <v-card class="flex place-content-center">
                    <div class="shadow-lg p-4 m-2 hover:bg-hovercolor rounded-md">
                        <div class="max-w-sm">
                            
                        </div>
                        <div>
                            <p class="text-base text-center">Tugas 8 - Pengkondisian (Diskon)</p>
                        </div>
                        
                    </div>            
                </v-card>

            </NuxtLink>
            <div class="">
                <p class="text-justify p-4 mt-10">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Dolores excepturi mollitia quidem adipisci, sapiente enim quis dignissimos vero necessitatibus soluta!</p>
            </div>
            <div>
                <p class="text-justify p-4">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Dolores excepturi mollitia quidem adipisci, sapiente enim quis dignissimos vero necessitatibus soluta!</p>
            </div>

        </div>

    </div>

        

    
</template>

<script>
    export default {
    layout: 'default',
}

</script>

<style lang="scss" scoped>
//

</style>