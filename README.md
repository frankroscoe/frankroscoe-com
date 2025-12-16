# Frank Roscoe Portfolio
[![CI/CD Workflow](https://github.com/frankroscoe/frankroscoe-com/actions/workflows/ci.yml/badge.svg)](https://github.com/frankroscoe/frankroscoe-com/actions/workflows/ci.yml)

This repository hosts the professional IT portfolio site for **Frank Roscoe**.  
It is designed to present a recruiter‑friendly, polished view of my background, skills, and teaching artifacts.

## 📌 Purpose
This repo models intentional, recruiter‑friendly portfolio discipline:
- Provides clear structure and reproducible workflow.  
- Demonstrates technical identity hygiene with intentional commit attribution.  
- Serves as both a professional showcase and a teaching artifact for IT students.  

## 🌐 Site Overview
The portfolio includes:

- **Home (`index.html`)** — introduction with tagline *“Rebuilding with Code. Rejoining with Purpose.”* and narrative on my journey back to software development.
- **About Me (`aboutme.html`)** — career journey from IT executive to programmer, highlighting values of accessibility, clarity, and mentorship, with a focus on modern languages and inclusive design.
- **Resume (`resume.html`)** — recruiter‑friendly resume available in both web and PDF formats, showcasing technical expertise, leadership roles, and academic achievements.
- **Skills and Qualifications (`skills.html`)** — combines decades of engineering experience with current coursework in C++, C#, web authoring, and accessibility‑first design, highlighting both technical expertise and mentoring strengths.
- **GitHub Repositories (`githubrepos.html`)** — curated hub for coursework, practice projects, and portfolio utilities, with future additions such as C++ design patterns and independent projects.
- *(Future)* **Key Achievements** — planned section to highlight milestone accomplishments.

## 🎨 Features
- Metadata polish for recruiter visibility (SEO keywords, Open Graph tags, favicon, theme color).
- Clean, responsive design with external stylesheet (`stylesheets/mainstyle.css`).
- Includes resume PDF, profile/logo graphics, favicon, and GitHub branding assets.
- Contact links for email and GitHub profile.

## 🚀 Getting Started
You can view the live portfolio site here:  
[https://frankroscoe.github.io/frankroscoe-com/](https://frankroscoe.github.io/frankroscoe-com/)  

### 🔧 Prerequisites
Before running locally, make sure you have:
- **Git** installed (to clone the repository)  
- **Python 3** installed (to run a simple local server)  
- A modern web browser (Chrome, Edge, Firefox, Safari)

### ▶️ To run locally:

1. Clone the repo:
   ```bash
   git clone git@github.com-frankroscoe:frankroscoe/frankroscoe-com.git
   ```
2. Navigate into the project directory:
   ```bash
   cd frankroscoe-com
   ```
3. Open in your browser (using a simple local server, e.g. Python):
   ```bash
   python3 -m http.server
   ```
Then visit http://localhost:8000.
(Any local server tool may be used; Python is shown here for simplicity.)

## 🛠️ Built With
- **HTML5** – semantic structure for portfolio pages  
- **CSS3** – responsive styling and layout  
- **GitHub Pages** – hosting and deployment  
- **MIT License** – open‑source clarity and professionalism

## 🔮 Future Enhancements
- Adds a Key Achievements page to highlight milestone projects.  
- Implements CI/CD automation with GitHub Actions for linting, accessibility checks, and build badges.  
- Showcases additional GitHub repositories, including C++ design pattern demos and independent projects, to strengthen the portfolio’s technical depth and teaching artifacts.  
- Maintains the site with **GitHub Pages** mapped to **frankroscoe.com**, serving as the front door to my professional portfolio.  
- Introduces a hybrid governance model: fully automated deployment paired with a post‑deployment notification email to `frank@frankroscoe.com` for manual verification and sign‑off. This approach demonstrates CI/CD capability while modeling creative verification practices as a teaching artifact.  

## 📄 License
This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.