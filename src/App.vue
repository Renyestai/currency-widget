<template>
  <div id="app">
    <CurrencyWidget />
  </div>
</template>

<script>
import CurrencyWidget from './components/CurrencyWidget.vue';
import 'flag-icon-css/css/flag-icons.min.css';

export default {
  name: 'App',
  components: {
    CurrencyWidget,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
