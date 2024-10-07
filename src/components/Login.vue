<script>
    import {ref} from 'vue'

    const user = ref('')
    const password = ref('')

</script>


<template>
    <div>

        <input type="text" placeholder="Usuario" v-model="user">
        <input type="text" placeholder="Contraseña" v-model="password">

        <button type="submit">Login</button>

    </div>

</template>

<style scoped>
</style>