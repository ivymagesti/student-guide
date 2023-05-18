
<template>
  <div id="app">
    <AppHeader/>
    <AppFooter/>
 </div>
</template>

<script>
import './styles/global.css';
import AppHeader from './components/AppHeader';
import AppFooter from './components/AppFooter.vue';

export default {
  name: 'App',
  components: {
    AppHeader,
    AppFooter,
  }
}
</script>

<style>

</style>
