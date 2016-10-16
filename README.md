# udacity-portfolio-project
My portfolio project
This my own created portfolio that i will use to post projects of past websites that i have created to future clients or employers. 

I used notepad to install this page
To download notepad: 
1. I went to the website and clicked the download link. 
2. open your downloads folder and click on the notepad link to begin the download
3. select your preferred language
4. read the information and click the license agreement.
5. select the location of where you want to install the notepad
6. read the info on the final window and click Run. 

lessons to help build portfolio
I. Intro to HTML and CSS
a. HTML, CSS, and boxes
b. CSS frameworks and responsive layouts
c. bootstraps and other frameworks

II. Responsive Web development design fundamentals
III. Responsive images


Getting started

basic html tree and style

<!DOCTYPE HTML>
<html>
    <head>
    </head>

    <body>
    </body>
</html>

Adding the title

<head>
        <title>My portfolio</title>
    </head>
    
    add css
    
    .name {
	font-size:48px;
	text-align:right;
	padding-right: 150px;
	font-style:normal;
	font-weight:70;
	margin-top:-12px;
	font-weight: normal;
}

.title {
	text-align:right;
	margin-top: -33px;
	padding-right: 150px;
}

.logo {
	position: absolute;
	left: 320px;
	top: 20px;
	
	width: 70px;
	height: 60px;
}
*/* {
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    -ms-box-sizing: border-box;
    box-sizing: border-box;
} */



hr {
	width: 65%;
	margin-right:150px;
	background-color:#7d97ad;
	height:6px;
}
.main {
margin-right: 150px;	
 width: 850px;
 height:420px;
 display:block;
 border: none;
 
 
}

.ninja {
	text-align: right;
	margin-right:148px;
	margin-top:-30px;
}

.pictures {
  margin-left:2px;
  margin-right:-30px;
  border: none;
  max-width: 100%;
  padding-left: 100 px;
  padding-right:0 px;
  width:335px;
  height: auto%;
  display: block;
  background: #fffff;
  transition: transform .2s ease-in-out;
}

#gallery {
  margin: 0;
  padding: 5%;
  padding-left:280px;
  list-style: none;
  height:100%;
  width:30%;
  display: flex;
  
  
}
#gallery li {
  margin: 2.0%;
  background-color: #fffff;
  color: #fffff;
}

a {
  display: inline-block;
  margin-bottom: 8px;
  width: calc(27% - 4px);
  text-decoration: none;
  margin-left: 25px;
  
  color: black;
  
}

a:nth-of-type(3n) {
  margin-right: 0;
}

.features {
	position:absolute;
	top: 530px;
	left: 330px;
	color: #7d97ad;
	font-size: 40px;
}

figcaption {
  margin-top: 15px;
}/*the url link of my projects*/

.title {
  text-align: center;
  font-size: 1em;
  margin: 5px 0 20px 90px;
  display:flex;
  padding: 0 auto;
 
  width:100%;
}

add the link to the css page and the meta viewport so website can easily accessible on either screen.

<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" type="text/css" href="css\styles.css">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="viewport" content="user-scalable=0, initial-scale=1.0">
<title>My portfolio</title>
</head>


add my gallery
between the body and under the header, add the section tag.
<section>

<h2 class="features">Featured work</h2>
<div id ="gallery">
  <a href="images/portfolio-1.png" class="pictures">
    <figure>
      <img src="images/portfolio-1.png" class="pictures" alt="">
	  <h4 class="title">portfolio i made for treehouse</h4>
      <figcaption>https://github.com/Odis22/Portfolio</figcaption>
    </figure>
  </a>
  <a href="images/portfolio-2.png" class="pictures">
    <figure>
      <img src="images/portfolio-2.png" class="pictures" alt="">
	 <h4 class="title">a site for responsive images</h4>
     <figcaption>https://github.com/Odis22/respimages</figcaption>
    </figure>
  </a>
  <a href="images/portfolio-3.png" class="pictures">
    <figure>
      <img src="images/portfolio-3.png" class="pictures" alt="">
	  <h4 class="title">sass website</h4>
      <figcaption>https://github.com/Odis22/sass</figcaption>
    </figure>
  </a>
  </div>
  </section>
  
  make sure you include the div tags and classes. 

    
