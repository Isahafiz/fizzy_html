<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Isah Abdulhafeez</title>
    <link rel="stylesheet" href="fizzy.css">
    <script src="https://kit.fontawesome.com/dcd182b9fc.js" crossorigin="anonymous"></script>
</head>
<body> 

   <section class="go">
        <h1><span class="virgo">ISAH ABDULHAFEEZ</span></h1>
        <nav>
            <ul>
                <li> <a href="">Home</a> </li>
                <li> <a href="">Portfolio</a></li>
                <li> <a href="#">Contact</a></li>
            </ul>
            <a href="#contact" class="btn">CONTACT</a>
        </nav>
    </section>
    <section class="hero">
      <div>
        <p class="intro">--- intro</p>
        <h2>
            Hello <br> i'm <br> Isah <br> Abdulhafeez
        </h2>
        <p class="ui">I’m a Website Designer currently based in Nigeria. <br> I enjoy solving users’ problems and turning them <br> into beautiful designs.</p>
        <a href="#contact" class="bto">CONTACT</a>
      </div>
    </section>
    <section class="div">
        <div class="one">
            <i class="fa-solid fa-3x fa-bezier-curve" style="margin-top:20px ;"></i> <br>
           <h4> Developer & Designer</h4> <br>
          <i>i'm a front-end web developer. I can provide clean code and pixel perfect design. I also make the website more & more interactive with web animations.I can provide clean code and pixel perfect design. I also make the website more & more interactive with web animations.A responsive design makes your website accessible to all users, regardless of their device.</i>
            
            
        </div>
        <div class="two">
            <i class="fa-brands fa-3x fa-aws" style="margin-top:20px;"></i> <br>
         <h4>Our Services </h4> <br>
         <i> Web Development <br>
            Every website should be built with two primary goals: Firstly, it needs to work across all devices. Secondly, it needs to be fast as possible.</i>
            
            
        </div>
        <div class="three">
            <i class="fa-brands fa-3x fa-css3" style="margin-top:20px ;"></i> <br>
        <h4>Logo Design</h4> <br>
           <i>The technological revolution is changing aspect.</i> 
        </div>
        <div class="four">
            <i class="fa-regular fa-3x fa-mobile" style="margin-top:20px ;"></i> <br>
         <h4>Mobile Design</strong> <h4>
           <i>you are looking for a user-friendly app that will attract more mobile users, I can help you design and build a platform with the latest and trendiest look and feel.</i> 
        </div>

    </section>
     <section class="last">
     <div class="ok">
        <hr class="hr"> <br>
        <h3>
            Isah Abdulhafeez </h3><br>

          <strong>For more HTML, CSS, and coding tutorial - please click on the link below to subscribe to my channel:</strong>
          <a href="#contact" class="btc">CONTACT</a>
        </div>
     </section>
     <footer>
          <div class="social">
            <a href="http://www.facebook.com/abdulhafiz.isah.37"><i class="fa-brands fa-2x fa-facebook"></i></a>
            <a href="http://wa.me/2348142912008"> <i class="fa-brands fa-2x fa-whatsapp"></i></a>
            <a href="http://twitter.com/fizzyofafrica"> <i class="fa-brands fa-2x fa-twitter"></i></a>

          </div>
        
        <h6>CopyRight © 2022 Isah Abdulhafiz</h6>
     </footer>
    
</body>
</html>
*{
    margin: 0;
    padding: 0;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    box-sizing: border-box;
}
body{
    background: linear-gradient(
        to bottom,
        #181616 0vh,
        #181616 230vh,
        black 230vh,
        black 250vh
    );
    height: 250vh;
}

.virgo{
    font-size: 150%;
    background-image: linear-gradient(
        to bottom,
        rgb(251,246,226),
        rgb(226,241,175),
        rgb(74,245,172)
    );
    -webkit-background-clip: text;
    -moz-background-clip: text;
    background-clip: text;
    color: transparent;
    
    
}
    
    
h1{
    margin-top: 30px;
    margin-left: 60px;
}
nav{
    margin-top: -7%;
    
}
nav ul li{
    justify-content: space-between;
    float: left;
    display: inline;
    padding: 5%;
    
    
    
    
}
nav ul li a{
    color: white;
    text-decoration: none;
    list-style: none;
    position: absolute;
    display: flex;
    text-align: center;
    font-weight: bold;
    margin-left: 30%;
    margin-bottom: 120%;
    font-size: 150%;
    
}

