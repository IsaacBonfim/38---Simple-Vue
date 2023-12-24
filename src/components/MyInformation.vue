<template>
  <p class="info">
    Olá, meu nome é Isaac Oliveira e sou um Dev Front-end Junior.
  </p>
  <p class="info">
    Nasci em 27 de Dezembro de 1991, sou uma pessoa motivada pelo estudo e pela busca por diversos tipos de desafios. Estou constantemente buscando oportunidades para aprender e me aprimorar!
  </p>
  <p class="info">
    Neste projeto eu tenho como intuito apenas praticar o básico do Vue, como sua componentização e estruturação basica, além de renovar um antigo projeto feito em HTML e CSS puro.
  </p>
  <ul class="list">
    <span>Algumas das minhas stacks são:</span>
    <li>Git&Github</li>
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
    <li>React</li>
    <li>TypeScript</li>
    <li>Vue</li>
    <li>SQL</li>
  </ul>
</template>

<script>
export default {
  name: 'MyInformation'
}
</script>

<style>
  .info, .list {
    color: white;
    font-size: larger;
  }

  .info {
    margin: 1vh 0;
    max-width: 90%;
  }

  .list {
    display: flex;
    flex-wrap: wrap;
    justify-content: flex-start;
    width: 85%;
  }

  .list span {
    margin: 1vh 0;
    width: 100%;
  }

  .list li {
    width: 15%;
  }
</style>
