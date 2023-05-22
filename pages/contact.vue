<template class="">
    <div class="bg-txtprimary">
        <h1 class="mb-10 font-bold text-4xl text-primarycolor tracking-wide text-center">Contact Me</h1>
        <div class="flex place-content-center">
            <!-- <props  :subheading="'Ummi Jumria'" :text="'a finar year student in telkom university with major telecommunication engineering'" :tag1="'ig: um.jriaa'" :tag2="'mail: ummijumria@gmailcom'" :tag3="'linkedin: ummijumria'" /> -->
            <props :subheading="'Ummi Jumria'" :text="'a final year student in telkom university majoring telecommunication engineering'" :tag1="'ummijumria@gmail.com'" :tag2="'ummijumria1101'" :tag3="'ummijumria'" :tag4="'+62 821 2446 0650'"/>
            <div class="flex-none">
                <card :subheading="'Organizational Experience'" :tag="'Dasar Transmisi laboratory'" :tag2="'Senior Residents'" :tag3="'Intellectual Community'"  />
                <card :subheading="'Academic Project Experience'"  :tag="'MBKM KEDAIREKA'" :tag2="'Design Antenna'" :tag3="'Tableau Visualization'"/>
                <card :subheading="'Skill and Abilities'"  :tag="'Simulator Computer Studio (CST)'" :tag2="'Excel'" :tag3="'Python'"/>
                <card :subheading="'Further Contact'"  :tag="'+62 821 244 606 50'" :tag2="'www.linkedin.com/in/ummi-jumria'" :tag3="' github.com/ummijumria1101'"/>

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

</style>