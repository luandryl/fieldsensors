<script>
export default {
  name: 'home',
};
</script>
<template>
  <div id='home' class="home-wrapper">
    <div class='navbar-wrapper'>
      <div class="nav-logo">
        <img src='../assets/img/logo.png'>
      </div>
      <div class="nav-links">
        <ul class='links-list'>
          <li><a href='#' class='link-home' v-scroll-to="'#about'">Soluções</a></li>
          <li><a href='#' class='link-home' v-scroll-to="'#team'">Equipe</a></li>
          <li><a href='#' class='link-home' v-scroll-to="'#contact'">Contato</a></li>
        </ul>
      </div>
    </div>

    <div class='home-container'>
      <h1 class='title'> Conectando para fazer mais</h1>
      <h2 class='subtitle'>Agricultura de precisão, de verdade.</h2>
      <div class="call-to-action">
        <a v-scroll-to="'#about'" class="btn" href='#'> Saiba Mais</a>
      </div>
    </div>
  </div>

  
</template>
<style lang='sass' scoped>
$green01: #47c186
$green04: #006836

.home-wrapper
  display: flex
  justify-content: space-around
  flex-flow: column wrap
  background: url('../assets/img/bg-home.jpg') no-repeat center center fixed
  -webkit-background-size: cover
  -moz-background-size: cover
  background-size: cover
  -o-background-size: cover
  min-height: 95vh
  position: relative
  height: 95%
  padding: 2rem
  
  
.navbar-wrapper
  display: flex
  justify-content: space-around
  flex-flow: row wrap

.nav-logo
.nav-links

.links-list
  display: flex
  margin: 1rem

.link-home 
  margin: 1rem
  color: #fff
  font-family: 'Source Sans Pro', sans-serif;
  font-size: 20px
  font-weight: 200
  transition: all .3s ease

.link-home:hover
  color: $green04

.home-container 
  display: flex
  justify-content: center
  align-items: center
  flex-flow: column wrap
  flex-grow: 1
  position: relative

.home-container hr 
  border-top: 2px solid #fff
  color: #fff
  width: 20%
  margin: 2rem 1rem 2rem 1rem

.title
  font-family: 'Source Sans Pro', sans-serif;
  font-size: 60px
  font-weight: 200
  color: #fff

.subtitle
  font-family: 'Source Sans Pro', sans-serif;
  font-weight: bold
  font-size: 40px
  color: #fff

.call-to-action
  margin: 3.5rem 0 1rem 0

.btn
  color: #fff
  font-family: 'Source Sans Pro', sans-serif;
  font-size: 18px
  font-weight: bold
  margin: 1rem
  padding: 1rem 2rem 1rem 2rem
  color: #fff
  cursor: pointer
  text-transform: uppercase
  transition: all .1s ease
  border: 2px solid #fff

.btn:hover
  color: $green04
  border: 2px solid $green04
</style>
