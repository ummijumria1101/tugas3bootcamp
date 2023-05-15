<template class="bg-gray-400">
    <div class="bg-gray-400">
        <NuxtLayout :name="default"></NuxtLayout>
    </div>
    <div class="card bg-gray-400 m-8">      
        <h2 class="text-center text-4xl font-semibold text-white">Untuk tutorial lebih lanjut bisa dilihat pada link youtube berikut</h2>
            
        </div>
    
</template>

<script setup>

</script>

<style lang="scss" scoped>
    h2 {
        margin-bottom: 20px;
        font-size: 20px;
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
   
    background-color: rgb(156 163 175); 
    height: 100vh;
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