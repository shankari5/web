<!DOCTYPE html>
<html lang="en">
<head>
<title>Page Title</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}


body {
  font-family: Arial, Helvetica, sans-serif;
  margin: 0;
}


.header {
  padding: 80px;
  text-align: center;
  background: #1abc9c;
  color: white;
}


.header h1 {
  font-size: 40px;
}

.navbar {
  overflow: hidden;
  background-color:black ;
}

/* Style the navigation bar links */
.navbar a {
  float: left;
  display: block;
  color: white;
  text-align: center;
  padding: 14px 20px;
  text-decoration: none;
}

/* Right-aligned link */
.navbar a.right {
  float: right;
}

/* Change color on hover */
.navbar a:hover {
  background-color: #ddd;
  color:black ;
}

/* Column container */
.row {  
  display: -ms-flexbox; /* IE10 */
  display: flex;
  -ms-flex-wrap: wrap; /* IE10 */
  flex-wrap: wrap;
}

/* Create two unequal columns that sits next to each other */
/* Sidebar/left column */
.side {
  -ms-flex: 30%; /* IE10 */
  flex: 30%;
  background-color: #f1f1f1;
  padding: 20px;
}

/* Main column */
.main {   
  -ms-flex: 70%; /* IE10 */
  flex: 70%;
  background-color: white;
  padding: 20px;
}


.fakeimg {
  background-color: #aaa;
  width: 100%;
  padding: 20px;
}


.footer {
  padding: 20px;
  text-align: center;
  background: #ddd;
}


@media screen and (max-width: 700px) {
  .row {   
    flex-direction: column;
  }
}


@media screen and (max-width: 400px) {
  .navbar a {
    float: none;
    width: 100%;
  }
}
</style>
</head>
<body>

<div class="header">
  <h1>About Myself</h1>
  <p>And My college</p>
</div>

<div class="navbar">
  <a href="#" class="active">Me</a>
  <a href="https://kongu.ac.in">College</a>
  
  
</div>

<div class="row">
  <div class="side">
    
    <h5>My favourites:</h5>
    <img src="C:\Users\Nanku\Pictures\Screenshots\lam5.png" width="1174px" height="587px" >
    
    <p>My favourite are so many one among them is cars.</p>
    <p>In those lamborghini is my favourite one, so i have mentioned. </p>
    <h3>This is just a small information about me.</h3>
    <p>Thank you</p>
   
    
    
  </div>
  <div class="main">
    <h2>About Me:</h2>
    <h5>'15th January, 2006' is my DOB</h5>
    <p>Some text..</p>
    <p>I'am living in a small family with three member and no siblings.</p>
    
    <br>
    <h2>My College and My Carrier</h2>
    <h5>I'am studying in Kongu Engineering College as a first year student.</h5>
    <img src="C:\Users\Nanku\OneDrive\Documents\college.png" width="600" height="500">
    <p>Some text about my aim:</p>
    <p>AIML(Artificial Intelligence and Machine Learning) is the course that i have choosen.</p>
    <p>Though our college has a good NIRF ranking and i believe that i will be placed in a good company.</p>
    <h5>My inspiration:</h5>
    <img src="C:\Users\Nanku\Downloads\sun1.webp" width="900px" height="750px">
    <p>Sundar Pichai is a computer engineer and the current CEO of Google Inc. The technology giant Google, which specializes in Internet-related services and products, underwent a major corporate restructuring in 2015 following which Alphabet Inc was launched as its parent company with co-founders Larry Page as its CEO and Sergey Brin as President.</p>
  </div>
</div>

<div class="footer">
  <p>Thank you</p>
  <p>“Where there’s a will, there’s a way.”</p>
  <h2>JAI HIND!!</h2>
</div>

</body>
</html>
