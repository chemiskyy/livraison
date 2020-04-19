---
layout: splash
header:
#  overlay_color: "#000"
#  overlay_filter: "0.5"
  overlay_image: /assets/images/layout_index.png
  cta_label: "Tester !"
  cta_url: "https://github.com/simcoon/simcoon/"
excerpt: "Créer des cartes interactives facilement pour livrer à domicile"
intro: 
- excerpt: 'Vous souhaitez livrer à domicile vos clients? Avec cette carte interactive vous pourrez facilement définir une carte de livraison avec les informations essentielles et la possibilité de connecter directement votre navigateur gps (sur téléphone). Voici comment procéder:'
feature_row:
  - image_path: assets/images/index/excel_logo.png
    alt: "Fichier de livraison"
    title: "Étape 1 : Fichier de livraison"
    excerpt: "A partir de votre site de réservation en ligne, ou de votre tableur préféré"
    url: "/documentation/excel"
    btn_label: "Détails"
    btn_class: "btn--primary"
  - image_path: /assets/images/index/csv_logo.png
    alt: "Transformer en fichier .csv"
    title: "Etape 2 : Transformer en fichier .csv"
    excerpt: "Enregistrer votre base de données de clients sous le format CSV (UTF-8) pour qu'il puisse être lu par le générateur de cartes de livraison"
    url: "/documentation/csv"
    btn_label: "Détails"
    btn_class: "btn--primary"
  - image_path: /assets/images/index/map_mini.png
    alt: "Générer la carte interactive"
    title: "Etape 3 : Générer la carte interactive"
    excerpt: "Téléversez votre fichier CSV et lancez le logiciel pour obtenir votre **carte interactive**"
    url: "/documentation/map"
    btn_label: "Détails"
    btn_class: "btn--primary"
feature_row2:
  - image_path: /assets/images/index/map_example.png
    alt: "Carte de livraison"
    title: "Carte de livraison"
    excerpt: "Cette carte de livraison se présente sous la forme d'un fichier html. Vous pouvez le télécharger sur votre téléphone portable pour l'utiliser pendant votre tournée de livraison"
    url: "/documentation"
    btn_label: "Détails"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

Cette carte:

- Attribue une couleur par "tournée" si vous ajoutez un fichier permettant d'affecter une tournée par code postal
- Effectue, pour chaque tournée, un calcul du plus cour chemin en fonction de votre point de départ de livraison. Chaque client se voit attribuer un numéro en fonction de l'ordre de livraison optimal. Vous pouvez ainsi ranger votre camionette en fonction de cet ordre :)
- Vous avez la possibilité de récupérer le fichier client mis dans l'ordre de la livraison. Pratique pour éditer des factures ;)
- Ajoute un icone pour chaque client à livrer sur la carte (avec le numéro d'ordre)
- En cliquand sur chaque icone, vous avez un lien permettant de démarrer l'application gps de Google. Vous pouvez donc obtenir le trajet vers le prochain client automatiquement!
- **Bonne livraison!**

