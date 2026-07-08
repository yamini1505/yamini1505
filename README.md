<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Yamini Nagothu | Portfolio</title>
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@400;600;700&display=swap" rel="stylesheet" />
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />
  <link rel="stylesheet" href="https://unpkg.com/aos@2.3.1/dist/aos.css" />
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <nav class="navbar">
      <div class="logo">Yamini</div>
      <ul class="nav-links">
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#experience">Experience</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#resume">Resume</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="home" class="hero" data-aos="fade-up">
    <div class="hero-content hero-row">
      <div class="hero-img">
        <img src="userx.png" alt="Yamini Nagothu" />
      </div>
      <div class="hero-text">
        <h1>Hey I'm <span>Yamini Nagothu</span></h1>
        <h2>Computer Science Student | Full Stack Developer</h2>
        <p>Passionate about full stack web development, AI/ML, and building intelligent systems. Currently pursuing B.Tech in Computer Science and Engineering at SRM AP University.</p>
        <div class="social-icons">
          <a href="https://github.com/yamini1505" target="_blank"><i class="fab fa-github"></i></a>
          <a href="https://linkedin.com/in/yamini-nagothu-28b264291" target="_blank"><i class="fab fa-linkedin"></i></a>
          <a href="mailto:nagothuyamini4848@gmail.com"><i class="fab fa-envelope"></i></a>
        </div>
        <a href="#resume" class="btn">Download CV</a>
      </div>
    </div>
  </section>

  <section id="about" data-aos="fade-up">
    <div class="container">
      <h2>About Me</h2>
      <p>I'm Yamini Nagothu, a Computer Science Engineering student at SRM AP University. I love building full stack web applications and exploring AI/ML systems, from real-time chat apps to neural-symbolic reverse engineering pipelines.</p>
      <div class="about-cards">
        <div class="card">Studying at SRM AP University</div>
        <div class="card">B.Tech CSE | CGPA: 8.01</div>
        <div class="card">Graduation Year - 2027</div>
      </div>
    </div>
  </section>

  <section id="skills" class="skills" data-aos="fade-up">
    <h2>Skills</h2>
    <div class="skill-cards">
      <div class="card">Python</div>
      <div class="card">C</div>
      <div class="card">C++</div>
      <div class="card">JavaScript</div>
      <div class="card">TypeScript</div>
      <div class="card">SQL</div>
      <div class="card">React.js</div>
      <div class="card">Node.js</div>
      <div class="card">Express.js</div>
      <div class="card">MongoDB</div>
      <div class="card">Git & GitHub</div>
      <div class="card">Vercel</div>
      <div class="card">Render</div>
      <div class="card">Data Structures & Algorithms</div>
    </div>
  </section>

  <section id="experience" class="experience" data-aos="fade-up">
    <h2>Work Experience</h2>
    <div class="experience-list">
      <div class="card">
        <h3>Intern — Edunet Foundation</h3>
        <p class="exp-year">2025</p>
        <p>Developed a real-time chat application using the MERN stack with secure JWT authentication. Integrated Socket.IO for instant messaging and designed RESTful APIs with MongoDB schema modeling.</p>
      </div>
      <div class="card">
        <h3>Research Intern (Faculty Guided) — SRM AP University</h3>
        <p class="exp-year">2025</p>
        <p>Worked on an AI-based multilingual transcription system for law enforcement. Implemented NLP pipelines for automated summarization and structured report generation.</p>
      </div>
    </div>
  </section>

  <section id="projects" class="projects" data-aos="fade-up">
    <h2>Projects</h2>
    <div class="project-filters">
      <button onclick="filterProjects('all')">All</button>
      <button onclick="filterProjects('ai')">AI/ML</button>
      <button onclick="filterProjects('web')">Web</button>
      <button onclick="filterProjects('security')">Security</button>
    </div>
    <div class="project-list">
      <div class="project-card ai security">
        <h3>Source Retrieval Using Transformers and Project-Aware Agent</h3>
        <p>AI-powered neural-symbolic reverse engineering system using Python, Ghidra, and Transformer-based LLMs to recover human-readable source code from compiled binaries. Multi-agent pipeline achieving a 91% compilation success rate.</p>
      </div>
      <div class="project-card ai security">
        <h3>Machine Learning for Security in Vehicular Networks</h3>
        <p>ML-based system to identify and detect security threats in smart vehicle networks, improving communication security by analyzing DDoS, Sybil, and spoofing attacks.</p>
      </div>
      <div class="project-card ai web">
        <h3>Sentiment Analysis System</h3>
        <p>ML-based sentiment classifier using Amazon, IMDB, and Yelp datasets with SVM, ANN, and Random Forest models. Deployed as a real-time Streamlit web app.</p>
      </div>
    </div>
  </section>

  <section id="certifications" class="certifications" data-aos="fade-up">
    <h2>Certifications</h2>
    <div class="cert-list">
      <div class="card">Edunet Foundation Full Stack Web Development Internship Certificate</div>
      <div class="card">Oracle Java Programming Certification</div>
      <div class="card">MongoDB Certification</div>
    </div>
  </section>

  <section id="resume" data-aos="fade-up">
    <h2>Resume</h2>
    <p>Download my latest CV here to know more about my academic background and experiences.</p>
    <a href="Yamini_Nagothu_CV.pdf" download class="btn">Download CV</a>
  </section>

  <section id="contact" data-aos="fade-up">
    <h2>Contact Me</h2>
    <form id="contactForm">
      <input type="text" name="name" placeholder="Your Name" required />
      <input type="email" name="email" placeholder="Your Email" required />
      <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
      <button type="submit" class="btn">Send Message</button>
    </form>
    <p>Email: <a href="mailto:nagothuyamini4848@gmail.com">nagothuyamini4848@gmail.com</a></p>
    <p>Phone: <a href="tel:9000217196">9000217196</a></p>
  </section>

  <footer>
    <p>© 2025 Yamini Nagothu. All rights reserved.</p>
  </footer>

  <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
  <script>
    AOS.init();

    function filterProjects(category) {
      const projects = document.querySelectorAll('.project-card');
      projects.forEach(project => {
        if (category === 'all' || project.classList.contains(category)) {
          project.style.display = 'block';
        } else {
          project.style.display = 'none';
        }
      });
    }

    document.getElementById('contactForm').addEventListener('submit', function(e) {
      e.preventDefault();
      alert('Thank you for your message!');
      this.reset();
    });
  </script>
</body>
</html>
