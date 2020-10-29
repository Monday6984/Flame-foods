<template>
  <div id="app">

    <!--Header-->
    <header>
      <div id="header-wrap">
        <div class="logo">
          <img src="./assets/Logo.png"/>
        </div >

    <!--Nav-->
    <div class="desc"> 
    <nav>
      <ul>
        <li><a href="#">MENU</a></li>
        <li><a href="#">CONTACT</a></li>
        <li><a href="#">FAQ</a></li>
        <li><a href="#">|</a></li>
        <li><a href="#">LOGIN</a></li>
        <li><a href="#"><span>IMAGE</span></a></li>
      </ul>
    </nav>    
          
          
      <div class="about"><h1>GOOD TIMES</h1>
      <h1><span>WITH</span></h1>
      <h1>GREAT FRIENDS</h1>
      <p>Lorem Ipsum is simply dummy text of the printing 
         typesetting industry. Lorem Ipsum has been the 
         industry's standard dummy text ever.</p>
         <button type="button">View Menu</button>
         </div>

    </div>
         
    </div> 
     
    </header>

    <!--Main body-->
    <main>
      <section class="top">
        <h2>What's <span>available with us</span></h2>
      </section>

      <!--Services-->
      <section class="product-cards">
        <div id="product-card1">
          <img src="./assets/L11@1X.png"/>
          <h3>Deliciously Prepare Meal</h3>
          <p >It is a long established fact that a</p>
          <p>reader will be distracted by the</p>
          <p>readable content of a page when</p> 
          <p>looking at its layout. The point of</p>
          <p>using Lorem Ipsum.</p>
      
        </div>

        <div id="product-card2">
          <img src="./assets/Forma 1@1X.png"/>
          <h3>Custom Meal Just for You</h3>
          <p >It is a long established fact that a</p>
          <p>reader will be distracted by the</p>
          <p>readable content of a page when</p> 
          <p>looking at its layout. The point of</p>
          <p>using Lorem Ipsum.</p>
      
        </div>

       <div id="product-card3">
         <img src="./assets/L0001@1X.png"/>
          <h3>Meal for Family and Events</h3>
          <p >It is a long established fact that a</p>
          <p>reader will be distracted by the</p>
          <p>readable content of a page when</p> 
          <p>looking at its layout. The point of</p>
          <p>using Lorem Ipsum.</p>
      
        </div> 

      </section> 

      <!--About us-->
      <section class="About-us">
        <div id="About-image">
          <img src="./assets/Layer 515@1X.png"/>
          <img class="margin" src="./assets/Layer.png"/>     
        </div>

        <div id="About-desc">
          <h2>About <span>us</span></h2>
          <p >It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using 'Content here, content here', making it look like readable English. Many desktop publishing packages and web page editors now use Lorem Ipsum as their default model text, and a search for 'lorem ipsum.It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. </p>
        </div>
        </section>

        <section class="top">
        <h2>Top <span>menu</span></h2>
        </section>

        <!--Menus-->
        <section class="menus">
        <div class="menu">
          <div id="price">$25</div>
          <img src="./assets/Layer 516@1X.png"/>
          <h3>Fish Permentier</h3>
          <p>It is a long established fact that a reader 
           will be distracted by the readable content of a page</p>
        </div>

        <div class="menu">
          <div id="price">$32</div>
          <img src="./assets/Layer 517@1X.png"/>
          <h3>Caeser Sald</h3>
          <p class="original-price">It is a long established fact that a reader 
            will be distracted by the readable content of a page</p>
        </div>

        <div class="menu">
          <div id="price">$50</div>
          <img src="./assets/Layer 518@1X.png"/>
          <h3>Apple Strudel 2</h3>
          <p>It is a long established fact that a reader 
            will be distracted by the readable content of a page</p>
        </div>
      </section>

      <section class="top">
        <h2>Inst<span>agram</span></h2>
      </section>

      <!--Varieties-->
      <section id="display">
        <img src="./assets/pics1.png" id="pics1"/>
        <img src="./assets/pics2.png" id="pics2"/>
        <img src="./assets/pics3.png" id="pics3"/>
        <img src="./assets/pics4.png" id="pics4"/>
        <img src="./assets/pics5.png" id="pics5"/>
        <img src="./assets/pics6.png" id="pics6"/>
        <img src="./assets/pics7.png" id="pics7"/>
        <img src="./assets/pics8.png" id="pics8"/>

        
        <div class="edge1"></div>
        <div class="edge2"></div>
        <div class="edge3"></div>
        <div class="edge4"></div>
                    
      </section>

      <div id="social">
         <button type="button" >Follow Us</button>
      </div>
         
   
    </main>

    <footer>
      <section class="footer-rows">
        <div class="footer-row">
          <h4>About Us</h4>
          <p class="original-price">There are many variations of passages of <br> 
          Lorem Ipsum available, but the majority <br> have suffered alteration in 
          some form, <br> by injecteted humour, or randomised <br> words which don't 
          look even slightly <br> believable </p>
        </div>

        <div class="footer-row">
          <h4>Important Links</h4>
          <ul>
            <li><a href="#">Menu</a></li>
            <li><a href="#">Contact</a></li>
            <li><a href="#">FAQ</a></li>
            <li><a href="#">Login</a></li>
            <li><a href="#">Privacy Policy</a></li>
            <li><a href="#">Terms & Conditions</a></li>
          </ul>
        </div>

        <div class="footer-row">
          <h4>Contact Info</h4>
          <ul>
            <li>$8 Shrewsbury Rd, 20, Mbonu Strret, D line </li>
            <li>info@restaurants.com</li>
            <li><i class="fa fa-phone"></i>08052485059</li>
          </ul>
        </div>
     
      </section>

        <div><p class="copyright">@2020 Restaurants. All rights reserved</p></div>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'App',

}
</script>

