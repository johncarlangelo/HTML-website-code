<html>
<title>
AniWiki
</title>
<head>
    <link rel="shortcut icon" type="image/png" href="image//favicon.png">
    <header>
   <a href="MainPage.html"> <button class="button button1"><font face="Hobo Std">AniWiki</font></button></a>
   <hr color="#fff" size="3px">
</header>
<style>
.button1 {
  background-color: maroon;
  border: none;
  border-radius: .5rem;
  color: white;
  padding: 16px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  transition-duration: 0.4s;
  cursor: pointer;
}

.button1 {
  background-color: white; 
  color: Maroon; 
  border: 2px solid Maroon;
}

.button1:hover {
  background-color: Maroon;	
  color: white;
}
</style>
</head>
<body>
      <div class="container">
        <li><a href="MainPage.html" class="cool-link">Home</a></li>
        <li><a href="List.html" class="cool-link">List</a></li>
        <li><a href="Info.html" class="cool-link">Info</a></li>
        <li><a href="AboutUs.html" class="cool-link">About Us</a></li>
    </div>
<section class="home-page-section">
  <div class="img-wrapper">
  <div class="jotaro-image"></div>
  </div>
  <div class="call-to-action">
    <h1 class="title"><img src="image/favicon.png" width="80px"> The Otaku's Hearthstone</h1>
    <span class="subtitle">Get the latest news and updates about new series and movies in one click.</span>
  </div>
</section>
<footer class="main-footer">
  <div class="content">
    <nav class="footer-nav">
      <section class="discover-main-section">
      <ul>
        <li>© 2020 John Carl Bulaon</li>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        <li>Group 1</li>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        <li>AniWiki 2020</li>&nbsp;&nbsp;&nbsp;&nbsp;
        <li>St. Michael 2019 - 2020</li>
      </ul>
      </section>
    </nav>
</footer>
<style>
  body {
      margin: 0;
      padding: 0;
      background: rgb(0, 0, 0);
  }
   .container {
   position: absolute;
   top: 3%;
   left: 50%;
   transform: transLateX(-50%) transLateY(-50%);
}
li {
display: inline-block;
}
li a {
text-decoration: none;
display: inline-block;
color: #fff;
font-family: Hobo Std;
font-weight: lighter;
font-size: 20px;
padding: 0 20px;
letter-spacing: 10px;
}
.cool-link::after{
content: '';
display: block;
width: 0;
height: 2px;
background: #fff ;
transition: width .3s
}    
.cool-link:hover::after{
width: 100%;
transition: width .3s
}
</style>
    <style>
    body {
        background: maroon;
        background-image: url("image/FINAL BG 2-2.jpg");
        color: white;
        font-family: Gill Sans, Helvetica, sans-serif, Helvetica, Arial, sans-serif;
        margin: 0;
        padding: 0;
      }
      
      header {
        background: maroon;
        padding: 0.1px;
      }
</style>
<style>

  .title {
    font-weight: 500;
    font-size: 4em;
    color: maroon;
    font-family: Hobo Std;
    margin-bottom: 1rem;
    margin-top: 0;
  }

  .subtitle {
    font-weight: 500;
    font-size: 1.2em;
    color: maroon;
    font-family: Hobo Std;
    margin-bottom: 2rem;
  }

  .call-to-action {
    border: maroon;
    background-color: white;
    border-width: 20px ;
    border-style: groove;
  }

  .home-page-section {
    display: flex;
    align-items: stretch;
    justify-content: space-between;
    flex-grow: 1;
  }

  .home-page-section .img-wrapper {
    flex-grow: 1;
    flex-direction: column;
    display: flex;
    align-items: stretch;
    justify-content: flex-end;
  }

  .home-page-section .jotaro-image {
    background-image: url(image/Jotaro4.png);
    flex-grow: 1;
    height: 700px;
    width: 800px;
    bottom:900rem;
    background-size: contain;
    background-repeat: no-repeat;
    background-position: bottom left;
  }

  .home-page-section .call-to-action{
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    margin: 1rem;
    align-self: center;  
  }

</style>
<style>
  .main-footer {
    font-family: Hobo Std;
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: maroon;
    font-weight: bold;
    padding: 15px;
  }

  .footer-nav ul {
    display: flex;
    margin: 0;
    padding: 0;
    list-style: none;
  }

  .main-footer .content {
    display: flex;
    justify-content: space-between;
  }
</style>
<style>
  .discover-main-section {
    margin: 0 365px;
    display: flex;
    align-items: center;
    justify-self: space-between;
    flex-grow: 1;
  }

  .discover-main-section .covers-image {
    width: 30vw;
    margin-left: 2rem;
    height: auto;
    max-width: 350px;
  }
</style>
</body>
</html>
