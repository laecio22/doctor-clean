<template>
    <div class="container">
       <HeaderApp></HeaderApp>
    </div>
</template>

<script >
  import HeaderApp from './HeaderApp.vue';
  export default {
    name: "containerMain",
    components: {
      HeaderApp
    }

  }
</script>

<style scoped>
  .container {
    width: 100%;
    min-height: 100vh;
    background-color: #F2F5FA;
  }
</style>