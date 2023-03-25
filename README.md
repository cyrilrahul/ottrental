<!DOCTYPE html>
<html>
  <head>
    <title>OTT RENTAL.CSS Template</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Raleway">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <style>
    body,h1,h2,h3,h4,h5,h6 {font-family: "Raleway", sans-serif}

    body, html {
      height: 100%;
      line-height: 1.8;
    }

    /* Full height image header */
    .bgimg-1 {
      background-position: center;
      background-size: cover;
      background-image: url("https://tinuiti.com/wp-content/uploads/2020/01/ott.jpg");
      min-height: 100%;
    }

    .w3-bar .w3-button {
      padding: 16px;
    }
    </style>
  </head>
<body>

<!-- Navbar (sit on top) -->
<div class="w3-top">
  <div class="w3-bar w3-white w3-card" id="myNavbar">
    <a href="#home" class="w3-bar-item w3-button w3-wide">OTT RENTAL</a>
       <marquee bgcolour="#03FAF8" loop="-1" scrollamount="2" width="100%"  >Say no to piracy, when you can watch movie within cost of a lays 😃😃😃😃😃😃</marquee>
    <!-- Right-sided navbar links -->
    <div class="w3-right w3-hide-small">
      <a href="#about" class="w3-bar-item w3-button"><i class="fa fa-bars "></i> ABOUT</a>
      <a href="#subscriptions" class="w3-bar-item w3-button"><i class="fa fa-bars"></i> TOP SUBSCRIPTIONS</a>
      <a href="#work" class="w3-bar-item w3-button"><i class="fa fa-th"></i> SUBSCRIPTIONS AVAILABLE</a>
      <a href="#pricing" class="w3-bar-item w3-button"><i class="fa fa-usd"></i> PRICING</a>
      <a href="#contact" class="w3-bar-item w3-button"><i class="fa fa-envelope"></i> CONTACT</a>
    </div>
    <!-- Hide right-floated links on small screens and replace them with a menu icon -->

    <a href="javascript:void(0)" class="w3-bar-item w3-button w3-right w3-hide-large w3-hide-medium" onclick="w3_open()">
      <i class="fa fa-bars"></i>
    </a>
  </div>
</div>

<!-- Sidebar on small screens when clicking the menu icon -->
<nav class="w3-sidebar w3-bar-block w3-black w3-card w3-animate-left w3-hide-medium w3-hide-large" style="display:none" id="mySidebar">
  <a href="javascript:void(0)" onclick="w3_close()" class="w3-bar-item w3-button w3-large w3-padding-16">Close ×</a>
  <a href="#about" onclick="w3_close()" class="w3-bar-item w3-button">ABOUT</a>
  <a href="#team" onclick="w3_close()" class="w3-bar-item w3-button">TEAM</a>
  <a href="#work" onclick="w3_close()" class="w3-bar-item w3-button">WORK</a>
  <a href="#pricing" onclick="w3_close()" class="w3-bar-item w3-button">PRICING</a>
  <a href="#contact" onclick="w3_close()" class="w3-bar-item w3-button">CONTACT</a>
</nav>

<!-- Header with full-height image -->
<header class="bgimg-1 w3-display-container w3-grayscale-min" id="home">
  <div class="w3-display-bottomleft w3-text-white" style="padding:48px">
    <p><a href="#about" class="w3-button w3-white w3-padding-large w3-large w3-margin-top w3-opacity w3-hover-opacity-off">Learn more and start today</a></p>
  </div> 
<div class="w3-display-bottomleft w3-text-grey w3-large" style="padding:24px 48px">
      <i class="fa fa-whatsapp w3-hover-opacity"></i><a href="https://wa.me/message/64BML3BJ4LIEF1">GO</a>
      
  </div>
</header>

