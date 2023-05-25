<template>
    <div class="bg-txtprimary h-screen">
        <div class="bg-txtprimary">      
            <h1 class="text-center text-4xl font-semibold text-primarycolor p-4">Tugas 8 - Pengkondisian</h1>
            <p class="text-center font-semibold text-lg">Perhitungan Diskon Belanja</p>
        </div>
        
        <p class="text-center text-base p-4">Selamat datang di situs kami, tempat di mana Anda dapat menemukan informasi terkini tentang berbagai diskon menarik! Apakah Anda mencari kesempatan untuk menghemat uang saat berbelanja? Anda telah datang ke tempat yang tepat.</p>
        
        <div class="p-5 text-center">
            <label for="jumlah">Masukkan total harga:</label>
            <input  id="jumlah" placeholder="Input harga" class="p-2 rounded-md">
            
            <div class="bg-primarycolor m-2 p-2 rounded-lg">
                    <button onclick="hitungDiskon()">Total Diskon</button>
            </div>      
      
            <p id="disk"></p> 
            <p id="total"></p>
            <button @click="increment">Count is: {{ count }}</button>
      
        </div> 

    </div>         
</template>

<script >

export default {
  // Properties returned from data() become reactive state
  // and will be exposed on `this`.
  data() {
    return {
      count: 0
    }
  },

  // Methods are functions that mutate state and trigger updates.
  // They can be bound as event handlers in templates.
  methods: {
    increment() {
      this.count++
    }
  },

  // Lifecycle hooks are called at different stages
  // of a component's lifecycle.
  // This function will be called when the component is mounted.
  mounted() {
    console.log(`The initial count is ${this.count}.`)
  }
}


    // function hitungDiskon() {
    //     const jumlahInput = document.getElementById('jumlah');
    //     const jumlah = parseFloat(jumlahInput.value);
        
    //     let disk = 0;
    //     let total = 0;
        
    //     if (jumlah >= 100000) {
    //         disk = 10;
    //     } else if (jumlah >= 50000) {
    //         disk = 5;
    //     }
    //     else
    //         disk=0;
        
    //     total = jumlah - ((disk/100) *jumlah);
        
    //     const Display = document.getElementById('disk');

    //     const jumlahDisplay = document.getElementById('total');
        
    //     Display.textContent = `Anda mendapat diskon sebesar: ${disk}%`;
    //     jumlahDisplay.textContent = `Jumlah total belanjaan anda: Rp ${total}`;
    // }

</script>

<style lang="scss" scoped>
//

</style>