# Product Requirements Document — Kathan Shah's Portfolio

## 1. Overview

A modern, lightning-fast portfolio website built as a single HTML file with embedded CSS and vanilla JavaScript. Showcases Computer Science expertise with a focus on AI, full-stack development, and machine learning projects. The portfolio demonstrates technical depth through real projects, experience, and proven skills to attract SWE internship opportunities and technical collaborators.

**Key Approach:** Single-file simplicity inspired by Hershal Patel's portfolio. No build process, no dependencies, no complex frameworks. Just pure HTML, CSS, and JavaScript deployed directly to GitHub Pages or Vercel.

---

## 2. Target Users

- **Recruiters & Hiring Managers** — Looking for CS interns and junior developers with AI/ML experience
- **Potential Collaborators** — Other engineers interested in technical projects
- **Professors/Mentors** — Academic advisors reviewing student portfolio
- **Technical Interviewers** — Background research before technical interviews

---

## 3. Core Features

### 3.1 Hero Section
- **Headline:** "Crafting intelligent systems"
- **Subheading:** CS student at Clemson with AI & Finance minors building full-stack applications
- **CTAs:** GitHub profile link, Email contact
- **Impact:** Immediate clarity on who you are and what you do

### 3.2 About Me Section
- **Personal Story:** First-generation student from Union, SC
- **Education:** CS Major with AI Minor at Clemson University
- **Developer Profile:** Passionate about building systems that scale. Focused on shipping code that works—whether optimizing backend systems, training ML models, or building full-stack applications
- **Interests:** Gaming, anime, watching movies, relaxing at cafes. Curious about everything, always learning
- **Philosophy:** Best developers are well-rounded. Know when to step away and recharge
- **Key Stats:** 4.0 GPA, Available for SWE Internships

### 3.3 Experience Section
- **Registrar's Assistant** (Sep 2024 - Nov 2025)
  - Company: Tri County Technical College
  - Key achievements: 100% accuracy on 5,000+ records, 35% faster document retrieval, 78% error reduction
  - Demonstrates: Attention to detail, systems thinking, process optimization

### 3.4 Projects Section (Featured 4 Projects)

#### Project 1: CodeMentor AI
- **Type:** Full-stack AI application
- **Description:** Real-time intelligent code explanation engine supporting 11 programming languages. Uses intelligent LLM routing to select the best model for each code snippet. Features Monaco Editor for syntax highlighting, TiDB database for persistent storage, and SSE streaming for live explanations
- **Tech Stack:** FastAPI, LLM Routing, Monaco Editor, TiDB, SSE
- **Key Features:** 
  - Context-aware explanations for complex codebases
  - Multi-model LLM selection based on code type
  - Persistent chat history and explanations
  - Real-time streaming responses
- **Links:** GitHub, Live Demo

#### Project 2: FinPulse
- **Type:** Full-stack ML-powered analytics platform
- **Description:** Financial analytics platform combining high-performance data processing with ML predictions. Built C++17 backend for real-time market data ingestion. Implemented RandomForest and IsolationForest models for price prediction and anomaly detection. Full-stack application with Next.js dashboard and REST API
- **Tech Stack:** C++17 (backend), Python (ML), Next.js (frontend), TiDB
- **Key Features:** 
  - High-performance data ingestion engine
  - Real-time ML inference pipeline
  - Interactive dashboard with live charts
  - Anomaly detection for market volatility
  - REST API for data access
- **Links:** GitHub, Live Demo

#### Project 3: CUTRACKIT
- **Type:** Real-time sports check-in backend (48-hour hackathon)
- **Description:** Robust check-in system built for live event. Implemented secure QR code generation and real-time validation. Designed JWT authentication with bcrypt for security. Optimized database connection pooling for high concurrency. Proven reliability in production use
- **Tech Stack:** Flask, JWT Auth, PostgreSQL, QR Code generation
- **Key Features:** 
  - QR code generation and real-time validation
  - Secure JWT authentication with bcrypt hashing
  - Database connection pooling for scalability
  - Handled 50+ concurrent users
  - Sub-100ms response times
  - 99% uptime during live events
- **Links:** GitHub, Live Demo

#### Project 4: Basketball Analytics System
- **Type:** High-performance event processing engine
- **Description:** C++ system engineered for processing 500+ game events efficiently. Implemented polymorphic inheritance hierarchy for different event types. Used custom data structures (dynamic arrays, linked lists) for optimal performance. Demonstrates strong systems design and memory optimization skills
- **Tech Stack:** C++17, Data Structures, OOP Design, Memory Optimization
- **Key Features:** 
  - Polymorphic event type handling
  - Custom data structure implementation
  - 35% reduction in peak heap memory usage
  - Fast event queries and aggregation
  - Real-time analytics capability
- **Links:** GitHub

### 3.5 Technical Skills Section
- **Languages:** Java, Python, C/C++, SQL
- **Frameworks:** FastAPI, Flask, SQLAlchemy
- **Tools:** Git, GitHub, VS Code, TiDB, Supabase
- **Platforms:** Vercel, Render, Docker

### 3.6 Contact Section
- **Email:** Direct contact link
- **GitHub:** Profile link showing all projects
- **LinkedIn:** Professional network connection

