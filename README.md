<div align="center">
  <!-- Waving Header Banner -->
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00c3ff,100:ffff1a&height=180&section=header&text=Afifa%20Hoque%20%E2%9C%A8&fontSize=42&fontColor=003366" width="100%" />

  <!-- Dynamic Typing Effect -->
  <p align="center">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=00c3ff&center=true&vCenter=true&width=600&lines=Computer+Vision+%26+Egocentric+AI+Researcher;PyTorch+%7C+Vision-Language+Models;Building+Smart+Perception+Systems" alt="Typing SVG" />
  </p>

  <!-- Social & Portfolio Links -->
  <p style="display: flex; justify-content: center; gap: 10px; flex-wrap: wrap; margin-top: 10px;">
    <a href="https://linkedin.com/" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
    </a>
    <a href="https://scholar.google.com/" target="_blank">
      <img src="https://img.shields.io/badge/Google_Scholar-4285F4?style=for-the-badge&logo=google-scholar&logoColor=white" alt="Scholar"/>
    </a>
    <a href="mailto:afifahoque@gmail.com" target="_blank">
      <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
    </a>
  </p>
</div>

---

### 🔬 About Me

👋 Hi! I'm Afifa Hoque, a Computer Vision researcher focused on first-person video analysis, egocentric decision support systems, and vision-language model architectures.

- 🎓 **Background:** B.Sc. in Computer Science & Engineering.
- 🎯 **Primary Focus:** Egocentric AI, Vision-Language Models (VLMs), Object Detection, and Road Safety Perception.
- ⚙️ **Stack:** Python, PyTorch, OpenCV, Linux, Git, and Web Frameworks (React, Tailwind CSS).
- ⚡ **Fun Fact:** Huge Iron Man fan 🤖 and love preparing paper layouts in LaTeX!

---

<h2 align="center">💻 Tech & Toolkit</h2>

<div align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white" />
</div>

---

### 🏙️ 3D Contribution Isometric Map
> *A 3D city rendered directly from my GitHub contributions!*

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Afifahoque/Afifahoque/main/profile-3d-contrib/profile-night-view.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Afifahoque/Afifahoque/main/profile-3d-contrib/profile-green-animate.svg">
    <img alt="3D Contribution Map" src="https://raw.githubusercontent.com/Afifahoque/Afifahoque/main/profile-3d-contrib/profile-green-animate.svg">
  </picture>
</div>

---

<details>
  <summary><b>🔍 Catalyst Web Component Architecture (TypeScript)</b></summary>

  <br>

```typescript
import {attr, controller} from '@github/catalyst'

/**
 * ProfileWatcherElement
 * Custom Web Component setup for profile interactions
 */
@controller('profile-watcher')
export class ProfileWatcherElement extends HTMLElement {
  @attr declare activeTab: string

  connectedCallback() {
    console.log('Welcome to Afifa\'s GitHub Profile! 🚀')
  }
}
