MENU ej https://dev.to/tognola/menu-hamburguesa-solo-con-css-facil-1doc

! html 1st attempt!
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>SNCF* Hamburguesa</title>
    <link rel="stylesheet" href="menu.css" />
    <style>
      div {
        width: 70px;
        height: 15px;
        background-color: black;
        margin: 10px 0;
      }
    </style>
  </head>
  
  <body class="full">
     <> <div ></div> </area>
    <div  > </div>
    <div></div>
<hr></hr>
 <h1 class="tit">🚂 SNCF - Burger 🍔</h1>

  
 
    <br ></br>
     
                <ul>

                    <li class="pan">🔥 Coccion</li> </ul>

                    <ul><li class="pat">🍟 sides</li> </ul>
           <ul><li class="dri"> 🥤 bebidas</li>  </ul>
                              <ul><li class="des"> 🍩 postres</li>  </ul> 
  </body>
</html>


body {
  font-family: sans-serif;
}

.respmenu a {
  color: inherit;
  text-decoration: none;
  display: block;
  padding: 10px 20px;
  border-bottom: 2px solid #456789;
  max-width: 200px;
  background: #234567;
  font-variant: small-caps;
  text-shadow: 1px 1px black;
}

.respmenu input[type="checkbox"],
.respmenu .fa-bars,
.respmenu .fa-times {
  position: absolute;
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  right: 0;
  top: 0;
  width: 48px;
  height: 48px;
}

.respmenu .fa-bars,
.respmenu .fa-times {
  font-size: 48px;
  pointer-events: none;
}

.respmenu input[type="checkbox"] {
  opacity: 0;
}

.respmenu {
  color: white;
  position: relative;
  background: #123456;
  min-height: 48px;
}

.respmenu nav {
  display: none;
}

.respmenu input:checked ~ nav {
  display: block;
}

.respmenu input:checked ~ .fa-bars {
  display: none;
}

.respmenu input:not(:checked) ~ .fa-times {
  display: none;
}

/INTENTO 2/

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>SNCF* Hamburguesa</title>
    <link rel="stylesheet" href="menu.css" />
    
  </head>
  
  <body>

    <nav class="nav">
      <div class="nav_container">
        <h1 class ="nav_logo">🚂 SNCF - Burger 🍔 </h1>
     <div ></div>
    <div  > </div>
    <div></div>
<hr></hr>


    <br ></br>
     
                <ul>

                    <li class="pan">🔥 Coccion</li> </ul>

                    <ul><li class="pat">🍟 sides</li> </ul>
           <ul><li class="dri"> 🥤 bebidas</li>  </ul>
                              <ul><li class="des"> 🍩 postres</li>  </ul> 
  </body>
</html>


.nav_logo {
  color: black;
  text-align: left;
  text-decoration: underline;
  text-decoration: overline;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
}
.full {
  background-image: url("https://img.freepik.com/free-vector/seamless-pattern-with-burger-suitable-backgrounds-postcards-wrapping-paper-vector_174639-19568.jpg");
  color: black;
  align-items: center;
  padding-top: 10px;
  padding-bottom: 10px;
}

.but {
  width: 20px;
  height: 5px;
  background-color: white;
  margin: 6px 0;
}
.pan {
  text-align: center;
  font-size: 20px;
  font-family: monospace;
  list-style: none;
  position: relative;
  top: -5px;
  left: -10px;
}
.pat {
  text-align: center;
  font-size: 20px;
  font-family: monospace;
  list-style: none;
  position: relative;
  top: -5px;
  left: -10px;
}
.dri {
  text-align: center;
  font-size: 20px;
  font-family: monospace;
  list-style: none;
  position: relative;
  top: -5px;
  left: -10px;
}
.des {
  text-align: center;
  font-size: 20px;
  font-family: monospace;
  list-style: none;
}

