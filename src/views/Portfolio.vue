<template>
  <div class="landing-page">
    <header class="header">
      <nav class="navbar container">
        <a href="#" class="nav-logo">Portfolio</a>
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
            <a href="#" class="btn btn-primary">Download CV</a>
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
        </div>
        <div class="hero-image">
          <img src="../views/../assets/img/cover2.jpg" alt="John Kendric" />
        </div>
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
          <span class="highlight-skills">Skills</span>
        </h2>
        <div class="skills-grid">
          <div class="skill-item">
            <h3>PHP OOP</h3>
            <div class="skill-bar">
              <div class="skill-progress" style="width: 90%"></div>
            </div>
          </div>
          <div class="skill-item">
            <h3>Laravel Framework</h3>
            <div class="skill-bar">
              <div class="skill-progress" style="width: 80%"></div>
            </div>
          </div>

          <div class="skill-item">
            <h3>MySQL</h3>
            <div class="skill-bar">
              <div class="skill-progress" style="width: 90%"></div>
            </div>
          </div>
        </div>

        <div class="skills-grid mt-5">
          <div class="skill-item">
            <h3>RestAPI</h3>
            <div class="skill-bar">
              <div class="skill-progress" style="width: 80%"></div>
            </div>
          </div>

          <div class="skill-item">
            <h3>JavaScript</h3>
            <div class="skill-bar">
              <div class="skill-progress" style="width: 90%"></div>
            </div>
          </div>
          <div class="skill-item">
            <h3>VueJs</h3>
            <div class="skill-bar">
              <div class="skill-progress" style="width: 80%"></div>
            </div>
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
            <h3>Software Developer</h3>
            <p>Classic IT, 2023 - Present</p>
            <ul>
              <li>
                Developed and maintained web applications using PHP Laravel and MySQL.
              </li>
              <li>
                Build Implementation API for Frontend React.Js & Android Flutter Developer.
              </li>
              <li>
                Lead a team of developers to deliver high-quality projects on
                time.
              </li>
            </ul>
          </div>
          <div class="work-experience-item">
            <h3>Remote Job</h3>
            <p>Contract Based, 2023 - 2023</p>
            <ul>
              <li>
                Customize Web Software Laravel Blade.
              </li>
              <li>
                Build API for Flutter App.
              </li>
            </ul>
          </div>
          <div class="work-experience-item">
            <h3>Web Developer</h3>
            <p>LinkTech IT, 2019 - 2020</p>
            <ul>
              <li>
                Build Web Software Laravel Blade.
              </li>
            </ul>
          </div>
        </div>
      </div>
    </section>

    <section id="projects" class="projects">
      <div class="container">
        <h2 class="section-title">
          <span class="highlight-latest">Latest </span>
          <span class="highlight">Project</span>
        </h2>
        <div class="projects-grid">
          <div
            v-for="project in projects"
            :key="project.id"
            class="project-item"
          >
            <h3>{{ project.title }}</h3>
            <p>{{ project.description }}</p>
            <a :href="project.link" class="btn btn-primary" target="_blank">Visit project</a>
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
    title: "Creation Edge",
    description: "Project 1 description",
    link: "https://creationedge.com.bd/",
  },
  {
    id: 2,
    title: "Project 2",
    description: "Project 2 description",
    link: "#",
  },
  {
    id: 3,
    title: "Project 2",
    description: "Project 2 description",
    link: "#",
  },
  {
    id: 4,
    title: "Project 2",
    description: "Project 2 description",
    link: "#",
  },
  // Add more projects as needed
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
}

.nav-logo {
  color: #fff;
  font-size: 24px;
  text-decoration: none;
}

.nav-menu {
  list-style: none;
  display: flex;
  gap: 20px;
}

.nav-item {
  display: inline-block;
}

.nav-link {
  color: #fff;
  text-decoration: none;
  font-size: 18px;
}

/* Hero Section Styles */
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
}

.hero-text {
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

.hero-image img {
  border-radius: 8px;
  box-shadow: 0 0 20px rgba(0, 191, 166, 0.5);
  max-width: 500px;
}

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
}

.about-image img {
  max-width: 300px;
  border-radius: 50%;
  border: 4px solid #00bfa6;
  box-shadow: 0 0 20px rgba(0, 191, 166, 0.5);
}

.about-text {
  max-width: 600px;
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

/* Latest Projects Section Styles */

.projects {
  padding: 50px 0;
  background-color: #1e1e1e;
}

.section-title {
  text-align: center;
  font-size: 36px;
  margin-bottom: 40px;
}

.section-title .highlight-latest {
  color: #ffffff;
}

.section-title .highlight {
  color: #00bfa6;
}

.projects-grid {
  display: flex;
  gap: 20px;
  justify-content: center;
}

.project-item {
  background-color: #fff;
  padding: 20px;
  border-radius: 8px;
  text-align: center;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  flex: 1;
}

.btn-primary:hover {
  background-color: #009688;
}

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

.why-hire-me-content p,
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
