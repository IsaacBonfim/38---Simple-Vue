<template>
  <div class="board glass">
    <section class="area-1">
      <MyImage />
    </section>
    <section class="area-2">
      <InfoTable
        myName="Isaac Oliveira"
        myAge="31"
        myBirth="27 de Dezembro"
        myAdress="Betim - MG"
        mySchooling="Sup. Imcompleto"
      />
    </section>
    <section class="area-3">
      <MyInformation />
    </section>
  </div>
</template>

<script>
import InfoTable from './InfoTable.vue'
import MyImage from './MyImage.vue'
import MyInformation from './MyInformation.vue'

export default {
  name: 'InfoBoard',
  components: {
    InfoTable,
    MyImage,
    MyInformation
  }
}
</script>

<style>
  .glass {
    backdrop-filter: blur(3px);
    background-color: rgba(255, 255, 255, 0.1);
    border: 1px solid rgba(64, 224, 208, 0.2);
    box-shadow: 0 4px 1px 1px transparent,
      0 4px 20px 4px rgba(64, 224, 208, 0.2);
    -webkit-backdrop-filter: blur(3px);
  }

  .board {
    border-radius: 16px;
    display: flex;
    flex-wrap: wrap;
    height: 70vh;
    width: 50vw;
  }

  section {
    display: flex;
  }

  .area-1 {
    align-items: center;
    height: 50%;
    justify-content: center;
    width: 30%;
  }

  .area-2 {
    align-items: center;
    height: 50%;
    justify-content: center;
    width: 70%;
  }

  .area-3 {
    align-items: center;
    flex-direction: column;
    height: 50%;
    width: 100%;
  }
</style>
