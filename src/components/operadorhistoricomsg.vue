<template>
  <div class="fundototal">
    <div class="hello">
      
      <p class="teste"><a href="www.google.com.br" >Aqui os menus</a> - 

      </p>
    </div> 
    <div class="visualizadormsgdireita">
        
    </div>
    <div class="visualizadormsgesquerda">
      <div class="logo">
        <p>Logo</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'operadorhistoricomsg',
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
.hello{
  position: absolute;
  margin-top: 20px;
  left: 27%;
  width:100%;
  height:40px;
  border: 1px solid rgb(141, 141, 141);
  border-radius: 10px;
}
.visualizadormsgdireita{
  position: absolute;
  margin-top: 75px;
  margin-left: 27%;
  width: 100%;
  height: 85%;
  border: 1px solid rgb(141, 141, 141);
  border-radius: 10px;  
}
.visualizadormsgesquerda{
  position: absolute;
  margin-top: 20px;
  margin-left: 15px;
  width: 400px;
  height: 92.4%;
  border: 1px solid rgb(141, 141, 141);
  border-radius: 10px;
}
.btnenviarmsg{
  position: absolute;
  margin-top: 640px;
  margin-left: 630px;
  width: 120px;
  height: 35px;
  background-color: rgb(141, 141, 141);
  border-radius: 10px;
  color: #fff;
}
.teste{
  margin-top: 10px;
  margin-left: 15px;
}
.logo{
  position: absolute;
  margin-top: 20px;
  margin-left: 37%;
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
</style>
