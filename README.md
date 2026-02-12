<p align="center">
   <img src="https://github.com/srakotoarison/.Files/blob/main/PowerAutomate_scalable.svg" width="80px" />

</p>

<h2 align="center">
Protéger nos tout‑petits : Surveillance automatique des rappels Conso </h2>
<br>



<p align="center">Une solution low-code basée sur Power Automate et pensée pour la tranquillité d'esprit des parents. Automatisation Power Automate pour surveiller les rappels RappelConso du site https://rappel.conso.gouv.fr/ Automatiser la veille des rappels produits pour bébés. Ce projet montre comment le low‑code peut simplifier la vie de parents.</p>

<br>

#### Contexte
Avec la multiplication des rappels de produits pour bébés — notamment certains lots de laits infantiles comme Gallia ou Guigoz — j’ai réalisé, en tant que jeune parent, combien il est essentiel d’être informé rapidement et de manière fiable. La sécurité des tout‑petits ne laisse aucune place au hasard, et manquer une alerte peut avoir des conséquences importantes.
Pour éviter toute omission et gagner en sérénité, j’ai décidé d’automatiser cette veille. Ce projet repose sur Power Automate, qui récupère automatiquement les alertes du flux RSS officiel de RappelConso et nous notifie dès qu’un rappel touche un produit destiné aux bébés.
Une solution simple, mais qui apporte un vrai sentiment de sécurité au quotidien.


#### Vue d'ensemble

<div style="background:#F3F2F1; padding:20px; border-radius:8px;">
  <p>
    Ce projet utilise <strong>Power Automate</strong> pour automatiser la surveillance des rappels de produits potentiellement dangereux pour les bébés via le flux RSS officiel <strong>RappelConso</strong>.  Il illustre la capacité du low-code à résoudre des besoins concrets du quotidien </p>



#### Fonctionnement du flux

<!-- BLOC PRINCIPAL -->
<div style="background:#F3F2F1; padding:20px; border-radius:8px;">

  <ul style="border-left: 4px solid #4CC9F0; padding-left: 15px; list-style:none;">

<li style="margin-bottom:15px;">
  <strong style="color:#0078D4;">Lecture RSS : </strong> Récupération automatique à chaque nouveaux rappel du produit pour Bébé.
</li>


<li style="margin-bottom:5px;">
  <strong style="color:#4CC9F0;">Email HTML :</strong>
  Génération et envoi d’un e‑mail d'alerte personnalisé en HTML avec intégration d'un logo en base64.
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
Vous pouvez adapter le flux, ajouter des conditions, changer l’HTML ou étendre l'alerte à d’autres types de rappels ous pouvez ajouter d’autres filtres (allergènes, jouets, puériculture…).Vous pouvez adapter ce flux pour d’autres types d’alertes RappelConso.N’hésitez pas à partager vos idées !

<p align="center">
  Développé avec ❤️ par Sammy
</p>

