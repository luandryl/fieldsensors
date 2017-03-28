<template>
  <div id="app">
    <home></home>
    <about></about>
    <team></team>
  </div>
</template>

<script>
import home from './components/home';
import about from './components/about';
import team from './components/team';

export default {
  name: 'app',
  components: {
    home,
    about,
    team,
  },
};
</script>

<style lang='sass'>
</style>
