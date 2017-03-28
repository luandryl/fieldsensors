<template>
  <div id="app">
    <home></home>
    <about></about>
  </div>
</template>

<script>
import home from './components/home';
import about from './components/about';

export default {
  name: 'app',
  components: {
    home,
    about,
  },
};
</script>

<style lang='sass'>
</style>
