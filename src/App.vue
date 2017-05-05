<template>
  <div id="app">
    <home></home>
    <about></about>
    <solutions></solutions>
    <team></team>
    <contact></contact>
  </div>
</template>

<script>
import home from './components/home';
import solutions from './components/solutions';
import about from './components/about';
import team from './components/team';
import contact from './components/contact';

export default {
  name: 'app',
  components: {
    home,
    solutions,
    about,
    team,
    contact,
  },
};
</script>

<style lang='sass'>
</style>
