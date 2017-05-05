<script>
/* eslint-disable */
export default {
  name: 'about',
  data () {
    return {
      show_info: false
    }
  }
};
</script>
<template>
  <div id="about" class="about-wrapper">
    <div class="team-call">
      <h1><b>Monitore</b> as condições climáticas, mapas de prudutividade,</h1>
      <h1>estresse hídrico de <b>forma simples</b> e <b>eficaz</b></h1>
    </div>
    <div class="about-item item-01">
      <div class="number-wrapper">
        <span>01.</span>
      </div>
      <div class="content-wrapper">
        <h1>Coleta de Dados</h1>
        <p>Nossas <b>estações</b> fazem a leitura do estado do <b>solo</b> e comunicam-se<br /> 
        com a <b>central</b> </p> 
      
        <button v-scroll-to="'#farm-center'" class="btn" > Central Na Fazenda </button>

      </div>
    </div>
    <div id="farm-center" class="about-item item-02">
      <div class="number-wrapper">
        <span>02.</span>
      </div>
      <div class="content-wrapper">
        <h1>A Central na Fazenda</h1>
        <p>A <b>central</b> é responsável por <b>conectar</b>as estações do campo <br />
        com nossos <b>servidores</b> na nuvem</p>
        
        <p>A central é uma via de <b>duas mãos</b>, os <b>dados</b> processados voltam por ela e <br />
        são <b>re-distribuidos</b> para as <b>maquinas</b> no solo conectadas a nossa rede no campo.<br /></p>
        <button v-scroll-to="'#servers'" class="btn" > Nossos Servidores </button>

      </div>
    </div>
    <div id="servers" class="about-item item-03">
      <div class="number-wrapper">
        <span>03.</span>
      </div>
      <div class="content-wrapper">
        <h1>Servidores de processamento</h1>
        <p>Nossos <b>servidores</b> na nuvem <b>processam</b>, fazem backup e disponibilizam <br />
        os dados para os <b>sistemas clientes</b> </p>
        
        <p>Processamento, cálculos, análise e <b>resultados</b> são <b>gerados</b> em nossos <br /> 
        <b>Servidores</b> pelo baixo poder computacional da Central</p>

        <p>Por nascerem na <b>nuvem</b> os resultados de processamento ficam <b>disponíveis</b> para todas <br />
        plataformas conectadas com a <b>nossa rede.</b></p>
        <button v-scroll-to="'#info'" class="btn" > Informação onde você precisa </button>      </div>
    </div>
    <div id="info" class="about-item item-04">
      <div class="number-wrapper">
        <span>04.</span>
      </div>
      <div class="content-wrapper">
        <h1>Informação em qualquer lugar</h1>
        <p>Todas as informações coletadas e processadas ficam <b>disponíveis</b> na internet <br />
        pelo nosso <b>aplicativo oficial</b></p>
        
        <p>Ou se preferir pode-se<b>integrar</b> as informações obtidas<br /> 
        por nossas estações com <b>qualquer sistema</b> por meio de nossa API</p>

        <button v-scroll-to="'#solutions'" class="btn" > Descubra </button>      </div>

      </div>
    </div>
  </div>
</template>
<style lang='sass' scoped>
$green01: #47c186
$green02: #00a857
$green03: #008545
$green04: #006836
$green045: #004F29
$green05: #003119

.about-wrapper
  display: flex
  flex-flow: column wrap

.about-item
  flex-grow: 1
  height: 100vh
  display: flex
  justify-content: flex-start
  align-items: center
  flex-flow: row wrap
  text-align: center

.number-wrapper
  flex-grow: .5

.number-wrapper span
  padding: 2rem
  font-family: 'Source Sans Pro', sans-serif;
  font-size: 90px
  font-weight: 700  

.content-wrapper 
  flex-grow: 1
  margin: 2rem
  border-radius: 10px

.content-wrapper h1
  font-family: 'Source Sans Pro', sans-serif;
  font-size: 40px
  font-weight: 700
  padding-bottom: 1rem

.content-wrapper p
  font-family: 'Source Sans Pro', sans-serif;
  font-size: 22px
  font-weight: 500
  padding-bottom: 1rem

.content-wrapper b 
  font-weight: bold



.item-01
  background: url('../assets/img/01.jpg') center center
  -webkit-background-size: cover
  -moz-background-size: cover
  background-size: cover
  -o-background-size: cover
  color: $green04

.item-02
  background: url('../assets/img/02.jpg') center center
  -webkit-background-size: cover
  -moz-background-size: cover
  background-size: cover
  -o-background-size: cover
  color: $green045
  

.item-03
  background: url('../assets/img/03.jpg') center center
  -webkit-background-size: cover
  -moz-background-size: cover
  background-size: cover
  -o-background-size: cover
  color: $green045

.item-04
  background: url('../assets/img/04.jpg') center center
  -webkit-background-size: cover
  -moz-background-size: cover
  background-size: cover
  -o-background-size: cover
  color: $green045





.team-call
  background: #fff
  display: flex
  justify-content: center
  align-items: center
  flex-flow: column wrap
  padding: 3rem

.btn
  font-family: 'Source Sans Pro', sans-serif;
  font-size: 18px
  font-weight: bold
  margin: 1rem
  padding: 1rem 2rem 1rem 2rem
  color: $green04
  cursor: pointer
  text-transform: uppercase
  transition: all .1s ease
  border: 2px solid $green04

.btn:hover
  color: $green05

.team-call h1 
  color: $green04
  font-family: 'Source Sans Pro', sans-serif;
  font-size: 50px
  font-weight: 200
.team-call b
  font-weight: bold
</style>
