# Arham Topiwala — Full Stack Developer Portfolio

A minimal, responsive personal portfolio for **Arham Topiwala**, focused on full-stack web development, RESTful APIs, AI/LLM integrations, responsive UI engineering, automation, and performance optimization.

The portfolio is intentionally built with a clean, content-first visual system rather than a heavy framework or large component library. It is suitable for GitHub, recruiter review, personal branding, and deployment as a lightweight static website.

---

## ✦ Overview

This portfolio presents:

- Professional profile and introduction
- Full-stack development experience
- Academic background
- Technical skills grouped by discipline
- Engineering and AI-focused highlights
- Selected development projects
- Direct contact and social links
- Responsive mobile navigation
- Light / dark theme switching
- Live India Standard Time clock
- Expandable work-experience details
- Minimal profile image presentation
- Mobile-first responsive behavior

---

## 👨‍💻 About

**Arham Topiwala** is a Full Stack Web Developer based in Ahmedabad, Gujarat.

The portfolio focuses on practical software engineering capabilities across:

- Front-end development
- Back-end engineering
- RESTful API integration
- AI and LLM API integration
- Database systems
- Web performance
- Data processing and automation
- Deployment workflows
- Responsive UI engineering

### Professional profile

> Full Stack Web Developer | Scalable Applications | RESTful API Integrations | Performance Optimization

---

## 🧰 Technology Stack

The portfolio itself is intentionally lightweight.

### Core

- HTML5
- CSS3
- Vanilla JavaScript

### UI

- Responsive CSS
- CSS Grid
- Flexbox
- CSS custom properties
- Minimal card-based design system
- Lucide Icons

### External dependency

The interface loads Lucide Icons through its CDN:

```html
<script src="https://unpkg.com/lucide@latest"></script>
```

No npm installation is required for the standalone version.

---

## 📁 Project Structure

```text
Arham-Portfolio/
│
├── index.html       # Main portfolio page
├── styles.css       # Complete visual system and responsive styles
├── script.js        # Interactions, theme, clock and dynamic skills
├── pfp.jpeg         # Profile image
└── README.md        # Project documentation
```

---

## 🖥️ Main Sections

### 1. Hero

The hero section introduces:

- Name
- Full-stack developer profile
- Location
- Current India time
- Profile image
- Availability status

The profile image uses the supplied black-and-white portrait.

---

### 2. About

A concise professional summary covering full-stack development, RESTful API integration, responsive UI engineering, performance optimization, and data systems.

---

### 3. Work Experience

The experience section contains three professional roles:

#### ICAT Internship Studio
**Web Design and Development Intern**

October 2025 – February 2026

Focus areas include:

- Responsive web interfaces
- JavaScript and React
- RESTful API layers
- Image optimization
- Code splitting
- Accessibility
- Security standards
- Agile collaboration

#### Injala Pvt. Ltd
**Data Management & Systems Specialist (Contract)**

July 2025 – October 2025

Focus areas include:

- Data ingestion
- Automated validation
- Data cleansing
- Enterprise data verification
- Technical documentation
- Operational reporting

#### Genuine Bags
**E-Commerce Operations & Digital Platforms Specialist**

June 2024 – July 2025

Focus areas include:

- Product catalog management
- Inventory synchronization
- Digital order workflows
- Metadata architecture
- Marketplace content
- Operational automation

Each experience card can be expanded to reveal additional details.

---

## 🎓 Education

### L. J. University

**Bachelor of Science in Information Technology (BSc IT)**

2023 – 2026  
Ahmedabad, India

### A. G. HIGH SCHOOL

**12th Commerce**

2022 – 2023

The education cards use the same compact visual language as the experience section.

---

## 🧠 Skills

Skills are generated dynamically through JavaScript and organized into technical groups.

### Programming Languages

- JavaScript (ES6+)
- TypeScript
- HTML5
- CSS3
- Python
- SQL

### Front-End Development

- React.js
- Next.js
- Tailwind CSS
- Bootstrap
- DOM Manipulation
- Single Page Applications

### Back-End Engineering

- Node.js
- Express.js
- RESTful APIs
- Microservices Architecture
- Server-Side Logic

### Database Management

- MySQL
- PostgreSQL
- MongoDB
- Database Schema Design
- Query Optimization

### AI & Machine Learning Integration

- LLM API Integration
- OpenAI APIs
- Prompt Engineering
- Automated Data Extraction

### Cloud & DevOps

- Netlify
- Vercel
- AWS S3 basics
- Docker fundamentals
- CI/CD deployment pipelines

### Tools & Version Control

- Git
- GitHub
- Postman
- VS Code
- npm/yarn
- Webpack

### Web Architecture & Standards

- Responsive Web Design
- Cross-Browser Compatibility
- Web Performance Optimization
- CORS
- WCAG Accessibility

### Data Management & Systems

- Bulk Data Verification
- Data Cleansing
- ETL Processing
- Automation Scripts

### Development Methodologies

- Agile/Scrum
- SDLC
- Code Reviews
- UI/UX Design
- Prototyping
- Technical Documentation

---

## ⚡ Engineering Highlights

The portfolio uses a technical rather than inflated achievement section.

Highlights include:

- LLM API Integration
- Responsive Interface Engineering
- RESTful Backend Development
- Performance Optimization
- Deployment Automation
- Data Processing and Automation

These cards are intended to communicate engineering capabilities without inventing unsupported numerical claims.

---

## 🚀 Featured Projects

### 01 — Domain Management System

Java-based domain management application for organizing domain records and supporting structured domain administration workflows.

