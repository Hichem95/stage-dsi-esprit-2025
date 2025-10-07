<!-- 🌐 README professionnel - Projet de Stage DSI ESPRIT (style rouge & gris) -->

<p align="center">
  <img src="docs/images/esprit-logo.png" alt="Logo ESPRIT" width="160">
</p>


<h1 align="center" style="color:#c80000;">🎓 Stage DSI ESPRIT 2025</h1>
<h3 align="center" style="color:#555;">Entrepôt de Données Académique et Reporting Power BI</h3>

---

<p align="center">
  <img src="docs/images/pentaho.png" alt="Pentaho" height="28">
  &nbsp;&nbsp;&nbsp;
  <img src="docs/images/postgresql.png" alt="PostgreSQL" height="28">
  &nbsp;&nbsp;&nbsp;
  <img src="docs/images/powerbi.png" alt="Power BI" height="28">
  &nbsp;&nbsp;&nbsp;
  <img src="docs/images/github.png" alt="GitHub" height="28">
</p>

---

## 🧠 Présentation

Ce projet est réalisé dans le cadre du **stage ingénieur à la DSI d’ESPRIT**.  
Il consiste à concevoir un **entrepôt de données académique** complet et automatisé, accompagné de **tableaux de bord Power BI** pour le suivi des indicateurs clés.

🎯 **Objectif principal :**
> Construire une infrastructure BI permettant la centralisation, la transformation et la visualisation des données académiques.

---

## 🧰 Stack Technique

| Domaine | Outil / Technologie |
|:--|:--|
| **ETL / Intégration** | Pentaho PDI (Kettle) |
| **Base de données** | PostgreSQL |
| **Visualisation / BI** | Power BI Desktop |
| **Langages** | SQL, Bash, Python |
| **Versionnement** | Git & GitHub |

---

## 🧱 Structure du dépôt

<details>
<summary><b>📂 Voir la structure complète</b></summary>

<br>

```bash
stage-dsi-esprit-2025/
│
├── 🧩 pentaho/           # Jobs & Transformations (.ktr / .kjb)
├── 🗄️ sql/               # Scripts SQL (DDL, DML, vues, seeds)
├── 📊 powerbi/           # Rapports Power BI (.pbix)
├── 📚 docs/              # Journal de bord, schémas techniques, images
│   └── images/           # Logos, architecture, workflow
├── 📁 data/              # Jeux de données anonymisés
│
├── .gitignore
├── .gitattributes
└── README.md
```

</details>

---

## 📊 Architecture du Projet

<p align="center">
  <img src="docs/images/architecture.png" width="750" alt="Architecture du projet">
</p>

**🧩 Description du flux :**
1. Extraction des données sources académiques vers la *Staging Area (SA)*.  
2. Nettoyage, transformation et chargement vers le *Data Warehouse (DW)*.  
3. Visualisation et analyse dans Power BI avec indicateurs dynamiques.  

---

## ⚙️ Fonctionnalités Clés

- 🔄 **Processus ETL automatisé** (de la SA vers le DW).  
- 🧹 **Nettoyage et normalisation** des données académiques (notes, modules, étudiants).  
- 🧩 **Modélisation dimensionnelle** en étoile (dimensions et faits).  
- 📈 **Tableaux de bord Power BI** interactifs pour la direction et les départements.  
- 🧾 **Documentation et journal de bord** détaillant chaque étape du flux.  

---

## 🤝 Encadrement

- 👨‍💼 **Encadrant professionnel :** Équipe DSI ESPRIT  
- 👨‍🏫 **Encadrant académique :** Département BI & Data Science  
- 👨‍💻 **Stagiaire :** *Yosra Challakhi*

---

## 🏁 Livrables

- 📦 Entrepôt de données PostgreSQL (schéma SA & DW)  
- ⚙️ Jobs Pentaho ETL complets  
- 📊 Tableau de bord Power BI interactif  
- 🗒️ Documentation technique et rapport de stage  

---

## 💡 Outils et Environnement

<p align="center">
  <img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Pentaho%20PDI-orange?style=for-the-badge&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAoAAAAKCAYAAACNMs+9AAAAHElEQVQYV2NkQAP/GaIY/jNgQAcYBoYIg4HAAJ6UBQPw2zjUAAAAASUVORK5CYII=" />
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/GitHub-black?style=for-the-badge&logo=github&logoColor=white" />
</p>

---

## 🧾 Extrait du Workflow ETL

<p align="center">
  <img src="docs/images/pentaho.png" width="750" alt="Workflow Pentaho">
</p>
*(Capture du job Pentaho représentant le flux SA → DW)*

---

<p align="center">
  <a href="https://www.linkedin.com/in/yousra-challekh-b2722427b/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Yosra%20Challakhi-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Made%20with%20❤️%20at-ESPRIT-c80000?style=for-the-badge" />
</p>

<p align="center" style="color:#777;">
  © 2025 Yosra Challakhi — Projet académique sous encadrement DSI ESPRIT
</p>
