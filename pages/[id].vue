<template>
    <!-- <div class="flex h-screen bg-txtprimary place-content-center">
        <div class="max-w-xl text-justify shadow-xl p-4 my-auto">
        <p class="font-bold text-center text-xl">Ini adalah routing dari {{ [id] }}</p>
        <p class="">Lorem ipsum dolor sit amet consectetur adipisicing elit. Itaque neque placeat necessitatibus illum eum repellendus iure id qui quidem cupiditate quae quam, obcaecati rerum commodi ut laboriosam enim nemo autem vel eaque. Praesentium fuga quis blanditiis a expedita laboriosam fugit? Sequi in illum aspernatur. Et dolor perspiciatis fuga qui dolorem.</p>
    </div>
    </div> -->

    <div class="flex h-screen bg-txtprimary place-content-center">
        <div class="max-w-xl text-justify shadow-xl p-4 my-auto">
      <main v-if="$route.params.id">
        <h1 class="font-bold text-center text-xl" v-text="'Ini adalah routing dari ' + $route.params.id"></h1>
        <p class="">Lorem ipsum dolor sit amet consectetur adipisicing elit. Itaque neque placeat necessitatibus illum eum repellendus iure id qui quidem cupiditate quae quam, obcaecati rerum commodi ut laboriosam enim nemo autem vel eaque. Praesentium fuga quis blanditiis a expedita laboriosam fugit? Sequi in illum aspernatur. Et dolor perspiciatis fuga qui dolorem.</p>
      </main>
      <main v-else>
        <h1>lalala</h1>
      </main>
    </div>
    </div>
    
   
</template>

<script setup>
// const {  } = useRoute().params
// //console.log(route.params.id)

</script>

<style scoped>

</style>

