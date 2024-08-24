<template>
  <div class="landing-page">
    <header class="header">
      <nav class="navbar container">
        <a href="#" class="nav-logo">Fahidur Rahim</a>
        <ul class="nav-menu">
          <li class="nav-item"><a href="#" class="nav-link" @click.prevent="scrollToSection('hero')">Home</a></li>
          <li class="nav-item"><a href="#" class="nav-link" @click.prevent="scrollToSection('about')">About</a></li>
          <li class="nav-item"><a href="#" class="nav-link" @click.prevent="scrollToSection('skills')">Skills</a></li>
          <li class="nav-item"><a href="#" class="nav-link" @click.prevent="scrollToSection('work-experience')">Work/Experience</a></li>
          <li class="nav-item"><a href="#" class="nav-link" @click.prevent="scrollToSection('projects')">Latest Projects</a></li>
        </ul>
      </nav>
    </header>

    <section id="hero" class="hero">
      <div class="container hero-content">
        <div class="hero-text">
          <h1 class="hero-title">Hello, It's Me<br />{{ name }}</h1>
          <p class="hero-subtitle">
            And I'm a <span class="highlight">Software Developer</span>
          </p>
          <p class="hero-description">
            Phone: 01675717825
            <br>
            Email: farhan.fahidurrahim@gmail.com
          </p>
          <div class="hero-buttons">
            <a href="https://drive.google.com/file/d/1C1_z1VniOHn2QI0fEW-lwvIw_5FzsQ5Q/view?usp=sharing" target="_blank" class="btn btn-primary">Download Resume</a>
            <div class="social-links">
              <a
                  href="https://www.linkedin.com/in/md-fahidur-rahim/"
                  target="_blank"
                  rel="noopener noreferrer"
              >
                <i class="fab fa-linkedin"></i>
              </a>
              <a
                  href="https://github.com/farhanfahidurrahim"
                  target="_blank"
                  rel="noopener noreferrer"
              >
                <i class="fab fa-github"></i>
              </a>
            </div>
          </div>
          <p class="hero-subtitle mt-3">
            <span class="highlight">1+ years</span> of Experience
          </p>
        </div>
<!--        <div class="hero-image"></div> &lt;!&ndash; Background image applied through CSS &ndash;&gt;-->
      </div>
    </section>


    <section id="about" class="about">
      <div class="container about-content">
        <div class="about-image">
          <img src="../views/../assets/img/profile.jpg" alt="Your Image" />
        </div>
        <div class="about-text">
          <h2>About <span class="highlight">Me</span></h2>
          <!-- <h3>Software Developer!</h3> -->
          <p>
            I am Md. Fahidur Rahim, a passionate Software Developer with a strong background in PHP, Laravel, MySQL, RestAPI, JavaScript, and Vue.js. With over 1 years of experience in the industry, I have developed and maintained web applications, built APIs for frontend and mobile developers, and led teams to deliver high-quality projects on time. Currently, I am working at Classic IT, where I continue to hone my skills and contribute to exciting projects.
          </p>
          <!-- <a href="#" class="btn btn-secondary">Read More</a> -->
        </div>
      </div>
    </section>

    <section id="skills" class="skills">
      <div class="container">
        <h2 class="section-title">
          My <span class="highlight-skills">Skills</span>
        </h2>
        <div class="skills-grid">
          <div class="skill-item">
            <h3><img src="../assets/img/icon/php.png" alt="php Icon" style="width: 60px; vertical-align: middle;"> PHP OOP</h3>
