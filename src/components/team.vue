<template>
<div>
  <div id='team' class='team-wrapper'>
    <div class='team-member'>
      <img src='../assets/img/fidelis.png'>
      <h1>Lucas Fidelis</h1>
      <h2>Eng Automação</h2>
    </div>
    <div class='team-member'>
      <img src='../assets/img/sakuno.png'>
      <h1>Gabriel Sakuno</h1>
      <h2>Eng Automação</h2>
    </div>
    <div class='team-member'>
      <img src='../assets/img/denise.png'>
      <h1>Denise Akai</h1>
      <h2>Eng Automação</h2>
    </div>
  </div>
  <div class="team-wrapper">
    <div class='team-member'>
      <img src='../assets/img/luan.png'>
      <h1>Luan Andryl</h1>
      <h2>Eng Computação</h2>
    </div>
    <div class='team-member'>
      <img src='../assets/img/vinicius.png'>
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


</style>
