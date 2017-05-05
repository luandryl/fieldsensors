<template>
<div>
  <div id='team' class="team-call">
    <h1><b>Engenheiros</b> nascidos da paixão e <b>movidos</b></h1>
    <h1>pela curiosidade de <b>resolver problemas</b></h1>
  </div>
  <div class='team-wrapper'>
    <div class='team-member'>
      <img src='../assets/img/f.png'>
      <h1>Lucas Fidelis</h1>
      <h2>Eng Automação</h2>
    </div>
    <div class='team-member'>
      <img src='../assets/img/g.png'>
      <h1>Gabriel Sakuno</h1>
      <h2>Eng Automação</h2>
    </div>
    <div class='team-member'>
      <img src='../assets/img/d.png'>
      <h1>Denise Akai</h1>
      <h2>Eng Automação</h2>
    </div>
  </div>
  <div class="team-wrapper">
    <div class='team-member'>
      <img src='../assets/img/l.png'>
      <h1>Luan Andryl</h1>
      <h2>Eng Computação</h2>
    </div>
    <div class='team-member'>
      <img src='../assets/img/v.png'>
      <h1>Vinicius Pimentel</h1>
      <h2>Eng Automação</h2>
    </div>
  </div>
</div>
</template>
<style lang='sass' scoped>
$green01: #47c186
$green02: #00a857
$green03: #008545
$green04: #006836

.team-wrapper
  margin-top: 2rem
  display: flex
  justify-content: center
  align-items: center
  flex-flow: row

.team-member
  display: flex
  justify-content: center
  align-items: center
  flex-flow: column
  margin: 2rem

.team-member h1 
  font-family: 'Source Sans Pro', sans-serif;
  font-size: 22px
  font-weight: 700
  color: $green04
  text-transform: uppercase
  margin: 1rem
  margin-bottom: .5rem
.team-member h2 
  font-family: 'Source Sans Pro', sans-serif;
  font-size: 22px
  font-weight: 300
  color: $green04
  text-transform: uppercase






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
  border-radius: 10px
  text-transform: uppercase
  transition: all .1s ease

.btn:hover
  color: $green04

.team-call h1 
  color: $green04
  font-family: 'Source Sans Pro', sans-serif;
  font-size: 50px
  font-weight: 200
.team-call b
  font-weight: bold
</style>
