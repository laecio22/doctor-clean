<template>
    <div class="container">
       <HeaderApp></HeaderApp>
       <SectionHome></SectionHome>
       <SectionDiferencial></SectionDiferencial>
    </div>
</template>

<script >
  import HeaderApp from './HeaderApp.vue';
  import SectionDiferencial from './SectionDiferencial.vue';
  import SectionHome from './SectionHome.vue';
  
  export default {
    name: "containerMain",
    components: {
      HeaderApp,
      SectionHome,
      SectionDiferencial,
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