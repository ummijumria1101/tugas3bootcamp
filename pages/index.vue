<template>
    <div class="bg-gray-400">
        <NuxtLayout :name="default"></NuxtLayout>
    </div>
    <div class="bg-gray-400">      
        <h1 class="text-center text-4xl font-semibold text-white">Tutorial membuat membuat antena mikrostrip</h1>
        <img class="image mx-auto h-60 flex item-center" src = "https://i.postimg.cc/G28cdcB5/Suppression-of-Cross-Polarization-of-the-Microstrip-Integrated-Balun-Fed-Printed-Dipole-Antenna.jpg">
        
        <p class="card text-justify">Antena adalah perangkat yang biasanya terbuat dari logam (sebagai tongkat atau kawat) untuk memancarkan dan menerima gelombang radio. Antena adalah komponen utama dalam sistem WLAN. Antena bekerja dengan memancarkan gelombang elektromagnetik dalam arah radial yang terkoordinasi. Antena sangat diperlukan terutama dalam teknologi telekomunikasi saat ini. Antena terdiri dari berbagai jenis, terdapat antena horn, antena yagi uda, antena mikrostrip dan lain lain.</p>

        <h3 class="card font-semibold">Berikut adalah tutorial membuat salah satu jenis antena yaitu antena mikrostrip:</h3>
        <ul class="card2 ml-50 list-decimal">
            <li>Tentukan jenis patch yang akan dibuat</li>
            <li>Buat spesifikasi antena yang diinginkan</li>
          <li>Menghitung dimensi antena</li>
          <li>Mendesain antena di software CST</li>
          <li>Mencoba simulasi antena di software CST</li>
          <li>Memeriksa spesifikasi antena seperti VSWR dan return loss apakah sudah sesuai atau belum</li>
          <li>Jika belum sesuai optimasi dimensi antena di CST</li>
          <li>Fabrikasi antena yang spesifikasinya sudah sesuai di CST</li>
          <li>Mengukur antena yang sudah di fabrikasi dengan Vector Network Analyzer (VNA), pastikan spesifikasi antena sudah sesuai</li>
          <li>Antena telah jadi</li>   
          </ul>
            
        </div>
        

    
</template>

<script setup>

</script>

<style lang="scss" scoped>
    h2 {
        margin-bottom: 20px;
        font-size: 36px;
    }
    p{
        margin: 20px 0;
    }

    *,
html, 
body{
    margin:0;
    padding: 0;
    font-family: 'Poppins', sans-serif;
   

}

:root{
    --bg-primary: #383454;
    --bg-secondary: #8c4444;
    --txt-primary: #f0f0d6;
    --icon-bg-primary:#f0f0d6;
}

.card{
   /* border:1px solid #f0f0d6;
     background-color: var(--bg-secondary); */
    color: #1b1e23;
    /* padding: 32px;
    margin:8px; */
    margin-left: 0.875rem; /* 14px */
    margin-right: 0.875rem; /* 14px */
}
.card2{
   /* border:1px solid #f0f0d6;
     background-color: var(--bg-secondary); */
    color: #1b1e23;
    /* padding: 32px;*/
    margin-left:50px; 
    margin-top: 0px;


}

.wrapper{
    display: flex;
    justify-content: center;
    width: 100%;
    height: auto;
    text-align: center;   
  
    
}

.image{
  border:1px solid #f0f0d6;
  align-items: center;
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 50%;

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