<template>
<div>
  <h1>{{titulo}}</h1>

  <ul>
    <li v-for="foto of foto">
      <img :src="foto.url" :alt="foto.titulo">
    </li>
  </ul>
</div>
</template>

<script>
export default {

  data() {

    return {
      titulo:'AluraPic',
      foto: [
        {
          url:'https://independente.com.br/wp-content/uploads/2018/01/cachorro-independente.jpg',
          titulo: 'cachorro'
        },
        {
          url:'https://independente.com.br/wp-content/uploads/2018/01/cachorro-independente.jpg',
          titulo: 'cachorrao'
        }
      ]
    }
  }
}
</script>

<style>

</style>
