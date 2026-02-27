# Personal Portfolio Website

A modern, responsive portfolio website showcasing my projects, skills, experience, and education as a Computer Science student at the University of Waterloo.

## Live

**[ishvirchopra35.tech](https://ishvirschopra35.tech)**

---

## Screenshots

### Hero Section

<img width="1919" height="990" alt="image" src="https://github.com/user-attachments/assets/05f27532-22bb-44dc-a3ef-b4a77f4527b7" />

*Particle canvas background with typing animation*

### About Me

<img width="1919" height="985" alt="image" src="https://github.com/user-attachments/assets/aa94ea97-8f70-402d-ae1f-d8f17241b799" />

*Personal intro, GitHub activity graph, and stats*

### Projects

<img width="1919" height="990" alt="image" src="https://github.com/user-attachments/assets/90bc5f8b-2fc3-44e0-a052-34048ccb138b" />

*Project cards with tech tags, descriptions, and GitHub links*

### Experience

<img width="1919" height="986" alt="image" src="https://github.com/user-attachments/assets/0374a2af-b4e0-45f6-a016-4f1df0566893" />

*Timeline with internships and research*

### Skills

<img width="1919" height="987" alt="image" src="https://github.com/user-attachments/assets/a290c798-d79c-4cf8-b75f-30c9528fe6ae" />

*Tech stack organized by category*

### Education

<img width="1919" height="995" alt="image" src="https://github.com/user-attachments/assets/aa722cc9-3d67-4ba6-a248-57bb1fb72496" />

*University of Waterloo with coursework*

### Contact

<img width="1917" height="985" alt="image" src="https://github.com/user-attachments/assets/37136621-90cd-43f8-a956-e1dd69a2b3b9" />

*Social links and email*

---

## Features

- **Dark/Light Mode**: Toggles between dark and light theme, preference saved to localStorage
- **Particle Canvas Background**: Animated floating dots with connecting lines built in vanilla JS
- **Typing Animation**: "I am into..." cycles through interests with realistic backspace effect
- **Scroll Animations**: Fade-in on scroll using IntersectionObserver
- **Sticky Dot Navigation**: Fixed left sidebar showing which section you're currently in
- **Scroll Progress Bar**: Thin purple gradient bar at the top that fills as you scroll
- **Custom Scrollbar**: Purple styled scrollbar across all browsers
- **GitHub Activity Graph**: Live contribution graph embedded via ghchart.rshah.org
- **Responsive Design**: Fully mobile responsive with hamburger menu on small screens
- **Project Cards**: Hover lift and glow effect with tech tags and GitHub links
- **Experience Timeline**: Date-labeled vertical timeline with purple line and dots
- **Resume Download**: Direct PDF download from the navbar

## Sections

- **Hero**: Name, typing animation, CTA buttons, social links
- **About**: Bio, stats (GPA, internships, projects), GitHub activity
- **Projects**: Wrap It Up, ASL Classifier, Digit Classifier, E-Commerce App, Bronze Layer Data Warehouse, Sales Dashboard
- **Experience**: Compunnel Canada, Red Circle Inc, Arseam Foundation
- **Skills**: Languages, Frameworks, Tools, Concepts
- **Education**: University of Waterloo, BCS, 4.0 GPA
- **Contact**: Email button and social links

## Technologies Used

- **HTML5**
- **CSS3** (custom properties, animations, grid, flexbox)
- **Vanilla JavaScript** (no frameworks)
- **Font Awesome 6.5** via CDN for icons
- **Google Fonts** (Inter) via CDN
- **[ghchart.rshah.org](https://ghchart.rshah.org)** for live GitHub contribution graph

## Project Structure

```
portfolio/
├── index.html        # Everything — HTML, CSS, and JS in one file
├── me.jpg            # Profile photo
├── favicon.png       # Browser tab icon
└── resume.pdf        # Resume download
```

## Getting Started

No installs or build tools needed. Just open the file directly.

```bash
git clone https://github.com/Ishvirchopra35/portfolio.git
cd portfolio
# Open index.html in your browser
```

Or with a local server:

```bash
python -m http.server 8000
# Visit http://localhost:8000
```

## Deployment

Hosted on **Azure Static Web Apps**, connected to this GitHub repo. Every push to `main` triggers an automatic redeployment.

```bash
git add .
git commit -m "your message"
git push
```

Azure picks it up automatically within about a minute.

**Build settings:**
- App location: `/`
- Output location: `/`
- Build command: *(none)*

## Color Scheme

| Role | Value |
|------|-------|
| Background (dark) | `#0a0a0f` |
| Surface (dark) | `#12121a` |
| Primary accent | `#7c3aed` (purple) |
| Secondary accent | `#06b6d4` (cyan) |
| Background (light) | `#f8f8fc` |

## Social Links

- GitHub: [github.com/Ishvirchopra35](https://github.com/Ishvirchopra35)
- LinkedIn: [linkedin.com/in/ishvir-chopra-23758b2a8](https://www.linkedin.com/in/ishvir-chopra-23758b2a8/)
- YouTube: [youtube.com/@Ishvirchopra35](https://www.youtube.com/@Ishvirchopra35)
- Instagram: [instagram.com/ishvirchopra](https://www.instagram.com/ishvirchopra/)
- Email: ischopra@uwaterloo.ca

---

Made with by Ishvir Chopra
