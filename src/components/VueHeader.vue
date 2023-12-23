<template>
  <header class="Vue-Header">
    <h1 class="title">Bem vindo minha página simples de Vue</h1>
  </header>
</template>

<script>
export default {
  name: 'VueHeader'
}
</script>

<style>
 .Vue-Header {
   align-items: center;
   display: flex;
   height: 7vh;
   justify-content: center;
   margin-bottom: 7px;
   width: 100vw;
 }

 .title {
  color: white;
  text-shadow: -1px 1px 3px paleturquoise,
    -2px 2px 6px turquoise;
 }

</style>
