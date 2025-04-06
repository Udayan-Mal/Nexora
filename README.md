# Nexora - An Awwards-Inspired Web Experience

<div align="center">
  <img src="public/img/nexora-preview.jpg" alt="Nexora Preview" width="800"/>

  [![Live Demo](https://img.shields.io/badge/DEMO-LIVE-5542ff?style=for-the-badge&logo=vercel&logoColor=white)](https://nexora-kappa.vercel.app/)
  [![GitHub](https://img.shields.io/badge/SOURCE-CODE-010101?style=for-the-badge&logo=github)](https://github.com/your-username/nexora)
  [![License](https://img.shields.io/badge/LICENSE-MIT-4fb7dd?style=for-the-badge)](LICENSE)
</div>

---

## ✨ Introduction

Nexora is a visually stunning and interactive website, inspired by Zentry and built to reflect the feel of Awwwards-winning designs. This project showcases modern frontend technologies and advanced UI/UX concepts, aimed at developers eager to explore scroll-based interactions, animation, and responsive layouts.

> 🔮 Reimagined with a metagame layer and immersive "Play Economy" storytelling.

---

## 📋 Table of Contents

- [✨ Introduction](#-introduction)
- [🛠 Tech Stack](#-tech-stack)
- [🚀 Features](#-features)
- [📁 Project Structure](#-project-structure)
- [🤸 Quick Start](#-quick-start)
- [🔗 Assets](#-assets)
- [🚀 Deployment](#-deployment)
- [📜 License](#-license)

---

## 🛠 Tech Stack

### ⚙️ Core Technologies

| Technology | Description |
|------------|-------------|
| ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react) | Component-based architecture |
| ![Vite](https://img.shields.io/badge/Vite-B73BFE?style=flat-square&logo=vite&logoColor=FFD62E) | Fast development & optimized builds |
| ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white) | Utility-first CSS styling |

### 🎞️ Animation Libraries

| Library | Purpose |
|--------|---------|
| ![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=flat-square&logo=greensock&logoColor=white) | Scroll-triggered timeline animations |
| ![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=flat-square&logo=framer&logoColor=white) | Component-based animation handling |

---

## 🚀 Features

- 🔄 **Scroll-Based Animations**: Engaging transitions and reveal effects.
- 🌀 **Geometric Video Transitions**: Smooth `clip-path` animations for storytelling.
- 🧲 **3D Hover Effects**: Interactive tilt-based card hover effects.
- 📱 **Responsive Design**: Flawless rendering across devices.
- 🧠 **Metagame Theme**: Immersive "Play Economy" narrative layer.
- ⚙️ **Modular Architecture**: Clean structure for scalability and maintenance.

#### 🔍 Code Snippet Example - GSAP Clip-Path Animation

```js
gsap.to(".element", {
  clipPath: "polygon(0% 0%, 100% 0%, 100% 100%, 0% 100%)",
  scrollTrigger: {
    trigger: ".element",
    scrub: true
  }
});

```

---

### 🎮 3D Tilt Hover Interaction

```js
<div 
  onMouseMove={handleTilt}
  style={{ transform: `rotateX(${tiltX}deg) rotateY(${tiltY}deg)` }}
>
  Interactive Element
</div>

```

---

## 📁 Project Structure

```bash
nexora/
├── public/
│   ├── fonts/          # Custom fonts (woff2)
│   ├── videos/         # Background video assets
│   └── img/            # Static image assets
├── src/
│   ├── components/     # Reusable React components
│   │   ├── Hero.jsx    # Full-screen video hero
│   │   ├── Navbar.jsx  # Animated scroll-aware navbar
│   └── App.jsx         # Root component
│   └── main.jsx        # App entry point
├── tailwind.config.js  # Tailwind CSS config
└── vite.config.js      # Vite build config
```



---


## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/your-username/nexora.git
cd nexora
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Running the Project**

C

Open [http://localhost:5173](http://localhost:5173) in your browser to view the project.

## 🔨 Build for Production 

```bash
npm run build && npm run preview

```
---

## 🔗 Assets

Assets used are inspired by Zentry and included only for educational use:

📹 public/videos/ → hero-1.mp4, feature-1.mp4

🖼️ public/img/ → logo.png, about.webp

🔤 public/fonts/ → zentry-regular.woff2, general.woff2

⚠️ For commercial projects, replace these assets with your own.


---

## 🚀 Deployment

**Deployed Link**
**URL**: **[Nexora](https://nexora-kappa.vercel.app/)** 
Hosted on Vercel for fast, scalable deployment.

**How to Deploy Your Own Version**
1. **Push to GitHub**:
Create a repository on GitHub (e.g., nexora).
Push your local project:
```bash
git remote add origin https://github.com/your-username/nexora.git
git branch -M main
git push -u origin main
```

2. **Deploy on Vercel**:
Log in to **[vercel](https://vercel.com/)**
Import your GitHub repository.
Set Framework Preset to Vite, Build Command to npm run build, Output Directory to dist.
Click Deploy and get your unique URL.




**[Zentry](https://zentry.com/)**