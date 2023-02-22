<template>
  <div class="versiculo">
    <h3>"Acima de tudo, porém, revistam-se do amor, que é o elo perfeito."</h3> 
    <h4>Collossenses 3:14</h4>
  </div>
  <div class="form">
    <label for="fname">Informe seu nome: </label>
    <input type="text" id="name" class="input"><br><br>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .versiculo{
    font-size: 32px;
    color: #376367;
    margin: 0;
    padding: 0;
  }

  h3 {
    margin-top: 20px;
    margin-bottom: 3px;
  }

  h4{
    margin-top: 0px;
  }

  .form{
    font-family: 'Comfortaa', cursive;
    font-size: 18px;
  }

  .input{
    font-size: 20px;
    border-radius: 30px;
  }
</style>
