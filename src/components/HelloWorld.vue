<template>
  <div class="hello">
    <h0><font size="+7">NQD Games</font></h0>
    <h1>{{ msg }}</h1>
    <h2><font size="+7">Jeux :</font> </h2>

    <ul>
      <li>
        <a
          style="text-decoration:none"
          href="http://localhost:8080/#/p5Pong"
          target="_blank"
        >
          Pong-game
        </a>
      </li>
    </ul>
    <ul id="menu">
      <li>
        <a
          style="text-decoration:none"
          href="http://localhost:8080/#/p5Pong2"
          target="_blank"
        >
          Pong-game(1)
        </a>
      </li>
      <li>
        <a
          style="text-decoration:none"
          href="http://localhost:8080/#/backgroundtest"
          target="_blank"
        >
          backgroundtest
        </a>
      </li>
    </ul>
  </div>
</template>

<script>

export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: ''
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #0000FF;
}
.hello{
    backgroud-color: white;
    background-image: url("../assets/Fond.png") ;
}
ul {
 padding:0;
 margin:0;
 list-style-type:none;
 }
li {
 margin-left:200px;
 float:left;
 }
ul li a {
 display:block;
 float:left;
 width:300px;
 background-color:#FF0000;
 color:black;
 text-decoration:none;
 text-align:center;
 padding:5px;
 border:2px solid;
 border-color:#DCDCDC #696969 #696969 #DCDCDC;
 }
ul li a:hover {
 background-color:#800080;
 border-color:#696969 #DCDCDC #DCDCDC #696969;
 }
</style>
