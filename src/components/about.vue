<script>
export default {
  name: 'about',
  data() {
    return {
      msg: 'Welcome to Your Vue.js App',
    };
  },
};
</script>
<template>
  <div class="about-wrapper">

    <div class="about-title">
      <h1>Temos a <b>compreensão real</b></h1>
      <h1>Sobre os <b>desafios de negócio</b> dos nossos clientes</h1>
    </div>

    <div class="about-item">
     <div class="about-img"><img src='../assets/img/sensor.png'></div>
     <div class='about-text'>
      <h1>Nossas <b>estações</b> fazem a leitura <b>do solo</b> e comunicam-se</h1>
      <h1>com a <b>central</b></h1>
     </div>
    </div>
    
    <div class="about-item item-2">
      <div class='about-text'>
        <h1>A <b>central</b> é responsável por <b>conectar as estações</b></h1> 
        <h1>com os <b>servidores na nuvem</b></h1>
        <h1>e tambem para enviar dados para as <b>maquinas no solo</b></h1>
     </div>
     <div class="about-img"><img src='../assets/img/processor.png'></div>
    </div>

    <div class="about-item item-3">
     <div class="about-img"><img src='../assets/img/server.png'></div>
     <div class='about-text'>
      <h1>Nossos <b>servidores</b> na nuvem <b>processam</b>, fazem backup e disponibilizam </h1>
      <h1>os dados para os <b>sistemas clientes</b> </h1>
     </div>
    </div>

    <div class="about-item item-4">
      <div class='about-text'>
        <h1>Todas as informações ficam <b>disponíveis na internet</b></h1>
        <br>
        <br>
        <h1>Ou se preferir pode-se <b>integrar</b> as informações obtidas</h1>
        <h1>por nossas estações com <b>qualquer sistema</b> por meio de nossa <b>API</b></h1>
     </div>
     <div class="about-img"><img src='../assets/img/internet.png'></div>
     </div>
    </div>
    
  </div>
</template>
<style lang='sass' scoped>
$green01: #47c186
$green02: #00a857
$green03: #008545
$green04: #006836

.about-title
  margin: 3rem 0 3rem 0
  display: flex
  justify-content: center
  align-items: center
  flex-flow: column

.about-title h1 
  font-family: 'Source Sans Pro', sans-serif;
  font-size: 40px
  font-weight: 300
  color: $green01

.about-title b
  font-weight: bold

.about-item
  background: $green01
  padding: 2rem
  display: flex
  justify-content: space-between
  flex-flow: row wrap
  padding: 10rem
  
.about-item h1
  color: #fff
  font-family: 'Source Sans Pro', sans-serif;
  font-size: 25px
  font-weight: 200

.about-item b
  font-weight: bold
.item-2
  background: $green02
.item-3
  background: $green03
.item-4
  background: $green04

.about-text 
  display: flex
  justify-content: center
  align-items: center
  flex-flow: column wrap

</style>
