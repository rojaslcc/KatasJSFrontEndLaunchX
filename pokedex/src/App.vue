<template>
  <div class="body">
    <Header />
    <Footer />
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Footer from './components/Footer.vue';


export default {
  name: 'App',
  components: { Header, Footer }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');

.body {
  overflow-x: hidden;
  font-family: 'Roboto', sans-serif;
}

.button-vac {
  background-color: #3858d6;
  color: white;
  border: none;
  border-radius: 10px;
}

.button-vac-secondary {
  background-color: #f1f5ff;
  color: #3858d6;
  border: none;
  border-radius: 10px;
}

.page-subtitle {
  font-size: 3em;
  font-weight: bold;
  color: #1f3e72;
}

h1 {
    color: #1f3e72;
}
</style>