<!-- About Company -->
<div class="w3-container" style="padding:128px 16px" id="about">
  <h3 class="w3-center w3">ABOUT THE COMPANY</h3>
    <p class="w3-center w3-large">We lend and hire subscriptions of different platforms according to the selected time period of us.</p>
    <h3 class="w3-center">KEY FEATURES PROVIDED BY THE COMPANY</h3>
  <div class="w3-row-padding w3-center" style="margin-top:64px">
    <div class="w3-quarter">
      <i class="fa fa-desktop w3-margin-bottom w3-jumbo w3-center"></i>
      <p class="w3-large">HIRING SUBSCRIPTIONS</p>
      <p>We Hire subscriptions of various platforms. </p>
    </div>
    <div class="w3-quarter">
      <i class="fa fa-phone w3-margin-bottom w3-jumbo"></i>
      <p class="w3-large">BUYING SUBSCRIPTIONS</p>
      <p>We also Buy various Subscriptions for certain amount.</p>
    </div>
    <div class="w3-quarter">
      <i class="fa fa-diamond w3-margin-bottom w3-jumbo"></i>
      <p class="w3-large">PRICING AT LOW COSTS</p>
      <p>We lend subscriptions at low cost as per selected time limit.</p>
    </div>
    <div class="w3-quarter">
      <i class="fa fa-cog w3-margin-bottom w3-jumbo"></i>
      <p class="w3-large">Support</p>
      <p>We are available 24/7 foe resolving the troubleshoot problems.</p>
    </div>
  </div>
</div>

<!-- Promo Section - "We know design" -->
<div class="w3-container w3-light-grey" style="padding:128px 16px">
  <div class="w3-row-padding"   >
    <div class="w3-col m6 w3-margin-middle w3-large" >
      <h3>We know your needs.</h3>
      <p>We want to make your life simple, pick plans which fits your needs and buy it when you are free so that you can enjoy your day by watching Movies or Sports.By this you can save money reagrding subscriptions and you can make use of whatever the plan you select from us wisely.</p>
    </div>
    <div class="w3-col m6">
      <img class="w3-image w3-round-large" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQmqzqW6L-N-QLqCR8EXvgQDSJuZZQy9J_2nA&usqp=CAU" alt="OTT" width="100%">
    </div>
  </div>
</div>

<!--  Top Subscriptions -->
<div class="w3-container" style="padding:128px 16px" id="subscriptions">
  <h3 class="w3-center w3-jumbo"> TOP SUBSCRIPTIONS </h3>
  <div class="w3-row-padding w3-whitescale" style="margin-top:80px">
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-card">
        <img src="https://images.unsplash.com/photo-1643208589889-0735ad7218f0?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MTh8fG5ldGZsaXh8ZW58MHx8MHx8&w=1000&q=80" alt="Netflix" style="width:100%">
        <div class="w3-container">
          <h3>Netflix</h3>
          <p class="w3-opacity">Web Series and Movies.</p>
          <p>Entertainment Platform
            Movies, Series etc </p>
          <p><button class="w3-button w3-light-grey w3-block"><i class="fa fa-envelope">
<a href="https://wa.me/message/64BML3BJ4LIEF1">₹ Premium</a></p>
              </i></button></p>
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-card">
        <img src="https://images.unsplash.com/photo-1601944177325-f8867652837f?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1477&q=80" alt="Disney+ Hotstar" style="width:100%">
        <div class="w3-container">
          <h3>Disney+ Hotstar </h3>
          <p class="w3-opacity">Sports Live - Highlights and Movies.</p>
          <p>Entertainment & Sports Platform</p>
          <p><button class="w3-button w3-light-grey w3-block"><i class="fa fa-envelope">
<a href="https://wa.me/message/64BML3BJ4LIEF1">₹ Premium</a></p>
              </i></button></p>
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-card">
        <img src="https://images.unsplash.com/photo-1643208589888-23447d7e747f?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1469&q=80" alt="Amazon Prime" style="width:100%" >
        <div class="w3-container">
          <h3>Amazon Prime</h3>
          <p class="w3-opacity">Movies and E Commerce Deliveries.</p>
          <p>E Commerce</p>
          <p><button class="w3-button w3-light-grey w3-block"><i class="fa fa-envelope">
