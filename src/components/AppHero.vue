
<script>
export default {
    name: "AppHero"
}
</script>

<template>
  <div>
    <img src="../assets/vue.svg" alt="vue">
    <img src="../../public/vite.svg" alt="vite">
  </div>
</template>

<style scoped>
    div{
        width: 90%;
        margin: 0 auto;
    }

    div img:first-of-type{
        margin-right: 50px;
    }

    img{
        width: 40%;
    }
</style>