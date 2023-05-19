<template>
    <div>
        <p v-for="user in users">{{users}}</p>
    </div>
</template>

<script>
    import json from '~/asset/users.json'

    export default {
        data() {
            return { 
                users: json
            }
        }
    }
</script>

<style lang="scss" scoped>
//

</style>