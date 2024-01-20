---
layout: ../layouts/MarkdownLayout.astro
title: ChooseMeAGame
---
<script src="https://code.iconify.design/iconify-icon/1.0.7/iconify-icon.min.js"></script>

# ChooseMeAGame
<div class="container">
  <div class="call-to-action mt-24 mb-32 flex flex-col items-center gap-12 rounded-xl p-12 md:p-24">
    <img src="/src/assets/img/steam_logo.png" alt="WoW Logo" width="350" />
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

ChooseMeAGame est un script Python ayant pour intérêt de sélectionner un jeu dans la bibliothèque Steam de l'utilisateur, en fonction de différents paramètres
tels que le type de jeu (RPG, FPS, solo, coopération, etc) ainsi que sa durée de vie.

Pour ce faire, ChooseMeAGame utilise l'API de la plate-forme Steam afin d'être capable d'accéder à la bibliothèque. Par la suite, le script est chargé de traiter
les données reçues, et de sélectionner un jeu au hasard parmis ceux qui ont été pré-sélectionnés.

<center><a href="https://github.com/CCatheb/wow-Scanner2"><iconify-icon icon="mdi:github" style="font-size: 40px"></iconify-icon></a></center>

## Mes tâches
- Récupération des données via API Steam (inclus gestion de l'authentification à l'API)
- Traitement des données
- Sélection du jeu

## Technologies 

<iconify-icon icon="mdi:language-python" style="font-size: 40px" placeholder="Python"></iconify-icon>
<iconify-icon icon="mdi:database" style="font-size: 40px"></iconify-icon> 
<iconify-icon icon="mdi:api" style="font-size: 40px"></iconify-icon>