# 🚀 Shubham Panchal | Portfolio Website

A clean, minimalist, and highly responsive personal portfolio website built from scratch using vanilla HTML, CSS, and JavaScript. Designed to showcase professional experience, projects, and technical skills with a sophisticated warm aesthetic.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Responsive](https://img.shields.io/badge/Responsive-Design-green?style=for-the-badge)

---

## 📑 Table of Contents

- [Overview](#overview)
- [✨ Features](#-features)
- [🛠️ Tech Stack](#️-tech-stack)
- [📊 Work & Architecture Diagram](#-work--architecture-diagram)
- [📁 Project Structure](#-project-structure)
- [🚀 Getting Started](#-getting-started)
- [🎨 Customization Guide](#-customization-guide)
- [📱 Responsive Breakpoints](#-responsive-breakpoints)
- [📄 License](#-license)
- [📞 Contact](#-contact)

---

## 🌟 Overview

This portfolio is designed with a focus on typography, whitespace, and subtle micro-interactions. It moves away from heavy frameworks to deliver lightning-fast load times and complete control over the design system. The warm beige and terracotta color palette creates a welcoming, professional atmosphere.

---

## ✨ Features

- **🎨 Custom Design System:** Built with CSS Variables for easy theming (warm beige background, terracotta accents).
- **⚡ Zero Dependencies:** 100% Vanilla HTML/CSS/JS. No React, no Tailwind, no bloat.
- **📱 Fully Responsive:** Flawless experience across Mobile, Tablet, and Desktop.
- **🎭 Scroll Animations:** Elements fade in smoothly as the user scrolls down the page.
- **🕒 Live IST Clock:** Real-time clock in the header showing Solapur/India time.
- **🧭 Smart Navigation:** Active nav links update automatically based on the scroll position.
- **🖼️ Image Optimization:** Smart object-fit properties ensure profile images look perfect on any screen size.
- **📂 Comprehensive Sections:** Hero, About, Experience, Projects, Skills, Education, Certifications, and Contact.

---

## 🛠️ Tech Stack

| Technology | Usage |
| :--- | :--- |
| **HTML5** | Semantic structure and accessibility. |
| **CSS3** | Custom styling, CSS Grid, Flexbox, Animations, and Variables. |
| **JavaScript (ES6+)** | DOM manipulation, Intersection Observer for animations, and live clock logic. |
| **Google Fonts** | 'Space Grotesk' for headings, 'Inter' for body text. |

---

## 📊 Work & Architecture Diagram

This diagram illustrates the flow of the application, from page load to user interaction and DOM rendering.

```mermaid
graph TD
    subgraph "User Interaction"
        A[User Opens Website] --> B[Scrolls Through Sections]
        B --> C[Clicks Navigation Links]
        B --> D[Hovers Over Cards/Buttons]
    end

    subgraph "Core Engine (JavaScript)"
        E[DOMContentLoaded Event] --> F[Initialize Live Clock]
        E --> G[Setup Intersection Observer]
        E --> H[Setup Scroll Event Listeners]
        
        H --> I[Update Active Nav State]
        G --> J[Trigger Fade-In Animations]
        C --> K[Smooth Scroll to Section]
    end

    subgraph "UI & Rendering (HTML/CSS)"
        L[CSS Variables & Theme] --> M[Apply Warm Beige & Terracotta]
        N[CSS Grid & Flexbox] --> O[Responsive Layouts]
        P[HTML Semantic Tags] --> Q[Render Sections]
    end

    B -.-> G
    C -.-> K
    D -.-> R[CSS Hover Transitions]
### 💡 Tips for using this README:
1. **Mermaid Diagram:** GitHub automatically renders Mermaid diagrams. If you host this on GitHub, the flowchart will appear as a beautiful visual graphic.
2. **Update Links:** Don't forget to replace the `#` in the Contact section at the bottom with your actual LinkedIn and GitHub profile URLs.
3. **License:** If you want to add an actual license file, create a file named `LICENSE` in your folder and paste the standard MIT license text into it.
