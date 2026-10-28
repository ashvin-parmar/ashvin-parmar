# Ashvin Parmar

### Java Developer | Backend Systems & Framework Engineer

<p align="center">
  <a href="https://drive.google.com/file/d/1y53zLO--8srrA2zT7Uvqup71WzcMuza1/view?usp=drive_link" target="_blank">
    <img src="https://img.shields.io/badge/Resume-4285F4?style=for-the-badge&logo=googledrive&logoColor=white" alt="Resume" />
  </a>
  <a href="https://www.linkedin.com/in/ashvinparmar/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://ashvinparmar.vercel.app/" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" />
  </a>
  <a href="https://leetcode.com/u/ashvinparmar/" target="_blank">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode" />
  </a>
  <a href="mailto:ashwinparmar8181@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <!--
 <a href="tel:+91 6261659781">
    <img src="https://img.shields.io/badge/Phone_No.-brightgreen?style=for-the-badge&logo=phone&logoColor=white" alt="Phone Badge" />
  </a>
  -->
</p>

---

## About Me

Hi there! I am a backend-focused Software Engineer and aspiring **Java Developer** with real-world production internship experience and strong computer science fundamentals.

To truly understand how modern enterprise frameworks work, I designed and built custom frameworks from scratch, including a **Servlet-based MVC framework** (recreating Spring MVC internals) and an **annotation-driven ORM** (recreating Hibernate/JPA mechanics) before moving to Spring Boot and Angular. I enjoy writing clean, maintainable code, solving complex algorithmic challenges, and building reliable backend services that solve real business problems.

- **Current Goal**: Seeking a Java Developer / Backend Software Engineer role where I can contribute to high-quality codebases and collaborate with seasoned engineering teams.
- **Problem Solving**: Solved **450+ problems** on LeetCode with **950+ GitHub contributions** over the past year.
- **Production Experience**: Software Developer Intern at TechZest Global Solutions, working on C++ control plane architecture and order validation for institutional algorithmic trading.

---

## Technical Skills

### Languages
<p align="left">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="SQL" />
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
</p>

### Frameworks & Libraries
<p align="left">
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/Hibernate_/_JPA-59666C?style=for-the-badge&logo=hibernate&logoColor=white" alt="Hibernate" />
  <img src="https://img.shields.io/badge/Java_Servlets-ED8B00?style=for-the-badge&logo=apachetomcat&logoColor=white" alt="Servlets" />
  <img src="https://img.shields.io/badge/JDBC-4479A1?style=for-the-badge&logo=openjdk&logoColor=white" alt="JDBC" />
  <img src="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white" alt="Angular" />
</p>

### Backend & Core Competencies
- **Architecture & Design**: REST APIs, MVC Architecture, Dependency Injection (DI), Front Controller Pattern, Java Reflection API, Annotation Processing
- **Concurrency & Internals**: Multithreading, Concurrency, ThreadLocal Session Management, Connection Pooling, Classpath Scanning
- **Data & CS**: Data Structures and Algorithms (DSA), Object-Oriented Programming (OOP), Relational Schema Design, Query Optimization

### Databases & Developer Tools
<p align="left">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  <img src="https://img.shields.io/badge/Apache_Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white" alt="Maven" />
  <img src="https://img.shields.io/badge/Apache_Tomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=black" alt="Tomcat" />
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" alt="Postman" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
</p>

---

## Highlighted Projects