<style>
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
body {
  font-family: sans-serif;
  background-color: #fff;
  
}
header {
  display: flex;
  width: 100%;
  /*justify-content: center;*/
  background-color: #000;
  color: #fff;
  
}

#header-wrap {
  width: 1000px;
  height: 500px;
  margin: 0 auto;
}

.logo {
  width: 500px;
  height: 500px;
  background-image: url(./assets/burger.png);
  padding: 20px 0px 0px 20px;
  float: left;
}


.desc {
  width: 500px;
  height: 500px;
  float: left;
  }

nav {
  background-color: #fff;
  margin: 20px 50px 0px 20px;
  width: 340px;

  }

nav ul {
  display: flex;
  list-style: none;
  font-size: 15px;
  font-family: Lato, -apple-system, BlinkMacSystemFont, "Segoe UI", "Helvetica Neue", Helvetica, Arial, sans-serif;
}

nav a {
  color: black;
  display: block;
  padding: 10px;
  text-decoration: none;
}

nav ul > li:last-child {
  background-color: #F61907;
}

nav a span {
  color: #fff;
}

nav a:hover {
  text-decoration: underline;
}

.about {
  margin: 50px;
}

.about h1 {
  margin-bottom: 15px;
  color: #f4b41a;
  font-family: Lato, -apple-system, BlinkMacSystemFont, "Segoe UI", "Helvetica Neue", Helvetica, Arial, sans-serif;;
}

.about h1 span {
  color: #fff;
}

button {
  color: #fff;
  background-color: #F61907 ;
  padding: 10px 30px 10px 30px;
  margin-top: 50px;
  font-size: 20px;
  
}

.top {
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: #fff;
  padding: 30px;
  font-size: 20px;
  margin-bottom: 50px;
    
}

h2 span, h3 span {
  color: #f4b414;
}

.product-cards {
  display: grid;
  grid-template-columns: auto auto auto;
  margin-bottom: 50px;
  background-color: rgb(255, 0, 0);
}

  #product-card1 {
  background-color: #F61907;
  display: inline-block;
  padding: 50px;
  text-align: center;
  color: #fff;
  line-height: 25px;
}

  #product-card2 {
  background-color: #f4b41a;
  display: inline-block;
  padding: 35px;
  text-align: center;
  color: #fff;
  line-height: 25px;
  
}

  #product-card3 {
  background-color: #047617;
  display: inline-block;
  padding: 35px;
  text-align: center;
  color: #fff;
  line-height: 25px;
  
}

