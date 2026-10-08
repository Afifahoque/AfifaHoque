<div align="center">

  <!-- Header Banner -->
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:ffe600,100:00c3ff&height=200&section=header&text=I'm%20Ready!%20🍍&fontSize=42&fontColor=003366" width="100%" />

  <!-- Dynamic Typing Effect -->
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=003366&center=true&vCenter=true&width=600&lines=Flipping+Krabby+Patties+and+Training+Models...;Launching+code+like+Angry+Birds!+%F0%9F%9A%80;Welcome+to+my+GitHub+Lair!+%E2%9C%A8" alt="Typing SVG" />

  <br><br>

  <!-- Animated GIF -->
  <img src="https://media.giphy.com/media/nDSlfqf0Ukgz6/giphy.gif" width="280" alt="SpongeBob Coding" />

  <br><br>

  <!-- Fun Tech Stack Badges -->
  <img src="https://img.shields.io/badge/SpongeBob_(Python)-FFD700?style=for-the-badge&logo=python&logoColor=black" />
  <img src="https://img.shields.io/badge/Chuck_(PyTorch)-FFD700?style=for-the-badge&logo=pytorch&logoColor=black" />
  <img src="https://img.shields.io/badge/Patrick_(React)-FF69B4?style=for-the-badge&logo=react&logoColor=white" />
  <img src="https://img.shields.io/badge/Red_(Linux)-E50914?style=for-the-badge&logo=linux&logoColor=white" />

</div>

---

### 🕹️ Arcade Contribution Graph
> *Pac-Man eating through my contribution grid daily!*

<div align="center">
  <img src="https://raw.githubusercontent.com/Afifahoque/Afifahoque/output/pacman-contribution-graph.svg" alt="Pac-Man Contribution Graph" width="100%" />
</div>

---

### 🏆 Krusty Krab Stats & Trophies

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Afifahoque&theme=onedark&column=4" width="90%" />
  
  <br><br>

  <img src="https://github-readme-stats.vercel.app/api?username=Afifahoque&show_icons=true&theme=sunshine&hide_border=true" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Afifahoque&layout=compact&theme=sunshine&hide_border=true" width="48%" />
</div>

---

<details>
  <summary><b>🔍 Peek inside my component architecture (TypeScript)</b></summary>

  <br>

```typescript
import {attr, controller} from '@github/catalyst'

/**
 * ProfileEasterEggElement
 * Fun controller listening to active tab states!
 */
@controller('profile-easter-egg')
export class ProfileEasterEggElement extends HTMLElement {
  @attr declare greeting: string

  connectedCallback() {
    console.log("I'm Ready! 🍍")
  }
}
