<template>
  <div class="landing-page">
    <header class="header">
      <nav class="navbar container">
        <a href="#" class="nav-logo">Portfolio</a>
        <ul class="nav-menu">
          <li class="nav-item">
            <a href="#" class="nav-link" @click.prevent="scrollToSection('hero')">Home</a>
          </li>
          <li class="nav-item">
            <a href="#" class="nav-link" @click.prevent="scrollToSection('about')">About</a>
          </li>
          <li class="nav-item">
            <a href="#" class="nav-link" @click.prevent="scrollToSection('skills')">Skills</a>
          </li>
          <li class="nav-item">
            <a href="#" class="nav-link" @click.prevent="scrollToSection('work-experience')">Work/Experience</a>
          </li>
          <li class="nav-item">
            <a href="#" class="nav-link" @click.prevent="scrollToSection('projects')">Latest Projects</a>
          </li>
        </ul>
      </nav>
    </header>

    <section id="hero" class="hero">
      <div class="container hero-content">
        <div class="hero-text">
          <h1 class="hero-title">Hello, It's Me<br/>{{ name }}</h1>
          <p class="hero-subtitle">
            <span class="highlight">Software Developer</span>
          </p>
          <p class="hero-description">
            Phone: 01675717825
            <br/>
            Email: farhan.fahidurrahim@gmail.com
          </p>
          <div class="hero-buttons">
            <a href="https://drive.google.com/file/d/19V-FDZcgG7dktPQnFJK9g16XlRvzU5i7/view?usp=sharing" target="_blank"
               class="btn btn-primary">Download Resume</a>
            <div class="social-links">
              <a href="https://www.linkedin.com/in/md-fahidur-rahim/" target="_blank" rel="noopener noreferrer">
                <i class="fab fa-linkedin"></i>
              </a>
              <a href="https://github.com/farhanfahidurrahim" target="_blank" rel="noopener noreferrer">
                <i class="fab fa-github"></i>
              </a>
            </div>
          </div>
          <p class="hero-subtitle-exp mt-3">
            <span class="highlight">2+ years</span> of Experience
          </p>
        </div>
        <!--        <div class="hero-image"></div> &lt;!&ndash; Background image applied through CSS &ndash;&gt;-->
      </div>
    </section>

    <section id="about" class="about">
      <div class="container about-content">
        <div class="about-image">
          <img src="../views/../assets/img/profile.jpg" alt="Your Image"/>
        </div>
        <div class="about-text">
          <h2>About <span class="highlight">Me</span></h2>
          <!-- <h3>Software Developer!</h3> -->
          <p>
            I am Md. Fahidur Rahim, a passionate Software Developer with over 2 years of experience and a strong
            background in PHP (OOP), Laravel, MySQL, PostgreSQL, and RESTful API development. I am currently learning
            frontend development using React.js and am also familiar with Vue.js. Throughout my career, I have developed
            and maintained web applications, built APIs for frontend and mobile developers, and led teams to deliver
            high-quality projects on time. I am eager to contribute to innovative projects while continuing to grow my
            expertise in a collaborative, dynamic environment. I am seeking a role that allows me to tackle challenging
            projects and further develop my skills within a team.
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
            <h3>
              <img src="../assets/img/icon/php.png" alt="php Icon" style="width: 60px; vertical-align: middle"/>
              PHP OOP
            </h3>
            <!--            <div class="skill-bar">-->
            <!--              <div class="skill-progress" style="width: 90%"></div>-->
            <!--            </div>-->
          </div>
          <div class="skill-item">
            <h3>
              <img src="../assets/img/icon/laravel.png" alt="laravel Icon"
                   style="width: 60px; vertical-align: middle"/>
              Laravel
            </h3>
          </div>
          <div class="skill-item">
            <h3>
              <img src="../assets/img/icon/database.png" alt="mysql Icon" style="width: 60px; vertical-align: middle"/>
              MySQL
            </h3>
          </div>
          <div class="skill-item">
            <h3>
              <img src="../assets/img/icon/pgsql.png" alt="pgsql Icon" style="width: 60px; vertical-align: middle"/>
              PgSQL
            </h3>
          </div>
        </div>

        <div class="skills-grid mt-5">
          <div class="skill-item">
            <h3>
              <img src="../assets/img/icon/api.png" alt="api Icon" style="width: 60px; vertical-align: middle"/>
              RestAPI
            </h3>
          </div>
          <div class="skill-item">
            <h3>
              <img src="../assets/img/icon/javascript.png" alt="js Icon" style="width: 60px; vertical-align: middle"/>
              JavaScript
            </h3>
          </div>
          <div class="skill-item">
            <h3>
              <img src="../assets/img/icon/react.png" alt="react Icon" style="width: 60px; vertical-align: middle"/>
              React JS
            </h3>
          </div>
          <div class="skill-item">
            <h3>
              <img src="../assets/img/icon/vue.png" alt="vue Icon" style="width: 60px; vertical-align: middle"/>
              Vue JS
            </h3>
          </div>
        </div>

        <div class="skills-grid mt-5">
          <div class="skill-item">
            <h3>
              <img src="../assets/img/icon/bootstrap.png" alt="bootstrap Icon"
                   style="width: 60px; vertical-align: middle"/>
              Bootstrap
            </h3>
          </div>
          <div class="skill-item">
            <h3>
              <img src="../assets/img/icon/jquery.png" alt="jquery Icon" style="width: 60px; vertical-align: middle"/>
              Jquery
            </h3>
          </div>
          <div class="skill-item">
            <h3>
              <img src="../assets/img/icon/ajax.png" alt="ajax Icon" style="width: 60px; vertical-align: middle"/>
              Ajax
            </h3>
          </div>
          <div class="skill-item">
            <h3>
              <img src="../assets/img/icon/git.png" alt="git Icon" style="width: 60px; vertical-align: middle"/>
              Git
            </h3>
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
            <p>
              <span class="company-name">Totalofftec</span>, 19 October 2024 - Present
            </p>
            <ul>
              <li>
                Build new projects and add new features to existing Laravel-based software based on client requirements.
              </li>
              <li>
                Debug and fix issues in existing Laravel applications and provide ongoing client support.
              </li>
              <li>
                Develop, build and maintain RESTful APIs using Laravel Integrate and build frontend features using
                React.js.
              </li>
              <li>
                Collaborate with clients to ensure high-quality, scalable project delivery.
              </li>
            </ul>
          </div>
          <div class="work-experience-item">
            <h3>Jr. Software Developer</h3>
            <p>
              <span class="company-name">Classic IT</span>, 07 November 2023 - 15 October 2024
            </p>
            <ul>
              <li>
                Conduct client meetings to gather and clarify project
                requirements, convert the requirements into actionable project
                ideas and designs.
              </li>
              <li>
                Develop, build, and maintain RESTful APIs using Laravel and
                MySQL to support front-end applications (React, Vue, Flutter).
              </li>
              <li>
                Develop and build front-end applications using Vue.js,
                integrated with Laravel APIs.
              </li>
              <li>
                Identify and resolve bugs and errors in the project, providing
                client support for updates and testing to ensure project
                quality.
              </li>
            </ul>
          </div>
          <div class="work-experience-item">
            <h3>Remote Job</h3>
            <p>Contract Based, July 2023 - October 2023</p>
            <ul>
              <li>
                Gather and clarify project requirements in client meetings,
                converting them into actionable project designs.
              </li>
              <li>
                Create, build, and customize web software using Laravel Blade
                templates.
              </li>
              <li>Develop, build & maintain RESTful APIs for Flutter App.</li>
            </ul>
          </div>
          <div class="work-experience-item">
            <h3>Laravel Developer</h3>
            <p>LinkTech IT, 10 October 2019 - February 2020</p>
            <ul>
              <li>
                Create, develop and maintain dynamic websites using Laravel MVC
                and Blade templates to meet client requirements.
              </li>
              <li>
                Gather and clarify client requirements, convert them into
                actionable designs and identify and resolve bugs, errors in the
                project.
              </li>
            </ul>
          </div>
          <div class="work-experience-item">
            <h3>Internship</h3>
            <p>Codeless Technologies, 3 Months</p>
            <ul>
              <li>Web design & convert PSD to html web page.</li>
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
          <div v-for="project in projects" :key="project.id" class="project-item">
            <!--            <div class="project-image">-->
            <!--              <img :src="project.image" :alt="project.title" />-->
            <!--            </div>-->
            <div class="project-content">
              <h3>{{ project.title }}</h3>
              <p>Technology: {{ project.technology }}</p>
              <ul>
                <li v-for="point in project.key_points" :key="point">
                  {{ point }}
                </li>
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
            <p>American International University Bangladesh (AIUB), 2019</p>
            <p>CGPA: 3.01</p>
            <!-- <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin ac
              libero nec quam aliquet suscipit.
            </p> -->
          </div>

          <div class="education-item">
            <h3>HSC</h3>
            <p>Gurudayal Govt College, 2013</p>
            <p>GPA: 4.10</p>
          </div>

          <div class="education-item">
            <h3>SSC</h3>
            <p>Kishoreganj Govt Boys High School, 2011</p>
            <p>GPA: 4.75</p>
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
            I bring a unique blend of technical expertise and practical
            experience to the table. With a proven track record of delivering
            high-quality projects, I am committed to continuously honing my
            skills and staying up-to-date with the latest industry trends. My
            ability to lead a team and collaborate effectively makes me a
            valuable asset to any organization. Here are some reasons why you
            should consider hiring me:
          </p>
          <ul>
            <li>
              Strong foundation in software development principles and
              practices.
            </li>
            <li>
              Extensive experience in backend development with PHP, Laravel, and MySQL, along with working experience in
              PgSQL.
            </li>

            <li>
              Extensive expertise in developing and implementing highly
              efficient and scalable RESTful APIs.
            </li>
            <li>
              Proficient in JavaScript, including AJAX and jQuery for dynamic
              web development.
            </li>
            <li>Recently learning in frontend development using React.js</li>
            <li>Familiarity with frontend development using Vue.js.</li>
            <li>
              Track record of leading successful projects and delivering on
              time.
            </li>
            <li>
              Committed to continuous learning and professional development.
            </li>
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
        <div class="footer-text"></div>
        <div class="footer-image"></div>
      </div>
    </section>
  </div>