<!--            <div class="skill-bar">-->
<!--              <div class="skill-progress" style="width: 90%"></div>-->
<!--            </div>-->
          </div>
          <div class="skill-item">
            <h3><img src="../assets/img/icon/laravel.png" alt="laravel Icon" style="width: 60px; vertical-align: middle;"> Laravel</h3>
          </div>
          <div class="skill-item">
            <h3><img src="../assets/img/icon/database.png" alt="mysql Icon" style="width: 60px; vertical-align: middle;"> MySQL</h3>
          </div>
        </div>

        <div class="skills-grid mt-5">
          <div class="skill-item">
            <h3><img src="../assets/img/icon/api.png" alt="api Icon" style="width: 60px; vertical-align: middle;"> RestAPI</h3>
          </div>
          <div class="skill-item">
            <h3><img src="../assets/img/icon/javascript.png" alt="js Icon" style="width: 60px; vertical-align: middle;"> JavaScript</h3>
          </div>
          <div class="skill-item">
            <h3><img src="../assets/img/icon/vue.png" alt="vue Icon" style="width: 60px; vertical-align: middle;"> Vue JS</h3>
          </div>
        </div>

        <div class="skills-grid mt-5">
          <div class="skill-item">
            <h3><img src="../assets/img/icon/jquery.png" alt="vue Icon" style="width: 60px; vertical-align: middle;"> Jquery</h3>
          </div>
          <div class="skill-item">
            <h3><img src="../assets/img/icon/ajax.png" alt="vue Icon" style="width: 60px; vertical-align: middle;"> Ajax</h3>
          </div>
          <div class="skill-item">
            <h3><img src="../assets/img/icon/git.png" alt="vue Icon" style="width: 60px; vertical-align: middle;"> Git</h3>
          </div>
        </div>
      </div>
    </section>

    <section id="work-experience" class="work-experience">
      <div class="container">
        <h2 class="section-title">
          <span class="highlight-work">Work & </span>
          <span class="highlight-experience">Experience</span>
        </h2>
        <div class="work-experience-grid">
          <div class="work-experience-item">
            <h3>Jr. Software Developer</h3>
            <p>Classic IT, November 2023 - Present</p>
            <ul>
              <li>
                Conduct client meetings to gather and clarify project requirements, convert the requirements into actionable project ideas and designs.
              </li>
              <li>
                Develop, build, and maintain RESTful APIs using Laravel and MySQL to support front-end applications (React, Vue, Flutter).
              </li>
              <li>
                Develop and build front-end applications using Vue.js, integrated with Laravel APIs.
              </li>
              <li>
                Create and develop dynamic websites following the Laravel MVC pattern in client requirements.
              </li>
              <li>Identify and resolve bugs and errors in the project, providing client support for updates and testing to ensure project quality.
              </li>
            </ul>
          </div>
          <div class="work-experience-item">
            <h3>Remote Job</h3>
            <p>Contract Based, February 2023 - July 2023</p>
            <ul>
              <li>
                Gather and clarify project requirements in client meetings, converting them into actionable project designs.
              </li>
              <li>
                Create, build, and customize web software using Laravel Blade templates.
              </li>
              <li>
                Develop, build & maintain RESTful APIs for Flutter App.
              </li>
            </ul>
          </div>
          <div class="work-experience-item">
            <h3>Web Developer</h3>
            <p>LinkTech IT, October 2019 - January 2020</p>
            <ul>
              <li>
                Create, build, and maintain web software using Laravel Blade templates.
              </li>
            </ul>
          </div>
          <div class="work-experience-item">
            <h3>Internship</h3>
            <p>Codeless Technologies, 3 Months</p>
            <ul>
              <li>
                Web design & convert PSD to html web page.
              </li>
            </ul>
          </div>
        </div>
      </div>
    </section>

<!--    <section id="projects" class="projects">-->
<!--      <div class="container">-->
<!--        <h2 class="section-title">-->
<!--          <span class="highlight-latest">Latest </span>-->
<!--          <span class="highlight">Project</span>-->
<!--        </h2>-->
<!--        <div class="projects-grid">-->
<!--          <div-->
<!--            v-for="project in projects"-->
<!--            :key="project.id"-->
<!--            class="project-item"-->
<!--          >-->
<!--            <h3>{{ project.title }}</h3>-->
<!--            <p>{{ project.description }}</p>-->
<!--            <a :href="project.link" class="btn btn-primary" target="_blank">Visit project</a>-->
<!--          </div>-->
<!--        </div>-->
<!--      </div>-->
<!--    </section>-->

    <section id="projects" class="projects">
      <div class="container">
        <h2 class="section-title">
          <span class="highlight-latest">Latest</span>
          <span class="highlight"> Projects</span>
        </h2>
        <div class="projects-grid">
          <div
              v-for="project in projects"
              :key="project.id"
              class="project-item"
          >
