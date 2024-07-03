<template>
  <div class="landing-page">
    <header class="header">
      <nav class="navbar">
        <a href="#" class="nav-logo">Portfolio</a>
        <ul class="nav-menu">
          <li class="nav-item"><a href="#" class="nav-link">Home</a></li>
          <li class="nav-item"><a href="#" class="nav-link">About</a></li>
          <li class="nav-item"><a href="#" class="nav-link">Services</a></li>
          <li class="nav-item"><a href="#" class="nav-link">Portfolio</a></li>
          <li class="nav-item"><a href="#" class="nav-link">Contact</a></li>
        </ul>
      </nav>
    </header>

    <section class="hero">
      <div class="container hero-content">
        <div class="hero-text">
          <h1 class="hero-title">Hello, It's Me<br />{{ name }}</h1>
          <p class="hero-subtitle">
            And I'm a <span class="highlight">Software Developer</span>
          </p>
          <p class="hero-description">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusantium
            ab, obcaecati repellat reiciendis ipsam perspiciatis.
          </p>
          <div class="hero-buttons">
            <a href="#" class="btn btn-primary">Download CV</a>
            <div class="social-links">
              <!-- <a
                href="https://www.facebook.com"
                target="_blank"
                rel="noopener noreferrer"
              >
                <i class="fab fa-facebook"></i>
              </a>
              <a
                href="https://twitter.com"
                target="_blank"
                rel="noopener noreferrer"
              >
                <i class="fab fa-twitter"></i>
              </a> -->
              <a
                href="https://www.linkedin.com"
                target="_blank"
                rel="noopener noreferrer"
              >
                <i class="fab fa-linkedin"></i>
              </a>
              <a
                href="https://www.github.com"
                target="_blank"
                rel="noopener noreferrer"
              >
                <i class="fab fa-github"></i>
              </a>
            </div>
          </div>
        </div>
        <div class="hero-image">
          <img src="" alt="John Kendric" />
        </div>
      </div>
    </section>

    <section class="about">
      <div class="container about-content">
        <div class="about-image">
          <img src="" alt="Your Image" />
        </div>
        <div class="about-text">
          <h2>About <span class="highlight">Me</span></h2>
          <h3>Frontend Developer!</h3>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Et,
            delectus itaque. Aliquid officia aliquid aliquam dolorum consequatur
            suscipit ducimus tenetur maiores vel commodi veniam ratione! Nisi
            praesentium delectus, fugit officia cupiditate in illum, modi unde
            recusandae, molestias excepturi voluptatum temporibus.
          </p>
          <a href="#" class="btn btn-secondary">Read More</a>
        </div>
      </div>
    </section>

    <section class="skills">
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

    <section class="work-experience">
      <div class="container">
        <h2 class="section-title">
          <span class="highlight-work">Work &</span>
          <span class="highlight-experience">Experience</span>
        </h2>
        <div class="work-experience-grid">
          <div class="work-experience-item">
            <h3>Senior Frontend Developer</h3>
            <p>Company Name, 2021 - Present</p>
            <ul>
              <li>
                Developed and maintained web applications using Vue.js and
                React.
              </li>
              <li>
                Led a team of developers to deliver high-quality projects on
                time.
              </li>
              <li>
                Implemented responsive design and ensured cross-browser
                compatibility.
              </li>
            </ul>
          </div>
          <div class="work-experience-item">
            <h3>Frontend Developer</h3>
            <p>Company Name, 2018 - 2021</p>
            <ul>
              <li>
                Worked on various client projects, providing frontend
                development solutions.
              </li>
              <li>
                Collaborated with designers to create intuitive user interfaces.
              </li>
              <li>
                Optimized web applications for performance and scalability.
              </li>
            </ul>
          </div>
        </div>
      </div>
    </section>

    <section class="services">
      <div class="container">
        <h2 class="section-title">
          <span class="highlight-our">Our </span>
          <span class="highlight">Services</span>
        </h2>
        <div class="services-grid">
          <div class="service-item">
            <h3>Web Development</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
            <a href="#" class="btn btn-secondary">Read More</a>
          </div>
          <div class="service-item">
            <h3>Graphic Design</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
            <a href="#" class="btn btn-secondary">Read More</a>
          </div>
          <div class="service-item">
            <h3>Digital Marketing</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
            <a href="#" class="btn btn-secondary">Read More</a>
          </div>
        </div>
      </div>
    </section>

    <section class="projects">
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
            <a :href="project.link" class="btn btn-primary">Visit project</a>
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
            <h3>Bachelor's Degree in Computer Science</h3>
            <p>University Name, Year</p>
            <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin ac
              libero nec quam aliquet suscipit.
            </p>
          </div>
          <div class="education-item">
            <h3>Master's Degree in Software Engineering</h3>
            <p>University Name, Year</p>
            <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin ac
              libero nec quam aliquet suscipit.
            </p>
          </div>
        </div>
      </div>
    </section>

    <section class="contact">
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
    </section>
  </div>
</template>

<script setup>
const name = "Md. Fahidur Rahim";
const projects = [
  {
    id: 1,
    title: "Project 1",
    description: "Project 1 description",
    link: "#",
  },
  {
    id: 2,
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
  padding: 20px 0;
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
  max-width: 300px;
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

/* Work & Experience Section Styles */
.work-experience {
  padding: 50px 0;
  background-color: #1e1e1e;
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
  background-color: #fff;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  color: #1e1e1e;
}

.work-experience-item h3 {
  margin-bottom: 10px;
}

.work-experience-item p {
  margin-bottom: 10px;
}

.work-experience-item ul {
  list-style-type: disc;
  padding-left: 20px;
}

.work-experience-item ul li {
  margin-bottom: 5px;
}

/* Services Section Styles */
.services {
  padding: 50px 0;
  background-color: #1e1e1e;
}

.section-title {
  text-align: center;
  font-size: 36px;
  margin-bottom: 40px;
}

.section-title .highlight-our {
  color: #ffffff;
}

.section-title .highlight {
  color: #00bfa6;
}

.services-grid {
  display: flex;
  gap: 20px;
  justify-content: center;
}

.service-item {
  background-color: #fff;
  padding: 20px;
  border-radius: 8px;
  text-align: center;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  flex: 1;
}

/* Projects Section Styles */

.projects {
  padding: 50px 0;
  background-color: #29292a;
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
  background-color: #fff;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  color: #1e1e1e;
}

/* End */

.contact {
  padding: 50px 0;
  background-color: #1e1e1e;
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
