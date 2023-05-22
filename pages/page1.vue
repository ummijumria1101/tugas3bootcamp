<template>
    <div class="flex">
        <div class="bg-txtprimary">      
        <h1 class="text-center text-4xl font-semibold text-primarycolor p-4">Jenis jenis antena</h1>
        <img class="image mx-auto flex item-center" src = "https://i.postimg.cc/G28cdcB5/Suppression-of-Cross-Polarization-of-the-Microstrip-Integrated-Balun-Fed-Printed-Dipole-Antenna.jpg">
        <div class="ml-10 mr-10 inline-block">
            <p class="text-primarycolor text-justify p-4">Dalam dunia komunikasi modern, antena berperan penting dalam memfasilitasi transmisi dan penerimaan sinyal. Namun, tidak semua antena diciptakan sama. Dalam artikel ini, kita akan menjelajahi berbagai jenis antena yang ada, mulai dari antena Yagi yang populer hingga antena parabola yang mengesankan. </p>
        </div>

        <h3 class="ml-10 mr-10 inline-block font-semibold text-primarycolor pl-4">Mari kita eksplorasi jenis-jenis antena ini dan temukan solusi komunikasi yang tepat untuk kebutuhan Anda.</h3>
        <div class="mr-10 ml-10">
            <ul class="ml-10 mr-10 inline-block mb-50 list-decimal text-primarycolor pb-8 pl-8 text-justify">
            <li><b>Antena Yagi</b></li>
            <p>Antena Yagi adalah salah satu jenis antena yang paling umum dan populer. Dikenal dengan tampilan garis-garis elemen logamnya, antena Yagi efisien dalam mengarahkan sinyal pada satu arah tertentu. Artikel ini akan membahas prinsip kerja, keunggulan, dan aplikasi antena Yagi dalam berbagai konteks, mulai dari komunikasi nirkabel hingga penyiaran TV.</p> <br>
            <li><b>Antena Dipole</b></li>
            <p>Antena Dipol merupakan jenis antena yang cukup sederhana dan sering digunakan dalam komunikasi radio dan TV. Artikel ini akan menjelaskan konsep dasar antena Dipol, termasuk struktur dan mode radiasi yang unik. Kami juga akan membahas kelebihan dan kelemahan antena Dipol serta penerapannya dalam berbagai aplikasi komunikasi.</p> <br>
          <li><b>Antena Parabola</b></li>
          <p>Siapa yang tidak mengenal antena parabola yang mengesankan? Artikel ini akan memperkenalkan prinsip dasar dan struktur antena parabola yang memungkinkan pemfokusan sinyal pada satu titik fokus. Kami akan menjelajahi keunggulan antena parabola dalam komunikasi satelit dan TV satelit serta memberikan wawasan tentang instalasi dan penyetelan yang efektif.</p> <br>
          <li><b>Antena Mikrostrip</b></li>
          <p>Antena Mikrostrip adalah jenis antena yang ringkas dan sering digunakan dalam aplikasi elektronik modern, seperti komunikasi nirkabel dan radar. Artikel ini akan menjelaskan desain dan struktur dasar antena Mikrostrip, serta memperkenalkan keunggulan dan kelemahan yang melekat pada jenis antena ini. Kami juga akan memberikan informasi tentang aplikasi praktis antena Mikrostrip dalam berbagai sistem komunikasi.</p>   
          </ul>  
        </div>
   
        <p class="text-primarycolor text-justify p-4 ml-10 mr-10 pb-5">Dalam dunia yang terus berkembang ini, pemahaman tentang berbagai jenis antena menjadi kunci untuk mencapai komunikasi yang efektif dan andal. Dalam artikel ini, kita telah menjelajahi empat jenis antena yang menarik, mulai dari antena Yagi yang terkenal hingga antena Mikrostrip yang inovatif. Semoga pengetahuan ini membantu Anda dalam memilih solusi komunikasi yang tepat untuk memenuhi kebutuhan Anda. Jadi, pilihlah jenis antena yang sesuai dan sambutlah era komunikasi yang lebih baik dengan antena yang tepat!</p>

        </div>
        <div class="flex-col bg-txtprimary drop-shadow-xl max-w-fit max-h-50">
            <div>
                <p class="text-center font-semibold text-lg">Other Page</p>
            </div>
            <div>
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
            </div>
            <div>
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
            </div>
            <div>
                <NuxtLink to="page3">
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