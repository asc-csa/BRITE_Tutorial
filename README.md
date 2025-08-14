<p align="center">
    <a href="https://www.asc-csa.gc.ca/eng/satellites/brite/">
   <img src="https://www.asc-csa.gc.ca/images/recherche/hi-res/076c3dc0-3162-4aea-ae20-90fe768ab80a.jpg" alt="Image du BRITE | Image of BRITE" height=300>
    </a>
    <br> Crédit d'image | Image credit: <a href="https://www.asc-csa.gc.ca/eng/satellites/brite/">UTIAS Space Flight Laboratory</a>
</p>

<p align="center">
    <a href="#stars">
        <img alt="Étoiles sur GitHub | GitHub Repo stars" src="https://img.shields.io/github/stars/asc-csa/BRITE_Tutorial">
    </a>
    <a href="#watchers">
        <img alt="Spectateurs sur Github | GitHub watchers" src="https://img.shields.io/github/watchers/asc-csa/BRITE_Tutorial">
    </a>
    <a href="https://github.com/asc-csa/BRITE_Tutorial/commits/main">
        <img alt="Dernier commit sur GitHub | GitHub last commit" src="https://img.shields.io/github/last-commit/asc-csa/BRITE_Tutorial">
    </a>
    <a href="https://github.com/asc-csa/BRITE_Tutorial/graphs/contributors">
        <img alt="Contributeurs sur GitHub | GitHub contributors" src="https://img.shields.io/github/contributors/asc-csa/BRITE_Tutorial">
    </a>
    <a href="https://twitter.com/intent/follow?screen_name=csa_asc">
        <img alt="Suivre sur Twitter | Twitter Follow" src="https://img.shields.io/twitter/follow/csa_asc?style=social">
    </a>
</p>

---

<h3 align="center">
  <a href="#titre-du-projet">Français</a> |
  <a href="#project-title">English (follows)</a>
</h3>

---

<a id="titre-du-projet"></a>
# BRITE Constellation - Un tutoriel

> **Description brève :**
> Ce tutoriel aide les utilisateurs à exploiter les données ouvertes des courbes de lumière de la mission de la Constellation BRITE.

## À propos

**BRITE Constellation - Un tutoriel** est un tutoriel Jupyter Notebook qui guide les utilisateurs à travers l'exploitation des données ouvertes des courbes de lumière de la mission de la Constellation BRITE. Il couvre :

- Téléchargement des données depuis les archives publiques
- Traitement et analyse des courbes de lumière stellaires
- Techniques de détection d'exoplanètes
- Visualisation et interprétation des données photométriques

La mission Constellation BRITE utilise des nanosatellites pour étudier la variabilité stellaire et détecter des exoplanètes par la méthode des transits.

*Ce tutoriel est fourni à des fins pédagogiques et expérimentales.*

Pour plus d'informations :
- [CSA - BRITE](https://www.asc-csa.gc.ca/fra/satellites/brite/)
- [Équipe BRITE](https://brite-constellation.at/)

## Prérequis

- Python 3.9.18
- Jupyter Notebook ou Jupyter Lab
- Connexion Internet (pour le téléchargement des données)
- Bibliothèques d'analyse de données (NumPy, Matplotlib, Pandas)

## Démarrage rapide

1. 📦 **Cloner le dépôt**
   ```bash
   git clone https://github.com/asc-csa/BRITE_Tutorial.git
   cd BRITE_Tutorial
   ```
2. 🐍 **Créer un environnement**
   ```bash
   # Avec virtualenv
   python -m venv env
   source env/bin/activate

   # Ou avec conda
   conda create -n brite_env python=3.9.18
   conda activate brite_env
   ```
3. 📥 **Installer les dépendances**
   ```bash
   pip install -r requirements.txt
   ```
4. 🚀 **Lancer le tutoriel**
   ```bash
   jupyter notebook
   ```

> **Remarque :** Assurez-vous d'avoir accès aux archives publiques de données BRITE.

## Remerciements

Basé sur les données collectées par la mission du satellite BRITE Constellation, conçu, construit, lancé, exploité et soutenu par :
- Agence autrichienne de promotion de la recherche (FFG)
- Université de Vienne
- Université technique de Graz
- Agence spatiale canadienne (ASC)
- Institut d'études aérospatiales de l'Université de Toronto (UTIAS)
- Fondation pour la science et la technologie polonaise (FNiTP MNiSW)
- Centre national des sciences (NCN)

## Licence

Ce projet est sous une licence MIT modifiée – voir le fichier [LICENSE](https://github.com/asc-csa/BRITE_Tutorial/blob/main/LICENSE.txt) pour plus de détails.

---

<h3 align="center">
  <a href="#project-title">English </a> |
  <a href="#titre-du-projet">Français (précède)</a>
</h3>

---

<a id="project-title"></a>
# BRITE Constellation - A Tutorial

> **Brief description:**
> This tutorial helps users make use of the open lightcurve data from the BRITE Constellation Mission.

## About

**BRITE Constellation - A Tutorial** is a Jupyter Notebook tutorial that guides users through exploiting open lightcurve data from the BRITE Constellation Mission. It covers:

- Downloading data from public archives
- Processing and analyzing stellar lightcurves
- Exoplanet detection techniques
- Visualization and interpretation of photometric data

The BRITE Constellation mission uses nanosatellites to study stellar variability and detect exoplanets through the transit method.

*This tutorial is provided for educational and experimental purposes.*

More information:
- [CSA - BRITE](https://www.asc-csa.gc.ca/eng/satellites/brite/)
- [BRITE Team](https://brite-constellation.at/)

## Prerequisites

- Python 3.9.18
- Jupyter Notebook or Jupyter Lab
- Internet connection (for data download)
- Data analysis libraries (NumPy, Matplotlib, Pandas)

## Quick Start

1. 📦 **Clone the repo**
   ```bash
   git clone https://github.com/asc-csa/BRITE_Tutorial.git
   cd BRITE_Tutorial
   ```
2. 🐍 **Create environment**
   ```bash
   # Using virtualenv
   python -m venv env
   source env/bin/activate

   # Or using conda
   conda create -n brite_env python=3.9.18
   conda activate brite_env
   ```
3. 📥 **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
4. 🚀 **Run the tutorial**
   ```bash
   jupyter notebook
   ```

> **Note:** Ensure you have access to the BRITE public data archives.

## Acknowledgements

Based on data collected by the BRITE Constellation satellite mission, designed, built, launched, operated and supported by:
- Austrian Research Promotion Agency (FFG)
- University of Vienna
- Technical University of Graz
- Canadian Space Agency (CSA)
- University of Toronto Institute for Aerospace Studies (UTIAS)
- Foundation for Polish Science & Technology (FNiTP MNiSW)
- National Science Centre (NCN)

## License

This project is licensed under a modified MIT license - see the [LICENSE](https://github.com/asc-csa/BRITE_Tutorial/blob/main/LICENSE.txt) file for details.
