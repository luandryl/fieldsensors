<script>
export default {
  name: 'home',
};
</script>
<template>
  <div class="home-wrapper">
    <div class='navbar-wrapper'>
      <div class="nav-logo">
        <img src='../assets/img/logo.png'>
      </div>
      <div class="nav-links">
        <ul class='links-list'>
          <li><a href='#'>Home</a></li>
          <li><a href='#'>O que fazemos?</a></li>
          <li><a href='#'>Quem somos?</a></li>
          <li><a href='#'>Contato</a></li>
        </ul>
      </div>
    </div>

    <div class='home-container'>
      <h1 class='title'> Conectando para fazer mais</h1>
      <h2 class='subtitle'>Agricultura de precisão, de verdade.</h2>
      <hr />
      <div class="call-to-action">
        <button class="btn bt-green" href='#'> Saiba Mais</button>
        <button class='btn'href='#'>Contato</button>
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

.links-list a 
  margin: 1rem
  color: #fff
  font-family: 'Source Sans Pro', sans-serif;
  font-size: 18px
  font-weight: bold
  transition: all .3s ease

.links-list a:hover
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
  font-weight: bold
  color: #fff

.subtitle
  font-family: 'Source Sans Pro', sans-serif;
  font-weight: bold
  font-size: 40px
  color: #fff

.btn
  color: #fff
  font-family: 'Source Sans Pro', sans-serif;
  font-size: 18px
  font-weight: bold
  margin: 1rem
  padding: 1rem 2rem 1rem 2rem
  background: #fff
  color: $green01
  cursor: pointer
  border-radius: 10px
  text-transform: uppercase
  transition: all .3s ease

.btn:hover
  text-decoration: underline
  color: $green04

.bt-green 
  background: $green01
  color: #fff
</style>
