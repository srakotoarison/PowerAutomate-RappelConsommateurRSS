
<h1 align="center">🔔 Protéger nos tout‑petits</h1>
<p align="center">Automatisation Power Automate pour surveiller les rappels RappelConso</p>

<p align="center">
  <img src="https://via.placeholder.com/800x250/2d89ef/ffffff?text=Header+Image" width="80%">
</p>

<hr style="border: 0; border-top: 1px dashed #bbb;" />
<div style="border:1px solid #e1e4e8; border-radius:8px; padding:16px;">
  <h3>🚀 Objectif</h3>
  <p>Créer une veille automatique des rappels pour bébés via Power Automate.</p>
</div>

<h2 align="center">✨ Fonctionnement du flux ✨</h2>

<div align="center" style="padding:20px; border:1px solid #ddd; border-radius:10px;">
  <h3>🔔 Une vraie aide au quotidien</h3>
  <p>Ce projet montre comment le low‑code peut simplifier la vie de parents.</p>
</div>



<table>
<tr>
<td width="33%">
  <img src="https://via.placeholder.com/300x180" width="100%">
  <h3 align="center">1. Lecture RSS</h3>
  <p align="center">Le flux récupère automatiquement les alertes RappelConso</p>
</td>
<td width="33%">
  <img src="https://via.placeholder.com/300x180" width="100%">
  <h3 align="center">2. Filtrage</h3>
  <p align="center">Seules les alertes liées aux produits bébés sont conservées</p>
</td>
<td width="33%">
  <img src="https://via.placeholder.com/300x180" width="100%">
  <h3 align="center">3. Email HTML</h3>
  <p align="center">Un mail clair et lisible est envoyé automatiquement</p>
</td>
</tr>
</table>

<p align="center">
  <img src="https://svg-badge.vercel.app/api/badge?text=Power%20Automate&colorA=f72585&colorB=7209b7&colorC=3a0ca3" />
</p>


> ### 💡 Astuce  
> Vous pouvez adapter ce flux pour d’autres types d’alertes RappelConso.

## 🚨 — Fonctionnement du flux — 🚨

<p align="center">
  <img src="https://via.placeholder.com/350x200" width="45%">
  <img src="https://via.placeholder.com/350x200" width="45%">
</p>



<div align="center">
  <img src="https://via.placeholder.com/300x180" width="30%" style="border-radius:10px; margin:0 10px;">
  <img src="https://via.placeholder.com/300x180" width="30%" style="border-radius:10px; margin:0 10px;">
  <img src="https://via.placeholder.com/300x180" width="30%" style="border-radius:10px; margin:0 10px;">
</div>