<a href="https://wa.me/message/64BML3BJ4LIEF1">₹ Premium</a></p>
              </i></button></p>
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-card">
        <img src="https://images.unsplash.com/photo-1541877944-ac82a091518a?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1470&q=80" alt="Youtube Premium" style="width:100%">
        <div class="w3-container">
          <h3>Youtube Premium</h3>
          <p class="w3-opacity">Additional plans to Youtube</p>
          <p>Watch Advertisement free youtube.</p>
          <p><button class="w3-button w3-light-grey w3-block"><i class="fa fa-envelope">
<a href="https://wa.me/message/64BML3BJ4LIEF1">₹ Premium</a></p>
              </i></button></p>
        </div>
      </div>
  </div>
</div>
<!-- Promo Section "Statistics" -->
<div class="w3-container w3-row w3-center w3-dark-grey w3-padding-64">
  <div class="w3-quarter">
    <span class="w3-xxlarge">21+</span>
    <br>Subscriptions Available
  </div>
  <div class="w3-quarter">
    <span class="w3-xxlarge">5</span>
    <br>Types of Packages 
  </div>
  <div class="w3-quarter">
    <span class="w3-xxlarge">8+</span>
    <br>Active Crew
  </div>
  <div class="w3-quarter">
    <span class="w3-xxlarge">150+</span>
    <br>Active Customers
  </div>
    </div>

<!--SUBSCRIPTIONS AVAILABLE -->
<div class="w3-container" style="padding:128px 16px" id="work">
   <h3 class="w3-center w3-jumbo"> SUBSCRIPTIONS  AVAILABLE </h3>
    
<div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-card">
        <img src="https://images.unsplash.com/photo-1643208589889-0735ad7218f0?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MTh8fG5ldGZsaXh8ZW58MHx8MHx8&w=1000&q=80" alt="Netflix" style="width:100%">
        <div class="w3-container">
          <h3>Netflix</h3>
          <p class="w3-opacity">Web Series and Movies.</p>
          <p>Entertainment Platform
            Movies, Series etc </p>
          <p><button class="w3-button w3-light-grey w3-block"><i class="fa fa-envelope">
<a href="https://wa.me/message/64BML3BJ4LIEF1">₹ Premium</a></p>
              </i></button></p>
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-card">
        <img src="https://images.unsplash.com/photo-1601944177325-f8867652837f?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1477&q=80" alt="Disney+ Hotstar" style="width:100%">
        <div class="w3-container">
          <h3>Disney+ Hotstar </h3>
          <p class="w3-opacity">Sports Live - Highlights and Movies.</p>
          <p>Entertainment & Sports Platform</p>
          <p><button class="w3-button w3-light-grey w3-block"><i class="fa fa-envelope">
<a href="https://wa.me/message/64BML3BJ4LIEF1">₹ Premium</a></p>
              </i></button></p>
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-card">
        <img src="https://images.unsplash.com/photo-1643208589888-23447d7e747f?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1469&q=80" alt="Amazon Prime" style="width:100%" >
        <div class="w3-container">
          <h3>Amazon Prime</h3>
          <p class="w3-opacity">Movies and E Commerce Deliveries.</p>
          <p>E Commerce</p>
          <p><button class="w3-button w3-light-grey w3-block"><i class="fa fa-envelope">
<a href="https://wa.me/message/64BML3BJ4LIEF1">₹ Premium</a></p>
              </i></button></p>
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-card">
        <img src="https://images.unsplash.com/photo-1541877944-ac82a091518a?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1470&q=80" alt="Youtube Premium" style="width:100%">
        <div class="w3-container">
          <h3>Youtube Premium</h3>
          <p class="w3-opacity">Additional plans to Youtube</p>
          <p>Watch Advertisement free youtube.</p>
          <p><button class="w3-button w3-light-grey w3-block"><i class="fa fa-envelope">
<a href="https://wa.me/message/64BML3BJ4LIEF1">₹ Premium</a></p>
              </i></button></p>
        </div>
      </div>
  </div>
    <div class="w3-row-padding w3-whitescale" style="margin-top:80px">
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-card">
        <img src="https://bingeddata.s3.amazonaws.com/uploads/2021/12/Aha-Videos-OTT-Line-Up-Looks-Promising.jpg" alt="AHA" style="width:100%">
        <div class="w3-container">
          <h3>AHA</h3>
          <p class="w3-opacity">Movies.</p>
          <p>Entertainment Platform
            Movies </p>
          <p><button class="w3-button w3-light-grey w3-block"><i class="fa fa-envelope">
