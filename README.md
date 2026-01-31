<div align="center">
  <a href="https://drasiotech.dev">
    <img src="https://drasiotech.dev/favicon.png" alt="Logo Drasiotech" width="80" height="80">
  </a>

  <h1 align="center">Drasiotech.dev</h1>

  <p align="center">
    <strong>L'Art de la Performance Web & du SEO Technique</strong>
    <br />
    Architecture Serverless • Vanilla JS • Edge Network
  </p>

  <p align="center">
    <a href="https://drasiotech.dev"><strong>Voir le site en Live »</strong></a>
    <br />
    <br />
    <img src="https://img.shields.io/badge/Lighthouse-100%2F100-success?style=for-the-badge&logo=google-lighthouse" alt="Lighthouse Score" />
    <img src="https://img.shields.io/badge/Vercel-Deployed-000000?style=for-the-badge&logo=vercel" alt="Vercel Deployment" />
    <img src="https://img.shields.io/badge/Security-HSTS%20Preload-blue?style=for-the-badge&logo=letsencrypt" alt="Security" />
  </p>
</div>

---

## ⚡ À propos du projet

**Drasiotech** est une démonstration technique radicale réalisée dans le cadre du BTS SIO SLAM.
À une époque où le web est alourdi par des frameworks complexes, ce projet prend le contre-pied : **revenir aux fondamentaux pour une performance absolue.**

L'objectif ? Prouver qu'une stack native (HTML5/CSS3/JS) couplée à une infrastructure Edge (Vercel) surpasse les solutions modernes en termes de vitesse, de SEO et d'éco-conception.

### 🎯 Les Scores (Audit Lighthouse)
| Métrique | Score | Impact |
| :--- | :---: | :--- |
| **Performance** | 🟢 **100** | Chargement instantané (< 0.5s LCP) |
| **Accessibilité** | 🟢 **100** | Compatible lecteurs d'écran & navigation clavier |
| **Best Practices** | 🟢 **100** | HTTPS, HSTS, pas de vulnérabilités |
| **SEO** | 🟢 **100** | Données structurées (JSON-LD) & balisage sémantique |

---

## 🛠️ Stack Technique

Ce projet suit la philosophie **"Zero Bloat"**. Aucune librairie inutile.

* **Core :** ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) (Vanilla ES6+)
* **Build Tool :** ![Webpack](https://img.shields.io/badge/Webpack-8DD6F9?style=flat-square&logo=webpack&logoColor=black) (Minification & Bundling)
* **Hosting & Edge :** ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white) (Serverless Functions & CDN)
* **Sécurité :** WAF Vercel, HSTS Preload, DDoS Mitigation.

---

## 🚀 Fonctionnalités Clés

### 🧠 SEO "Grey Hat" & White Hat
* **Entity Stacking :** Implémentation de schémas JSON-LD complexes liant l'organisation aux profils fondateurs (GitHub/LinkedIn).
* **Edge SEO :** Utilisation de `vercel.json` pour injecter des headers de cache agressifs (`stale-while-revalidate`) et des balises `X-Robots-Tag`.
* **SGE Optimized :** Structure HTML (`<dl>`, `<table>`) optimisée pour les réponses des IA génératives (Google SGE, ChatGPT).

### 🛡️ Cybersécurité Active
* **Bot Protection :** Filtrage des requêtes via TLS Fingerprinting pour bloquer les scripts Python/Curl.
* **No-Sniff & CSP :** En-têtes de sécurité stricts pour prévenir les attaques XSS et MIME-sniffing.

### 🎮 Rétention Utilisateur (Page 404)
Une page 404 interactive intégrant un **Snake Game** complet en Vanilla JS (< 4ko) pour transformer une erreur en opportunité de Dwell Time.

---

## 💻 Installation Locale

Si vous souhaitez auditer le code ou tester la performance en local :

```bash
# 1. Cloner le repo
git clone [https://github.com/NyloodzZ/drasiotech.git](https://github.com/NyloodzZ/drasiotech.git)

# 2. Installer les dépendances (Webpack)
npm install

# 3. Lancer le serveur de développement
npm start
```
## 👤 Auteurs

**Clément DELACOUX / Gabriel MANSET**

* [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/TonPseudo)
* [![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@drasiotech_officiel)
* [![Website](https://img.shields.io/badge/Portfolio-Drasiotech.dev-0070f3?style=for-the-badge&logo=vercel&logoColor=white)](https://drasiotech.dev)

---

<div align="center">
  <sub>Projet académique - BTS SIO SLAM 2025</sub>
  <br>
  <small>Designed & Engineered with precision.</small>
</div>

