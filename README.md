<p align="center">
   <img src="https://github.com/srakotoarison/.Files/blob/main/PowerAutomate_scalable.svg" width="80px" />

</p>

<h2 align="center">
Protéger nos tout‑petits : Surveillance automatique des Rappel Conso </h2>
<br>



<p align="center">Une solution low-code basée sur Power Automate, conçue pour la tranquillité d’esprit des parents. Elle permet d’automatiser la surveillance des rappels produits pour bébés via le site rappel.conso.gouv.fr. Ce projet illustre comment le low-code peut simplifier le quotidien des parents.</p>

<br>

#### Contexte
Avec la multiplication des rappels de produits pour bébés — notamment certains lots de laits infantiles (Gallia, Guigoz, etc.) — j’ai réalisé, en tant que jeune parent, à quel point il est essentiel d’être informé rapidement et de manière fiable. La sécurité des tout‑petits ne laisse aucune place au hasard, et manquer une alerte peut avoir des conséquences graves. Pour éviter toute omission et gagner en sérénité, j’ai décidé d’automatiser cette veille. Ce projet repose sur Power Automate, qui récupère automatiquement les alertes du flux RSS officiel de RappelConso et nous notifie dès qu’un rappel touche un produit destiné aux bébés.
Une solution simple, mais qui apporte un vrai sentiment de sécurité au quotidien.


#### Vue d'ensemble

<div style="background:#F3F2F1; padding:20px; border-radius:8px;">
  <p> Ce projet utilise Power Automate pour automatiser la surveillance des rappels de produits potentiellement dangereux pour les bébés, via le flux RSS officiel de <strong>Rappel Conso</strong> Il illustre la capacité du low-code à résoudre des besoins concrets du quotidien.

  
#### Fonctionnement du flux

<!-- BLOC PRINCIPAL -->
<div style="background:#F3F2F1; padding:20px; border-radius:8px;">

  <ul style="border-left: 4px solid #4CC9F0; padding-left: 15px; list-style:none;">

<li style="margin-bottom:15px;">
  <strong style="color:#0078D4;">Lecture RSS : </strong> Récupération automatique à chaque nouveau rappel du produit pour bébé.
</li>


<li style="margin-bottom:5px;">
  <strong style="color:#4CC9F0;">Email HTML :</strong>
  génération et envoi d’un email d’alerte personnalisé (format HTML), incluant un logo encodé en base64.
</li>

  </ul>

</div>

<br>

<!-- BLOC IMPORTANT -->
<div style="background:#FFF8C5; border-left:6px solid #FFD33D; padding:12px 15px; border-radius:6px;">
  <strong>⚠️ Important :</strong> Ce projet utilise le flux RSS officiel de <strong>RappelConso</strong>.
</div>

<br>




#### 📸 Aperçus de la solution

<div align="center" style="padding:20px; border:1px solid #ddd; border-radius:10px;">
  <p></p>
</div>



<table>
<tr>
<td width="50%"  align="center"> 
  <img src="https://github.com/srakotoarison/PowerAutomate-RappelConsommateurRSS/blob/main/Flow.png" width="75%" >
</td>
<td width="50%"  align="center">
  <img src="https://github.com/srakotoarison/PowerAutomate-RappelConsommateurRSS/blob/main/Mail.png" width="65%">
</td>
</tr>
</table>


<p align="center">
  <a href="https://github.com/srakotoarison/PowerAutomate-RappelConsommateurRSS/tree/main/PowerAutomate" style="background:#4361ee; padding:12px 25px; color:white; border-radius:8px; text-decoration:none; font-weight:600;">
    📥 Télécharger le flux Power Automate
  </a>
</p>


#### 🚀 Installation
1. Télécharger les fichiers `.zip` depuis le dossier **flows**
2. Aller dans **Power Automate → My Flows → Import Package (Legacy)**
3. Mettre à jour les connexions (RSS, Outlook…)
4. Modifier les adresses e-mail de réception

#### 💬 Suggestions et améliorations
 Vous pouvez adapter ce flux : ajouter des conditions, modifier le template HTML, étendre les alertes à d’autres types de rappels (allergènes, jouets, puériculture, etc.), ou encore ajouter des filtres personnalisés. Ce flux peut aussi être adapté pour d’autres types d’alertes RSS. N’hésitez pas à partager vos idées et améliorations !


<p align="center">
  Développé avec ❤️ par Sammy
</p>