<a href="https://wa.me/message/64BML3BJ4LIEF1">₹ Premium</a></p>
              </i></button></p>
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-card">
        <img src="https://cdn.wallpapersafari.com/7/6/8qH14d.jpg" alt="Spotify" style="width:100%">
        <div class="w3-container">
          <h3>Spotify </h3>
          <p class="w3-opacity">MUSIC.</p>
          <p>Unlimited Music</p>
          <p><button class="w3-button w3-light-grey w3-block"><i class="fa fa-envelope">
<a href="https://wa.me/message/64BML3BJ4LIEF1">₹ Premium</a></p>
              </i></button></p>
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-card">
        <img src="https://etimg.etb2bimg.com/photo/76905080.cms" alt="Sony Liv" style="width:100%" >
        <div class="w3-container">
          <h3>SONY liv</h3>
          <p class="w3-opacity">Movies and Live Sports.</p>
          <p>Live sports and Movies</p>
          <p><button class="w3-button w3-light-grey w3-block"><i class="fa fa-envelope">
<a href="https://wa.me/message/64BML3BJ4LIEF1">₹ Premium</a></p>
              </i></button></p>
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-card">
        <img src="https://i0.wp.com/techchahiye.com/wp-content/uploads/2019/09/airtel-tv-is-now-airtel-xstream.png?fit=1200%2C900&ssl=1"  alt="Airtel xstream"  style="width: 100%">
        <div class="w3-container">
          <h3>Airtel Xstream</h3>
          <p class="w3-opacity">Live Channels</p>
          <p>Watch Channels and Movies.</p>
          <p><button class="w3-button w3-light-grey w3-block"><i class="fa fa-envelope">
<a href="https://wa.me/message/64BML3BJ4LIEF1">₹ Premium</a></p>
              </i></button></p>
        </div>
      </div>
  </div>
<hr color="black">
    <div class="w3-row-padding w3-whitescale" style="margin-top:80px">
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-card">
        <img src="https://s3images.zee5.com/wp-content/uploads/2022/01/ZEE5logo2022010511282120220105122506.jpg" alt="ZEE5" style="width:100%">
        <div class="w3-container">
          <h3>ZEE5</h3>
          <p class="w3-opacity">Movies.</p>
          <p>Entertainment Platform
            Movies </p>
          <p><button class="w3-button w3-light-grey w3-block"><i class="fa fa-envelope">
<a href="https://wa.me/message/64BML3BJ4LIEF1">₹ Premium</a></p>
              </i></button></p>
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-card">
        <img src="https://upload.wikimedia.org/wikipedia/en/8/86/Altbalaji_Logo.svg" alt="ALT Balaji" style="width:75.5%" align="right">
        <div class="w3-container">
          <h3>ALT Balaji </h3>
          <p class="w3-opacity">SHOWS.</p>
          <p>Popular Movies and Shows</p>
          <p><button class="w3-button w3-light-grey w3-block"><i class="fa fa-envelope">
<a href="https://wa.me/message/64BML3BJ4LIEF1">₹ Premium</a></p>
              </i></button></p>
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-card">
        <img src="https://www.apkmirror.com/wp-content/uploads/2020/08/06/5f4388574b044.png" alt="BIG FLIX" style="width:75%" align="right" >
        <div class="w3-container">
          <h3>BIG FLIX</h3>
          <p class="w3-opacity">Online Movies.</p>
          <p>Movies and Shows</p>
          <p><button class="w3-button w3-light-grey w3-block"><i class="fa fa-envelope">
<a href="https://wa.me/message/64BML3BJ4LIEF1">₹ Premium</a></p>
              </i></button></p>
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-card">
        <img src="https://play-lh.googleusercontent.com/jFi2iC10wQJ42gu-DO2CMeIcN3qcmNQHtY5EBT_wtp4jCIozS4n3Q9pA7ZloDUGHHw"  style="width: 75%" align="right">
        <div class="w3-container">
          <h3>SUN NXT</h3>
          <p class="w3-opacity">Live Channels</p>
          <p>Watch Channels and Movies.</p>
          <p><button class="w3-button w3-light-grey w3-block"><i class="fa fa-envelope">
