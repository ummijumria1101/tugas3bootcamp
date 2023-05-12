<template>
    <div class="bg-gray-400">
        <h2>home</h2>        
        <h1 class="text-center text-4xl font-semibold text-white">Tutorial membuat membuat antena mikrostrip</h1>
        <img class="image mx-auto h-60 flex item-center" src = "https://images.unsplash.com/photo-1621685207734-a215716273d3?crop=entropy&cs=srgb&fm=jpg&ixid=MnwzMjM4NDZ8MHwxfHJhbmRvbXx8fHx8fHx8fDE2ODM2OTg4NjI&ixlib=rb-4.0.3&q=85">
        
        <p class="card text-justify mx-10">Antena adalah perangkat yang biasanya terbuat dari logam (sebagai tongkat atau kawat) untuk memancarkan dan menerima gelombang radio. Antena adalah komponen utama dalam sistem WLAN. Antena bekerja dengan memancarkan gelombang elektromagnetik dalam arah radial yang terkoordinasi. Antena sangat diperlukan terutama dalam teknologi telekomunikasi saat ini. Antena terdiri dari berbagai jenis, terdapat antena horn, antena yagi uda, antena mikrostrip dan lain lain.</p>

        <h3 class="card font-semibold mx-20">Berikut adalah tutorial membuat salah satu jenis antena yaitu antena mikrostrip:</h3>
        <ul class="card list-decimal pl-5 mx-20">
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
    color: var(--txt-primary);
    /* padding: 32px;
    margin:8px; */
}

.wrapper{
    display: flex;
    justify-content: center;
    width: 100%;
    height: auto;
    text-align: center;   
  
    
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