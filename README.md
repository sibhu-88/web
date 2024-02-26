<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My Portpolio</title>
    <link rel="stylesheet" href="Portfolio/Style.css" />
    <link rel="stylesheet" href="Portfolio/mediaqueries.css" />
  </head>
  <body>
    <nav id="desktop-nav">
      <div class="logo">Siva Prabhu</div>
      <div>
        <ul class="nav-links">
          <li><a href="#about">About</a></li>
          <li><a href="#experience">Experience</a></li>
          <li><a href="#projects">Projects</a></li>
          <li><a href="#contact">contact</a></li>
        </ul>
      </div>
    </nav>
    <nav id="hamburger-nav">
      <div class="logo">Siva Prabhu</div>
      <div class="hamburger-menu">
        <div class="hamburger-icon" onclick="toggleMenu()">
          <span></span>
          <span></span>
          <span></span>
        </div>
        <div class="menu-links">
          <li><a href="#about" onclick="toggleMenu()">About</a></li>
          <li><a href="#Experiences" onclick="toggleMenu()">Experiences</a></li>
          <li><a href="#projects" onclick="toggleMenu()">projects</a></li>
          <li><a href="#contact" onclick="toggleMenu()">contact</a></li>
        </div>
      </div>
    </nav>
    <section id="profile">
      <div class="section__pic-container section__pic-container-1">
        <img src="Portfolio/assets/DSC_4382 .jpg" alt="John Doe profile picture" />
      </div>
      <div class="section__text">
        <p class="section__text__p1">Hello, I'm</p>
        <h1 class="title">Siva Prabhu</h1>
        <p class="section__text__p2">Frontend Developer</p>
        <div class="btn-container">
          <button
            class="btn btn-color-2"
            onclick="window.open('Portfolio/assets/Siva Prabhu_resume.pdf', '_blank')"
          >
            Download CV
          </button>
          <button class="btn btn-color-1" onclick="location.href='./#contact'">
            Contect Info
          </button>
        </div>
        <div class="socials-container">
          <img
            src="Portfolio/assets/linkedin.png"
            alt="My linkedin profile"
            class="icon"
            onclick="window.open('https://www.linkedin.com/in/siva-prabhu-v-273084248/', '_blank')"
          />
          <img
            src="Portfolio/assets/github.png"
            alt="My github profile"
            class="icon"
            onclick="window.open('https://github.com/prabhu-88', '_blank')"
          />
        </div>
      </div>
    </section>
    <section id="about">
      <p class="section__text__p1">Get To Know More</p>
      <h1 class="title">About Me</h1>
      <div class="section-container">
        <div class="section__pic-container">
          <img
            src="Portfolio/assets/20230717012730_IMG_8401-01.jpeg"
            alt="profile picture"
            class="about-pic"
          />
        </div>
        <div class="about-details-container">
          <div class="about-containers">
            <br />
            <div class="details-container">
              <img
                src="Portfolio/assets/experience.png"
                alt="Experience icon"
                class="icon"
              />
              <h3>Experience</h3>
              <p>
                6 months <br />
                DataBase Administrator
              </p>
            </div>
            <br />
            <div class="details-container">
              <img
                src="Portfolio/assets/education.png"
                alt="Experience icon"
                class="icon"
              />
              <h3>Edication</h3>
              <p>
                BE Electronics & Instrumentation Engineering <br />
                2017-2021
              </p>
            </div>
          </div>
          <div class="text-container">
            <p>
              I am looking forward to a challenging placement that lets me
              explore and implement innovative solutions in a prestigious
              organization that provides encouragement and growth.
            </p>
          </div>
        </div>
      </div>
      <img
        src="Portfolio/assets/arrow.png"
        alt="Arrow icon"
        class="icon arrow"
        onclick="location.href='./#experience'"
      />
    </section>
    <section id="experience">
      <p class="section__text__p1">Explore My</p>
      <h1 class="title">Experiences</h1>
      <div class="experience-details-container">
        <div class="about-container">
          <div class="details-container">
            <h2 class="experience-sub-title">DataBase Administrator</h2>
            <div class="article-container">
              <article>
                <img
                  src="Portfolio/assets/checkmark.png"
                  alt="Experience icon"
                  class="icon"
                />
                <div>
                  <h3>SQL</h3>
                  <p>Intermediate</p>
                </div>
              </article>
              <article>
                <img
                  src="Portfolio/assets/checkmark.png"
                  alt="Experience icon"
                  class="icon"
                />
                <div>
                  <h3>PL/SQL</h3>
                  <p>Basic</p>
                </div>
              </article>
              <article>
                <img
                  src="Portfolio/assets/checkmark.png"
                  alt="Experience icon"
                  class="icon"
                />
                <div>
                  <h3>MongoDB</h3>
                  <p>Intermediate</p>
                </div>
              </article>
              <article>
                <img
                  src="Portfolio/assets/checkmark.png"
                  alt="Experience icon"
                  class="icon"
                />
                <div>
                  <h3>Ansible</h3>
                  <p>Intermediate</p>
                </div>
              </article>
              <article>
                <img
                  src="Portfolio/assets/checkmark.png"
                  alt="Experience icon"
                  class="icon"
                />
                <div>
                  <h3>Terraform</h3>
                  <p>Basic</p>
                </div>
              </article>
              <article>
                <img
                  src="Portfolio/assets/checkmark.png"
                  alt="Experience icon"
                  class="icon"
                />
                <div>
                  <h3>wordpress</h3>
                  <p>Intermediate</p>
                </div>
              </article>
            </div>
          </div>
          <br />
          <div class="details-container">
            <h2 class="experience-sub-title">Front-end</h2>
            <div class="article-container">
              <article>
                <img
                  src="Portfolio/assets/checkmark.png"
                  alt="Experience icon"
                  class="icon"
                />
                <div>
                  <h3>HTML</h3>
                  <p>Experienced</p>
                </div>
              </article>
              <article>
                <img
                  src="Portfolio/assets/checkmark.png"
                  alt="Experience icon"
                  class="icon"
                />
                <div>
                  <h3>CSS</h3>
                  <p>Experienced</p>
                </div>
              </article>
              <article>
                <img
                  src="Portfolio/assets/checkmark.png"
                  alt="Experience icon"
                  class="icon"
                />
                <div>
                  <h3>Java Script</h3>
                  <p>Intermediate</p>
                </div>
              </article>
              <article>
                <img
                  src="Portfolio/assets/checkmark.png"
                  alt="Experience icon"
                  class="icon"
                />
                <div>
                  <h3>React</h3>
                  <p>Basic</p>
                </div>
              </article>
              <article>
                <img
                  src="Portfolio/assets/checkmark.png"
                  alt="Experience icon"
                  class="icon"
                />
                <div>
                  <h3>Git</h3>
                  <p>Basic</p>
                </div>
              </article>
              <article>
                <img
                  src="Portfolio/assets/checkmark.png"
                  alt="Experience icon"
                  class="icon"
                />
                <div>
                  <h3>Excel</h3>
                  <p>Basic</p>
                </div>
              </article>
            </div>
          </div>
        </div>
      </div>
      <img
        src="Portfolio/assets/arrow.png"
        alt="Arrow icon"
        class="icon arrow"
        onclick="location.href='./#projects'"
      />
    </section>
    <section id="projects">
      <p class="section__text__p1">Browse My Recent</p>
      <h1 class="title">Projects</h1>
      <div class="experience-details-container">
        <div class="about-containers">
          <div class="details-container color-container">
            <div class="article-container">
              <img
                src="Portfolio/assets/project-1.png"
                alt="Project 1"
                class="project-img"
              />
            </div>
            <h2 class="experience-sub-title project-title">Project One</h2>
            <div class="btn-container">
              <button
                class="btn btn-color-2 project-btn"
                onclick="window.open('https://github.com/prabhu-88', '_blank')"
              >
                GitHub
              </button>
              <button
                class="btn btn-color-2 project-btn"
                onclick="window.open('https://github.com/prabhu-88', '_blank')"
              >
                Live Demo
              </button>
            </div>
          </div>
          <div class="details-container color-container">
            <div class="article-container">
              <img
                src="Portfolio/assets/project-2.png"
                alt="Project 2"
                class="project-img"
              />
            </div>
            <h2 class="experience-sub-title project-title">Project Two</h2>
            <div class="btn-container">
              <button
                class="btn btn-color-2 project-btn"
                onclick="window.open('https://github.com/prabhu-88', '_blank')"
              >
                GitHub
              </button>
              <button
                class="btn btn-color-2 project-btn"
                onclick="window.open('https://github.com/prabhu-88', '_blank')"
              >
                Live Demo
              </button>
            </div>
          </div>
          <div class="details-container color-container">
            <div class="article-container">
              <img
                src="Portfolio/assets/project-3.png"
                alt="Project 3"
                class="project-img"
              />
            </div>
            <h2 class="experience-sub-title project-title">Project Three</h2>
            <div class="btn-container">
              <button
                class="btn btn-color-2 project-btn"
                onclick="window.open('https://github.com/prabhu-88', '_blank')"
              >
                GitHub
              </button>
              <button
                class="btn btn-color-2 project-btn"
                onclick="window.open('https://github.com/prabhu-88', '_blank')"
              >
                Live Demo
              </button>
            </div>
          </div>
        </div>
      </div>
      <img
        src="Portfolio/assets/arrow.png"
        alt="Arrow icon"
        class="icon arrow"
        onclick="location.href='./#contact'"
      />
    </section>
    <section id="contact">
      <p class="section__text__p1">Get In Touch</p>
      <h1 class="title">Contact Me</h1>
      <div class="contact-info-upper-container">
        <div class="contact-info-container">
          <img
            src="Portfolio/assets/email.png"
            class="icon contact-icon email-icon"
            alt="Email icon"
          />
          <p>
            <a href="mailto:sprabhu0808@gmail.com">sprabhu0808@gmail.com</a>
          </p>
        </div>
        <div class="contact-info-container">
          <img
            src="Portfolio/assets/linkedin.png"
            alt="linkedIn icon"
            class="icon contact-icon"
          />
          <p>
            <a href="http://www.linkedin.com/in/siva-prabhu-v-273084248/"
              >LinkedIn</a
            >
          </p>
        </div>
      </div>
    </section>
    <footer>
      <nav>
        <div class="nav-links-container">
          <ul class="nav-links">
            <li><a href="#about">About</a></li>
            <li><a href="#experience">Experience</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">contact</a></li>
          </ul>
        </div>
      </nav>
      <p>Copyright &#169; 2023 Siva Prabhu. All Rights Reserved.</p>
    </footer>
    <script src="Portfolio/script.js"></script>
  </body>
</html>