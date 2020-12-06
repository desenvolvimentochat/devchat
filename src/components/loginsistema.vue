<template>
  <div class="fundototal">
    <div class="hello">
      <div class="logo">
        <p>Logo</p>
      </div>
      <div>
        <input type="text" class="login" placeholder="Digite seu e-mail"/>
      </div>
        <input type="password" class="senha" placeholder="Digite sua senha"/>
      <div>
        <button class="entrar">Entrar</button>
        <button class="cancelar">Cancelar</button>
      </div>  
    </div> 
  </div>
</template>

<script>
export default {
  name: 'loginsistema',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.fundototal{  
  position: absolute;
  background-color: rgb(238, 238, 238);
  width: 100%;
  height: 100%;
  top: 0px;
  left: 0px;
}
.logo{
  position: absolute;
  margin-top: 20px;
  margin-left: 130px;
  width: 100px;
  height: 100px;
  border: 1px solid  rgb(141, 141, 141);
  text-align: center;
  vertical-align: center;
}
div.logo p {
  margin: 0;
  position: absolute;
  top: 50%;
  left: 50%;
  margin-right: -50%;
  transform: translate(-50%, -50%) 
}
.hello{
  position: absolute;
  background-color: #FFF;
  width:360px;
  height:300px;
  top: 50%;
  left: 50%;
  margin-top: -190px;
  margin-left: -200px;
  border: 1px solid rgb(141, 141, 141);
  border-radius: 10px;
}
.login{
  position: absolute;
  margin-top: 160px;
  margin-left: 25px;
  width: 305px;
  height: 25px;
  border: 1px solid rgb(141, 141, 141);
  border-radius: 10px;  
  font-family: Verdana, Geneva, Tahoma, sans-serif; 
}
.senha{
  position: absolute;
  margin-top: 220px;
  margin-left: 25px;
  width: 305px;
  height: 25px;
  border: 1px solid rgb(141, 141, 141);
  border-radius: 10px;
}
.entrar{
  position: absolute;
  margin-top: 280px;
  margin-left: 35px;
  width: 120px;
  height: 35px;
  background-color: rgb(141, 141, 141);
  border-radius: 10px;
  color: #fff;
}
.cancelar{
  position: absolute;
  margin-top: 280px;
  margin-left: 205px;
  width: 120px;
  height: 35px;
  background-color: rgb(141, 141, 141);
  border-radius: 10px;
  color: #fff;
}

</style>
