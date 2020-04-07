<template>
  <div id="app">

    <div id='header'>
   <div class='icon'>
     <img src="./assets/1024.png" alt="">
   </div>
   <div class='headerRight'>
 
       <div id="nav">
      <router-link to="/">官網主頁</router-link> |
      <router-link to="/about">隱私政策</router-link> 
 
    </div>
   </div>
  

    </div>
<!--   

<div id='main'>

  <div class='download'>
    <div class="card">
  <div class="card-header" style="text-align: center;">
    游戲介紹
  </div>
  <div class="card-body">
  
      <p>
【精致画风，真实体验】<br>
精致的中国风立绘、恢弘的场景，带你重返原汁原味的古风世界，体验真实的大清生活。<br>
【红颜邂逅，美人坐怀】<br>
手如柔荑，肤如凝脂；巧笑倩兮，美目盼兮。各色倾国倾城的红颜佳人在此处静待邂逅，任君采撷。<br>
【超强代入，原创剧情】<br>
一介书生，终金榜题名奉旨上任。然而官场诡谲，风起云涌，你的仕途何去何从？第一人称剧情成长体验，多重分支结局，你的命运由你抉择。<br>
【历代名士，猛将如云】<br>
招贤纳士，历史名士均为我所用。智将们出谋划策，为你在官场争斗中脱颖而出，权倾天下！<br>
【子嗣养成，分封领地】<br>
培养子嗣，出门游历增长见识，分封领地，争取税收，富国强民!
      </p>
    

  </div>
</div>


  </div>

 <div class='slider'>
  <div class="card">
  <div class="card-header" style="text-align: center;">
 美術宣傳
  </div>
  <div class="card-body">
   <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
  <ol class="carousel-indicators">
    <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="3"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="4"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="5"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="6"></li>
  </ol>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="./assets/1.jpg" class="lbt" alt="">
    </div>
    <div class="carousel-item">
      <img src="./assets/2.jpg" class="lbt" alt="">
    </div>
    <div class="carousel-item">
      <img src="./assets/3.jpg" class="lbt" alt="">
    </div>
      <div class="carousel-item">
      <img src="./assets/4.jpg" class="lbt" alt="">
    </div>
    <div class="carousel-item">
      <img src="./assets/5.jpg" class="lbt" alt="">
    </div>
    <div class="carousel-item">
      <img src="./assets/6.jpg" class="lbt" alt="">
    </div>
    <div class="carousel-item">
      <img src="./assets/7.jpg" class="lbt" alt="">
    </div>
  </div>
  <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>
 </div>

  </div>
   </div>
  
  <div class='content'>
    <div class="jumbotron">
  <h1 class="display-4">Hello, world!</h1>
  <p class="lead">This is a simple hero unit, a simple jumbotron-style component for calling extra attention to featured content or information.</p>
  <hr class="my-4">
  <p>It uses utility classes for typography and spacing to space content out within the larger container.</p>
  <a class="btn btn-primary btn-lg" href="#" role="button">Learn more</a>
</div>
  </div>

 


</div>
 -->

<router-view></router-view>

  <div id='footer'>
    <div>
<p>抵制不良游戏 拒绝盗版游戏 注意自我保护 谨防受骗上当 适度游戏益脑 沉迷游戏伤身 合理安排时间 享受健康生活</p>
<p>©xxxxx</p>
</div>
 </div>

  </div>
</template>

<style lang='less' scoped="" type="">


#app {
background-color: #f8f9fa;
  display: flex;
flex-direction: column;
position: absolute;
height:900px;
width: 100%;

}




#header{
background-image: url(./assets/11.png);
  display: flex;
background-repeat:no-repeat; 
background-size:100% 100%;
-moz-background-size:100% 100%;
 
 
  flex-direction: row;
width: 100%;
height:30%;

.icon{
 flex:0.15;

 display: flex;
 justify-content: center;
 align-items: center;
 img{
  width: 100px;
  height: 100px;
 }
}

.headerRight{

flex: 1;
display: flex;
flex-direction: column;
align-items:flex-end;
justify-content: flex-end;


#nav {


height: 20%;
  padding: 40px;
  a {
  font-weight: bold;
  
  color: white;
  font-size: 20px;
}

a.router-link-exact-active {

  color: #2c3e50;
}
}


}



}



#main{
  padding-top: 10px;
  position: relative;
width: 100%;
height:50%;

display: flex;
flex-direction: row;


.download{

padding-left: 10px;
display: flex;
flex-direction: column;
justify-content: center;
align-items: center;
align-content: center;
width: 25%;
  background-color: white;
.card{
height: 100%;

  p{
  font-size: 12px;

}

}
}
.slider{
  padding-left: 10px;
  background-color: ;
flex-direction: row;
justify-content: center;
align-items: center;
align-content: center;
 display: flex;
position: relative;
width: 30%;
.card{
  height: 100%;
.card-body{
  padding:0;

li{background-color:#333744 ;}

.lbt{
height: 380px;
width: 100%;
 padding: 20px;

}}
}}

.content{
  padding-left: 10px;
  padding-right: 10px;
width: 45%;
.jumbotron{
  height: 100%;
}
}





}
#footer{
 margin-top: 10px;
  display: flex;
flex-direction: column;
justify-content: center;
align-items: center;

width: 100%;
height:10%;
background-color: #333744;
p{
  color:white;
  text-align: center;
}
}
</style>
