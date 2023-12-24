<template>
  <img class="image" alt="Foto pessoal" src="../assets/Eu.jpeg" />
</template>

<script>
export default {
  name: 'MyImage'
}
</script>

<style>
  .image {
    border: 1px solid rgba(64, 224, 208, 0.2);
    border-radius: 8px;
    box-shadow: 0 4px 1px 1px transparent,
      0 4px 20px 4px rgba(64, 224, 208, 0.2);
    height: 85%;
    width: 65%;
  }
</style>
