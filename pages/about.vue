<template class="">
    <div class="">
        <NuxtLayout :name="default"></NuxtLayout>
    </div>
    <div class="bg-txtprimary">     
        <!-- <h2 class="text-4xl text-center font-semibold">Tentang Website</h2>  -->
        <div class="wrapper justify-center inline-block align-middle">
            <div class=" bg-txtprimary space-x-10 object-cover h-300 w-full">
                <img class="item-center " src = "https://i.postimg.cc/PqqVzdht/aboutus.png">
            </div>
            <div class="mr-100 bg-txtprimary text-primarycolor">
                <h3 class="card text-4xl text-center font-semibold space-y-80">Tentang Website</h3>
                <p class="card1 space-x-10 text-justify">Website ini dibuat sebagai bagian dari tugas bootcamp yang diadakan oleh PT Juke Teknologi. Dalam rangkaian program bootcamp ini, peserta diberikan kesempatan untuk mempelajari dan mengembangkan keterampilan dalam pengembangan website. Dengan membangun website ini, peserta dapat mengaplikasikan pengetahuan yang telah mereka peroleh dan memperlihatkan kemampuan mereka dalam merancang dan membangun sebuah situs web fungsional. Tujuan dari pembuatan website ini adalah untuk memberikan kesempatan kepada peserta untuk berlatih dan memperluas pemahaman mereka tentang teknologi web, serta untuk memperkuat keterampilan mereka dalam menghadapi tantangan pengembangan perangkat lunak.</p>
            </div>
        </div>
    </div>
    <div>
        
    </div>
    
</template>

<script setup>

</script>

<style lang="scss" scoped>
   /* h2 {
        margin-bottom: 20px;
        font-size: 20px;
    }  */
   /* p{
        margin: 20px 0;
    } */

    *,
html, 
body{
    margin:0;
    padding: 0;
    font-family: 'Poppins', sans-serif;
   

}


.card{
    margin-top: 30px;
    margin-bottom: 20px;
   // text-size-adjust: 50px;
    /* padding: 32px;
    margin:8px; */
}

.card1{
    margin-right: 50px;
}

.wrapper{
    display: flex;
    justify-content: center;
    // width: auto;
   height: 100vh;
   padding-top: 100px;
   background-color: #F1E1AA ;
   // text-align: center; 
   // vertical-align:20px;
  //  margin-top: 50px;
    // margin-left:
   // margin: 100px;  
    //margin-right: 100px;
  
    
}
.cardd{
    border:1px solid #f0f0d6;
    padding: 32px;
    margin:8px;
}

.image{
  border:1px solid #f0f0d6;
}
.icons{
    font-size: 20px;
    color: var(--icon-bg-primary);

}

.hs-responsive-embed-youtube {
position: relative;
padding-bottom: 56.25%; /* 16:9 Aspect Ratio */
padding-top: 25px;
}
.hs-responsive-embed-youtube iframe {
position: absolute;
width: 100%!important;
height: 100%!important;
}
</style>