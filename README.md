
[![Netlify Status](https://api.netlify.com/api/v1/badges/0f2eed56-75a1-4771-8c6b-88c4023b617a/deploy-status)](https://app.netlify.com/sites/datalabanstat/deploys)

# 🌐 DataLab Website

Bienvenue sur le dépôt du **site web officiel du DataLab**, une initiative portée par le Système Statistique National (SSN) pour encourager les **échanges, expérimentations et innovations autour des données**.

Ce site, développé avec [Quarto](https://quarto.org/), sert de **plateforme collaborative** dédiée aux acteurs du SSN, aux chercheurs, aux ingénieurs de données, aux décideurs publics, ainsi qu’aux citoyens intéressés par l’usage des données dans la transformation numérique et le pilotage des politiques publiques.

## 🎯 Objectifs du site

- Offrir une vitrine sur les projets, initiatives et travaux du DataLab.
- Favoriser le partage d’expériences, de méthodes et d’outils innovants liés aux données.
- Soutenir la diffusion des résultats de recherche, des tableaux de bord, des APIs et des documents produits par le DataLab.
- Faciliter l’interconnexion des acteurs du SSN autour de problématiques concrètes.

## 🛠️ Technologies utilisées

- **[Quarto](https://quarto.org/)** : génération du site statique.
- **Markdown / Quarto Markdown (.qmd)** : rédaction du contenu.
- **GitHub Pages** : hébergement du site web.
- **R / Python (optionnel)** : pour l'intégration de données dynamiques ou de visualisations.

## 📁 Structure du dépôt

- `index.qmd` – Page d’accueil du site
- `about.qmd` – Présentation du DataLab
- `projets.qmd` – Projets innovants en cours
- `ressources.qmd` – Documents, outils, jeux de données
- `docs/` – Répertoire de déploiement GitHub Pages
- `_quarto.yml` – Configuration du site (menus, thèmes, etc.)

## 🚀 Lancer le site en local

Assurez-vous d’avoir installé Quarto sur votre machine :  
➡️ [Guide d'installation officiel](https://quarto.org/docs/get-started/)

Ensuite :

```bash
git clone https://github.com/cae-ins/datalabwebsite.git
cd datalabwebsite
quarto preview