<!--            <div class="project-image">-->
<!--              <img :src="project.image" :alt="project.title" />-->
<!--            </div>-->
            <div class="project-content">
              <h3>{{ project.title }}</h3>
              <p>Technology: {{ project.technology }}</p>
              <ul>
                <li v-for="point in project.key_points" :key="point">{{ point }}</li>
              </ul>
              <a :href="project.link" class="btn btn-primary link" target="_blank">Visit Project</a>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="education">
      <div class="container">
        <h2 class="section-title">
          <span class="highlight-education">Education</span>
        </h2>
        <div class="education-grid">
          <div class="education-item">
            <h3>BSc in Software Engineering</h3>
            <p>American International University Bangladesh (AIUB)</p>
            <!-- <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin ac
              libero nec quam aliquet suscipit.
            </p> -->
          </div>

          <div class="education-item">
            <h3>HSC</h3>
            <p>Gurudayal Govt College, 2013</p>
          </div>

          <div class="education-item">
            <h3>SSC</h3>
            <p>Kishoreganj Govt Boys High School, 2011</p>
          </div>
        </div>
      </div>
    </section>

    <section id="why-hire-me" class="why-hire-me">
      <div class="container">
        <h2 class="section-title">
          <span class="highlight-why">Why </span>
          <span class="highlight-hire">Hire Me?</span>
        </h2>
        <div class="why-hire-me-content">
          <p>
            I bring a unique blend of technical expertise and practical experience to the table. With a proven track record of delivering high-quality projects, I am committed to continuously honing my skills and staying up-to-date with the latest industry trends. My ability to lead a team and collaborate effectively makes me a valuable asset to any organization. Here are some reasons why you should consider hiring me:
          </p>
          <ul>
            <li>Strong foundation in software development principles and practices.</li>
            <li>Extensive experience with PHP, Laravel, MySQL, JavaScript, and Vue.js.</li>
            <li>Proven ability to develop and implement RESTful APIs.</li>
            <li>Track record of leading successful projects and delivering on time.</li>
            <li>Commitment to continuous learning and professional development.</li>
          </ul>
        </div>
      </div>
    </section>

    <!-- <section class="contact">
      <div class="container">
        <h2 class="section-title">Contact Me</h2>
        <form class="contact-form">
          <div class="form-group">
            <label for="name">Name</label>
            <input type="text" id="name" class="form-control" />
          </div>
          <div class="form-group">
            <label for="email">Email</label>
            <input type="email" id="email" class="form-control" />
          </div>
          <div class="form-group">
            <label for="message">Your Message</label>
            <textarea id="message" class="form-control"></textarea>
          </div>
          <button type="submit" class="btn btn-primary">Send Message</button>
        </form>
      </div>
    </section> -->

    <section id="footer" class="footer">
      <div class="container footer-content">
        <div class="footer-text">
        </div>
        <div class="footer-image">
        </div>
      </div>
    </section>
  </div>
</template>

<script setup>

const scrollToSection = (sectionId) => {
  const element = document.getElementById(sectionId);
  if (element) {
    element.scrollIntoView({ behavior: 'smooth' });
  }
};