### 1. WEBRock: Full-Stack Servlet-Based MVC Web Framework
- **Repository**: [Codebase on GitHub](https://github.com/ashvin-parmar/j2ee-webapps/tree/master/webrock)
- **Tech Stack**: Java, Java Servlets, Java Reflection API, Custom Annotations, Apache Tomcat, iText PDF, JavaScript (ES6)
- **What it does**: A lightweight MVC web framework built directly on raw Java Servlets that implements Spring MVC design principles from first principles, eliminating the need for rigid XML configuration.
- **Key Features & Problems Solved**:
  - Implemented a centralized **Front Controller Dispatcher** handling request routing dynamically via custom `@PATH` annotations.
  - Engineered a **recursive classpath scanner** that inspects classes at Tomcat startup to auto-register endpoints, cutting endpoint configuration overhead by 90% without touching `web.xml`.
  - Built multi-scope **`@AutoWired` dependency injection** across Request, Session, and Application scopes, and a declarative `@SecuredAccess` authorization guard that slashed security boilerplate by 80%.
  - Designed an **automated ES6 client SDK generator** using Reflection to introspect Java controller methods and generate Promise-based AJAX client scripts, guaranteeing 100% API contract consistency between frontend and backend.

---

### 2. ORMFM: Custom Object-Relational Mapping (ORM) Engine
- **Repository**: [Codebase on GitHub](https://github.com/ashvin-parmar/j2ee-webapps/tree/master/ormfm/WEB-INF)
- **Tech Stack**: Java, JDBC, Java Reflection API, Custom Annotations, ThreadLocal, MySQL
- **What it does**: A custom persistence framework inspired by Hibernate that simplifies database interactions with dynamic SQL assembly, object-relational mapping, and session isolation.
- **Key Features & Problems Solved**:
  - Created an annotation-based mapping system (`@Table`, `@Column`) paired with a fluent query builder, reducing raw JDBC boilerplate code by ~70%.
  - Designed a **`ThreadLocal`-based session manager** binding exactly one database connection per thread, preventing connection leaks and ensuring strict transaction isolation in concurrent multi-threaded Servlet environments.
  - Built an in-memory **`@Cacheable` LRU cache** backed by `LinkedHashMap`, serving frequent read queries in O(1) time to minimize unnecessary database round-trips.
  - Included a CLI utility (`ORMFMTool`) that uses `DatabaseMetaData` to inspect live database schemas and auto-generate annotated entity POJOs.

---

### 3. ZestAlgo: Institutional Algorithmic Trading Platform (OMS Control Plane)
- **Context**: TechZest Global Solutions (Software Developer Intern | Jul 2025 - Sep 2025)
- **Tech Stack**: Modern C++, Layered Architecture, Concurrency, State Machine Design, Backend Systems
- **What it does**: Core structural control plane and Order Management System (OMS) controller for a high-frequency algorithmic trading platform.
- **Key Features & Problems Solved**:
  - Engineered a decoupled layered architecture in Modern C++ isolating execution management logic from protocol decoders, improving modularity across latency-critical execution pipelines.
  - Designed state-machine order validation rules and robust exception handlers in the OMS controller, eliminating invalid order state transitions during high-throughput execution workflows.

---

## What I Am Currently Learning & Focus Areas

I believe in continuous learning and sharpening my backend engineering toolkit:
- **Microservices Architecture**: Exploring Spring Cloud, API Gateways, Eureka Service Discovery, and event-driven patterns.
- **Docker & Containerization**: Containerizing Java Spring Boot applications and writing multi-service Docker Compose setups.
- **Data Structures & Algorithms**: Consistent problem solving on LeetCode focusing on Dynamic Programming, Graphs, and Trees.
- **Cloud Foundations**: Learning core AWS concepts (EC2, S3, RDS) for deploying and monitoring scalable backend services.

---

## GitHub Stats & LeetCode Progress

<div align="center">

<a href="https://github.com/ashvin-parmar" target="_blank">
  <img src="https://github-readme-stats.vercel.app/api?username=ashvin-parmar&show_icons=true&theme=tokyonight&hide_border=true" width="48%" alt="GitHub Stats" />
</a>
<a href="https://github.com/ashvin-parmar" target="_blank">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ashvin-parmar&theme=tokyonight&layout=compact&langs_count=5&hide_border=true&hide=html,css,cmake" width="37%" alt="Top Languages" />
</a>

<br>

<a href="https://leetcode.com/u/ashvinparmar/" target="_blank">
  <img src="https://leetcard.jacoblin.cool/ashvinparmar?theme=nord&font=Snippet&colors=%231a1b26%2C%23565f89%2C%2C%2C%23c0caf5%2C%2C%2C" width="47%" alt="LeetCode Card" />
</a>

<a href="https://github.com/ashvin-parmar" target="_blank">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=ashvin-parmar&theme=tokyonight&hide_border=true" width="48%" alt="GitHub Streak" />
</a>

</div>

---

## Let's Connect!

I am actively looking for **Junior Java Developer** and **Backend Software Engineer** opportunities. If you are hiring or would like to discuss clean code, Java internals, or system design, please feel free to reach out!

- **Email**: [ashwinparmar8181@gmail.com](mailto:ashwinparmar8181@gmail.com)
- **LinkedIn**: [linkedin.com/in/ashvinparmar](https://www.linkedin.com/in/ashvinparmar/)
- **Portfolio**: [ashvinparmar.vercel.app](https://ashvinparmar.vercel.app/)
- **Resume**: [View on Google Drive](https://drive.google.com/file/d/1y53zLO--8srrA2zT7Uvqup71WzcMuza1/view?usp=drive_link)
- **Location**: Indore, India (Open to on-site and remote roles)