nav ul li a:hover{
	color: #f9004d;
	transition: .4s;
    
}

p{
    color: green;
    margin-top: 5%;
    margin-left: 5%;
    font-size: x-large;
}
.btn{
	background-color:#FECD1A;;
	color: white;
	text-decoration: none;
	border: 2px solid transparent;
	font-weight: bold;
	padding: 20px 50px;
	border-radius: 30px;
	transition: transform .4s;
    margin-left: 85%;
    display: inline;
    margin-top: 5%;
     
}
.btn:hover{
    transform: scale(1.2);
    background-color: #64F4AB;
}
h2{
    margin-top: 0%;
    color: white;
    margin-left: 5%;
    font-size: 500%;
}
div p.ui{
    color: white;
}
.bto{
	background-color:#FECD1A;
	color: white;
	text-decoration: none;
	border: 2px solid transparent;
	font-weight: bold;
	padding: 20px 50px;
	border-radius: 30px;
	transition: transform .4s;
    margin-left: 40%;
    display: inline;

     
}
.bto:hover{
  transform: scale(1.2); 
  background-color: #64F4AB;
}
.one{
    background-color: black;
    border: 2px white transparent;
    width: 23vw;
    height: 55vh;
    border-radius: 15px;
    margin-top: 5%;
    margin-left: 2%;
    text-align: center;
    color: white; 
    justify-content: center;
}
.one:hover{
    transform: scale(1.0);
    background-color: #64F4AB;
}
.two{
    background-color: black;
    border: 2px white transparent;
    width: 23vw;
    height: 55vh;
    border-radius: 15px;
    margin-top: 5%;
    margin-left: 2%;
    text-align: center;
    color: white;
}
.two:hover{
    transform: scale(1.0);
    background-color: #64F4AB;;
}
.three{
    background-color: black;
    border: 2px white transparent;
    width: 23vw;
    height: 55vh;
    border-radius: 15px;
    margin-top: 5%;
    margin-left: 2%; 
    text-align: center;
    color: white;  
}
.three:hover{
    transform: scale(1.0);
    background-color: #64F4AB;   
}
.four{
    background-color: black;
    border: 2px white transparent;
    width: 23vw;
    height: 55vh;
    border-radius: 15px;
    margin-top: 5%;
    margin-left: 2%;
    text-align: center;
    color: white;
    
}
.four:hover{
    transform: scale(1.0);
    background-color: #64F4AB;   
}
.div{
    position: absolute;
    display: flex;
    margin-left: 2.5%;
   
}
h4{
    margin-top: 10px;
}
.ok{
    background-color: black;
    border-radius: 30px;
    border: 2px solid transparent;
    width: 90vw;
    height: 50vh;
    margin-top: 40%;
    margin-left: 4.8%;
    color: white;
    text-align: center;
}
.hr{
    color: green;
    width: 5%;
    margin-left: 45%;
    margin-top: 5%;
}
h3{
    margin-top: 3%;
    font-size: xx-large;
}
.btc{
	background-color:#FECD1A;
	color: white;
	text-decoration: none;
	border: 2px solid transparent;
	font-weight: bold;
	padding: 20px 50px;
	border-radius: 30px;
	transition: transform .4s;
    display: inline;
    margin-top: 10%;

     
}
.btc:hover{
    transform: scale(1.2);
    background-color: #64F4AB;
}
/*.hori{
    margin-top: 18%;
    padding-right: 25%;
}*/
footer i.end{
    margin-top: 10%;
    
}

.social{
    margin-top: 10%;
    margin-left: 80%;
    
}
h6{
    margin-top: 2%;
    color: white;
    text-align: center;
    font-size: larger;
}
