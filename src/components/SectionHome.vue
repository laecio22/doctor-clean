<template>
    <section class="block-home">
       <div class="container-content-block-home">
        <div>
            <p>20 anos  de experiência</p>
            <p>Realizando sonhos de um <span>Sorriso Perfeito!</span></p>
            <div class="container-buttons">
                <button class="button-contact">
                  <img src="../assets/icones/icone-whatsapp.png" alt="ícone whatsapp" >
                  Entre  em contato
                </button>
                <button class="button-about">Saiba mais</button>
            </div>
        </div>

      </div>
       <div class="container-image-block-home">
        <img src="../assets/imagens/imagem-sessao-principal.png" alt="imagem de um dentista  e  seu  cliente" />
       </div>
    </section>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
   .block-home{
    background-color: #DAE9F2;
    height: 514px;
    display: flex;
   }

   .container-content-block-home {
     width: 50%;
     display: flex;     
     justify-content: center;
     align-items: center;   
   }

   .container-content-block-home div p {
    font-style: normal;
    font-weight: 700;
    font-size: 44px;
    color: var(--dark);
    width: 540px;
    padding-bottom: 10px;
   }

   .container-content-block-home div p:first-child {
    font-style: normal;
    font-weight: 400;
    font-size: 28px;
    color: var(--darkLight);
   }

   .container-buttons {
    display: flex;
    gap: 30px;
   }

   .container-buttons button {
    font-style: normal;
    font-weight: 700;
    font-size: 18px;
    height: 41px;   
   }

   .container-buttons button.button-contact {
    width: 220px;
    background-color: var(--blueLigh);
    color:#F2F5FA;
    border: none;
    border-radius: 3px;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 8px;   
    cursor: pointer;  
    transition: 0.3s;     
   }

   .container-buttons button.button-contact:hover {
     background-color: var(--blueDark);
   }

   .container-buttons button.button-about {
     width: 129px;
     border: 1px solid rgba(2, 14, 31, 0.09);
     border-radius: 3px;
     background-color: #DAE9F2;
     cursor: pointer;
     transition: 0.3s;
     color: var(--blueDark);
   }

   .container-image-block-home{
    width: 50%;    
   }

   .container-image-block-home img {
    width: 100%;
    height: 100%; 
    object-fit: fill;  

   }


</style>