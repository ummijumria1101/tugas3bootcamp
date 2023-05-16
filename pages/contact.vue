<template class="">
    <div class="bg-txtprimary">
        <h1 class="mb-10 font-bold text-4xl text-primarycolor tracking-wide text-center">Contact Me</h1>
        <div class="flex place-content-center">
            <props  :subheading="'Ummi Jumria'" :text="'a finar year student in telkom university with major telecommunication engineering'" :tag1="'ig: um.jriaa'" :tag2="'mail: ummijumria@gmailcom'" :tag3="'linkedin: ummijumria'" />
            <div class="flex-none">
                <card :subheading="'Organizational Experience'" :tag="'Dasar Transmisi laboratory'" :tag2="'Senior Residents'" :tag3="'Intellectual Community'"  />
                <card :subheading="'Academic Project Experience'"  :tag="'MBKM KEDAIREKA'" :tag2="'Design Antenna'" :tag3="'Tableau Visualization'"/>
                <card :subheading="'Skill and Abilities'"  :tag="'Simulator Computer Studio (CST)'" :tag2="'Excel'" :tag3="'Python'"/>
                <card :subheading="'Further Contact'"  :tag="'+62 821 244 606 50'" :tag2="'www.linkedin.com/in/ummi-jumria'" :tag3="' github.com/ummijumria1101'"/>

            </div>
       

        </div>

        <!-- <card :title="hello" :subheading="inicontohdoang" :text="iniadalahtext" :tag="sdfa">cobaje</card> -->

    </div>
    
   <!-- <div class="flex bg-txtprimary w-full min-h-screen justify-center item-center">
        <h1 class="font-bold text-4xl tracking-wide">Contact Me</h1>
                <p class="pt-2 text-sm">Untuk kontak lebih jauh bisa cek kontak dibawah ini^^</p>
                <h3>+62 821 244 606 50</h3>
                    <h3>ummijumria@gmail.com</h3>
        <div class="flex flex-col space-y-6 bg-white w-full max-w-4xl p-8 rounded-xl shadow lg text-primarycolor">
        </div>   
         <div class="flex flex-col justify-between text-primarycolor"> 
            <div>

            </div>

        </div>        
    </div> --> 

</template>

<script>
    export default {
    layout: 'default',
}

</script>

<style lang="scss" scoped>
    h2 {
        margin-bottom: 20px;
        font-size: 20px;
    }
    p{
        margin: 20px 0;
    }


</style>