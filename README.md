# product-landing-page

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF_8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
  <link
      rel="stylesheet"
      href="https://use.fontawesome.com/releases/v5.8.1/css/all.css"
      integrity="sha384-50oBUHEmvpQ+1lW4y57PTFmhCaXp0ML5d60M1M7uH2+nqUivzIebhndOJK28anvf"
      crossorigin="anonymous"
    />
  </head>
  <body>
    <div id="page-wrapper">
  <header id="header">
    <div class="logo">
    <img id="header-img" src="https://cdn.freecodecamp.org/testable-projects-fcc/images/product-landing-page-logo.png"  alt="original trombones logo"/>
  </div>
  <nav id="nav-bar">
    <ul>
    <li><a class="nav-link" href="#features">Features</a></li>
    <li><a class="nav-link" href="#how_it_works">How It Works</a></li>
   <li><a class="nav-link" href="#pricing">Pricing</a></li>
   </ul>
   </nav>  
  </header>
      <div class="container"></div>
      <section id="hero">
    <h2>Handcrafted, home-made masterpieces</h2>
    <form id="form" action="https://www.freecodecamp.com/email-submit">
    <input id="email" placeholder="Enter your email address" type="email" name="email" required>
    <br><input id="submit" type="submit" value="GET STARTED" class="btn"/></br>
    </form>
    </section>

    <div class="container">
    <section id="features">
    <div class="grid">
    <div class="icon"><i class="fa fa-3x fa-fire"></i></div>
    <div class="desc">
    <h2>Premium Materials</h2>
    <p>Our trombones use the shiniest brass which is sourced locally. This will increase the longevity of your purchase.</p>
    </div>
          </div>
          <div class="grid">
            <div class="icon"><i class="fa fa-3x fa-truck"></i></div>
            <div class="desc">
    <h2>Fast Shipping</h2>
    <p>We make sure you recieve your trombone as soon as we have finished making it. We also provide free returns if you are not satisfied.</p>
    </div>
          </div>
          <div class="grid">
            <div class="icon">
              <i class="fa fa-3x fa-battery-full" aria-hidden="true"></i>
            </div>
            <div class="desc">
    <h2>Quality Assurance</h2>
    <P>For every purchase you make, we will ensure there are no damages or faults and we will check and test the pitch of your instrument.</p>
    </div>
          </div>
        </section>
        <section id="how_it_works">
    <iframe height="240" id="video" src="https://www.youtube-nocookie.com/embed/y8Yv4pnO7qc?rel=0&amp;controls=0&amp;showinfo=0" frameborder="0" allowfullscreen type="video/mp4" >
    </iframe>
    </section>
    <section id="pricing">
          <div class="product" id="tenor">
            <div class="level">Tenor Trombone</div>
            <h2>$600</h2>
            <ol>
              <li>Lorem ipsum.</li>
              <li>Lorem ipsum.</li>
              <li>Lorem ipsum dolor.</li>
              <li>Lorem ipsum.</li>
            </ol>
            <button class="btn">Select</button>
          </div>
          <div class="product" id="bass">
            <div class="level">Bass Trombone</div>
            <h2>$900</h2>
            <ol>
              <li>Lorem ipsum.</li>
              <li>Lorem ipsum.</li>
              <li>Lorem ipsum dolor.</li>
              <li>Lorem ipsum.</li>
            </ol>
            <button class="btn">Select</button>
          </div>
          <div class="product" id="valve">
            <div class="level">Valve Trombone</div>
            <h2>$1200</h2>
            <ol>
              <li>Plays similar to a Trumpet</li>
              <li>Great for Jazz Bands</li>
              <li>Lorem ipsum dolor.</li>
              <li>Lorem ipsum.</li>
            </ol>
            <button class="btn">Select</button>
          </div>
        </section>
        <footer>
          <ul>
            <li><a href="#">Privacy</a></li>
            <li><a href="#">Terms</a></li>
            <li><a href="#">Contact</a></li>
          </ul>
          <span>Copyright 2016, Original Trombones</span>
        </footer>
      </div>
    </div>
  </body>
</html>
