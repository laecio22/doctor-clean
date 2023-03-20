<template>
  <ContainerMainVue />
</template>

<script>
import ContainerMainVue from './components/ContainerMain.vue';

export default {
  name: 'App',
  components: {
    ContainerMainVue,    
  }
}
</script>

<style>
:root {
  --blueDark: #0C63DF; 
  --blueLigh : #2098E3;
  --yellow: #FFD502;
  --dark: rgba(2, 14, 31, 0.85);
  --darkLight: rgba(2, 14, 31, 0.69);

}

 *{
   padding: 0;
   margin: 0;
   box-sizing: border-box;

 }

 h1, h2, h3, h4, h5, h6 {
  color: var(--dark);
 }

 body {
   font-size: 16px;
   font-family: 'Inter', sans-serif;   
 }

 ul {
  list-style: none;
 }

 a {
  text-decoration: none;
 }



</style>