## Built With
- **Single HTML File:** All code in one `index.html` (easily customizable)
- **Embedded CSS:** Responsive design with media queries for all devices
- **Vanilla JavaScript:** Smooth scrolling, nav effects, no frameworks
- **No Dependencies:** Zero npm packages, instant loading

---

## 4. Goals

### Primary Goals
1. **Attract Internship Opportunities** — Demonstrate CS + AI competency to recruiters
2. **Showcase Technical Depth** — Display real, deployed projects with live demos
3. **Communicate Personal Brand** — Show combination of technical rigor and creative thinking
4. **Enable Easy Contact** — Make it simple for recruiters/collaborators to reach out

### Secondary Goals
1. Build credibility through 4.0 GPA and Clemson affiliation
2. Demonstrate first-generation achievement
3. Show diverse technical experience (backend, ML, full-stack, systems)
4. Provide proof points for each claim (live demos, GitHub repos)

---

## 5. Success Metrics

| Metric | Target | How to Measure |
|--------|--------|---|
| **Page Load Time** | < 2 seconds | Google PageSpeed Insights, DevTools |
| **Mobile Responsiveness** | 100% | Test on iOS/Android browsers |
| **GitHub Repo Visits** | +50% from portfolio traffic | GitHub analytics |
| **Email Inquiries** | +5 from portfolio link | Track clicks, count emails |
| **Interview Callbacks** | +3 internship interviews | Personal tracking |
| **Time to First Meaningful Paint** | < 1.2 seconds | Core Web Vitals |
| **Bounce Rate** | < 30% | Vercel/Plausible analytics |
| **Project Demo Engagement** | +20 demo clicks/month | Click tracking |

---

## 6. Non-Goals

- ❌ No blog or long-form content (keep focus on projects)
- ❌ No testimonials or third-party validation (just facts and code)
- ❌ No dark mode toggle (single optimized dark theme)
- ❌ No animations beyond subtle transitions (performance focus)
- ❌ No ecommerce or monetization

---

## 7. User Stories

### User Story 1: Recruiter Background Check
**As a** recruiter screening engineering interns,  
**I want to** quickly understand Kathan's technical depth and experience,  
**So that** I can decide if they're worth scheduling for a technical interview.

**Acceptance Criteria:**
- ✅ Can view 4+ real projects with descriptions in < 30 seconds
- ✅ Can access GitHub repos and live demos directly
- ✅ Can see GPA and Clemson affiliation
- ✅ Can find email to schedule interview

### User Story 2: Technical Interview Prep
**As a** technical interviewer preparing to interview Kathan,  
**I want to** see what projects they've built and understand their technical approach,  
**So that** I can prepare relevant technical questions.

**Acceptance Criteria:**
- ✅ Can access full project descriptions
- ✅ Can review code on GitHub
- ✅ Can see tech stack choices and why they matter
- ✅ Can view live demos of working applications

### User Story 3: Potential Collaborator
**As a** fellow engineer interested in collaborating,  
**I want to** understand Kathan's interests and current work,  
**So that** I can propose relevant projects or contributions.

**Acceptance Criteria:**
- ✅ Can see Kathan's interests (ML, full-stack, systems design)
- ✅ Can easily find email or LinkedIn
- ✅ Can view GitHub repos to understand coding style
- ✅ Can see what technologies they're actively using

---

## 8. Constraints & Assumptions

### Constraints
- Must deploy to Vercel (free tier)
- Must be mobile-responsive (60% of traffic from mobile)
- Max page size: 500KB (performance priority)
- No authentication needed (public portfolio)

### Assumptions
- Visitors spend < 2 minutes on site (recruiters are busy)
- Most visitors come from Google, LinkedIn, or GitHub
- Mobile visitors should have same experience as desktop
- GitHub links are the main "proof" of technical ability

---

## 9. Future Enhancements (Out of Scope)

- Blog posts on technical topics
- Case studies for each major project
- Video walkthroughs of projects
- Newsletter signup
- Dark/light theme toggle
- Internationalization (other languages)

---

## 10. Acceptance Criteria (Complete Portfolio)

- ✅ All 4 projects have descriptions, tech tags, and links to GitHub + demos
- ✅ About section mentions: first-gen, Clemson, AI minor, interests
- ✅ Contact section has email, GitHub, LinkedIn links (all working)
- ✅ Site loads in < 2 seconds on 4G connection
- ✅ Mobile responsive (tested on iPhone + Android)
- ✅ GitHub repo includes README, proper folder structure, .gitignore
- ✅ Deployed to Vercel with custom domain (optional: kathan.dev)
- ✅ Analytics enabled (Vercel built-in or Plausible)
- ✅ No broken links or 404s
- ✅ SEO basics: title, meta description, OG tags

---

## 11. Release Plan

**Phase 1 (This Week):** Design & Development
- Finalize design in code
- Implement all sections
- Connect project links and GitHub

**Phase 2 (Next Week):** Testing & Polish
- Test on mobile devices
- Performance optimization
- Accessibility audit

**Phase 3 (Week 3):** Launch
- Deploy to Vercel
- Share on LinkedIn & Twitter
- Send to mentors/professors for feedback
