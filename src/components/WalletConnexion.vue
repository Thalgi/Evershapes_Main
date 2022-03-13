<template>
    <button @click="connexion">Connexion</button>
</template>

<script setup>
function connexion() {
    window.location.href = 'https://wallet.elrond.com/hook/login?callbackUrl=http://localhost:3000/';
}
</script>

<style scoped>

</style>
