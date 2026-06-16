# akhilsai-portfolio
My Java Full Stack Developer Portfolio
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Akhilsai Anumolu | Java Full Stack Developer</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f5f7fb;
      color: #1f2937;
      line-height: 1.6;
    }
    header {
      background: #111827;
      color: white;
      padding: 50px 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 36px;
    }
    header p {
      margin: 10px 0;
      font-size: 18px;
    }
    .container {
      max-width: 1000px;
      margin: auto;
      padding: 30px 20px;
    }
    section {
      background: white;
      margin-bottom: 24px;
      padding: 28px;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.06);
    }
    h2 {
      color: #111827;
      border-bottom: 2px solid #e5e7eb;
      padding-bottom: 8px;
    }
    .skills span {
      display: inline-block;
      background: #e5e7eb;
      padding: 8px 12px;
      margin: 6px;
      border-radius: 20px;
      font-size: 14px;
    }
    .project {
      margin-bottom: 20px;
    }
    .project h3 {
      margin-bottom: 6px;
      color: #1d4ed8;
    }
    ul {
      padding-left: 22px;
    }
    .contact a {
      color: #2563eb;
      text-decoration: none;
      font-weight: bold;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #111827;
      color: white;
    }
  </style>
</head>
<body>

<header>
  <h1>Akhilsai Anumolu</h1>
  <p>Java Full Stack Developer | Spring Boot | Microservices | AWS | Azure</p>
  <p>Raleigh, NC | 660-528-9074 | akhilsaianumolu14@gmail.com</p>
</header>

<div class="container">

  <section>
    <h2>About Me</h2>
    <p>
      I am a Java Full Stack Developer with hands-on experience building backend services,
      REST APIs, microservices, and full-stack applications using Java, Spring Boot,
      React, Angular, Kafka, Docker, AWS, and Azure. I focus on writing clean backend logic,
      building scalable APIs, integrating frontend applications, and supporting enterprise
      application development.
    </p>
  </section>

  <section>
    <h2>Technical Skills</h2>
    <div class="skills">
      <span>Java</span><span>Java 21</span><span>Spring Boot</span><span>REST APIs</span>
      <span>Microservices</span><span>Kafka</span><span>JMS</span><span>JWT</span>
      <span>OAuth2</span><span>Spring Security</span><span>React</span><span>Angular</span>
      <span>JavaScript</span><span>Axios</span><span>HttpClient</span><span>Docker</span>
      <span>AWS ECS</span><span>Azure AKS</span><span>WebLogic</span><span>JPA</span>
      <span>Hibernate</span><span>Postman</span><span>JUnit</span><span>Maven</span>
      <span>Jenkins</span><span>SQL</span>
    </div>
  </section>

  <section>
    <h2>Featured Projects</h2>

    <div class="project">
      <h3>Insurance Claims & Policy Backend System</h3>
      <p>
        Built backend services for an insurance platform using Java 21, Spring Boot,
        REST APIs, Kafka, Docker, AWS ECS, JWT, and WebLogic.
      </p>
      <ul>
        <li>Developed REST APIs for claims, policy, and billing workflows.</li>
        <li>Used Kafka producer and consumer logic for asynchronous communication.</li>
        <li>Containerized services using Docker and deployed them on AWS ECS.</li>
        <li>Implemented JWT token validation, expiration handling, and refresh-token flow.</li>
        <li>Configured WebLogic server instances and load balancing for microservice traffic.</li>
      </ul>
    </div>

    <div class="project">
      <h3>Enterprise Messaging & Angular Application</h3>
      <p>
        Developed enterprise backend components using Spring Boot, JMS, Angular,
        Docker, and Azure Kubernetes Service.
      </p>
      <ul>
        <li>Built RESTful services in Spring Boot and consumed them from Angular using HttpClient.</li>
        <li>Implemented JMS messaging for reliable communication between distributed services.</li>
        <li>Containerized Java applications with Docker and deployed them on Azure AKS.</li>
        <li>Worked on secure backend components and application integration flows.</li>
      </ul>
    </div>

    <div class="project">
      <h3>Full Stack Java Application</h3>
      <p>
        Created a full-stack application using Spring Boot backend services and React frontend.
      </p>
      <ul>
        <li>Designed REST endpoints for frontend integration.</li>
        <li>Connected React UI with backend APIs using Axios.</li>
        <li>Validated API behavior using Postman and handled error scenarios.</li>
        <li>Improved application performance using caching strategies.</li>
      </ul>
    </div>
  </section>

  <section>
    <h2>Experience Summary</h2>
    <p>
      My experience is focused on backend Java development, API development,
      microservices, cloud deployment, messaging systems, authentication, and frontend
      integration. I have worked with enterprise tools such as WebLogic, Kafka, JMS,
      Docker, AWS ECS, Azure AKS, JPA/Hibernate, and CI/CD pipelines.
    </p>
  </section>

  <section>
    <h2>Education</h2>
    <p><strong>Master of Science in Information Systems</strong><br>
    Northwest Missouri State University, USA</p>
    <p><strong>Bachelor of Technology in Electronics and Communication Engineering</strong><br>
    MLR Institute of Technology, India</p>
  </section>

  <section class="contact">
    <h2>Contact</h2>
    <p>Email: <a href="mailto:akhilsaianumolu14@gmail.com">akhilsaianumolu14@gmail.com</a></p>
    <p>Phone: 660-528-9074</p>
    <p>LinkedIn: Add your LinkedIn URL here</p>
    <p>GitHub: Add your GitHub URL here</p>
  </section>

</div>

<footer>
  <p>© 2026 Akhilsai Anumolu</p>
</footer>

</body>
</html>
"""

path = Path("/mnt/data/akhilsai_portfolio.html")
path.write_text(html, encoding="utf-8")
path.as_posix()
