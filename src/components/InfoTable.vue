<template>
  <table>
    <thead>
      <tr>
        <td colspan="2">Informações pessoais</td>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td class="bold">Meu Nome</td>
        <td>{{myName}}</td>
      </tr>
      <tr>
        <td class="bold">Idade</td>
        <td>{{myAge}} Anos</td>
      </tr>
      <tr>
        <td class="bold">Aniversário</td>
        <td>{{myBirth}}</td>
      </tr>
      <tr>
        <td class="bold">Onde Moro</td>
        <td>{{myAdress}}</td>
      </tr>
      <tr>
        <td class="bold">Formação</td>
        <td>{{mySchooling}}</td>
      </tr>
    </tbody>
  </table>
</template>

<script>
export default {
  name: 'InfoTable',
  props: {
    myName: String,
    myAge: Number,
    myBirth: String,
    myAdress: String,
    mySchooling: String
  }
}
</script>

<style>
  table {
    background-color: transparent;
    border: 1px solid rgba(64, 224, 208, 0.2);
    box-shadow: 0 4px 1px 1px transparent,
      0 4px 20px 4px rgba(64, 224, 208, 0.2);
    color: white;
    height: 80%;
    width: 80%;
  }

  thead {
    font-size: larger;
    font-weight: 700;
    text-align: center;
  }

  thead tr td {
    border: 2px solid rgba(64, 224, 208, 0.1);
    height: 50px;
  }

  tbody tr td{
    height: 40px;
  }

  .bold {
    font-size: large;
    font-weight: 700;
    text-align: center;
  }
</style>