const name = "Md. Fahidur Rahim";
const projects = [
  {
    id: 1,
    title: "Vue Js Project (Personal)",
    technology: "Vue Js [ Frontend ]",
    key_points: [
      "Developed and built dynamic frontend applications using Vue.js.",
      "Integrated Vue.js applications with Laravel APIs for seamless backend communication.",
      "Implemented Vue.js 3 Composition API to build interactive interfaces & ensure performance.",
    ],
    link: "https://github.com/farhanfahidurrahim/POS-Software-Frontend-VueJs",
  },
  {
    id: 2,
    title: "Classic POS",
    technology: "PHP Laravel (API) [ Backend ]",
    key_points: [
      "Develop, build, and maintain RESTful APIs using Laravel and MySQL to support front-end.",
      "Focused on backend logic, providing APIs for seamless integration with the React.js frontend.",
      "Create and develop dynamic websites following the Laravel MVC pattern in client requirements."
    ],
    link: "https://classic-pos-frontend.classicit.org",
  },
  {
    id: 3,
    title: "Creation EDGE",
    technology: "PHP Laravel (API) [ Backend ]",
    key_points: [
      "Develop, build, and maintain RESTful APIs using Laravel and MySQL to support front-end.",
      "Focused on backend logic, providing APIs for seamless integration with the React.js frontend.",
      "Create and develop dynamic websites following the Laravel MVC pattern in client requirements."
    ],
    link: "https://pos.creationedge.com.bd",
  },
  {
    id: 4,
    title: "Sun Shine Power",
    technology: "PHP Laravel (API) [ Backend ]",
    key_points: [
      "Develop, build, and maintain RESTful APIs using Laravel and MySQL to support front-end.",
      "Focused on backend logic, providing APIs for seamless integration with the React.js frontend.",
      "Create and develop dynamic websites following the Laravel MVC pattern in client requirements."
    ],
    link: "https://sunsine.classicitltd.com",
  },
  {
    id: 5,
    title: "Porichoy Traders Flutter App",
    technology: "PHP Laravel (API) [ Backend ]",
    key_points: [
      "Develop, build, and maintain RESTful APIs using Laravel and MySQL to support front-end.",
      "Focused on backend logic, providing APIs for seamless integration with the Flutter.js frontend.",
      "Create and develop dynamic websites following the Laravel MVC pattern in client requirements."
    ],
    link: "https://play.google.com/store/apps/details?id=com.porichoytraders.porichoytraders&hl=en",
  },
  {
    id: 6,
    title: "Wood Machinery (Web & Flutter)",
    technology: "PHP Laravel (API) [ Backend ]",
    key_points: [
      "Create and develop dynamic websites following the Laravel MVC pattern in client requirements.",
      "Develop, build, and maintain RESTful APIs using Laravel and MySQL to support front-end.",
      "Focused on backend logic, providing APIs for seamless integration with the Flutter.js frontend.",
    ],
    link: "https://woodmachinery.com.bd",
  },
];
</script>

<style scoped>
/* Header Styles */
.header {
  background-color: #121212;
  padding: 5px 0;
  position: fixed;
  width: 100%;
  top: 0;
  left: 0;
  z-index: 1000;
}

.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0 20px;
}

.nav-logo {
  color: #fff;
  font-size: 24px;
  text-decoration: none;
  font-weight: bold;
}

.nav-menu {
  list-style: none;
  display: flex;
  gap: 20px;
  margin: 0;
  padding: 0;
}

.nav-item {
  display: inline-block;
}

.nav-link {
  color: #fff;
  text-decoration: none;
  font-size: 18px;
}

.nav-link:hover {
  text-decoration: underline;
}

/* Responsive styles */
@media (max-width: 768px) {
  .nav-menu {
    display: none;
    flex-direction: column;
    width: 100%;
    background-color: #333;
    position: absolute;
    top: 60px;
    left: 0;
    z-index: 1000;
  }

  .nav-menu.active {
    display: flex;
  }

  .nav-item {
    margin: 15px 0;
    text-align: center;
  }

  .nav-toggle {
    display: flex;
  }
}

/* End Header Section Styles */

/* Hero Section Styles */

section#hero {
  background: url('../src/assets/img/fbgcover.webp');
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  position: relative;
  z-index: 2;
}

