---
layout: page
title: . .
subtitle: James Webb is cool but insert group photos!
cover-img: ["assets/img/NASA-james-webb-telescope-07.jpg.webp","assets/img/4537.jpg.webp"]
full-width: true

# thumbnail-img: ""
# share-img: ""
# comments:
# tags:
# css: assets/css/About.css
---

<!-- <html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
html {
  box-sizing: border-box;
}


</style>
</head>
<body> -->

<!-- <div class="row">
  <div class="column">
    <div class="card">
      <img src="/assets/img/NASA-james-webb-telescope-07.jpg.webp" alt="James Webb" style="width:100%">
      <div class="container">
        <h2>Awesomw!</h2>
        <p class="title">Something</p>
        <p>Some text that describes me lorem ipsum ipsum lorem.</p>
        <p>keshavsinghal2002@gmail.com</p>
        <p><button class="button">Contact</button></p>
      </div>
    </div>
  </div>

  <div class="column">
    <div class="card">
      <img src="/assets/img/NASA-james-webb-telescope-07.jpg.webp" alt="James Webb" style="width:100%">
      <div class="container">
        <h2>Test2</h2>
        <p class="title">Art Director</p>
        <p>Some text that describes me lorem ipsum ipsum lorem.</p>
        <p>example@example.com</p>
        <p><button class="button">Contact</button></p>
      </div>
    </div>
  </div>
  
  <div class="column">
    <div class="card">
      <img src="/assets/img/4537.jpg.webp" alt="John" style="width:100%">
      <div class="container">
        <h2>Okay</h2>
        <p class="title">Designer</p>
        <p>Some text that describes me lorem ipsum ipsum lorem.</p>
        <p>example@example.com</p>
        <p><button class="button">Contact</button></p>
      </div>
    </div>
  </div>
</div>

</body>
</html>

 -->
 <style>
   @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@100;300;400;500;700;900&display=swap');
*{
  margin:0;
  padding:0;
  font-family: 'Roboto', sans-serif;
}
/* 
body {
  display:flex;
  justify-content:center;
  align-items:center;
  min-height:100vh;
  background:#e0f7f1;
} */

.container{
  position:relative;
  display:flex;
  flex-direction:row;
  justify-content:center;
  align-items:center;
  flex-wrap:wrap;
  margin-left:auto; 

}
.container .card {
  position:relative;
  width:250px;
  height:300px;
  margin:20px;
  overflow:hidden;
  box-shadow:0 5px 15px rgba(0,0,0,.2);
  border-radius:15px;
  display:flex;
  justify-content:center;
  align-items:center;
  cursor:pointer;
}
.container .card .imgBox {
  width:100%;
  height:100%;
}
.container .card .imgBox img {
  width:100%;
  height:100%;
  background-position: center;
  background-size: cover;
  object-fit:cover;
  transition:.3s ease-in-out;
}
.container .card:hover .imgBox img{
  transform:translateY(-20px);
}
.container .card .content{
  position:absolute;
  bottom:-160px;
  width:100%;
  height:160px;
  display:flex;
  justify-content:center;
  align-items:center;
  z-index:10;
  flex-direction:column;
  backdrop-filter:blur(15px);
  box-shadow:0 -10px 10px rgba(0,0,0,.1);
  border:1px solid rgba(255, 255, 255, 0.2);
  color:#fff;
  transition:bottom .4s ease-in-out;
}

.container .card:hover .content {
  bottom: 0px;
}
.container .card .content .contentBox h3{
  color:#fff;
  text-transform:uppercase;
  letter-spacing:2px;
  font-weight:500;
  font-size:18px;
  text-align:center;
  line-height:1.1em;
  transition:.5s;
  margin:20px 0 15px;
  opacity:0;
  transform:translateY(-20px);
}
.container .card:hover .content .contentBox h3 {
  opacity:1;
  transform:translateY(0);
}
.container .card .content .contentBox h3 > span {
  font-size:12px;
  font-weight:300;
  text-transform:initial;
}
.container .card .content .social {
  position:relative;
  bottom:10px;
  display:flex;
}
.container .card .content .social li{
  list-style:none;
  margin: 0 10px;
  transform:translateY(40px);
  transition:.5s;
  opacity:0;
  transition-delay: calc(0.2s * var(--i))
}
.container .card:hover .content .social li{
  transform:translateY(0);
  opacity:1;
}

.container .card .content .social li a{
  color:#fff;
  font-size:24px;
}
.f:hover{
  color: #4287f5;
}
.i:hover{
  color:#fc44b3;
}
.t:hover {
  color:#448efc;
}
 </style>


<div class="container">

  <div class="card">
    <div class="imgBox">
      <img src="https://images.pexels.com/photos/3380805/pexels-photo-3380805.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940">
    </div>
    <div class="content">
      <div class="contentBox">
        <h3>Title<br><span>Sub-title</span></h3>
      </div>
      <ul class="social">
        <li style="--i:1;"><a href="#"><i class="fab fa-facebook-f f"></i></a></li>
        <li style="--i:2;"><a href="#"><i class="fab fa-instagram i"></i></a></li>
        <li style="--i:3;"><a href="#"><i class="fab fa-linkedin t"></i></a></li>
      </ul>
    </div>
  </div>

  <div class="card">
    <div class="imgBox">
      <img src="https://images.pexels.com/photos/3380805/pexels-photo-3380805.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940">
    </div>
    <div class="content">
      <div class="contentBox">
        <h3>Title<br><span>Sub-title</span></h3>
      </div>
      <ul class="social">
        <li style="--i:1;"><a href="#"><i class="fab fa-facebook-f f"></i></a></li>
        <li style="--i:2;"><a href="#"><i class="fab fa-instagram i"></i></a></li>
        <li style="--i:3;"><a href="#"><i class="fab fa-linkedin t"></i></a></li>
      </ul>
    </div>
  </div>

  <div class="card">
    <div class="imgBox">
      <img src="https://images.pexels.com/photos/3380805/pexels-photo-3380805.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940">
    </div>
    <div class="content">
      <div class="contentBox">
        <h3>Title<br><span>Sub-title</span></h3>
      </div>
      <ul class="social">
        <li style="--i:1;"><a href="#"><i class="fab fa-facebook-f f"></i></a></li>
        <li style="--i:2;"><a href="#"><i class="fab fa-instagram i"></i></a></li>
        <li style="--i:3;"><a href="#"><i class="fab fa-linkedin t"></i></a></li>
      </ul>
    </div>
  </div>
</div>


