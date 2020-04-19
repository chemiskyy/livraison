---
title: "Enregistrement du fichier csv"
layout: single
permalink: /documentation/csv/
last_modified_at: 2018-01-10T11:22:24-05:00
toc: false
sidebar:
  title: "Documentation"
  nav: sidebar-sample
---

<script type="text/javascript" async
  src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-MML-AM_CHTML">
</script>

Une fois votre fichier de commandes préparés avec votre tableur favori (ou autre d'ailleurs), vous pouvez l'enregistrer au format CSV. Faites "Fichier -> enregistrez-sous" et dans le format, sélectionnez CSV UTF-8. Vérifiez bien que les séparateurs sont des ponts-virgules : **;**

Vous devriez obtenir un fichier qui ressemble à cela, et qui correspond à votre fichier issu du tableur

    Nº;Type;Commentaires;Prénom;Nom;Tel;Adresse;Ville;CP;Qté totale
    1419;Livraison;code 0849;Martin;Pêcheur;0642905254;25 rue Bellevue;Montigny-les-Metz;57950;24
    1417;Retrait;;Elisabeth;THEQUEEN;0636096600;56 avenue de Nancy;METZ;57000;12
    1420;Livraison;;John;LENNON;0639098802;5 rue du Moyen Pont;METZ;57000;12
    1421;Livraison;;Lemmy;KILMEISTER;0666097562;32, rue de Metz;BOUSSE;57310;12
    1422;Livraison;;Johnny;CASH;0622134456;6, rue des trois Évêchés;METZ;57070;12
    1422;Livraison;;La;RACLURE;0612844564;4 rue Turgot;METZ;57070;24

Le logiciel vous permet également d'effectuer des "tournées" de livraison, en séparant les clients par groupe. Vous pouvez numéroter les groupes en fonction des codes postaux. Voici un exemple au format tableur:

|CP   |Groupe|
|-----|------|
|57000|1     |
|57050|2     |
|57070|2     |
|57130|2     |
|57140|2     |
|57155|2     |
|57160|2     |
|57950|2     |

Et le fichier "groupes.csv" que vous devez préparer. **Attention** il faut que le fichier porte le nom "**groupes.csv**"

    CP;Groupe
    57000;1
    57050;2
    57070;2
    57130;2
    57140;2
    57155;2
    57160;2
    57950;2