<a href="https://wa.me/message/64BML3BJ4LIEF1">₹ Premium</a></p>
              </i></button></p>
        </div>
      </div>
  </div>
</div>

<!-- Modal for full size images on click-->
<div id="modal01" class="w3-modal w3-black" onclick="this.style.display='none'">
  <span class="w3-button w3-xxlarge w3-black w3-padding-large w3-display-topright" title="Close Modal Image">×</span>
  <div class="w3-modal-content w3-animate-zoom w3-center w3-transparent w3-padding-64">
    <img id="img01" class="w3-image">
    <p id="caption" class="w3-opacity w3-large"></p>
      <hr color="black">
  </div>
</div>

<!-- Skills Section -->
<div class="w3-container w3-light-grey w3-padding-64">
  <div class="w3-row-padding">
    <div class="w3-col m6">
      <h3>Customer satisfaction.</h3>
      <p>Analysis of Ratings given by customers who hired subscriptions and who sold subscriptions.</p>
    </div>
    <div class="w3-col m6">
      <p class="w3-wide"><i class="fa fa-camera w3-margin-right"></i>Overall Customer satisfaction</p>
      <div class="w3-grey">
        <div class="w3-container w3-dark-grey w3-center" style="width:93%">93%</div>
      </div>
      <p class="w3-wide"><i class="fa fa-desktop w3-margin-right"></i>Cost Efficiency</p>
      <div class="w3-grey">
        <div class="w3-container w3-dark-grey w3-center" style="width:87%">87%</div>
      </div>
      <p class="w3-wide"><i class="fa fa-photo w3-margin-right"></i>Buyers and sellers satisfaction</p>
      <div class="w3-grey">
        <div class="w3-container w3-dark-grey w3-center" style="width:91%">91%</div>
      </div>
    </div>
  </div>
</div>

<!-- Pricing Section -->
<div class="w3-container w3-center w3-dark-grey" style="padding:128px 16px" id="pricing">
  <h3>PLANS</h3>
  <p class="w3-large">Choose a Timing plan that fits your needs.</p>
  <div class="w3-row-padding" style="margin-top:64px">
    <div class="w3-third w3-section">
      <ul class="w3-ul w3-white w3-hover-shadow">
        <li class="w3-black w3-xlarge w3-padding-32">Basic</li>
        <li class="w3-padding-16"><b>6</b> Hours</li>
        <li class="w3-padding-16"><b>6</b> Packages</li>
        <li class="w3-padding-16"><b>Netflix, Aha, Amazon</b>Zomato Pro, Byjus, Sony Liv </li>
        <li class="w3-padding-16">
          <h2 class="w3-wide">₹ 30</h2>
          <span class="w3-opacity">per Hour</span>
        </li>
        <li class="w3-light-grey w3-padding-24">
            <p><button class="w3-button w3-light-grey w3-block"><i class="w3-light-grey w3-padding-24">
<a href="https://wa.me/message/64BML3BJ4LIEF1">₹ Purchase</a></p>
              </i></button></p>
</script>
        </li>
      </ul>
    </div>
    <div class="w3-third">
      <ul class="w3-ul w3-white w3-hover-shadow">
        <li class="w3-red w3-xlarge w3-padding-48">Premium</li>
        <li class="w3-padding-24"><b>24</b> Hours</li>
        <li class="w3-padding-24"><b>6</b> Packages</li>
        <li class="w3-padding-24"><b>Netflix, Aha, Amazon</b>Zomato Pro, Byjus, Sony Liv </li>
        <li class="w3-padding-24">
          <h2 class="w3-wide">₹ 150</h2>
          <span class="w3-opacity">For 12 Hours</span>
        </li>
        <li class="w3-light-grey w3-padding-24">    
              <p><button class="w3-button w3-light-grey w3-block"><i class="w3-light-grey w3-padding-24">
<a href="https://wa.me/message/64BML3BJ4LIEF1">₹ Purchase</a></p>
              </i></button></p>
