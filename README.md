# Search-action

<p align="center">
    <img src="https://img.shields.io/github/license/your-username/education-research-guide?style=flat-square" alt="Licence MIT" />
    <img src="https://img.shields.io/github/workflow/status/your-username/education-research-guide/Deploy%20to%20GitHub%20Pages?label=build&style=flat-square" alt="Statut Build" />
    <img src="https://img.shields.io/badge/accessibility-AA%20WCAG%202.1-blueviolet?style=flat-square" alt="Accessibilité AA" />
    <img src="https://img.shields.io/github/v/release/your-username/education-research-guide?style=flat-square" alt="Dernière version" />
</p>


# 🌍 Education Research Guide

<p align="center">
    <img src="docs/demo-screenshot.png" alt="Aperçu du site" width="600" />
</p>



**Education Research Guide** est une plateforme open source interactive pour apprendre, pratiquer et enseigner la méthodologie de recherche action en éducation.

Pensée pour :
- **Étudiants** (futurs enseignants, conseillers d'orientation, éducateurs...)
- **Enseignants & Formateurs**
- **Chercheurs en éducation**

Le guide propose un parcours progressif, des outils interactifs, et des ressources pédagogiques pour rendre la recherche accessible à tous.



🔗 **Démo en ligne** : [Accéder au site](https://your-username.github.io/education-research-guide/)

♿ **Accessibilité** : Compatible lecteurs d’écran, navigation clavier, contrastes adaptés

---

## 📋 Table des Matières

- [📦 Prérequis](#-prérequis)
- [🛠️ Technologies utilisées](#️-technologies-utilisées)
- [🚀 Fonctionnalités](#-fonctionnalités)
- [📂 Structure](#-structure)
- [⚙️ Installation](#️-installation)
- [🌐 Déploiement](#-déploiement)
- [🛡️ Accessibilité](#️-accessibilité)
- [🤝 Contribuer](#-contribuer)
- [📜 Licence](#-licence)
- [🙌 Crédits](#-crédits)
- [📸 Captures d'écran](#-captures-décran)
- [⭐ Pourquoi ?](#-pourquoi-)

---

## 📦 Prérequis

- [Node.js](https://nodejs.org/) >= 18.x
- [npm](https://www.npmjs.com/) >= 9.x
- Navigateur moderne (Chrome, Firefox, Edge, Safari)

## 🛠️ Technologies utilisées

- **React**
- **React Router**
- **Tailwind CSS**
- **Jest** (tests unitaires)
- **GitHub Actions** (CI/CD)

---

## 🚀 Fonctionnalités

- 📖 **Parcours structuré** : phases de la recherche (Conceptuelle → Diffusion)  
- ✅ **Checklists interactives** pour chaque étape  
- 🎯 **Mini-QCM** pour auto-évaluation  
- 📊 **Ressources pédagogiques** (protocoles, consentements, grilles, exemples)  
- 🖨️ Export PDF du guide  
- ♿ **Accessibilité renforcée** : ARIA, navigation clavier, contraste, transcripts  

---

## 📂 Structure

```bash
src/
 ├── components/   # Composants UI (Checklist, QCM, Navigation)
 ├── pages/        # Pages du guide (Conceptuelle, Méthodologique…)
 ├── App.jsx       # Routage principal
 └── main.jsx      # Entrée React
```

---

## ⚙️ Installation

### Cloner le dépôt
```bash
git clone https://github.com/your-username/education-research-guide.git
cd education-research-guide
```

### Installer les dépendances
```bash
npm install
```

### Lancer en local
```bash
npm run dev
```

### Build pour production
```bash
npm run build
```

---

## 🌐 Déploiement sur GitHub Pages

Le projet utilise GitHub Actions pour builder et déployer automatiquement.

Branche main → build → publication sur gh-pages.

Vérifiez le fichier : .github/workflows/deploy.yml

---

## 🛡️ Accessibilité (A11y)

Compatible NVDA / JAWS / VoiceOver

Navigation clavier (Tab / Shift+Tab)

Balises ARIA et rôles sémantiques

Contrastes conformes WCAG 2.1 AA

Transcriptions disponibles pour tout contenu audio/vidéo

---

## 🤝 Contribuer

Les contributions sont les bienvenues ! 🎉

**Comment contribuer ?**

1. Forkez le repo
2. Créez une branche `feature/ma-fonctionnalite`
3. Décrivez clairement votre modification dans le commit
4. Poussez la branche et ouvrez une Pull Request

**Idées de contributions :**
- Corriger des bugs
- Améliorer l’accessibilité
- Ajouter des exemples ou ressources
- Traduire le guide

Merci de consulter le fichier [CONTRIBUTING.md](CONTRIBUTING.md) si disponible, ou d’ouvrir une issue pour toute question !

---

## 📜 Licence

MIT License
 – libre, gratuit et ouvert à tous.

---

## 🙌 Crédits

Inspiré par :
- Guides méthodologiques en éducation (recherches en sciences de l'éducation, sociologie, pédagogie)
- Supports pédagogiques universitaires (ESPE, Inspé, Sciences de l'éducation)
- Communauté open source

---

## 📸 Captures d'écran

<p align="center">
    <img src="docs/step-list.png" alt="Étapes du guide" width="350" />
    <img src="docs/checklist-demo.png" alt="Checklist interactive" width="350" />
</p>

---

## ⭐ Pourquoi ?

La recherche en éducation est essentielle pour :

Améliorer la qualité de l'enseignement et de l'apprentissage

Développer des pratiques fondées sur des données probantes (Evidence-Based Education)

Transformer les pratiques pédagogiques par l'analyse réflexive

Former les futurs enseignants et formateurs à la rigueur scientifique

Avec ce guide, chacun peut apprendre, pratiquer et partager ses connaissances.


