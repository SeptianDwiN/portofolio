<template>
  <svg id="wave" style="transform:rotate(0deg); transition: 0.3s" viewBox="0 0 1440 180" version="1.1" xmlns="http://www.w3.org/2000/svg"><defs><linearGradient id="sw-gradient-0" x1="0" x2="0" y1="1" y2="0"><stop stop-color="rgba(9.481, 120.255, 196.124, 1)" offset="0%"></stop><stop stop-color="rgba(5.99, 171.155, 232.552, 1)" offset="100%"></stop></linearGradient></defs><path style="transform:translate(0, 0px); opacity:1" fill="url(#sw-gradient-0)" d="M0,18L18.5,15C36.9,12,74,6,111,3C147.7,0,185,0,222,15C258.5,30,295,60,332,87C369.2,114,406,138,443,135C480,132,517,102,554,78C590.8,54,628,36,665,48C701.5,60,738,102,775,126C812.3,150,849,156,886,156C923.1,156,960,150,997,123C1033.8,96,1071,48,1108,33C1144.6,18,1182,36,1218,60C1255.4,84,1292,114,1329,105C1366.2,96,1403,48,1440,42C1476.9,36,1514,72,1551,96C1587.7,120,1625,132,1662,114C1698.5,96,1735,48,1772,30C1809.2,12,1846,24,1883,42C1920,60,1957,84,1994,102C2030.8,120,2068,132,2105,132C2141.5,132,2178,120,2215,114C2252.3,108,2289,108,2326,102C2363.1,96,2400,84,2437,78C2473.8,72,2511,72,2548,81C2584.6,90,2622,108,2640,117L2658.5,126L2658.5,180L2640,180C2621.5,180,2585,180,2548,180C2510.8,180,2474,180,2437,180C2400,180,2363,180,2326,180C2289.2,180,2252,180,2215,180C2178.5,180,2142,180,2105,180C2067.7,180,2031,180,1994,180C1956.9,180,1920,180,1883,180C1846.2,180,1809,180,1772,180C1735.4,180,1698,180,1662,180C1624.6,180,1588,180,1551,180C1513.8,180,1477,180,1440,180C1403.1,180,1366,180,1329,180C1292.3,180,1255,180,1218,180C1181.5,180,1145,180,1108,180C1070.8,180,1034,180,997,180C960,180,923,180,886,180C849.2,180,812,180,775,180C738.5,180,702,180,665,180C627.7,180,591,180,554,180C516.9,180,480,180,443,180C406.2,180,369,180,332,180C295.4,180,258,180,222,180C184.6,180,148,180,111,180C73.8,180,37,180,18,180L0,180Z"></path></svg>
    <footer class="footer">
     <div class="container">
       <div class="row">
         <div class="footer-col">
           <h4>About Myportofolio</h4>
           <ul>
             <li><a href="#">About us</a></li>
             <li><a href="#">Contact us</a></li>
             <li><a href="#">Blog</a></li>
             <li><a href="#">Our service</a></li>
             <li><a href="#">Carrers</a></li>
           </ul>
         </div>
         <div class="footer-col">
           <h4>Product</h4>
           <ul>
             <li><a href="#">Flights</a></li>
             <li><a href="#">Trains</a></li>
             <li><a href="#">Hotels</a></li>
             <li><a href="#">Eats</a></li>
             <li><a href="#">Paylater</a></li>
             <li><a href="#">Xperience</a></li>
           </ul>
         </div>
         <div class="footer-col">
           <h4>Guide and Help</h4>
           <ul>
            <li><a href="#">Care</a></li>
              <li><a href="#">Privacy Policy</a></li>
              <li><a href="#">Terms and Condition</a></li>
              <li><a href="#">Mitra</a></li>
            </ul>
          </div>
          <div class="footer-col">
            <h4>Contact Me</h4>
            <div class="social-media">
              <a href="#"><i class=""></i></a>
              <a href="#"><i class="fab fa-instagram"></i></a>
              <a href="#"><i class="fab fa-twitter"></i></a>
              <a href="#"><i class="fab fa-youtube"></i></a>
            </div>
          </div>
        </div>
      </div>
    </footer>
    <div class="fixed-footer">
      <div class="container">Copyright &copy; 2023 </div>
    </div>
</template>

<style>
body {
  line-height: 1.5;
  font-family: "Poppins", sans-serif;
}
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.container {
  max-width: 1170px;
  margin: auto;
}
.row {
  display: flex;
  flex-wrap: wrap;
}
ul {
  list-style: none;
}
.footer {
    background: linear-gradient(
        120deg,
        #0a7fec 20.69%,
        #078dc2 50.19%,
        #0d9df1 79.69%
    );
  padding: 70px 0;
}
.footer-col {
  width: 25%;
  padding: 0 15px;
}
.footer-col h4 {
  font-size: 18px;
  color: rgba(255, 255, 255, 1);
  text-transform: capitalize;
  margin-bottom: 35px;
  font-weight: 500;
  position: relative;
}
.footer-col h4::before {
  content: "";
  position: absolute;
  left: 0;
  bottom: -10px;
  background-color: rgba(0, 3, 255, 0.8);
  height: 2px;
  box-sizing: border-box;
  width: 50px;
}
.footer-col ul li:not(:last-child) {
  margin-bottom: 10px;
}
.footer-col ul li a {
  font-size: 16px;
  text-transform: capitalize;
  color: rgba(255, 255, 255, 1);
  text-decoration: none;
  font-weight: 300;
  color: #bbbbbb;
  display: block;
  transition: all 0.3s ease;
}
.footer-col ul li a:hover {
  color: rgb(0, 0, 0);
  padding-left: 8px;
}
.footer-col .social-media a {
  display: inline-block;
  height: 40px;
  width: 40px;
  background-color: rgba(255, 255, 255, 0.2);
  margin: 0 10px 10px 0;
  text-align: center;
  line-height: 40px;
  border-radius: 50%;
  color: rgba(243, 22, 22, 0.5);
  margin: 0 10px 10px 0;
  transition: all 0.5s ease;
}
.fixed-footer {
    width: 100%;
    position: relative;
    background: #0f79f3;
    margin: 0 10px 10px 0;
    padding: 10px 0;
    color: rgba(255, 255, 255, 1);
    text-align: center;
  }
  
  
</style>