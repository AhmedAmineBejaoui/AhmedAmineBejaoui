# README.md — Profil Futuriste & Animé

> Copie-colle **tout** ce contenu dans `README.md` de ton repo **AhmedAmineBejaoui** (même nom que ton pseudo). Remplace les liens (LinkedIn/Portfolio/Medium) par les tiens.

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=220&text=Ahmed%20Amine%20Bejaoui&fontAlign=50&fontAlignY=40&color=0:0f0c29,50:302b63,100:24243e&animation=fadeIn&fontColor=ffffff" alt="header"/>
</p>

<p align="center">
  <a href="https://github.com/AhmedAmineBejaoui">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1200&width=600&lines=Développeur+Web+%7C+Builder+de+Communautés;React+%2B+Next.js+%2B+Node.js+%2B+MongoDB;Design+%26+Perf+orientés+produit;Toujours+partant+pour+des+collabs+impactantes" alt="typing intro"/>
  </a>
</p>

<p align="center">
  <b>Passionné par la tech, le produit et l'impact social</b> ✨
</p>

---

### 🧠 À propos de moi

* 👨‍💻 Je développe des applications utiles avec une vraie vision produit
* 🛠️ Stack principale : **JavaScript, React, Next.js, Node.js, MongoDB, TailwindCSS**
* 🔧 Backend & Auth : **Express.js, Firebase, Supabase, FastAPI**
* 🌱 En ce moment : **IA appliquée au web** + **architectures serverless**
* 💬 Ouvert aux collabs sur projets **AI, social, community tools**
* ✨ Objectif 2025 : **contribuer à l’open‑source** et **scaler des apps utiles**

---

### 🚀 Projets en avant

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🎨 Elegance</h3>
      <p>Un projet web moderne et élégant, optimisé pour la performance et le design.</p>
      <p>
        <a href="https://github.com/AhmedAmineBejaoui/elegance">
          <img src="https://img.shields.io/badge/Repo-Elegance-302b63?style=for-the-badge&logo=github"/>
        </a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🏘️ Neighborhood (soon)</h3>
      <p>Une plateforme pour connecter et renforcer les communautés locales.</p>
      <p>
        <a href="https://github.com/AhmedAmineBejaoui/neighborhood">
          <img src="https://img.shields.io/badge/Repo-Neighborhood-24243e?style=for-the-badge&logo=github"/>
        </a>
      </p>
    </td>
  </tr>
</table>

---

### 🧰 Toolbox & Technologies

<p align="center">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=000"/>
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
  <img src="https://img.shields.io/badge/Next.js-000?style=for-the-badge&logo=next.js&logoColor=fff"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=fff"/>
  <img src="https://img.shields.io/badge/MongoDB-4DB33D?style=for-the-badge&logo=mongodb&logoColor=white"/>
  <img src="https://img.shields.io/badge/TailwindCSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white"/>
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=000"/>
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=fff"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github"/>
</p>

---

### 📊 Stats & Activité

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=AhmedAmineBejaoui&show_icons=true&theme=tokyonight" alt="GitHub Stats" />
  <br/>
  <img src="https://github-readme-streak-stats.herokuapp.com?user=AhmedAmineBejaoui&theme=tokyonight" alt="GitHub Streak" />
  <br/>
  <img src="https://github-profile-trophy.vercel.app/?username=AhmedAmineBejaoui&theme=algolia&margin-w=10&margin-h=10" alt="GitHub Trophies" />
</p>

---

### 🛰️ Futuristic Add‑ons (animés)

* ✍️ **Typing banner** (déjà actif tout en haut via `readme-typing-svg`).

* 🐍 **Snake contributions** — animation de ta grille de contributions :

  ```md
  <!-- S'affichera une fois l'action ci-dessous configurée -->
  ![snake gif](https://github.com/AhmedAmineBejaoui/AhmedAmineBejaoui/blob/output/github-contribution-grid-snake.svg)
  ```

* 🌊 **Header/Footer ondulés** — rendus par `capsule-render` (déjà utilisés).

---

### 🔗 Me retrouver ailleurs

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=flat\&logo=linkedin\&logoColor=white)](https://linkedin.com/in/tonprofil)
[![Portfolio](https://img.shields.io/badge/-Portfolio-000?style=flat\&logo=vercel\&logoColor=white)](https://tonsite.com)
[![Medium](https://img.shields.io/badge/-Medium-12100E?style=flat\&logo=medium\&logoColor=white)](https://medium.com/@tonprofil)

---

<p align="center">
  <em>“Construire des outils simples pour résoudre des problèmes réels.”</em>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&section=footer&height=150&color=0:0f0c29,50:302b63,100:24243e"/>
</p>

---

## 🛠️ Setup des animations (en 2 min)

### 1) Contribution Snake (GitHub Actions)

1. Dans le repo **AhmedAmineBejaoui**, crée:

   * Dossier: `.github/workflows/`
   * Fichier: `snake.yml`
2. Colle ce YAML:

```yaml
name: Generate Snake

on:
  schedule:
    - cron: "0 */12 * * *"   # 2x par jour
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: AhmedAmineBejaoui
          outputs: |
            dist/github-contribution-grid-snake.svg
      - name: Push snake
        uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

3. Lance le workflow via l'onglet **Actions** → **Generate Snake** → **Run workflow**.
4. Ajoute ensuite l'image dans ton `README.md` (déjà prévue plus haut).

### 2) Personnaliser le Typing Banner

Modifie l'URL `readme-typing-svg` en haut pour changer les textes/rythmes (paramètres `lines`, `pause`, `width`).

### 3) Thème GitHub

Settings → Appearance → Dark (reco: **Dark Dimmed** ou **Dark High Contrast**).

---

## ✅ Conseils pour un rendu ultra clean

* **Pinned repos**: épingle 6 projets clés (avec logos/captures dans chaque README).
* Ajoute des **screenshots/GIF** courts dans les projets pour montrer l'UX.
* Utilise des **titles + descriptions** clairs et concis.
* Maintiens tes **commits** réguliers (la Snake animera mieux ta grille !).

---

> Si tu veux, je peux aussi te générer le **README de projet** pour `elegance` (badges, scripts d'installation, images, démo).