</script>
        </li>
      </ul>
    </div>
    <div class="w3-third w3-section">
      <ul class="w3-ul w3-white w3-hover-shadow">
        <li class="w3-blue w3-xlarge w3-padding-32">Pro</li>
        <li class="w3-padding-16"><b>12</b> Hours</li>
        <li class="w3-padding-16"><b>6</b> Packages</li>
        <li class="w3-padding-16"><b>Netflix, Aha, Amazon</b>Zomato Pro, Byjus, Sony Liv </li>
          
        <li class="w3-padding-16">
          <h2 class="w3-wide">₹ 100</h2>
          <span class="w3-opacity">For 12 Hours</span>
        </li>
        <p><button class="w3-button w3-light-grey w3-block"><i class="w3-light-grey w3-padding-24">
<a href="https://wa.me/message/64BML3BJ4LIEF1">₹ Purchase</a></p>
              </i></button></p>

<script>
function myFunction() {
  location.replace("https://www.w3schools.com")1
}
</script>
      </ul>
    </div>
  </div>
</div>

<!-- Contact Section -->
<div class="w3-container w3-light-grey" style="padding:128px 16px" id="contact">
  <h3 class="w3-center">CONTACT</h3>
  <p class="w3-center w3-large">Lets get in touch. Send us a message:</p>
  <div style="margin-top:48px">
    <p><i class="fa fa-map-marker fa-fw w3-xxlarge w3-margin-right"></i> Hyderabad, Telangana, India</p>
    <p><i class="fa fa-phone fa-fw w3-xxlarge w3-margin-right"></i> Phone: +91 7670962307</p>
    <p><i class="fa fa-envelope fa-fw w3-xxlarge w3-margin-right"> </i> Email: ottrental.com@gmail.com</p>
    <br>
    <form action="/action_page.php" target="_blank">
      <p><input class="w3-input w3-border" type="text" placeholder="Name" required name="Name"></p>
      <p><input class="w3-input w3-border" type="text" placeholder="Email" required name="Email"></p>
      <p><input class="w3-input w3-border" type="text" placeholder="Subject" required name="Subject"></p>
      <p><input class="w3-input w3-border" type="text" placeholder="Message" required name="Message"></p>
      <p>
        <button class="w3-button w3-black" type="submit">
          <i class="fa fa-paper-plane"></i> SEND MESSAGE
        </button>
      </p>
    </form>
    <!-- Image of location/map -->
    <img src="https://www.w3schools.com/w3images/map.jpg" class="w3-image w3-greyscale" style="width:100%;margin-top:48px">
  </div>
</div>

<!-- Footer. This section contains an ad for w3Schools Spaces. You can leave it to support us. -->
<footer class="w3-center w3-black w3-padding-64">
  <a href="#home" class="w3-button w3-light-grey"><i class="fa fa-arrow-up w3-margin-right"></i>To the top</a>
  <div class="w3-xlarge w3-section">
    <i class="fa fa-facebook-official w3-hover-opacity"></i>
    <i class="fa fa-instagram w3-hover-opacity"></i>
    <i class="fa fa-snapchat w3-hover-opacity"></i>
    <i class="fa fa-pinterest-p w3-hover-opacity"></i>
    <i class="fa fa-twitter w3-hover-opacity"></i>
    <i class="fa fa-linkedin w3-hover-opacity"></i>
  </div>
<div class="copyright">
        <p>©2022. ottrental.com</p>
    </div>
</footer>
 
<script>
// Modal Image Gallery
function onClick(element) {
  document.getElementById("img01").src = element.src;
  document.getElementById("modal01").style.display = "block";
  var captionText = document.getElementById("caption");
  captionText.innerHTML = element.alt;
    
}


// Toggle between showing and hiding the sidebar when clicking the menu icon
var mySidebar = document.getElementById("mySidebar");

function w3_open() {
  if (mySidebar.style.display === 'block') {
    mySidebar.style.display = 'none';
  } else {
    mySidebar.style.display = 'block';
  }
}

// Close the sidebar with the close button
function w3_close() {
    mySidebar.style.display = "none";
}
    
</script>

</body>
</html>
