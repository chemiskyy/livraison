---
title: "Fichier de commande"
layout: single
permalink: /documentation/excel/
last_modified_at: 2018-01-10T11:22:24-05:00
toc: false
sidebar:
  title: "Documentation"
  nav: sidebar-sample
---

<script type="text/javascript" async
  src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-MML-AM_CHTML">
</script>

A l'aide de votre tableur préféré, vous pouvez préparer un fichier de commandes contenant les informations suivantes colonnes: 

- Nº : Numéro de livraison
- Nom : Nom du client
- Prénom : Prénom du client (peut rester vide)
- Adresse : Adresse du client
- CP : Code postal du client
- Ville : Ville du client
- Tel : Numéro de téléphone du client
- Type : Si vous avez des livraisons à domicile et du drive et que toutes vos données sont dans un fichier, mettez "L" pour la livraison et "R" pour un retrait au magasin. La carte va générer des points uniquement pour les livraisons à doomicile, donc avec un "L" dans cette colonne)
- Qté totale : Quantité à livrer (en cartons, colis, nombre de produits)
- Commentaires : Si des instructions sont spécifiques pour la livraison, elles seront rajoutées sur la carte

**Attention** vous devez placer en premiere ligne les titres des colonnes **exactement** comme indiqué ci-dessus. Sinon le code ne pourra pas fonctionner. Me contacter si vous voulez un exemple de fichier tableur (Excel ou OpenOffice) qui fonctionne.

Vous devriez avoir un fichier qui ressemble à celui-ci

|Nº  |Type     |Commentaires|Prénom   |Nom       |Tel       |Adresse                 |Ville            |CP   |Qté totale|
|----|---------|------------|---------|----------|----------|------------------------|-----------------|-----|----------|
|1419|Livraison|code 0849   |Martin   |Pêcheur   |0642905254|25 rue Bellevue         |Montigny-les-Metz|57950|24        |
|1417|Retrait  |            |Elisabeth|THEQUEEN  |0636096600|56 avenue de Nancy      |METZ             |57000|12        |
|1420|Livraison|            |John     |LENNON    |0639098802|5 rue du Moyen Pont     |METZ             |57000|12        |
|1421|Livraison|            |Lemmy    |KILMEISTER|0666097562|32, rue de Metz         |BOUSSE           |57310|12        |
|1422|Livraison|            |Johnny   |CASH      |0622134456|6, rue des trois Évêchés|METZ             |57070|12        |
|1422|Livraison|            |La       |RACLURE   |0612844564|4 rue Turgot            |METZ             |57070|24        |
