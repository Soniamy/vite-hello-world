<script>
//Importazione del componente
import AppHeader from './components/AppHeader.vue';
export default {
  data() {
    return { count: 0 };
  },
  //Dichiarazione del componente
  components: {
    AppHeader,
  },
};
</script>

<template>
  <div class="container">
    <!--Utilizzo del componente-->
    <AppHeader />
    <h1>Hello World</h1>
    <p>
      {{ count }}
    </p>
    <button @click="count++">Incrementa count</button>
    <p class="subtitle">A primo impatto sembra molto figo !</p>
  </div>
</template>

<style scoped>
h1 {
  text-align: center;
  font-size: 5em;
  color: blueviolet;
}
p {
  text-align: center;
}
button {
  margin-left: 655px;
  margin-top: 10px;
}
</style>