#product-card1 h3 {
  margin: 20px 20px;
}

#product-card2 h3 {
  margin: 20px 20px;
}

#product-card3 h3 {
  margin: 20px 20px;
}

.About-us {
  display: grid;
  grid-template-columns: auto auto;
  background-color: #fff;
  margin: 0 auto;
  width: 1000px;
  margin-bottom: 30px;
}

#About-image {
  display: inline-block;
  text-align: center;
  color: #fff;
  width: 500px;
}

#About-image > img:first-child {
  border-radius: 0px 0px 10px 10px;
}

#About-image > img:last-child {
  margin-top: -100px;
  border: 4px solid #fff;
  border-radius: 10px;
}

#About-desc {
  display: inline-block;
  margin-top: 120px;
  padding: 35px 60px 35px 35px;
  text-align: left;
  line-height: 25px;
}

#About-desc h2 {
  margin-bottom: 20px;
}

.menus {
  display: grid;
  grid-template-columns: auto auto auto;
  margin-bottom: 50px;
  margin: 0 auto;
  width: 1000px;
}

.menus img {
    border-radius: 10px;
}

.menu {
  position: relative;
  display: inline-block;
  text-align: center;
  color: #000;
  margin: 5px;     
}

.menu h3  {
  margin: 15px 15px;
}

.menu p  {
  padding: 0px 20px 0px 20px;
}

#price {
  position: absolute;
  left: 1px;
  padding: 15px 25px 15px 25px;
  background-color: #f4b41a;
  color: #fff;
  border-radius: 10px 0px 10px 0px;
    
}

#display {
  position: relative;
  margin: 0 auto;
  width: 1000px;
  height: 600px;
  margin-top: 100px;
  
}

.edge1 {
  position: relative;
  background-color: #f4b41a;
  width: 340px;
  height: 279px;
  margin-left: -70px;
  z-index: 1;
}

.edge2 {
  background-color: #F61907;
  width: 279px;
  height: 384px;
  float: right;
  margin-top: -330px;
  margin-right: -40px;
}

.edge3 {
  position: absolute;
  background-color: #F61907;
  width: 279px;
  height: 324px;
  margin-left: -20px;
  margin-top: -100px;

}

.edge4 {
  position: absolute;
  background-color: #f4b41a;
  width: 320px;
  height: 279px;
  right: -90px;
  margin-top: -57px;
}

#pics1 {
  position: absolute;
  top: -50px;
  left: 30px;
  z-index: 2;
}

#pics2 {
  position: absolute;
  top: 210px;
  left: 30px;
  z-index: 2;
}

#pics3 {
  position: absolute;
  top: 50px;
  left: 270px;
  z-index: 2;
}

#pics4 {
  position: absolute;
  top: 280px;
  left: 270px;
}

#pics5 {
  position: absolute;
  top: -90px;
  left: 510px;
  z-index: 2;
}

#pics6 {
  position: absolute;
  top: 170px;
  left: 510px;
  z-index: 2;
}

#pics7 {
  position: absolute;
  top: -20px;
  left: 750px;
  z-index: 2;
}

#pics8 {
  position: absolute;
  top: 240px;
  left: 750px;
  z-index: 2;
}

#social {
  color: #fff;
  width: 1000px;
  margin: 0 auto;
    
}

#social button {
margin-left: 400px;
}

footer {
  background-color: #000;
  color: #fff;
  width: 100%;
  padding-top: 30px;
  margin-top: 50px;
}

.footer-rows {
  display: grid;
  grid-template-columns: auto auto auto;
  margin-bottom: 50px;
  margin: 0 auto;
  width: 1000px;
}

.footer-row {
  display: inline-block;
  text-align: left;
  color: #fff;
  margin: 5px;
  margin-bottom: 50px;
  line-height: 25px;     
}

.footer-row h4  {
  margin-bottom: 10px;
}

.footer-row p  {
  margin-right: 50px ;
  
}

.footer-row ul {
  list-style-type: none;
}

.footer-row a {
  color: #fff;
  text-decoration: none;
}

.copyright {
  padding-bottom: 50px;
  text-align: center;
}
 
</style>
