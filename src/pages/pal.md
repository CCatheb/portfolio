---
layout: ../layouts/MarkdownLayout.astro
title: PAL 'Pile A Lire'
---
<script src="https://code.iconify.design/iconify-icon/1.0.7/iconify-icon.min.js"></script>


# Pile A Lire 'PAL' back-end

<div class="container">
  <div class="call-to-action mt-24 mb-32 flex flex-col items-center gap-12 rounded-xl p-12 md:p-24">
    <img src="/src/assets/img/pal-logo.png" alt="WoW Logo" width="350" />
  </div>
</div>
<style lang="scss">
  .call-to-action {
    color: var(--neutral-900);
    background-image: linear-gradient(40deg, var(--primary-100), var(--secondary-200));
  }
</style>


```bash
Projet toujours en cours
```

## Le projet

Pile A Lire 'PAL' est un projet porté par [Enora Lafforgue](https://enora-lafforgue.netlify.app/). Celui-ci a pour objectif de proposer une interface web permettant à l'utilisateur inscrit de renseigner les livres présents dans sa bibliothèque et d'en choisir un au hasard pour en débuter la lecture. 
PAL permet également de se tenir informé des dernières sorties chez les libraires.

<center><a href=""><iconify-icon icon="mdi:github" style="font-size: 40px"></iconify-icon></a></center>

## Mes tâches
J'ai été chargé du développement complet du back-end de ce projet, ce qui inclut:
- Récupération de données concernant les dernières sorties (scrapping web)
- Gestion de l'authentification de l'utilisateur
- Création de l'API pour la communication avec le front-end
- Création et gestion de la base de données

## Technologies 

<iconify-icon icon="mdi:language-python" style="font-size: 40px" placeholder="Python"></iconify-icon>
<iconify-icon icon="mdi:web" style="font-size: 40px"></iconify-icon>
<iconify-icon icon="mdi:database" style="font-size: 40px"></iconify-icon> 
<iconify-icon icon="mdi:api" style="font-size: 40px"></iconify-icon>