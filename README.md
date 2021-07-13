<!DOCTYPE html>
<html lang="en">
<head>
    <!-- Global site tag (gtag.js) - Google Analytics -->
    <script async src="https://www.googletagmanager.com/gtag/js?id=UA-177242401-1"></script>
    <script>
      window.dataLayer = window.dataLayer || [];
      function gtag(){dataLayer.push(arguments);}
      gtag('js', new Date());

      gtag('config', 'UA-177242401-1');
    </script>

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Artiom Shlyusberg | Web Developer</title>
    <meta name="description" content="A Front End Web Developer passionate about creating web sites and web apps." />
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Mukta:wght@200&display=swap">
    <link rel="stylesheet" href="fonts/LineIcons.css">
    <link rel="stylesheet" href="css/style.css">
</head>

<body>
  <!-- Mobile menu button -->
  <div id="home" class="visuallyHidden"></div>
  <div class="menuButton" id="menuButton" tabindex=0>
    <div class="linesContainer">
      <span></span>
    </div>
  </div>

  <!-- Side menu -->
  <aside class="sideMenu sideMenuShow" id="sideMenu"> 
    <img class="logo" src="imgs/logo-w.png" alt="Company Logo">
    <nav>
      <ul class="navBar">
        <li class="homeNav">
          <a href="#home" class="navItem">
            <i class="lni lni-home"></i>
            <span class="navItemName">HOME</span>
          </a>
        </li>
        <li class="aboutNav">
          <a href="#about" class="navItem">
            <i class="lni lni-user"></i>
            <span class="navItemName">ABOUT</span>
          </a>
        </li>
        <li class="skillsNav">
          <a href="#skills" class="navItem">
            <i class="lni lni-code"></i>
            <span class="navItemName">SKILLS</span>
          </a>
        </li>
        <li class="worksNav">
          <a href="#works" class="navItem">
            <i class="lni lni-briefcase"></i>
            <span class="navItemName">WORKS</span>
          </a>
        </li>
        <li class="contactNav">
          <a href="#contact" class="navItem">
            <i class="lni lni-phone"></i>
            <span class="navItemName">CONTACT</span>
          </a>
        </li>
      </ul>
    </nav>

    <div class="scrollDown" id="scrollDown">
      <i class="lni lni-arrow-down"></i>
      <span class="navItemName scrollDownText">Scroll Down</span>
    </div>
  </aside>

  <!--Beginning of the wrapper -->
  <div class="outerWrapper"> 
    <div class="innerWrapper">
      <!-- Header -->
      <header>
        <div class="heroImageContainer">
          <img src="imgs/me.jpg" alt="A picture of Artiom.">
        </div>
        <div class="heroDescription">
          <p class="greeting">HELLO THERE! MY NAME IS</p>
          <h1><span>ARTIOM</span> SHLYUSBERG</h1>
          <p class="smallBio">I'm an <span>Intermediate Web Developer</span> passionate about creating web sites and web apps.</p>
          <div class="socialsResume">
            <a class="resumeLink" href="" alt="Artiom Shlyusberg's resumé" target="_blank" rel="noopener noreferrer">Resumé</a>
            <ul class="socialsList">
              <li>
                <a href="https://www.facebook.com/arte50409" target="_blank" rel="noopener noreferrer"><i class="lni lni-facebook-filled" aria-label="Link to Artiom's facebook page."></i></a>
              </li>
              <li>
                <a href="https://github.com/arte504" target="_blank" rel="noopener noreferrer"><i class="lni lni-github-original" aria-label="Go to my GitHub page."></i></a>
              </li>
              <li>
                <a href="https://instagram.com/arte504" target="_blank" rel="noopener noreferrer"><i class="lni lni-instagram-filled" aria-label="Link to Alex's Twitter profile."></i></a>
              </li>
            </ul>
          </div>
        </div>
      </header>
      <!-- Beginning of Main -->
      <main>
        <!-- About Section -->
        <section class="aboutSection" id="about">
          <div class="sectionHead">
            <span>HERE SOME INFO</span>
            <h2>ABOUT ME</h2>
          </div>
          
          <article class="aboutContainer sectionContainer">
            <p>I'm a web developer with a background in computer systems. 
            Recently, I graduated from the <span>immersive online program Yandex Practicum100</span>. 
            I'm like to use code to solve problems, and I'm excited to work with other people to solve thier problems or other programmers to learn something new!</p>
          </article>
        </section>

        <!-- Skills Section -->
        <section class="skillsSection" id="skills">
          <div class="sectionHead">
            <span>HERE IS MY</span>
            <h2>SKILLS</h2>
          </div>
        
          <div class="skillsContainer sectionContainer">
            <ul class="skillsGrid">
              <li>
                <div class="itemContainer">
                  <img src="imgs/skills/html.svg">
                  <p>HTML</p>
                </div>
              </li>
              <li>
                <div class="itemContainer">
                  <img src="imgs/skills/css.svg">
                  <p>CSS</p>
                </div>
              </li>
              <li>
                <div class="itemContainer">
                  <img src="imgs/skills/javascript.svg">
                  <p>JavaScript</p>
                </div>
              </li>
              <li>
                <div class="itemContainer">
                  <img src="imgs/skills/react.svg">
                  <p>React</p>
                </div>
              </li>
              <li>
                <div class="itemContainer">
                  <img src="imgs/skills/jquery.svg">
                  <p>JQuery</p>
                </div>
              </li>
              <li>
                <div class="itemContainer">
                  <img src="imgs/skills/vscode.svg">
                  <p>VS Code</p>
                </div>
              </li>
              <li>
                <div class="itemContainer">
                  <img src="imgs/skills/git.svg">
                  <p>Git</p>
                </div>
              </li>
              <li>
                <div class="itemContainer">
                  <img src="imgs/skills/microsoftWindows.svg">
                  <p>Windows</p>
                </div>
              </li>
              <li>
                <div class="itemContainer">
                  <img src="imgs/skills/microsoft.svg">
                  <p>Office</p>
                </div>
              </li>
              <li>
                <div class="itemContainer">
                  <img src="imgs/skills/c.svg">
                  <p>C</p>
                </div>
              </li>
              <li>
                <div class="itemContainer">
                  <img src="imgs/skills/cpp.svg">
                  <p>C++</p>
                </div>
              </li>
              <li>
                <div class="itemContainer">
                  <img src="imgs/skills/py.svg">
                  <p>Python</p>
                </div>
              </li>
              </li>
            </ul>
          </div>
        </section>

        <!-- Works Section -->
        <section class="worksSection" id="works">
          <div class="sectionHead">
            <span>TAKE A LOOK AT MY</span>
            <h2>PROJECTS</h2>
          </div>

        <!-- Contact Section -->
        <section class="contactSection" id="contact">
          <div class="sectionHead">
            <span>IF YOU WANT, JUST</span>
            <h2>CONTACT ME</h2>
          </div>

          <div class="contactContainer sectionContainer">
            <h3>Get in Touch</h3>
            <div class="contactTypes">
              <div class="flexContainer">
                <div class="typeBox">
                  <i class="lni lni-envelope"></i>
                  <a href="mailto:arte504@gmail.com">arte504@gmail.com</a>
                  <p>Email Me</p>
                </div>
              </div>
              <div class="flexContainer">
                <div class="typeBox">
                  <i class="lni lni-calendar"></i>
                  <a href="https://calendly.com/arte504/30min" target="_blank" rel="noopener noreferrer">Calendly</a>
                  <p>Schedule a Meeting</p>
                </div>
              </div>
            </div>
            <div class="contactFormContainer">
              <h3>Contact Form</h3>

              <form id="contactForm" action="https://formspree.io/f/myyldzve" method="POST">
                  <label for="nameInput" class="srOnly"></label>
                  <input type="text" id="nameInput" name="nameInput" class="nameInput" required placeholder="Your Name*"/>
                  <label for="emailInput" class="srOnly"></label>
                  <input type="email" id="emailInput" name="emailInput" class="emailInput" required placeholder="Your Email*" />
                  <label for="subjectInput" class="srOnly"></label>
                  <input type="text" id="subjectInput" name="subjectInput" class="subjectInput" required placeholder="Subject*"/>
                  <label for="messageInput" class="srOnly"></label>
                  <textarea class="messageInput" name="messageInput" id="messageInput" required placeholder="Your Message*"></textarea>
              </form>

              <button type="submit" class="formSend" target="_blank" form="contactForm" rel="noopener noreferrer">SEND</button>
            </div>
          </div> 

        </section>
      </main> <!-- End of Main -->
    </div>
    <!-- Footer -->
    <footer>
      <p>&copy; Artiom Shlyusberg 2021</p>
    </footer>
    <!-- Icons provided by https://lineicons.com/ -->
  </div> <!-- End of the wrapper -->
  <script src="https://code.jquery.com/jquery-3.5.1.js" integrity="sha256-QWo7LDvxbWT2tbbQ97B53yJnYU3WhH/C8ycbRAkjPDc=" crossorigin="anonymous"></script>
  <script type="text/javascript" src="js/index.js"></script>
</body>
</html>
