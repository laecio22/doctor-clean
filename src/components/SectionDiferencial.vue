<template>
  <section class="block-diferencial">
    <div class="container-content-block-diferencial">
      <h2>Diferencial</h2>     
    
      <div class="content-block-diferencial">
        <CardDiferencial v-for="diferencial of listDiferencial" :key="diferencial.id"/>
      </div>
    </div>
  </section>
</template>

<script >
import CardDiferencial from './CardDiferencial.vue';

export default { 

  components: {
    CardDiferencial,
  },
 
  data() {
    const listDiferencial = [
      {
        id: "644d1da3ce9fd38a4e2afafc",
        name: "profissionais capacitados",
        description: "Nossa equipe de dentistas e assistentes é formada apenas por profissionais altamente qualificados."
      },
      {
        id: "644d1da323fef9d75fd839e1",
        name: "horários flexíveis",
        description: "A marcação de consultas e exames pode ser feita de acordo com o melhor horário para os nossos pacientes."
      },
      {
        id: "644d1da38031e17c411b00a5",
        name: "tratamento  personalizado",
        description: "Cada paciente é recebido de forma única e seu conforto é uma prioridade para nós."
      },
      {
        id: "644d1da34d4dae584fc6c6c6",
        name: "solicite  um  orçamento",
        description: "Nossa equipe de dentistas e assistentes é formada apenas por profissionais altamente qualificados."
      },
      {
        id: "644d1da31b25d4a7de5ed5f8",
        name: "trabalho  em  equipe",
        description: "A marcação de consultas e exames pode ser feita de acordo com o melhor horário para os nossos pacientes."
      },
      {
        id: "644d1da3c5abd8cf695b03b5",
        name: "higiene  e  segurança",
        description: "Cada paciente é recebido de forma única e seu conforto é uma prioridade para nós."
      },
    ];   

    
    return {
      listDiferencial,         
       
    };
  },

};
</script>

<style scoped>
.block-diferencial {
  height: 800px;
}

.container-content-block-diferencial {
  width: 1250px;
  margin: 0 auto;
  padding-top: 64px;
}

.container-content-block-diferencial h2 {
  padding: 5px 0 10px 35px;
}

.content-block-diferencial {
  width: 100%;
  display: flex;
  flex-wrap: wrap;
  gap: 30px;
  justify-content: center;
}
</style>