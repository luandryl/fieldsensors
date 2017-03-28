<template>
  <div id="app">
    <home></home>
    <about></about>
    <team></team>
    <contact></contact>
  </div>
</template>

<script>
import home from './components/home';
import about from './components/about';
import team from './components/team';
import contact from './components/contact';

export default {
  name: 'app',
  components: {
    home,
    about,
    team,
    contact,
  },
};
</script>

<style lang='sass'>
</style>
