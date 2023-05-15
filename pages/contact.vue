<template class="">
    <div class="bg-gray-400">
        <NuxtLayout :name="default"></NuxtLayout>
    </div>
    <div class="card bg-gray-400">      
        <h3 class="mx-10">Saya ummi jumria seorang mahasiswa S1 Teknik Telekomunikasi di Universitas Telkom. Untuk kontak lebih jauh bisa pada:</h3>
        <ul class="mx-10">
            <li>Email : ummijumria@gmail.com</li>
            <li>instagram : um.jriaa</li>
            <li>linkedin : ummijumria</li>
        </ul>
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
    .wrapper{
    display: flex;
    justify-content: center;
    width: 100%;
    height: auto;
    text-align: center;   

}
.card{
   
   background-color: rgb(156 163 175); 
   height: 100vh;
   /* padding: 32px;
   margin:8px; */
}
</style>