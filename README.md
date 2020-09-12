<!DOCTYPE html>
<html>
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.0.0-alpha.4/css/bootstrap.min.css">
<style>

h1 {text-align: center;
  font-family: "Sofia";
    color:black;}
h3 {text-align: center;
  font-family: "Sofia";
  font-size: 22px;
    color:black;}


input[type=text], select, textarea {
  width: 120%;
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 5px;
  box-sizing: border-box;
  margin-top: 1px;
  margin-bottom: 5px;
  resize: vertical;
}

input[type=submit] {
  background-color: rgb(9, 138, 9);
  color: white;
  padding: 15px 40px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}



.container{
  border-radius: 3px;
 background: linear-gradient(160deg,#3500D3,pink);
 
  padding: 50px;
}
.header {
  overflow: hidden;
  background-color:#9ded41 ;
  padding: 20px 10px;
}

.header a {
  float: left;
  color: black;
  text-align: center;
  padding: 12px;
  text-decoration: none;
  font-size: 18px; 
  line-height: 25px;
  border-radius: 4px;
}

.header a.logo {
  font-size: 25px;
  font-weight: bold;
}

.header a:hover {

  background-color: rgb(141, 138, 138);
  color: black;
}

.header a.active {
  background-color:green;
  color: white;
}

.header-right {
  float: right;
}










a,
a:hover,
a:focus,
a:active {
  text-decoration: none;
  color: inherit;
}
a {
  -webkit-transition: all .25s ease-in-out;
  transition: all .25s ease-in-out;
}
.ct-u-paddingTop10 {
  padding-top: 10px !important;
}
.ct-footer {
  background-color:white;
  padding-top: 1px;
  margin-top: 1px;
  position: relative;
}
.ct-footer-pre {
  width: 100%;
  padding-bottom: 55px;
  border-bottom: 1px solid #555;
  border-bottom: 1px solid rgba(255, 255, 255, 0.1);
}
.ct-footer-list {
  padding: 50px 0;
  list-style: none;
  padding-left: 0;
  
  display: table;
  width: 100%;
  border-bottom: 1px solid #555;
  border-bottom: 1px solid rgba(255, 255, 255, 0.1);
}
.ct-footer-list > li .ct-footer-list-header {
  font-family: 'Open Sans Condensed', sans-serif;
  color: #00bff3;
  font-size: 30px;
}
.ct-footer-list > li ul {
  list-style: none;
  padding-left: 0;
}
.ct-footer-list > li ul li a {
  color: #fff;
}
.ct-footer-list > li ul li a:hover,
.ct-footer-post a:hover {
  text-decoration: underline;
}
.ct-footer-post {
  background: white;
  padding: 30px 0;
}


@media (min-width:1200px) {
  .ct-footer-pre {
    display: table;
  }
  .ct-footer-pre > .inner {
    display: table-cell;
    vertical-align: middle;
  }
  .ct-footer-list > li {
    width: 20%;
    display: table-cell;
    vertical-align: top;
  }
  .ct-footer-list > li:last-child {
    width: 7%;
}
@media (max-width:1199px) {
  .ct-footer-pre .form-group {
      padding-top: 15px
  }
}
@media (max-width: 1199px) {
  .ct-footer-list > li {
    display: inline-block;
    float: left;
  }
}

body{
margin:0;
padding:0;
background-image:url(main.jpg);
background-size:cover;
background-position:center;
}

 .contact-form {
        background: rgba(0,0,0,.6);
        color:white;
        margin-top: 10px;
        padding: 12px;
        box-shadow:  grey;
        width: 12;
        height: 320;
    }


</style>
</head><title>contactpage</title>
<body>

<div class="header"style="  background: linear-gradient(160deg,#3500D3,pink);">
  <a href="#default" class="logo">Logo</a>
  <div class="header-right">
    <a href="#home">Home</a>
    <a href="#pricing">Pricing</a>
    <a href="#blog">Blog</a>
    <a href="#Category">Category</a>
    <a href="#contact us">Contact Us</a>
    <a href="#Login">LOGIN</a>
  </div>
</div>

<h1>We'd love to hear from you</h1>
<h3>get in touch with us</h3>


  <div class="container contact-form" >
<div class="container-center" style="max-width:600px;margin:auto;">
  <form action="tq.png" >
    <label for="name"></label>
    <input type="text" id="fname" name="name" placeholder="NAME" type="text" tabindex="1" required autofocus>

    <label for="Email-id"></label>
    <input type="text" id="e-mail" name="E-mail" placeholder="EMAIL-ID" type="email" tabindex="2" required>

    <label for="Phone No"></label>
    <input type="text" id="phone no" name="Phone No" placeholder="PHONE NO" type="tel" tabindex="3" required>

    <label for="subject"></label>
    <textarea id="Message" name="subject" placeholder="MESSAGE" tabindex="5" required style="height:200px"></textarea>
<br>
    <input type="submit" value="Submit" onClick="Submit"  style="margin-left: 40%">
  </form>
</div>
  </div>


  <script>
function Submit() {
  var xhttp = new XMLHttpRequest();
  xhttp.onreadystatechange = function() {
    if (this.readyState == 4 && this.status == 200) {
      document.getElementById("demo").innerHTML =
      this.responseText;
    }
  };
  xhttp.open("GET", "tq.png", true);
  xhttp.send();
}
</script>









  



  <footer class="ct-footer">
    <div class="container">
      <ul class="ct-footer-list text-center-sm">
        <li>
          <h2 class="ct-footer-list-header">Learn More</h2>
          <ul>
            <li>
              <a href="">PRIVACY POLICY</a>
            </li>
            <li>
              <a href="">CAREER</a>
            </li>
            <li>
              <a href="">CONTACT US</a>
            </li>
           
          </ul>
        </li>
        <li>
          <h2 class="ct-footer-list-header">Services</h2>
          <ul>
            <li>
              <a href="">BLOG</a>
            </li>
            <li>
              <a href="">TERMS&COND</a>
            </li>
            <li>
              <a href="">HELP</a>
            </li>
           
          </ul>
        </li>
        <li>
          <h2 class="ct-footer-list-header">The course</h2>
          <ul>
            <li>
              <a href="">CONDITIONS</a>
            </li>
            <li>
              <a href="">CONTACT FOR BUSINESS</a>
            </li>
            <li>
              <a href="">FaQ</a>
            </li>
          </ul>
        </li>
      </ul>
    </div>
  </footer>


</body>
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.6/css/bootstrap.min.css" rel="stylesheet">
<link href="collapsible-footer.scss" rel="stylesheet">
<script src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.6/js/bootstrap.min.js"></script>


</html>