section#hero::after {
  position: absolute;
  content: '';
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  background: #000;
  opacity: .5;
  z-index: -1;
}

.hero {
  text-align: left;
  padding: 100px 0;
  background-color: #1e1e1e;
  color: #fff;
}

.hero-content {
  display: flex;
  align-items: center;
  justify-content: space-between;
  flex-wrap: wrap;
}

.hero-text {
  flex: 1;
  max-width: 600px;
}

.hero-title {
  font-size: 48px;
  margin-bottom: 20px;
}

.hero-subtitle {
  font-size: 24px;
  margin-bottom: 10px;
}

.hero-subtitle .highlight {
  color: #00bfa6;
}

.hero-description {
  font-size: 18px;
  margin-bottom: 20px;
}

.hero-buttons {
  display: flex;
  align-items: center;
  gap: 20px;
}

.btn-primary {
  background-color: #00bfa6;
  color: #fff;
  border: none;
  padding: 10px 20px;
  font-size: 18px;
  cursor: pointer;
  text-decoration: none;
  display: inline-block;
  border-radius: 25px;
  transition: all 0.3s ease;
  box-shadow: 0 0 10px rgba(0, 191, 166, 0.5);
}

.btn-primary:hover {
  background-color: #009688;
  box-shadow: 0 0 20px rgba(0, 191, 166, 0.7);
}

.social-links {
  display: flex;
  gap: 15px;
}

.social-links a {
  color: #00bfa6;
  font-size: 24px;
  width: 40px;
  height: 40px;
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 50%;
  background-color: #1e1e1e;
  border: 2px solid #00bfa6;
  transition: all 0.3s ease;
  box-shadow: 0 0 10px rgba(0, 191, 166, 0.5);
}

.social-links a:hover {
  color: #fff;
  background-color: #00bfa6;
  box-shadow: 0 0 20px rgba(0, 191, 166, 0.7);
}

.hero-image {
  flex: 1;
  padding: 20px;
  background-image: url('../views/../assets/img/bg_cover.jpg'); /* Set the background image */
  background-size: cover; /* Cover the entire div */
  background-position: center; /* Center the image */
  border-radius: 8px;
  box-shadow: 0 0 20px rgba(0, 191, 166, 0.5);
  height: 300px; /* Adjust height as needed */
}

.hero-image img {
  max-width: 100%;
  height: auto;
  border-radius: 8px;
  box-shadow: 0 0 20px rgba(0, 191, 166, 0.5);
}

/* Responsive styles */
@media (max-width: 768px) {
  .hero-title {
    font-size: 2em;
  }

  .hero-subtitle {
    font-size: 1.2em;
  }

  .hero-description {
    font-size: 0.9em;
  }

  .hero-buttons {
    flex-direction: column;
  }

  .social-links {
    margin-top: 10px;
  }

  .hero-image {
    height: 200px; /* Adjust height for smaller screens */
  }
}

@media (max-width: 480px) {
  .hero-title {
    font-size: 1.5em;
  }

  .hero-subtitle {
    font-size: 1em;
  }

  .hero-description {
    font-size: 0.8em;
  }

  .hero-buttons .btn-primary {
    padding: 8px 16px;
  }

  .hero-image {
    height: 150px; /* Adjust height for even smaller screens */
  }
}
/* End Hero Section Styles */

/* About Section Styles */

.about {
  text-align: left;
  padding: 50px 0;
  background-color: #29292a;
  color: #fff;
}

.about-content {
  display: flex;
  align-items: center;
  justify-content: space-between;
  flex-wrap: wrap;
}

.about-image {
  flex: 1;
  padding: 20px;
  display: flex;
  justify-content: flex-start;
  align-items: center;
}

.about-image img {
  max-width: 50%;
  height: auto;
  border-radius: 50%;
  border: 4px solid #00bfa6;
  box-shadow: 0 0 20px rgba(0, 191, 166, 0.5);
}

.about-text {
  flex: 1;
  max-width: 600px;
}