![Power Automate](https://img.shields.io/badge/Power_Automate-0066FF?style=for-the-badge&logo=powerautomate&logoColor=white)
![RSS](https://img.shields.io/badge/RSS-FFA500?style=for-the-badge&logo=rss&logoColor=white)
![HTML Email](https://img.shields.io/badge/Email-HTML-blueviolet?style=for-the-badge)


# 🔔 Protéger nos tout‑petits avec Power Automate

## Automatiser la veille des rappels produits pour bébés

![Dashboard Power Automate](./docs/screenshot-dashboard.png)
*Exemple fictif de tableau de bord Power Automate*

---
## 🌱 Contexte
Avec les récents rappels de produits pour bébés, il est devenu essentiel d'être informé rapidement. Ce projet utilise **Power Automate** pour envoyer automatiquement les alertes RSS du site **RappelConso** lorsqu'un rappel concerne des produits destinés aux tout‑petits.

---
## 🤖 Fonctionnement du flux

### 1. Récupération du flux RSS
![Bloc RSS Power Automate](./docs/screenshot-rss.png)
*Capture fictive du connecteur RSS dans Power Automate*

### 2. Filtrage des rappels liés aux produits bébés
![Filtrage Power Automate](./docs/screenshot-filter.png)
*Exemple visuel fictif du filtrage dans Power Automate*
### 3. Envoi d’un e-mail HTML personnalisé

<p>
  <img src="https://github.com/srakotoarison/PowerAutomate-RappelConsommateurRSS/blob/main/Mail.PNG" alt="Dashboard" width="48%" />
  <img src="https://github.com/srakotoarison/PowerAutomate-RappelConsommateurRSS/blob/main/Mail.PNG" alt="RSS" width="48%" />
</p>




<div style="display: flex; justify-content: space-between;">
  <div style="width: 32%; text-align: center;">
    <img src="https://github.com/srakotoarison/PowerAutomate-RappelConsommateurRSS/blob/main/Mail.PNG" alt="Dashboard" width="48%">
    <p><em>Dashboard Power Automate</em></p>
  </div>

  <div style="width: 32%; text-align: center;">
    <img src="https://github.com/srakotoarison/PowerAutomate-RappelConsommateurRSS/blob/main/Mail.PNG" alt="Filtrage" width="48%">
    <p><em>Bloc de filtrage</em></p>
  </div>

  <div style="width: 32%; text-align: center;">
    <img src="./docs/screenshot-email.png" alt="Email" width="100%">
    <p><em>Email HTML généré</em></p>
  </div>
</div>

![Email HTML](https://github.com/srakotoarison/PowerAutomate-RappelConsommateurRSS/blob/main/Mail.PNG)
*Modèle fictif d’e-mail envoyé lors d’un rappel*

---
## 📁 Contenu du dépôt
```
📦 baby-product-recall-alert
 ┣ 📂 flows
 ┃ ┣ 📄 flux_principal.zip
 ┃ ┗ 📄 flux_secondaire.zip
 ┣ 📂 docs
 ┃ ┣ 🖼️ screenshot-dashboard.png
 ┃ ┣ 🖼️ screenshot-rss.png
 ┃ ┣ 🖼️ screenshot-filter.png
 ┃ ┗ 🖼️ screenshot-email.png
 ┣ 📄 email_template.html
 ┗ 📄 README.md
```

---
## 🚀 Installation
1. Télécharger les fichiers `.zip` depuis le dossier **flows**
2. Aller dans **Power Automate → Solutions → Importer**
3. Mettre à jour les connexions (RSS, Outlook…)
4. Modifier les adresses e-mail de réception

---
## 💬 Suggestions et améliorations
Vous pouvez adapter le flux, ajouter des conditions, changer l’HTML ou étendre l'alerte à d’autres types de rappels.

N’hésitez pas à partager vos idées !





# Power Automate : RSS Rappel Consommateur

🔔 Protéger nos tout‑petits avec Power Automate
Automatiser la veille des rappels produits liés aux bébés
🌱 Contexte
Avec les récents rappels de produits pour bébés — notamment certains lots de laits infantiles (Gallia, Guigoz, etc.) — j’ai réalisé, en tant que jeune parent, à quel point il est important d’être informé rapidement et de manière fiable.
Pour ne rien laisser passer, j’ai décidé d’automatiser cette veille.
## A propos
Creating a two-level navigation menu in Power Apps, without using a nested gallery 😱

Nested galleries are a common technique to create this kind of functionality. However, nested galleries demand increased loading resource and therefore can produce increased load times/performance issues.

## Solution
This solution features a component that acts as a two-level navigation menu, using only 1 gallery:

![image](https://github.com/srakotoarison/PowerAutomate-RappelConsommateurRSS/blob/main/Mail.PNG)

This technique could be extended with further levels. The key is how to structure the data that feeds the menu, using key attributes to drive functionality and formatting.

## Installation
Download the NestedNavigationMenu_1_0_0_2.zip file, then follow <a href="https://learn.microsoft.com/en-us/power-apps/maker/data-platform/import-update-export-solutions">this Microsoft Learn Article</a> to import the solution into your chosen environment.

## Licence
This is free to use, no Power Platform licensing required.
