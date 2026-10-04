# Gaurang Soni — Modern Personal Portfolio Website

A modern, high-performance personal portfolio website built with **React**, **Vite**, and **Tailwind CSS**. Designed specifically for showcasing engineering coursework, technical skills, projects, and achievements with a clean, dark-mode glassmorphic aesthetic.

---

## 🌟 Highlights & Features

- **Hero Section**: Dynamic introduction, animated status indicator, direct CTA buttons (*View Projects*, *Contact Me*, *Resume View*), and social links.
- **About Me**: Student-friendly background, core pillars (Artificial Intelligence, Web Development, Digital Productivity, Continuous Learning), and key highlights checklist.
- **Education Section**: Comprehensive academic showcase highlighting **B.Tech at JECRC University (1st Year)** and 6 relevant engineering learning areas.
- **Skills Showcase**: Attractive, categorized skill cards for **HTML, CSS, JavaScript, Python, Artificial Intelligence, Generative AI, Web Development, and Digital Productivity**, complete with filter tabs and proficiency bars.
- **Featured Projects**:
  1. *Personal Portfolio Website* (React + Tailwind + Vite)
  2. *AI Website Project* (Generative AI + Python + Web APIs)
  3. *Student Productivity Project* (Workflow & Task Management)
  - Includes interactive **Project Modal** for deep dives into features and tech stacks.
- **Achievements Section**: Filterable categories for *Certifications*, *Hackathons*, *Courses*, *Awards*, and *Other Achievements*, with an expandable guide on adding new milestones.
- **Contact Section**: One-click **Copy Email** (`gaurangsoni2007@gmail.com`), direct **LinkedIn** & **GitHub** profile cards, and an interactive message form with mail client support.
- **Resume Viewer**: Built-in resume modal with clean summary and one-click print/PDF export.
- **Mobile Responsive**: Fully adaptive layout with smooth mobile hamburger drawer navigation.

---

## 🚀 Quick Start Guide

### 1. Install Dependencies
```bash
npm install
```

### 2. Start the Local Development Server
```bash
npm run dev
```
Open [http://localhost:3000](http://localhost:3000) in your web browser.

### 3. Production Build
```bash
npm run build
```
Creates an optimized production bundle in the `dist/` directory ready for deployment.

---

## ✏️ Easy Customization

All data on this website is centralized in a single, well-organized file:

```
src/data/portfolioData.js
```

You can customize:
- Personal details, bio, and social media handles
- Add or edit projects, descriptions, and preview links
- Update skills, categories, and proficiency levels
- Add future certifications, hackathons, and awards in the `achievements` array
- Contact email and location

---

## 🌐 Deploy to Vercel (Recommended)

This project is 100% ready for Vercel deployment:

### Option A: Via GitHub (Easiest)
1. Push this repository to your GitHub account (`https://github.com/gaurangsoni/...`).
2. Go to [vercel.com](https://vercel.com) and log in.
3. Click **"Add New Project"** and import your repository.
4. Framework Preset: **Vite** (auto-detected).
5. Click **"Deploy"**.

### Option B: Via Vercel CLI
```bash
npm install -g vercel
vercel
```

---

## 📁 Project Architecture

```
gaurang-soni/
├── index.html               # Main HTML entry with Google fonts & metadata
├── package.json             # Project dependencies and npm scripts
├── vite.config.js           # Vite configuration
├── tailwind.config.js       # Custom Tailwind theme and animations
├── postcss.config.js        # PostCSS configuration
├── src/
│   ├── main.jsx             # React entrypoint
│   ├── App.jsx              # Main App component with scrollspy & modal states
│   ├── index.css            # Global CSS, Tailwind directives & glass styles
│   ├── data/
│   │   └── portfolioData.js # Centralized portfolio content & info
│   └── components/
│       ├── Navbar.jsx       # Sticky glassmorphic navigation & mobile drawer
│       ├── Hero.jsx         # Hero banner with animations and CTAs
│       ├── About.jsx        # Story, pillars, and student stats
│       ├── Education.jsx    # JECRC University, 1st Year, and learning areas
│       ├── Skills.jsx       # Categorized skill cards with progress bars
│       ├── Projects.jsx     # 3 featured projects with interactive modal
│       ├── ProjectModal.jsx # Detailed project overview modal
│       ├── Achievements.jsx # Filterable achievements & extensible card
│       ├── Contact.jsx      # Email copy utility, socials & contact form
│       ├── ResumeModal.jsx  # Printable student resume modal
│       └── Footer.jsx       # Navigation, copyright & back-to-top button
```

---

© Gaurang Soni • B.Tech Student, JECRC University
