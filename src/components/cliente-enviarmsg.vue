<template>
  <div class="fundototal">
    <div class="hello">
      <div>
        <input class="caixavisualizarmensagem" />
      </div>
      <div>
        <textarea class="caixaescrevermensagem" />
        <button class="btnenviarmsg">Enviar</button>
      </div>
    </div> 
  </div>
</template>

<script>
export default {
  name: 'cliente-enviarmsg',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.fundototal{  
  position:absolute;
  background-color: rgb(238, 238, 238);
  width: 100%;
  height: 100%;
  top: 0px;
  left: 0px;
}
.hello{
  position:absolute;
  margin-top: 20px;
  left: 27%;
  width:760px;
  height:700px;
  border: 1px solid rgb(141, 141, 141);
  border-radius: 10px;
}
.caixavisualizarmensagem{
  position: absolute;
  margin-top: 20px;
  margin-left: 10px;
  width: 600px;
  height: 580px;
  border: 1px solid rgb(141, 141, 141);
  border-radius: 10px;  
}
.caixaescrevermensagem{
  position: absolute;
  margin-top: 620px;
  margin-left: 10px;
  width: 602px;
  height: 50px;
  border: 1px solid rgb(141, 141, 141);
  border-radius: 10px;
  font-family: Verdana, Geneva, Tahoma, sans-serif; 
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

</style>
