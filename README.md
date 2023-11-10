<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Project Pot</title>
  <link rel = "stylesheet" href="style.css">
  <script src="https://kit.fontawesome.com/390b940683.js" crossorigin="anonymous"></script>  
</head>
<body>
  <div class = "banner">
    <div class ="navbar">
      <img src="potlogo1.png" width="250"  class = "logo" id = "potlogo">
      <ul>
        <li><a href = 'index.html'>Home</a></li>
        <li><a href = "Feature.html">Features</a></li>
        <li><a href = "#">About us</a></li>
      </ul>
    </div>
    <div class="content">
      <h1>Welcome to Smart Pot fam</h1>
      <p>This is the official website for our elctronic pots.<br>To purchase your pot, head over to Buy.</p>
      <div>
        <button onclick = "window.location.href = 'SignUp.html';" type="button"><span></span>Sign Up</button>
        <button onclick = "window.location.href = 'BuyPot.html';" type="button"><span></span>Buy Smart Pot</button>
      </div>
    </div>
  </div>
<br>
  <div class="small-container">
    <h1>Some of our customers</h1>
  </div>

    <div class="container">
      <div class="row">
        <div class="col">
          <img src = "vijayplant.jpg" class="pic">

          <div class="layer">
            <img src = "vijayplant.jpg">
          </div>

          <div class="info">
            <h2>Vijay</h2>
            <p>Actor, Singer</p>
            <div class="icons">
              <i class="fa-brands fa-twitter"></i>
              <i class="fa-brands fa-instagram"></i>
            </div>
          </div>
          
        </div>
        <div class="col">
        <img src="suriyaplant.jpg" class="pic">

        <div class="layer">
          <img src = "suriyaplant.jpg">
        </div>

        <div class="info">
          <h2>Suriya</h2>
          <p>Actor, Producer</p>
          <div class="icons">
            <i class="fa-brands fa-twitter"></i>
            <i class="fa-brands fa-instagram"></i>
          </div>
        </div>
        
        </div>
        <div class="col">
        <img src="shruthiplant.jpg" class="pic">

        <div class="layer">
          <img src = "shruthiplant.jpg">
        </div>

        <div class="info">
          <h2>Shruthi Hassan</h2>
          <p>Actress, Singer</p>
          <div class="icons">
            <i class="fa-brands fa-twitter"></i>
            <i class="fa-brands fa-instagram"></i>
          </div>
        </div>
        
        </div>
      </div>
    </div>
      <section id = "testimonial">
        <b><p id = "tt">Testimonial</p></b>
        <div class="title-text">
          
          <h1>Customer reviews</h1>
        </div>
        <div class="testimonial-row">
          <div class="testimonial-col">
            <div class="user">
              <img src = "rajini.jpg">
              <div class="user-info">
                <h4>Rajinikanth <i class="fa-brands fa-twitter"></i></h4>
                <small>@rajinikanth</small>
              </div>
            </div>
            <p>One of the best electronic pots I've ever used. Has saved so much of my time.</p>
          </div>
          <div class="testimonial-col">
            <div class="user">
              <img src="allu.jpg">
              <div class="user-info">
                <h4>Allu Arjun<i class="fa-brands fa-twitter"></i></h4>
                <small>@alluarjun</small>
              </div>
            </div>
          <p>Really good product. UI is super interactive and bug-free.</p>
          </div>
          <div class="testimonial-col">
            <div class="user">
              <img src="mahesh.jpg">
              <div class="user-info">
                <h4>Mahesh Babu <i class="fa-brands fa-twitter"></i></h4>
                <small>@urstrulymahesh</small>
              </div>
            </div>
            <p>The Project-pot is super useful and saves so much of my effort.</p>
          </div>
        </div>
      </section>

      <!--Footer-->
      <div class="footer">
        <div class="container1">
          <div class="row1">
            <div class="footer-col-1">
              <h3>Download Our App</h3>
              <p>Download Smart Pot App - available on Android and IOS</p>
              <div class="app-logo">
                <i class="fa-brands fa-google-play"></i>
                <i class="fa-brands fa-apple"></i>
              </div>
            </div>
            <div class="footer-col-2">
              <img src="potlogo2.png">
              <p>Eco Smart Pot - nature in our hands</p>
            </div>
            <div class="footer-col-3">
              <h3>Support Us</h3>
              <ul id="ul">
                <li>Patreon <i class="fa-brands fa-patreon"></i></li>
                <li>Git Hub <i class="fa-brands fa-github"></i></li>
                <li>Gpay <i class="fa-brands fa-google-pay"></i></li>
                
              </ul>
            </div>
            <div class="footer-col-4">
              <h3>Follow Us</h3>
              <ul id="ull">
                <li>YouTube</li>
                <li>Twitter</li>
                <li>Instagram</li>
              </ul>
            </div>
          </div>
          <hr>
          <p class="copyright">Copyright 2023 - Smart Pot</p>
        </div>
      </div>
</body>
</html>
