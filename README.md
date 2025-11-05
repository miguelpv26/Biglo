# Biglo — Full-Stack Logistics Platform (Case Study)

Biglo is a **B2B logistics platform** connecting logistics operators, warehouse owners, and seekers — companies searching for space, storage, or logistics services.  
The platform focuses on providing **secure, ethical, and efficient logistics solutions** through a modern digital experience.

This case study showcases the architecture, technologies, decisions, and optimizations behind Biglo.  
*(Note: The source code is private due to confidentiality.)*

---

## ✅ My Role

I was responsible for **100% of the project**, including:

- Frontend architecture & UI development  
- Backend API & server design  
- Database modeling & optimization  
- Security & authentication layer  
- Deployment & infrastructure  
- Performance optimization (achieved **100/100** Lighthouse)  
- UX design & TailwindCSS component system  
- CI/CD and environment setup  

This was a complete, end-to-end full-stack responsibility.

---

## 🛠️ Tech Stack

### **Frontend**
- Vue.js (Vue 3)
- Pinia (state management)
- TailwindCSS
- TypeScript
- Vite
- Vue Router
- Form validation & sanitization

### **Backend**
- Node.js  
- Express.js  
- MongoDB (Mongoose ORM)  
- JWT Authentication  
- Bcrypt Encryption  
- Role-based access control  

### **Tools & Infrastructure**
- Git & GitHub  
- REST API architecture  
- Deployment on cloud (Node + MongoDB cluster)  
- Reverse proxy  
- CI/CD pipeline  
- Automated builds & environment variables  

---

## 🏗️ System Architecture

         ┌─────────────────────────────┐
         │          Frontend           │
         │  Vue 3 + Vite + Tailwind    │
         └──────────────┬──────────────┘
                        │ REST API
                        ▼
         ┌─────────────────────────────┐
         │          Backend            │
         │    Node.js + Express.js     │
         │  Auth, routing, validation  │
         └──────────────┬──────────────┘
                        │ Mongoose ODM
                        ▼
         ┌─────────────────────────────┐
         │          Database           │
         │          MongoDB            │
         └─────────────────────────────┘

---

## 🔐 Security Features

Biglo required a strong security foundation. Implemented:

- **JWT-based authentication** (access + refresh tokens)
- **Password hashing** using bcrypt
- **CSRF protection**
- **XSS protection**
- **Input validation + sanitization**
- **CORS configuration**
- **HTTPS enforcement**
- **Role-based access (operators, warehouse owners, seekers)**
- **Secure cookies & HTTP-only tokens**
- **npm audit clean — 0 vulnerabilities (secure dependency tree)**

Every sensitive flow was designed with security-first principles.

---

## ⚡ Performance Highlights

Biglo’s frontend was optimized to achieve:

✅ **100 / 100 — Performance**  
✅ **100 / 100 — Accessibility**  
✅ **100 / 100 — Best Practices**  
✅ **100 / 100 — SEO**
✅ **0 axe DevTools issues (Best Practices ON)**

Key optimizations:

- Script & asset minification
- Component-level code splitting
- Lazy-loaded routes
- Image optimization (WebP, compression)
- Caching strategies
- Removing render-blocking assets
- Efficient state management via Pinia
- TailwindCSS-only styling (no CSS bloat)
- Bundled size reduction using Vite optimizations

The goal was a **fast, responsive logistics platform** even under heavy usage.

---

## 📦 Core Features

### **For Logistics Operators**
- Manage available spaces
- Publish logistics services
- Dashboard with metrics & analytics
- Request management & communication

### **For Warehouse Owners**
- Register and configure warehouses
- Availability calendar
- Pricing and inventory tools
- Secure document handling

### **For Seekers (Companies Searching for Space)**
- Discover logistics operators
- Explore and filter warehouses
- Request services or capacity
- Track request status

### **General Platform Features**
- Authentication & user roles  
- Secure request workflows  
- Admin oversight capabilities  
- Modern dashboard UI  
- Real-time updates (where allowed)  
- Fully responsive layout  
- Accessible UI (WCAG-friendly)

---

## 🧪 Development & Architecture Decisions

### **1. Vue + Pinia**
Chosen for:
- Clean component-driven architecture  
- Predictable state management  
- Reusable UI patterns  
- High performance with Vite  

### **2. Node + Express**
Chose backend simplicity and scalability:
- REST endpoints  
- Middleware-based security  
- Consistent validation layer  

### **3. MongoDB**
Ideal for:
- Flexible data structures  
- Fast queries for logistics data  
- Scalable cloud cluster  

### **4. TailwindCSS**
Used for:
- Design consistency  
- Rapid UI iteration  
- Zero unused CSS via JIT mode  

### **5. Deployment & Cloud Infrastructure Management**
Configured and managed the platform’s deployment pipeline using modern cloud services:
- **Vercel** for frontend hosting  
- **Firebase** for authentication and supporting services  
- **Google Cloud Run** for containerized backend deployment  
- **Google Artifact Registry** for container storage  
- Environment variable & secret management  
- Automated builds and deployments

---

## 📸 Screenshots

Below are selected UI and performance screenshots from the platform.  
All screenshots avoid exposing confidential business data.

![Landing Page](/assets/screenshots/landing-page.png)
![Mission Section](/assets/screenshots/our-mission-section.png)
![Logo Carousel](/assets/screenshots/logo-carousel.gif)
![Sign Up](/assets/screenshots/sign-up.gif)
![Spaces Map Search Grid](/assets/screenshots/spaces-map-search-grid.png)
![Spaces Map Search List](/assets/screenshots/spaces-map-search-list.png)
![LightHouse Metrics Perfect Score](/assets/screenshots/lighthouse-perfect-score.png)
![axe DevTools 0 Issues](/assets/screenshots/axe-devtools-0-issues.png)
![npm audit 0 Vulnerabilities](/assets/screenshots/npm-audit-0-vulnerabilities.png)
![Head Optimization](/assets/screenshots/head-optimization.png)
![AI Overview](/assets/screenshots/ai-overview.png)

---
 
## 📚 What I Learned

- Architecting a full-stack application end-to-end  
- Improving security in production-ready systems  
- Designing scalable database models  
- Achieving perfect Lighthouse scores  
- Managing deployment pipelines  
- Building modern UI systems with Tailwind + Vue  
- Balancing UX, performance, and technical constraints  

Biglo was a full-stack challenge that strengthened both my front-end and back-end expertise while reinforcing performance-driven development.

---

## ✅ Summary

Biglo is a fully developed **B2B logistics platform** built with a focus on performance, security, reliability, and modern UI/UX.  
It demonstrates my capability to deliver a **complete, production-ready, secure, and scalable full-stack application** as a solo developer.

*(This repo is a case study only — source code remains private for confidentiality.)*
