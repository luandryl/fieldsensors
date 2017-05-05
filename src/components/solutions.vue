<template>
  <div class="solutions">
    <div id="solutions" class="solutions-title">
      <h1>Temos a <b>compreensão real</b></h1>
      <h1>Sobre os <b>desafios de negócio</b> dos nossos clientes</h1>
    </div>
    <div class="solutions-content">
      <div class="solutions-box">
        <h1>Mapas de Fertilidade</h1>
        <ul class="solutions-box-items">
          <li>Controle sobre as preciso sobre as áeras que necessitam de correção</li>
          <li>Aumento de sua produtividade</li>
          <li>Conhecimento real sobre as características químicas do solo</li>
        </ul>
      </div>
      <div class="solutions-box">
        <h1>Análise Física do Solo</h1>
        <ul class="solutions-box-items">
          <li>Controle sobre risco erosões, disponibilidade de agua para as culturas </li>
          <li>Garante o uso consciente de adubos</li>
          <li>Combinado com o Mapa de Fertilidade, tem-se um diagnóstico mais seguro do solo</li>
        </ul>
      </div>
      <div class="solutions-box">
        <h1>Integração dos dados</h1>
        <ul class="solutions-box-items">
          <li>Software proprio para analise dos resultados</li>
          <li>Acesse de qualque lugar pela internet ou aplicativo</li>
          <li>Nossas soluçõe conversam com o sistema que voce já usa</li>
          <li>Controle dos implementos remoto via WEB</li>
        </ul>
      </div>
    </div>
    <button v-scroll-to="'#team'" class="btn" > Conheça nosso time </button>  
  </div>
</template>
<style lang='sass' scoped>
$green01: #47c186
$green02: #00a857
$green03: #008545
$green04: #006836
$green05: #003119

.solutions
  background: #fff
  padding: 2rem
  display: flex
  justify-content: flex-start
  align-items: center
  flex-flow: column wrap
  padding: 10rem
  min-height: 95vh
  position: relative
  height: 95%
  padding: 2rem

.solutions-title
  margin: 5rem 0 5rem 0
  display: flex
  justify-content: center
  align-items: center
  flex-flow: column

.solutions-title h1 
  font-family: 'Source Sans Pro', sans-serif;
  font-size: 50px
  font-weight: 300
  color: $green04

.solutions-title b
  font-weight: bold

.solutions-content
  display: flex
  justify-content: center
  align-items: center
  flex-flow: row wrap

.solutions-box
  margin: 2rem
  width: 350px
  height: 350px
  background: $green04
  border-radius: 10px
  display: flex
  justify-content: center
  align-items: center
  flex-flow: column wrap

.solutions-box h1
  font-family: 'Source Sans Pro', sans-serif;
  font-size: 22px
  font-weight: 500
  color: #fff

.solutions-box-items
  font-family: 'Source Sans Pro', sans-serif;
  font-size: 18px
  font-weight: 300
  color: #fff
  margin: 2rem

.solutions-box-items li
  list-style: initial
  margin: .8rem
  text-align: left

.team-call
  background: $green04
  display: flex
  justify-content: center
  align-items: center
  flex-flow: column wrap
  padding: 3rem

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
  text-transform: uppercase
  transition: all .1s ease

.btn:hover
  color: $green02

.team-call h1 
  color: #fff
  font-family: 'Source Sans Pro', sans-serif;
  font-size: 50px
  font-weight: 200
.team-call b
  font-weight: bold

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

</style>
