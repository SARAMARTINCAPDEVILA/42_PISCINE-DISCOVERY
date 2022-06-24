<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menú Responsive</title>
    <link rel="stylesheet" href="burger.css">
   
</head>
<body>
    <nav>
        <input type="checkbox" id="check">
        <label for="check" class="checkbtn">
            <i class="fas fa-bars"></i>
        </label>
        <a href="#" class="enlace">
            <img src="C:\Users\Susanna\Desktop\P42\455-4553652_sncf-logo-sncf-png-transparent-png.png" alt="" class="logo">
        </a>
        <ul>
            <li><a class="active" href="#">MENU SNCF</a></li>
            <li><a href="#">Burgers</a></li>
            <li><a href="#">Sides</a></li>
            <li><a href="#">Sweets</a></li>
            <li><a href="#">Drinks</a></li>
        </ul>
    </nav>
    <section></section>
</body>
</html>142

*{
background-image: URL();
  list-style: none;
  box-sizing: border-box;
}

nav{
  background: #96cd2f;
  height: 80px;
  width: 100%;
}
.enlace{
  position: absolute;
  padding: 20px 50px;
}
.logo{
  height: 40px;
}
nav ul{
  float: right;
  margin-right: 20px;
}
nav ul li{
  display: inline-block;
  line-height: 80px;
  margin: 0 5px;
}
nav ul li a{
  color: black;
  font-size: 18px;
  padding: 7px 13px;
  border-radius: 3px;
  text-transform: uppercase;
  font-weight: 900;
}
li a.active, li a:hover{
  background:yellow;
  transition: .5s;
}
.checkbtn{
  font-size: 30px;
  color: #fff;
  float: right;
  line-height: 80px;
  margin-right: 40px;
  cursor: pointer;
  display: none;
}
#check{
  display: none;
}
section{
  background: url(fondo.jpg) no-repeat;
  background-size: cover;
  background-position: center center;
  height: calc(100vh - 80px);
}

@media (max-width: 952px){
  .enlace{
      padding-left: 20px;
  }
  nav ul li a{
      font-size: 16px;
  }
}

@media (max-width: 858px){
  .checkbtn{
      display: block;
  }
  ul{
      position: fixed;
      width: 100%;
      height: 100vh;
      background: #2c3e50;
      top: 80px;
      left: -100%;
      text-align: center;
      transition: all .5s;
  }
  nav ul li{
      display: block;
      margin: 50px 0;
      line-height: 30px;
  }
  nav ul li a{
      font-size: 20px;
  }
  li a:hover, li a.active{
      background: none;
      color: red;
  }
  #check:checked ~ ul{
      left:0;
  }
}


https://www.youtube.com/watch?v=f7QujqArvIw
