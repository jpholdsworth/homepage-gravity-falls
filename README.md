# 🌲 Gravity Falls Homepage

## 🌐 Live Demo
[View Live Demo](https://jpholdsworth.github.io/homepage-gravity-falls/)

![HTML](https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Status](https://img.shields.io/badge/status-live-brightgreen?style=for-the-badge)
![Made with](https://img.shields.io/badge/made%20with-HTML%20%26%20CSS-blue?style=for-the-badge)

![Homepage](/doc/screenshot.png)

## 🧭 Introduction
A responsive fan-made homepage inspired by the animated mystery-comedy *Gravity Falls*. This project demonstrates how a thoughtfully structured HTML & CSS layout adapts fluidly across mobile, tablet and desktop - no JavaScript, no framework, just the fundamentals done right.

## 💡 Why This Project Matters
This project focuses on mastering core front-end fundamentals without relying on frameworks.

In an ecosystem where tools like React are common, this demonstrates the ability to:
- Build responsive layouts from first principles
- Write clean, scalable CSS
- Understand how the browser renders layouts

It reflects a strong foundation that can transfer easily to modern frameworks and larger applications.

## 📑 Table of Contents
- [The Vision](#-the-vision)
- [Features](#-features)
- [UI/UX](#-uiux)
- [Getting Started](#-getting-started)
- [Usage](#-usage)
- [Tech Stack](#️-tech-stack)
- [Architecture](#-architecture)
- [Challenges & Learnings](#-challenges--learnings)
- [Future Improvements](#-future-improvements)
- [License](#-license)

## 🎯 The Vision
The goal of this project was to recreate a visually engaging homepage inspired by my favourite cartoon, focusing on strong visual identity, responsive design and clean semantic HTML.

Rather than relying on frameworks or libraries, the project intentionally uses pure HTML and CSS to demonstrate a solid understanding of core front-end fundamentals.

**Key objectives:**
- Build a responsive layout from scratch
- Recreate a distinctive theme using custom typography and colour
- Practice clean, maintainable CSS structure
- Deploy a fully functional static site using GitHub Pages

## ✨ Features
- 📱 **Fully responsive** - works on any screen size or orientation
- 🎨 **Gravity Falls themed** - colours, typography and visuals inspired by the show
- 🔤 **Custom fonts** - loaded via `@font-face` for authentic personality
- ⚡ **Zero dependencies** - pure HTML & CSS, no build tools required
- 🌐 **Deployed** - live on GitHub Pages, accessible from any device

## 🎨 UI/UX
The design is inspired by the mysterious and rustic aesthetic of *Gravity Falls*, aiming to balance personality with usability.
 
### Design Choices
- **Colour Palette**: Earthy tones and darker overlays reflecting the forest setting
- **Typography**: Custom fonts inspired by the show's hand-drawn title style
- **Layout**: Clean structure with strong visual hierarchy
- **Responsiveness**: Mobile-first design approach - base styles target small screens, scaling up with `min-width` media queries
 
### User Experience
- Simple and intuitive navigation
- Fast loading due to lightweight architecture
- Consistent visual experience across all devices
 
## 🚀 Getting Started
### Installation & Setup
1. Clone the repository
```bash
git clone https://github.com/jpholdsworth/homepage-gravity-falls.git
cd homepage-gravity-falls
```

2. Open with Live Server (recommended):
    - Install the [Live Server extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) in VS Code
    - Right click `index.html` in the VS Code file explorer
    - Select **"Open with Live Server"**
    - The site will open at `http://127.0.0.1:5500`

> No build tools or dependencies required — it's plain HTML and CSS!

## ⚡ Usage
1. Open the web application in your browser (localhost during dev or the deployed GitHub Pages URL)
2. Resize the browser window or change your device orientation to see the layout respond in real time
3. Use browser DevTools (`F12` → Toggle Device Toolbar) to simulate different screen sizes

## 🛠️ Tech Stack
- **HTML5** — semantic structure, responsiveness and accessibility
- **CSS3** — styling, layout and responsiveness
- **GitHub Pages** — deployment and hosting

| Feature | Description |
| --- | --- |
| Mobile-First | Designed for the smallest screens first, scaling up via `min-width` queries |
| Grid & Flexbox | Hybrid layout system using Grid for macro-layout and Flexbox for micro-components |
| `@font-face` | Custom local font loading with optimised fallback stacks - no external CDN |

## 🧠 Architecture
- Separation of concerns between structure (HTML) and styling (CSS)
- Organised asset management for scalability
- Local font loading using `@font-face` — no external CDN required

## 🧩 Development Principles
- **Simplicity first** — no unnecessary frameworks
- **Performance-focused** — lightweight and fast-loading
- **Responsive design** — works across devices and screen sizes
- **Maintainability** — readable and well-organised code
- **Progressive enhancement** — core experience works everywhere

## 🚧 Challenges & Learnings
Building this project provided practical experience working with core front-end technologies without relying on frameworks or external libraries.

### Key Challenges
**Creating a Responsive Layout Without Frameworks**
Designing layouts for multiple screen sizes required careful use of Flexbox, Grid, media queries and relative units.
✅ *Learning*: Stronger understanding of mobile-first responsive design.

**Maintaining Visual Consistency**
Recreating a themed design while keeping readability and usability required balancing aesthetics with accessibility.
✅ *Learning*: Improved understanding of typography hierarchy, spacing and contrast.

**Working with Custom Fonts**
Loading fonts locally introduced challenges around performance and fallback handling.
✅ *Learning*: Better knowledge of font optimisation and loading strategies.

**Keeping CSS Maintainable**
As styling expanded, structure and naming conventions became essential.
✅ *Learning*: Writing cleaner selectors and organising styles for scalability.

### Key Takeaways
- Strong fundamentals can replace heavy frameworks
- Planning layout early reduces refactoring later
- Small UI decisions strongly affect user experience
- Deployment completes the full development lifecycle

## 🔮 Future Improvements
- [ ] Add subtle animations and micro-interactions
- [ ] Improve accessibility (ARIA labels and contrast checks)
- [ ] Introduce dark/light theme toggle
- [ ] Expand into a multi-page themed website

## 📜 License
This project is open source and available under the [MIT License](https://mit-license.org/).

> _Gravity Falls is the property of Disney / Alex Hirsch. This is a fan project built for educational and portfolio purposes only._
