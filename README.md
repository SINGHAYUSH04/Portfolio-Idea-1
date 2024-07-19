The provided code creates a responsive and stylish portfolio website for a front-end developer and web designer. To adapt this template for your cybersecurity portfolio, you'll need to update the content and possibly modify some sections to better fit your skills, experience, and the theme of cybersecurity.

Here are the modifications you could make:

1. **Update Personal Information**: Replace "Faraz Choudhary" and other personal details with your information.

2. **Change the Theme Colors**: Adjust the colors to fit a cybersecurity theme, focusing on green and black as preferred.

3. **Update Section Content**:
   - **About Section**: Tailor the content to reflect your background in cybersecurity, skills, and experiences.
   - **Skills Section**: Highlight your cybersecurity skills such as penetration testing, network security, Python programming, etc.
   - **Portfolio Section**: Showcase your projects related to cybersecurity, vulnerability assessments, etc.
   - **Contact Section**: Provide your contact details and relevant social media links.

Here is a revised version of the HTML with some adjustments:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Ayush Singh - Cybersecurity Portfolio</title>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width" />
    <link rel='stylesheet' href='https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.0.0-alpha.6/css/bootstrap.min.css'>
    <link rel='stylesheet' href='https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css'>
    <link rel='stylesheet' href='https://fonts.googleapis.com/css?family=Montserrat:300,400,700"rel="stylesheet'>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <div class="menu-responsive">
      <nav>
        <ul>
          <li><a class="scroll" href="#about">About</a></li>
          <li><a class="scroll" href="#skills">Skills</a></li>
          <li><a class="scroll" href="#portfolio">Portfolio</a></li>
          <li><a class="scroll" href="#contact">Contact</a></li>
        </ul>
      </nav>
    </div>

    <header>
      <div class="container">
        <div class="row">
          <div class="header__top">
            <div class="col-md-6 header__top-brand">
              <h1><span class="bold">Codewith</span> Ayush</h1>
              <hr>
            </div>
            <nav class="col-md-6 header__top-nav hidden-md-down">
              <ul>
                <li><a class="scroll" href="#about">About</a></li>
                <li><a class="scroll" href="#skills">Skills</a></li>
                <li><a class="scroll" href="#portfolio">Portfolio</a></li>
                <li><a class="scroll" href="#contact">Contact</a></li>
              </ul>
            </nav>
            <nav class="col-md-6 header__top--responsive hidden-lg-up">
              <ul>
                <li><a class="menu-bars" href="#"><i class="fa fa-bars" aria-hidden="true"></i></a></li>
              </ul>
            </nav>
          </div>
        </div>

        <div class="header__content">
          <p class="bold">Hello !</p>
          <p>I'm a Freelance <span class="bold">Cybersecurity Expert</span> & <span class="bold">Web Developer</span></p>
          <a class="btn scroll" href="#portfolio">See My Work</a>
        </div>

        <div class="header__arrow">
          <a class="scroll" href="#about"><i class="fa fa-chevron-down" aria-hidden="true"></i></a>
        </div>
      </div>
    </header>

    <section id="about">
      <div class="container">
        <h2>Who I Am</h2>
        <hr>
        <img src="your-image-url-here" alt="Ayush Singh">
        <p class="lead">Freelance Cybersecurity Expert & Web Developer</p>
        <p>I'm <span class="bold">Ayush Singh</span>, a <strong>Cybersecurity Expert</strong> and <strong>Web Developer</strong> from <a href="your-location-url-here" target="_blank">Jaipur, India</a>.</p>
        <p>I love <strong>helping businesses</strong> of all sizes to build and improve their online presence and security.</p>
        <p>I <strong>Design</strong> and <strong>Develop</strong> modern, secure, and responsive websites.</p>
        <p>Apart from cybersecurity, I enjoy learning new technologies, participating in hackathons, and gaming.</p>
      </div>
    </section>

    <section id="skills">
      <div class="container">
        <h2>My Skills</h2>
        <hr>
        <div class="row">
          <div class="skill col-12 col-lg-6">
            <div class="skills__percent">95%</div>
            <div class="progress-container">
              <strong>Python / Scripting</strong>
              <div class="progress">
                <div class="progress-bar" style="width: 95%"></div>
              </div>
            </div>
          </div>
          <div class="skill col-12 col-lg-6">
            <div class="skills__percent">90%</div>
            <div class="progress-container">
              <strong>Network Security</strong>
              <div class="progress">
                <div class="progress-bar" style="width: 90%"></div>
              </div>
            </div>
          </div>
          <div class="skill col-12 col-lg-6">
            <div class="skills__percent">85%</div>
            <div class="progress-container">
              <strong>Penetration Testing</strong>
              <div class="progress">
                <div class="progress-bar" style="width: 85%"></div>
              </div>
            </div>
          </div>
          <div class="skill col-12 col-lg-6">
            <div class="skills__percent">80%</div>
            <div class="progress-container">
              <strong>Web Development</strong>
              <div class="progress">
                <div class="progress-bar" style="width: 80%"></div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section id="portfolio">
      <h2>Portfolio</h2>
      <hr>
      <div class="container">
        <div class="portfolio__projects">
          <div class="row">
            <!-- Add your project details here -->
            <div class="col-lg-4 col-md-6">
              <figure>
                <figcaption>
                  <h3>Project Name</h3>
                  <p>Coming Soon</p>
                  <a href="#"><i class="fa fa-search-plus" aria-hidden="true"></i></a>
                </figcaption>
                <img src="http://via.placeholder.com/300x250">
              </figure>
            </div>
            <!-- Repeat for other projects -->
          </div>
        </div>
      </div>
    </section>

    <section id="contact">
      <div class="container">
        <p class="lead">Do you like what you see?</p>
        <p>Need a <span class="text-animate">cybersecurity expert?</span></p>
        <a class="btn" href="mailto:your-email@example.com">Contact Me</a>

        <div class="contact__social">
          <a href="#" target="_blank"><i class="fa fa-twitter" aria-hidden="true"></i></a>
          <a href="#" target="_blank"><i class="fa fa-linkedin" aria-hidden="true"></i></a>
          <a href="https://github.com/your-github-username" target="_blank"><i class="fa fa-github" aria-hidden="true"></i></a>
        </div>
      </div>
    </section>

    <section id="footer">
      <p>Made with <i class="fa fa-heart" aria-hidden="true"></i> by <a href="your-website-url-here" target="_blank">Ayush Singh</a> <i class="fa fa-copyright" aria-hidden="true"></i>2024</p>
    </section>
    <script src='https://cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js'></script>
    <script src='https://unpkg.com/scrollreveal/dist/scrollreveal.min.js'></script>
    <script src="script.js"></script>
  </body>
</html/>