.about-text p {
  text-align: justify;
}

.about-text .highlight {
  color: #00bfa6;
}

.about h2 {
  font-size: 36px;
  margin-bottom: 20px;
}

.about h3 {
  font-size: 24px;
  margin-bottom: 10px;
}

.about p {
  font-size: 18px;
  margin-bottom: 20px;
}

/* Responsive styles */
@media (max-width: 768px) {
  .about-content {
    flex-direction: column;
    align-items: center;
  }

  .about-image {
    justify-content: center;
  }

  .about-image img {
    max-width: 70%;
  }

  .about-text {
    flex: none;
    width: 100%;
    text-align: center;
    padding: 10px;
  }

  .about-text h2 {
    font-size: 2em;
  }

  .about-text p {
    font-size: 17px;
  }
}

/* End About Section Styles */


/* Skills Section Styles */
.skills {
  padding: 50px 0;
  background-color: #1e1e1e;
  color: #fff;
}

.section-title .highlight-skills {
  color: #00bfa6;
}

.skills-grid {
  display: flex;
  gap: 20px;
  justify-content: center;
}

.skill-item {
  flex: 1;
  text-align: center;
}

.skill-bar {
  background-color: #333;
  border-radius: 8px;
  overflow: hidden;
  margin-top: 10px;
}

.skill-progress {
  height: 20px;
  background-color: #00bfa6;
}

/* Responsive styles */
@media (max-width: 992px) {
  .skills-grid {
    grid-template-columns: repeat(2, 1fr);
  }
}

@media (max-width: 768px) {
  .skills-grid {
    grid-template-columns: 1fr;
  }

  .skill-item {
    margin-bottom: 20px;
  }
}

@media (max-width: 480px) {
  .section-title {
    font-size: 2em;
  }

  .skill-item h3 {
    font-size: 1em;
  }

  .skill-item img {
    width: 50px; /* Adjust the icon size for smaller screens */
  }
}

/* End Skill Section Styles */


/* Work & Experience Section Styles */
.work-experience {
  padding: 50px 0;
  background-color: #29292a;
  color: #fff;
}

.section-title .highlight-work {
  color: #ffffff;
}

.section-title .highlight-experience {
  color: #00bfa6;
}

.work-experience-grid {
  display: flex;
  flex-direction: column;
  gap: 20px;
  justify-content: center;
}

.work-experience-item {
  background-color: #201e1e;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  color: #1e1e1e;
}

.work-experience-item h3 {
  margin-bottom: 10px;
  color: #fff;
}

.work-experience-item p {
  margin-bottom: 10px;
  color: #fff;
}

.work-experience-item ul {
  list-style-type: disc;
  padding-left: 20px;
}

.work-experience-item ul li {
  margin-bottom: 5px;
  color: #fff;
}

/* End WorkExp Section Styles */

/* Latest Projects Section Styles */

.projects {
  padding: 70px 0;
  background-color: #1e1e1e;
}

.section-title {
  text-align: center;
  font-size: 40px;
  margin-bottom: 60px;
  color: #ffffff;
}

.section-title .highlight-latest {
  color: #ffffff;
}

.section-title .highlight {
  color: #00bfa6;
}

.projects-grid {
  display: grid;
  gap: 20px;
  grid-template-columns: repeat(3, 1fr); /* This ensures 3 items per row */
  justify-content: center;
}


.project-item {
  background-color: #2a2a2a;
  border-radius: 12px;
  overflow: hidden;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
}

.project-item:hover {
  transform: translateY(-10px);
  box-shadow: 0 15px 30px rgba(0, 0, 0, 0.3);
}

.project-image img {
  width: 100%;
  height: auto;
  display: block;
}

.project-content {
  padding: 20px;
  color: #ffffff;
  text-align: left;
}

.project-content h3 {
  font-size: 24px;
  margin-bottom: 15px;
}

.project-content p {
  font-size: 16px;
  margin-bottom: 20px;
}

