<template>
    <header>
        <section class="section-logo">     
            <div class="group-logo">
                <img src="../assets/imagens/dente-superior.png" alt="icone parte  superior do dente" class="image-dente-superior"/>
                <img src="../assets/imagens/dente-inferior.png" alt="icone  parte  inferior  do dente" class="image-dente-inferior" />
            </div>
            <div>
                <h4 class="title-logo">Odonto Clean</h4>
                <p>Clínica  odontológica</p>
            </div>
        </section>
        <section class="section-nav-links">
            <ul class="nav-links">
                <li><a href="#">Home</a></li>
                <li><a href="#">Sobre</a></li>
                <li><a href="#">Profissionais</a></li>
                <li><a href="#">Tratamentos</a></li>
                <li><a href="#">Dúvidas</a></li>
            </ul>
            <button>
                <img src="../assets/icones/icone-agendamento.png"  alt="ícone de  calendário"/>
                Agendar
            </button>
        </section>
    </header>
</template>

<script setup>

</script>

<style scoped>
   header {
    height: 80px;
    display: flex;
    justify-content: space-between;
    margin: 0 70px;
   }

   .section-logo {
    display: flex;  
    align-items: center;    
   }

   .title-logo{
    font-style: normal;
    font-weight: 700;
    font-size: 18px;
   }

   .section-logo p {         
        font-style: normal;
        font-weight: 400;   
        color:  var(--darkLight); 
        font-size: 13px;
   }

   .group-logo{
    display: flex;
    flex-direction: column;
    position: relative;
    margin-right: 10px;
   }

   .image-dente-superior {
    position: absolute;
    right: -0.01%;    
    bottom: 55.22%;
   }

   .image-dente-inferior {
    position: absolute;    
    right: 1.17%;
    top: -5px;
    bottom: 0%;
   }

   .section-nav-links {
    display: flex;
    align-items: center;
   }

   .nav-links {
    display: flex;
    align-items: center;
    gap: 20px;
    margin-right: 20px;
    font-style: normal;
    font-weight: 400;
    font-size: 20px;
   }   

   a {
     color: var(--dark);
     transition: 0.3s;
   }

   a:hover {
    color: var(--blueDark);
   }

   .section-nav-links button {
    width: 139px;
    height: 40px;
    background-color: var(--blueLigh);
    color:#F2F5FA;
    border-radius: 5px;
    border: none;
    font-size: 18px;
    font-style: normal;
    font-weight: 600;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 8px; 
    cursor: pointer;  
    transition: 0.3s; 
   }

   .section-nav-links button:hover{
    background-color: var(--blueDark);
   }


</style>