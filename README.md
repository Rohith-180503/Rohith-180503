# 👋 Welcome to My GitHub

**Full-Stack Developer | Game Developer | Problem Solver**

Building scalable web applications, engaging interactive experiences, and robust backend systems with modern technologies.

---

## 🚀 About Me

I'm a versatile developer specializing in full-stack development, game engineering, and task management systems. I combine clean architecture principles with modern frameworks to build production-ready applications that solve real-world problems. Experienced with both relational and NoSQL databases for diverse data modeling scenarios.

---

## 💻 Tech Stack & Skills

### **Frontend Development**
![HTML5](https://img.shields.io/badge/HTML5-E34C26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

### **Backend Development**
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8936?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)

### **Databases & Data Persistence**
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![H2 Database](https://img.shields.io/badge/H2_Database-0066CC?style=for-the-badge&logo=database&logoColor=white)
![Spring Data JPA](https://img.shields.io/badge/Spring_Data_JPA-6DB33F?style=for-the-badge&logo=spring&logoColor=white)

### **Authentication & Security**
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=json-web-tokens&logoColor=white)
![Bcrypt](https://img.shields.io/badge/Bcrypt-Security-blue?style=for-the-badge)

### **Payment & Third-Party Integration**
![Stripe](https://img.shields.io/badge/Stripe-008CDD?style=for-the-badge&logo=stripe&logoColor=white)

### **Build & Deployment Tools**
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apache-maven&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

### **Development Methodologies**
- **REST API Design** - Clean, scalable endpoints with proper HTTP semantics
- **Component Architecture** - Modular, reusable UI components
- **State Management** - Context API, cookie-based sessions, JWT authentication
- **Responsive Design** - Mobile-first approach with CSS media queries
- **Game Development** - Physics simulation, collision detection, sprite animations
- **Database Design** - Relational (MySQL) and NoSQL (MongoDB) schema modeling for diverse use cases

---

## 🎯 Featured Projects

### 🎓 [LearnHub](https://github.com/Rohith-180503/LEARNHUB) – Full-Stack Education Platform
**Live:** https://learnhub-wine.vercel.app

A production-grade online learning ecosystem featuring dynamic course delivery, secure authentication, and integrated payment processing.

**Tech Stack:** React 19 • Vite • Node.js • Express.js • MySQL • MongoDB • SQLite • JWT • Stripe

**Core Engineering Problems Solved:**
- **Stateless Authentication**: Implemented httpOnly JWT cookies to prevent XSS attacks while maintaining secure session management
- **Real-Time Progress Tracking**: Course completion data persists across sessions with seamless synchronization using relational database integrity
- **Payment Integration**: Integrated Stripe Checkout with webhook-based automation for frictionless course purchases
- **Global State Management**: Built Context API architecture to manage Auth and Cart states without prop drilling
- **Full Curriculum Architecture**: Designed hierarchical data model (Courses → Modules → Lessons) with efficient querying across relational and NoSQL stores
- **Polyglot Persistence**: Leveraged MySQL for transactional consistency and MongoDB for flexible document storage of course metadata

**Key Features:**
- 44+ curated courses with complete curriculum mapping
- User enrollment tracking and progress persistence
- Secure cart synchronization across devices
- Professional payment workflow with Stripe
- JWT-based secure session management
- Multi-database support for optimal data storage patterns

---

### 🐉 [Dragon Dash Game](https://github.com/Rohith-180503/DRAGON-DASH-GAME) – Endless Runner Game
**Live:** https://dragon-dash-game.vercel.app

An interactive endless runner game featuring advanced physics, sprite-based animation, and particle effects—built entirely with vanilla JavaScript.

**Tech Stack:** JavaScript (ES6+) • HTML5 • CSS3 • Web Audio API

**Core Engineering Problems Solved:**
- **Game Physics Engine**: Implemented gravity-based jumping mechanics with frame-perfect collision detection using bounding box algorithms
- **Sprite Animation Pipeline**: Built automated sprite frame sequencing using CSS keyframe calculations for smooth character and obstacle animations
- **Parallax Scrolling**: Layered background rendering with variable speeds for immersive visual depth perception
- **Audio Synthesis**: Created procedural sound effects using Web Audio API (jump sounds, level-ups, game-over audio)
- **Responsive Game Controls**: Dual input system supporting keyboard (desktop) and touch buttons (mobile)
- **High Score Persistence**: LocalStorage-based leaderboard system with client-side data management

**Key Features:**
- Endless obstacle spawning with progressive difficulty scaling
- Multi-directional player movement (left, right, jump, duck)
- Dynamic level progression with increasing game speed
- Visual feedback via screen shake and particle effects
- Mobile-friendly touch controls
- Persistent high score tracking

---

### ✅ [TaskFlow](https://github.com/Rohith-180503/TaskFlow) – Full-Stack Task Management
**Live:** https://todo-list-app-gray-iota.vercel.app

An enterprise-grade task management application demonstrating clean architecture, RESTful API design, and modern Spring Boot practices.

**Tech Stack:** Java 17 • Spring Boot 3.3 • Spring Data JPA • MySQL • H2 Database • Maven • Docker

**Core Engineering Problems Solved:**
- **Layered Architecture**: Implemented clean separation of concerns (Controller → Service → Repository) for maintainability and testability
- **Data Validation**: Added Bean Validation annotations for input sanitization and business rule enforcement
- **Exception Handling**: Centralized error handling with structured error responses and meaningful HTTP status codes
- **Database Persistence**: Utilized Spring Data JPA with MySQL for relational data integrity and H2 for in-memory testing with production-ready patterns
- **REST API Design**: RESTful endpoints with proper CRUD operations and query parameters for filtering/sorting
- **Frontend Integration**: Responsive HTML/CSS/JavaScript UI seamlessly communicating with backend via REST

**Key Features:**
- Complete CRUD operations for task management
- Priority-based filtering and sorting
- Task completion tracking with statistics
- Light/dark theme toggle
- RESTful API with structured error responses
- MySQL persistence with relational integrity
- Containerized deployment with Docker

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Rohith-180503&show_icons=true&theme=dark" alt="GitHub Stats" />
</div>

---

## 🔗 Let's Connect

- **GitHub**: [@Rohith-180503](https://github.com/Rohith-180503)
- **Email**: Open to opportunities and collaborations

---

## 🎓 Key Competencies

✅ **Full-Stack Architecture** - Frontend-to-database integration  
✅ **RESTful API Design** - Clean, scalable endpoint design  
✅ **Game Development** - Physics engines, collision detection, animations  
✅ **Security** - JWT auth, password hashing, XSS prevention  
✅ **State Management** - Context API, session persistence, real-time sync  
✅ **Database Design** - Relational (MySQL) and NoSQL (MongoDB) schema modeling  
✅ **Polyglot Persistence** - Choosing optimal data stores for different use cases  
✅ **Responsive UI/UX** - Mobile-first design, accessibility considerations  
✅ **DevOps & Deployment** - Docker, Vercel, environment configuration  

---

<div align="center">

**Transforming ideas into scalable, user-friendly software solutions** 🚀

</div>
