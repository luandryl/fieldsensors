<template>
  <div id='contact' class="contact-wrapper">
    <div class="contact-title">
      <h1>Entre em Contato</h1>
      <hr />
    </div>
    <div class="contact-form">

      <div class="form-group">
        <label>Nome</label>
        <input required type="text" v-model="name" name="name" placeholder="Ex: José Carlos">
      </div>

      <div class="form-group">
        <label>Email</label>
        <input required type="email" v-model="email" name="email" placeholder="Ex: jose.carlos@gmail.com">
      </div>

      <div class="form-group-wide">
        <label>Sua Mensagem</label>
        <textarea rows="4" cols="50">
            
        </textarea>
      </div>
      <div class="form-group-btn">
        <button class='btn'href='#'>Enviar</button>
      </div>
    </div>
    <div class="location-info">
      <h3>UTFPR Campus Cornélio Procópio</h3>
      <h3>AV: Alberto Carazzai, 1640 - Centro. Cornélio Procópio</h3>
    </div>
  </div>
</template>
<style lang='sass' scoped>
$green01: #47c186
$green02: #00a857
$green03: #008545
$green04: #006836

.contact-wrapper
  background: url('../assets/img/bg-contact.jpg') center 
  -webkit-background-size: cover
  -moz-background-size: cover
  background-size: cover
  -o-background-size: cover
  min-height: 95vh
  height: 95%
  padding: 8rem 2rem 2rem 2rem
  display: flex
  justify-content: space-around
  align-items: center
  flex-flow: column

.contact-form
  display: flex
  justify-content: center
  align-items: center
  flex-flow: row wrap
  margin-top: 3rem
  width: 60%
  
.form-group
  display: flex
  justify-content: flex-start
  align-items: flex-start
  flex-flow: column
  margin: 1.5rem

.form-group-wide
  width: 60%


.form-group-btn
  width: 60%
  display: flex
  justify-content: center
  align-items: center

label
  font-family: 'Source Sans Pro', sans-serif;
  font-size: 18px
  font-weight: 700
  color: $green04
  margin: 0 0 1rem 10px

input
  padding: .7rem
  color: #fff
  font-family: 'Source Sans Pro', sans-serif;
  font-size: 20px
  font-weight: 200
  background: rgba(0,104,54,.5)

textarea
  padding: .7rem
  color: #fff
  font-family: 'Source Sans Pro', sans-serif;
  font-size: 20px
  font-weight: 200
  background: rgba(0,104,54,.5)
  width: 100%

::-webkit-input-placeholder   
  color:#fff
input:-moz-placeholder  
  color:#fff
textarea:-moz-placeholder 
  color:#fff


.btn
  color: #fff
  font-family: 'Source Sans Pro', sans-serif;
  font-size: 18px
  font-weight: bold
  margin: 1rem -.5rem 1rem 1rem
  padding: 1rem 2rem 1rem 2rem
  background: #fff
  color: $green01
  cursor: pointer
  border-radius: 10px
  text-transform: uppercase
  transition: all .3s ease
  width: 85%
  text-aling: center
  box-shadow: 0 4px 5px 0 rgba(0,0,0,0.14), 0 1px 10px 0 rgba(0,0,0,0.12), 0 2px 4px -1px rgba(0,0,0,0.3)


.btn:hover
  color: $green04

.location-info
  text-aling: center

.location-info h3
  font-family: 'Source Sans Pro', sans-serif;
  font-size: 30px
  font-weight: 300
  color: #fff


.contact-title
  display: flex
  justify-content: center
  align-items: center
  flex-flow: column
  margin-top: -8.74rem

.contact-title h1
  font-family: 'Source Sans Pro', sans-serif;
  font-size: 70px
  font-weight: 700
  color: $green04

.contact-title hr
  border-top: 3px solid $green04
  color: $green04
  width: 20%
  margin: 2rem 1rem 2rem 1rem

</style>
