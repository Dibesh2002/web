
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Portfolio Website Dibesh</title>
    <link rel="stylesheet" href="./style.css" />
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.2/css/all.min.css"
    />
  </head>
  <body>
    <div class="container">
      <header class="flex">
        <div class="logo">DIBES<span>.</span></div>
        <nav>
          <ul class="flex">
            <li><a href="#about">About</a></li>
            <li><a href="#contact">Service</a></li>
            <li><a href="#project">Portfolio</a></li>
            <li><a href="#contact">Contact Me</a></li>
          </ul>
          <div id="search" class="flex">
            <i class="fa-solid fa-magnifying-glass"></i>
            <input type="text" name="" id="" placeholder="Search..." />
          </div>
        </nav>
      </header>

      <div class="main flex">
        <div class="main-one">
          <h1>Hy! I am</h1>
          <span class="auto">Dibesh Shrestha</span>
          <p>
            An enthusiastic engineering fresher, who is self starter and capable of using technical
            skills for betterment of organization.
          </p>
          <button>Hire Me</button>
        </div>
        <div class="main-two">
          <img src="PicsArt_10-15-09.15.35.jpg" alt="" />
        </div>
      </div>

      <section class="projects" id="project">
        <h1>My Awesome <br /><span>Projects</span></h1>
        <p>
          <ul>
            <li>Calculator</li>
            <li>Eye contractor</li>
            <li>Face detector</li>
        </p>
        <button class="button">Download CV</button>
        <div class="projects-div flex div-1">
          <img src="IMG_20210716_093341_Bokeh" alt="" />
          <h3>Calculator</h3>
          <p>
            Add, Subtract, Multiply and Divide can de done.
          </p>
          <button>Live Preview</button>
        </div>
        <div class="projects-div flex div-2">
          <img src="IMG_20210716_093341_Bokeh" alt="" />
          <h3>Eye contractor</h3>
          <p>
            Eyes situation can be watch.
          </p>
          <button>Live Preview</button>
        </div>
        <div class="projects-div flex div-3">
          <img src="IMG_20210716_093341_Bokeh" alt="" />
          <h3>Face Detector</h3>
          <p>
            Face can be detected it is moving here and there.
          </p>
          <button>Live Preview</button>
        </div>
      </section>
      <br /><br />

      <section class="about flex" id="about">
        <div class="about-one">
          <h1>About me</h1>
          <span>Dibesh Shrestha</span>
          <p>
           - An enthusiastic engineering fresher, who is self starter and capable of using technical
          skills for betterment of organization.
           - Degree in BE Engineering (Computer Science)        
          </p>
          <div class="btns">
            <button>Download CV</button>
            <button>Contact Me</button>
          </div>
        </div>
        <div class="about-two">
          <img src="./Images/About/1.png" alt="" />
        </div>
      </section>
      <br /><br /><br />

      <section class="contact" id="contact">
        <h1>Let Us <span>Talk!</span></h1>
        <div class="box flex">
          <div>
            <i class="fa-solid fa-user"></i>
            <input type="text" placeholder="Name.." />
          </div>
          <div>
            <i class="fa-solid fa-envelope"></i>
            <input type="email" placeholder="Email.." />
          </div>
          <textarea
            name=""
            id=""
            cols="60"
            rows="5"
            placeholder="Enter your Message here...."
          ></textarea>
          <div>
            <input type="submit" class="send" value="Send" />
          </div>
        </div>
      </section>
      <footer class="flex" id="footer">
        <div class="copy">@copywrite 2025 DIBES</div>
        <div class="social">
          <i class="fa-brands fa-instagram"></i>
          <i class="fa-brands fa-facebook"></i>
          <i class="fa-brands fa-whatsapp"></i>
          <i class="fa-solid fa-phone"></i>
        </div>
      </footer>
    </div>

    <script src="https://cdn.jsdelivr.net/npm/typed.js@2.0.12"></script>
    <script>
      var typed = new Typed(".auto", {
        strings: ["...", "Web Developer", "Android Developer","Dibesh Shrestha"],
        typeSpeed: 80,
        backSpeed: 100,
        loop: true,
      });
    </script>
  </body>
</html>