.btn-primary {
  background-color: #00bfa6;
  color: #ffffff;
  padding: 10px 20px;
  border-radius: 4px;
  text-transform: uppercase;
  font-weight: bold;
  transition: background-color 0.3s ease;
}

.btn-primary.link {
  font-size: 14px; /* Custom font size for .link */
  padding: 8px 16px; /* Custom padding for .link */
  border-radius: 4px; /* Custom border-radius for .link */
}

.btn-primary:hover {
  background-color: #009688;
}

/* Responsive styles */
@media (max-width: 992px) {
  .projects-grid {
    grid-template-columns: repeat(2, 1fr);
  }
}

@media (max-width: 768px) {
  .projects-grid {
    grid-template-columns: 1fr;
  }

  .project-content h3 {
    font-size: 1.3em;
  }

  .project-content p {
    font-size: 0.95em;
  }
}

@media (max-width: 480px) {
  .section-title {
    font-size: 2em;
  }

  .project-content h3 {
    font-size: 1.2em;
  }

  .project-content p {
    font-size: 0.9em;
  }

  .project-content .btn {
    padding: 8px 16px;
    font-size: 0.9em;
  }
}

/* End Project Section Styles */


/* Education Section Styles */
.education {
  padding: 50px 0;
  background-color: #29292a;
  color: #fff;
}

.section-title .highlight-education {
  color: #00bfa6;
}

.education-grid {
  display: flex;
  flex-direction: column;
  gap: 20px;
  justify-content: center;
}

.education-item {
  background-color: #201e1e;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  color: #1e1e1e;
}

.education-item h3 {
  margin-bottom: 10px;
  color: #fff;
}

.education-item p {
  margin-bottom: 10px;
  color: #fff;
}

/* Why Hire Me Section Styles */

.why-hire-me {
  padding: 60px 0;
  background-color: #1e1e1e;
  color: #fff;
}

.why-hire-me-content {
  margin: 0 auto;
}

.why-hire-me-content p {
  text-align: justify;
  margin-bottom: 20px;
  font-size: 1rem;
  line-height: 1.6;
}

.why-hire-me-content ul {
  font-size: 18px;
}

.why-hire-me-content ul {
  list-style: disc;
  padding-left: 20px;
}

.why-hire-me-content li {
  margin-bottom: 10px;
}

.section-title .highlight-hire {
  color: #00bfa6;
}

/* End Hire-Me Section Styles */


/* Footer Section Styles */
.footer {
  text-align: left;
  padding: 25px 0;
  background-color: #000000;
  color: #fff;
}

.footer-content {
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.footer-text {
  max-width: 600px;
}

.footer-title {
  font-size: 48px;
  margin-bottom: 20px;
}

.footer-subtitle {
  font-size: 24px;
  margin-bottom: 10px;
}

.footer-subtitle .highlight {
  color: #00bfa6;
}

.footer-description {
  font-size: 18px;
  margin-bottom: 20px;
}

.footer-buttons {
  display: flex;
  align-items: center;
  gap: 20px;
}

.btn-primary {
  background-color: #00bfa6;
  color: #fff;
  border: none;
  padding: 10px 20px;
  font-size: 18px;
  cursor: pointer;
  text-decoration: none;
  display: inline-block;
  border-radius: 25px;
  transition: all 0.3s ease;
  box-shadow: 0 0 10px rgba(0, 191, 166, 0.5);
}

.btn-primary:hover {
  background-color: #009688;
  box-shadow: 0 0 20px rgba(0, 191, 166, 0.7);
}

/* End */

.contact {
  padding: 50px 0;
  background-color: #29292a;
  color: #fff;
}

.contact-form {
  max-width: 600px;
  margin: 0 auto;
}

.form-group {
  margin-bottom: 20px;
}

.form-control {
  width: 100%;
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 4px;
}

.form-control:focus {
  border-color: #00bfa6;
}

.btn-primary:hover,
.btn-secondary:hover {
  background-color: #009688;
}
</style>
