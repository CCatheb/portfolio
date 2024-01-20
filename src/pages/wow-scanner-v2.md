---
layout: ../layouts/MarkdownLayout.astro
title: WoW Scanner V2
---
<script src="https://code.iconify.design/iconify-icon/1.0.7/iconify-icon.min.js"></script>

# WoW Scanner V2 


<div class="container">
  <div class="call-to-action mt-24 mb-32 flex flex-col items-center gap-12 rounded-xl p-12 md:p-24">
    <img src="/src/assets/img/World_of_Warcraft_Logo.png" alt="WoW Logo" width="350" />
  </div>
</div>

<style lang="scss">
  .call-to-action {
    color: var(--neutral-900);
    background-image: linear-gradient(40deg, var(--primary-100), var(--secondary-200));
  }
</style>


## Le projet

WoW Scanner V2 est un script Python ayant pour objectif de tracker le prix minimum, moyen, et maximum des objets mis en vente à l'hotel des ventes, sur le jeu World of Warcraft.

Le script utilise l'API REST fournie par Blizzard afin de récupérer les données directement sur les seveurs. Le script est personnalisable, et prend en charge:
- Le tracking de tous les objets, du moment qu'ils ont un identifiant, et qu'ils sont en vente
- Le tracking sur tous les serveurs Européens
- Le tracking du prix minimum, moyen et le plus élevé.

A ce script Python est couplé une base de données InfluxDb, en charge de stocker et de horodater les données.
Un Grafana est également mis en place pour l'affichage de tout ceci.

<center><a href="https://github.com/CCatheb/wow-Scanner2"><iconify-icon icon="mdi:github" style="font-size: 40px"></iconify-icon></a></center>




## Mes tâches
- Récupération de données via l'API
- Nettoyage des données, sortie des éléments inutiles
- Mise en place de la BDD InfluxDb & du Grafana
- Déploiement sur un serveur 24/7 assuré par une Raspberry Pi 4

## Technologies 

<iconify-icon icon="mdi:language-python" style="font-size: 40px" placeholder="Python"></iconify-icon>
<iconify-icon icon="mdi:server" style="font-size: 40px"></iconify-icon>
<iconify-icon icon="mdi:database" style="font-size: 40px"></iconify-icon> 
<iconify-icon icon="mdi:api" style="font-size: 40px"></iconify-icon>