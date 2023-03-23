<template>
    <div class="container">
       <HeaderApp></HeaderApp>
       <SectionHome></SectionHome>
    </div>
</template>

<script >
  import HeaderApp from './HeaderApp.vue';
  import SectionHome from './SectionHome.vue';
  export default {
    name: "containerMain",
    components: {
      HeaderApp,
      SectionHome
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