<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Alicia's List of Five</title>
    <link rel='stylesheet' href='fivecolorstools-styles.css'/>
    
    <link href="https://fonts.googleapis.com/css?family=Miriam+Libre&display=swap" rel="stylesheet">
    
    
    <link href="https://fonts.googleapis.com/css?family=Zilla+Slab+Highlight&display=swap" rel="stylesheet">
   
    <link href="https://fonts.googleapis.com/css?family=Alice&display=swap" rel="stylesheet">
  </head>
  
  
  <body>
    <header><h1 style="font-size:55px(max-width:780px)">Five Color Tools Every <br> Frontend Developer Needs
      </h1>
    </header>
    <figure>
    <img src="https://i.postimg.cc/fRYTh2W3/alicia-1.png" class="profil">
      <figcaption><span class="caption">Alicia Heraz </span> 
        </figcaption>
        <br>
        <figcaption class ="border">
        Last updated on November 5th 2019
        </figcaption>
      </figure>
    <div class = "wrapper">   
    
      <div class="colordot"><h2><span class="num">1.</span> Colordot</h2>
    <a href = "https://colorhunt.co//">Color.HailPixel.com
    </a>
    <p>Colordot from HailPixel is a color picker designed for human. It's intuitive, fast, and beautiful. Build palettes with a swipe of your finger or use your camera to capture colors from the world around you. Colordot is perfect for web developers, illustrators, interior designers and anyone who loves color!</p>

<p><mark class = "m2">This is one of the better color pallets apps I've used. The color control feels intuitive and natural on my iPad as well.

  </mark></p>
    <img src ="https://i.postimg.cc/VLnHq1gC/hailpixel-com.png" class = "img">
    
      <h2><span class="num">2.</span> Color Hunt</h2>
      
      <a href="">ColorHunt.co</a>
      
      <p>Color Hunt is a free and open platform for color inspiration with thousands of trendy hand-picked color palettes. Color Hunt got featured in many different websites, blogs, social networks and magazines related to design.</p>
      
      <p><mark class="m2">The best designers and artists share their best palettes. I stronlgy recommend it for developers who are not designers and don't know how to match colors.</p>
        
        <img src="https://i.postimg.cc/Mpzt1BXC/colorhunt-co.png" class="img">
        
      <h2><span class="num">3.</span> Image Color Picker</h2>
      
      <a href="">ImageColorPicker.com</a>
      
      <p>ImageColorPicker pickes your colors from any image online. Use the online image color picker to select a color and get the html Color Code of the selected pixel. You get the HEX, RGB and HSV color coding formats. You can either upload an image from your computer on open an online URL. A thumbnail is generated if you choose a URL to a website.</p>
      
      <p><mark class="m2">This tool is very practical and convenient. It is common to pick colors from picture and many artists do it to build their palette!</mark></p>
      
      <img src="https://i.postimg.cc/76zSFPf1/imagecolorpicker-com.png" class="img">
      
      <h2><span class="num">4.</span> Material.io</h2>
      
      <a href="">Material.io/Resources/Color</a>
      
      <p>Color Tool from Material.io makes it easy for you to create a color palette from only one dominant color. Use it to create, share and apply color palettes to your UI, as well as measure the accessibility level of any color combination.</p>
      
      <p><mark class="m2">This is one of the most comprehensive color picker for designers. It is very helpful when you have one color in mind but don't know how and where to place it in your UI.</mark></p>
      
      <img src="https://i.postimg.cc/Z5qpTxW5/material-io-1.png" class="img">
      
      <h2><span class="num">5.</span> Palette.Site</h2>
      
      <a href="">Palette.site</a>
      
   <p>Palette.site allows you to get the essential colours from any website. This browser extension generates comprehensive palettes and is a must-have tool for designers and frontend developers. It's a free colour scheme extraction.</p>
      
      
      <p><mark class="m2">We browse beautiful websites everyday! Why don't use this tool to extract the colors and understand the color choice of great designers and thus become a great artist!</mark></p>
      
      <img src="https://i.postimg.cc/yYpWT4N7/palette-site.png"
           class = "img">
  </body>
</html>

html,body{
  padding:0px;
  margin:0px;
  box-sizing:border-box;
}
header{
  color:white;
  text-align:center;
  background-image: linear-gradient(rgba(0, 0, 0, .3), rgba(0, 0, 0, .3)),url(https://i.postimg.cc/8z6qcMJL/header.png);
  background-repeat:none;
  background-size:cover;
  width:auto;
  border:solid 5px white;
  height:500px;
  display:flex;
  justify-content:center;
  align-items:center;
}
h1{
  font-family: 'Miriam Libre', sans-serif;
  font-size:55px
}

.profil{
  border-radius: 100%;
  border:solid 1px white;
  width:66%;
  margin-left:auto;
  margin-right:auto;
  display:flex;
  justify-content:center;
  width: 100px;
  margin-top:-50px;
}  

figcaption{
  width:66%;
  margin-left:auto;
  margin-right:auto;
  display:flex;
  justify-content:center;
  text-align:center;
  
}
.caption{
  font-family: 'Alice', serif;
  font-size:30px;
}
.border{
  border-bottom:solid 2px grey;
  padding-bottom:10px;
  width:15%;
}

.wrapper{
  width:66%;
  margin-left:auto;
  margin-right:auto;
}


h2{
  font-family: 'Zilla Slab Highlight', cursive;
  font-size:45px;
  font-weight:bold;
  margin-bottom:
}
  
.m2{
  font-style:italic;
  background-color:#FDD835;
  padding:3px;
  margin-top:20px;
}
p{
  font-family: 'Alice', serif;
  font-size:23px;
  line-height:32px;
  color:rgb(51,51,51);
  margin-bottom:20px;
}

a{
  color:#42b4d6;
  text-decoration:none;
  margin-bottom:20px;
}
a:hover{
  text-decoration:underline;
}
.img{
  width:100%;
  display: block;
  margin-bottom:120px;
}
.num{
  color:rgba(0, 0, 0, 0.25);
}