**Technologies**

`Java` `Domain Management` `Data Management` `Application Development`

---

### 02 — LangSphere — AI Language Learning App

Android language-learning application powered by Groq Llama 3 with AI conversations and language-learning workflows.

**Technologies**

`Android` `AI` `Groq Llama 3` `Conversational AI`

---

### 03 — PhisGuard — AI-Powered Phishing Sentinel

Hybrid cybersecurity platform combining external threat-intelligence APIs with a local AI-powered analysis workflow.

**Technologies**

`AI` `Cybersecurity` `Threat Intelligence APIs` `API Integration`

---

### 04 — StockEasy — Online Stock Exchange Platform

Django stock exchange platform with real-time market data, portfolios, watchlists and trading-oriented workflows.

**Technologies**

`Python` `Django` `JavaScript` `MySQL` `yfinance`

---

### 05 — Android Habit Tracker

Modern Kotlin habit-tracking app with habit management, daily completion and streak-based progress tracking.

**Technologies**

`Android` `Kotlin` `Habit Management` `Streaks`

---

## 📱 Responsive Design

The portfolio is designed to work across:

- Desktop
- Laptop
- Tablet
- Mobile
- Small mobile screens

Responsive behavior includes:

- Flexible content width
- Mobile hero stacking
- Responsive project cards
- Single-column mobile achievements
- Mobile-friendly experience cards
- Compact bottom navigation
- Responsive contact actions
- Small-screen typography adjustments

The work-experience cards use a consistent three-column desktop structure:

```text
┌──────────────────────────────────────────────────────────────┐
│  COMPANY / ROLE                         DATE             +   │
└──────────────────────────────────────────────────────────────┘
```

This keeps all three roles aligned and visually equivalent while preserving expandable details.

---

## 🌗 Theme System

The portfolio supports:

- Light mode
- Dark mode

The selected theme is stored in `localStorage`, so the preference remains available when the page is revisited.

Theme variables are defined in `styles.css`:

```css
:root {
  --bg: #fff;
  --fg: #18181b;
  --muted: #71717a;
}
```

Dark theme variables are activated through:

```html
<html data-theme="dark">
```

---

## 🕒 Live Clock

The hero displays the current time using:

```text
Asia/Kolkata
```

The clock updates every second through JavaScript.

---

## 🧩 JavaScript Features

`script.js` handles:

- Live clock
- Dynamic skill rendering
- Experience-card expansion
- Theme switching
- Theme persistence
- Lucide icon initialization

The code intentionally avoids unnecessary frameworks for this standalone version.

---

## ♿ Accessibility

The portfolio includes several accessibility-oriented practices:

- Semantic HTML sections
- Descriptive link titles
- `aria-label` on the LinkedIn navigation control
- Expandable experience controls using `aria-expanded`
- Readable text contrast
- Responsive typography
- Keyboard-friendly native links and buttons

---

## ⚙️ Local Setup

No build process is required.

### Option 1 — Open directly

Open:

```text
index.html
```

in a modern browser.

### Option 2 — Local server

Using Python:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

---

## 🌐 Deployment

Because this is a static HTML/CSS/JS portfolio, it can be deployed on services such as:

- GitHub Pages
- Netlify
- Vercel
- Cloudflare Pages
- Any standard static hosting provider

Upload the project files and make sure `index.html` is served as the entry page.

---

## 🔗 Contact & Profiles

**Name:** Arham Topiwala  
**Location:** Ahmedabad, Gujarat, India  
**Email:** topiwalaarham07@gmail.com  
**Phone:** +91 95129 59909

### GitHub

https://github.com/Arham43-ops

### LinkedIn

https://linkedin.com/in/arham

---

## 🎨 Design Philosophy

The interface intentionally follows a restrained visual language:

- Minimal
- Professional
- Technical
- Content-first
- Low visual noise
- Subtle borders
- Soft cards
- Neutral color palette
- Responsive spacing
- Small interaction cues

The objective is to make the portfolio feel like a polished developer workspace rather than a template-heavy landing page.

---

## 🔧 Customization

### Change profile image

Replace:

```text
pfp.jpeg
```

while keeping the same filename.

### Change contact information

Edit the contact section in:

```text
index.html
```

### Change skills

Edit `skillGroups` in:

```text
script.js
```

### Change theme colors

Edit the CSS variables at the beginning of:

```text
styles.css
```

### Add projects

Duplicate a:

```html
<article class="project">
```

block inside the Projects section.

### Add experience

Duplicate an:

```html
<article class="experience-card">
```

block inside the Work Experience section.

---

## 📌 Performance Notes

The standalone version avoids a heavy JavaScript framework and does not require a bundler.

Performance considerations include:

- Minimal JavaScript
- CSS-based responsive layout
- No large UI framework
- Native browser layout primitives
- Limited external dependency usage
- Compact page structure
- Reusable CSS variables
- No unnecessary animation libraries

The Lucide CDN is the primary external runtime dependency.

---

## 📄 License

This portfolio is a personal project belonging to **Arham Topiwala**.

The source can be adapted for personal development and portfolio purposes. Replace personal content, contact information, images, and project descriptions before reusing the structure for another individual.

---

## 👋 Author

**Arham Topiwala**

Full Stack Web Developer  
Scalable Applications · RESTful APIs · AI/LLM Integration · Performance Optimization

Ahmedabad, Gujarat, India

---

### Version

**Portfolio v3**

Focus:

```text
Full Stack Development
AI & LLM Integration
Responsive UI Engineering
RESTful APIs
Automation
Performance
```