</template>

<script setup>

import './Portfolio.css'

const scrollToSection = (sectionId) => {
  const element = document.getElementById(sectionId);
  if (element) {
    element.scrollIntoView({behavior: "smooth"});
  }
};

const name = "Md. Fahidur Rahim";
const projects = [
  {
    id: 1,
    title: "Naval House Management System (NHAMS)",
    technology: "Laravel, MySQL",
    key_points: [
      "Featured additions and bug fixing using Laravel.",
      "Naval area-wise house allotment, house roster, house change, house extension, transfer, parking, reporting, and system management modules.",
      "HAC (House Allotment Committee) report create, House Vacant Report"
    ],
    link: "http://nhams.kazionline.com",
  },
  {
    id: 2,
    title: "Health Engineering Department (HED)",
    technology: "Laravel, PgSQL, API Integration",
    key_points: [
      "Realtime attendance using fingerprint and facial recognition through API.",
      "Scheduled time tracking for present, absent, and late statuses with in-time and out-time records.",
      "Seamless integration with biometric machines for accurate attendance monitoring."
    ],
    link: "",
  },
  {
    id: 3,
    title: "Timetrack Biometric Attendance Management System",
    technology: "Laravel, MySQL, API Integration",
    key_points: [
      "Realtime attendance using fingerprint and facial recognition through API.",
      "Scheduled time tracking for present, absent, and late statuses with in-time and out-time records.",
      "Seamless integration with biometric machines for accurate attendance monitoring."
    ],
    link: "",
  },
  {
    id: 3,
    title: "Manufacturing Project",
    technology: "VueJs [Frontend], Laravel [Backend]",
    key_points: [
      "Developed and built dynamic frontend using Vue.js & Backend Laravel API",
      "Integrated Vue.js applications with Laravel APIs for seamless backend communication.",
      "Implemented Vue.js 3 Composition API to build interactive interfaces & ensure performance.",
    ],
    link: "https://manufacturing.classicitltd.com",
  },
  {
    id: 4,
    title: "Classic POS",
    technology: "PHP Laravel (API) [ Backend ]",
    key_points: [
      "Develop, build, and maintain RESTful APIs using Laravel and MySQL to support front-end.",
      "Focused on backend logic, providing APIs for seamless integration with the React.js frontend.",
      "Challenging Part: Product Variation, Branch wise stock, sale, accounting, print label, distribution.",
    ],
    link: "https://classic-pos-frontend.classicit.org",
  },
  {
    id: 5,
    title: "Creation EDGE",
    technology: "PHP Laravel (API) [ Backend ]",
    key_points: [
      "Develop, build, and maintain RESTful APIs using Laravel and MySQL to support front-end.",
      "Focused on backend logic, providing APIs for seamless integration with the React.js frontend.",
      "Challenging Part: Pathao Courier Api, Dispatch via Barcode Scanner machine.",
    ],
    link: "https://pos.creationedge.com.bd",
  },
  {
    id: 6,
    title: "Sun Shine Power",
    technology: "PHP Laravel (API) [ Backend ]",
    key_points: [
      "Develop, build, and maintain RESTful APIs using Laravel and MySQL to support front-end.",
      "Focused on backend logic, providing APIs for seamless integration with the React.js frontend.",
      "Challenging Part: Managing the Dealer part aspect while maintaining the client's company requirements.",
    ],
    link: "https://sunsine.classicitltd.com",
  },
  {
    id: 7,
    title: "Porichoy Traders Flutter App",
    technology: "PHP Laravel (API) [ Backend ]",
    key_points: [
      "Develop, build, and maintain RESTful APIs using Laravel and MySQL to support front-end.",
      "Focused on backend logic, providing APIs for seamless integration with the Flutter.js frontend.",
      "Challenging Part: Modifying supplier and customer aspects to meet client's requirements.",
    ],
    link: "https://play.google.com/store/apps/details?id=com.porichoytraders.porichoytraders&hl=en",
  },
  {
    id: 8,
    title: "Wood Machinery (Web & Flutter)",
    technology: "PHP Laravel (API) [ Backend ]",
    key_points: [
      "Modify, and fix bugs with logic, and implement Laravel Blade templates to meet client requirements.",
      "Develop, build, and maintain RESTful APIs using Laravel and MySQL to support front-end.",
      "Providing APIs for seamless integration with the Flutter.js frontend.",
    ],
    link: "https://woodmachinery.com.bd",
  },
];
</script>
