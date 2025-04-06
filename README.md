# Nexora - An Awwards-Inspired Web Experience

<div align="center">
  <img src="public/img/nexora-preview.jpg" alt="Nexora Preview" width="800"/>

  [![Live Demo](https://img.shields.io/badge/DEMO-LIVE-5542ff?style=for-the-badge&logo=vercel&logoColor=white)](https://nexora-kappa.vercel.app/)
  [![GitHub](https://img.shields.io/badge/SOURCE-CODE-010101?style=for-the-badge&logo=github)](https://github.com/Udayan-Mal/nexora)
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
- [🚀 Key Features](#-features)
- [UI Components](#-ui-components)  
- [📁 Project Structure](#-project-structure)
- [🤸 Quick Start](#-quick-start)
- [🔗 Assets](#-assets)
- [🚀 Deployment](#-deployment)
- [📜 License](#-license)
- [Acknowledgments](#-acknowledgments)
- [Contact](#-contact)
---

## 🛠 Tech Stack

### ⚙️ Core Technologies

| Technology | Usage |
|------------|-------|
| ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react) | Component architecture |
| ![Vite](https://img.shields.io/badge/Vite-B73BFE?style=flat-square&logo=vite&logoColor=FFD62E) | Build tool |
| ![Tailwind](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white) | Styling |

### 🎞️ Animation Libraries

| Library | Purpose |
|---------|---------|
| ![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=flat-square&logo=greensock&logoColor=white) | Scroll animations |
| ![Framer](https://img.shields.io/badge/Framer_Motion-0055FF?style=flat-square&logo=framer&logoColor=white) | Micro-interactions |
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

## 🖥️ UI Components

| Component          | Description                                                                 | Key Features                                                                 |
|--------------------|-----------------------------------------------------------------------------|------------------------------------------------------------------------------|
| **Hero Section**   | Full-screen video with animated transitions                                 | GSAP scroll triggers, video switching logic, 3D tilt effects                 |
| **Bento Grid**     | Interactive card layout with tilt effects                                   | Dynamic mouse tracking, radial gradient hovers, auto-playing video cards     |
| **Animated Navbar**| Scroll-aware navigation with audio toggle                                  | GSAP animations, scroll detection, audio visualizer                         |
| **About Section**  | Image reveal with clip-path animations                                     | Custom clip-path morphing, responsive text layout                           |
| **Features Cards** | Interactive product showcase                                               | 3D perspective transforms, coming soon indicators                          |
| **Contact Form**   | Layered image composition with custom shapes                               | SVG clip-paths, responsive positioning                                     |
| **Footer**         | Social media links and copyright                                           | Hover animations, responsive grid layout                                   |
| **Video Player**   | Custom mini video player component                                         | Click-to-expand functionality, smooth transitions                         |
| **Animated Text**  | Word-by-word reveal animations                                             | GSAP timeline, 3D rotation effects                                        |
| **Loading Screen** | Animated preloader                                                        | Three-body physics animation, smooth fade-out                              |

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

---

## 📜 License
This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for full details.  
*Note: This is an educational project created for learning purposes. All design credits belong to their respective owners.*

---

## 🎉 Acknowledgments
Special thanks to these technologies that made Nexora possible:

| Technology       | Contribution                          |
|------------------|---------------------------------------|
| **GSAP**         | Powering all scroll-triggered animations and complex timelines |
| **React Icons**  | Providing the sleek arrow and social media icons |
| **Vite**         | Enabling lightning-fast development builds |
| **Tailwind CSS** | Facilitating responsive design with utility classes |
| **Vercel**       | For seamless deployment and hosting |

*Design inspiration from [Zentry](https://zentry.com/)*

---

## 📧 Contact
**Project Maintainer**:  
👨‍💻 **Udayan Mal**  
📫 **GitHub**: [Udayan-Mal](https://github.com/Udayan-Mal)  
🌐 **Live Demo**: [Nexora on Vercel](https://nexora-kappa.vercel.app/)  




