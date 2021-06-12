---
presentation:
  theme: beige.css
  progress: true
  slideNumber: true
  history: true
  keyboard: true
---

<!-- slide -->

# Projet 3

# Oh my food

integrations de maquettes et d'animations avec Sass

<!-- slide -->

# Sass

- separation des dossiers en 7 in 1
- separation entre l'index et le main
- separation des animations dans des fichiers distincts
- utilisation des placeholders uniquement pour l'usage de flexbox

<!-- slide -->

# Base

- fonts
- espacement et la disposition des elements

<!-- slide -->

# Components

- animation des coeurs
- animation des nombres de liste index
- animation loading spinner
- animation des localisations de restaurants
- animations des menus
- animation des underlines verts sur les titres
- animations des produits

<!-- slide -->

# Layout

- header et footer

<!-- slide -->

# Pages

- Index scss
- Index espacement et disposition

<!-- slide -->

# Utils

- variables
- mixins
- placeholders

<!-- slide -->

# Themes / Vendors

-vide

<!-- slide -->

## #Elements possédants des animations

- loading spinner
- liste des localisations
- nombres de la liste de l'index
- boutons
- icones (coeurs)
- titres des menus
- liste des produits
- produits

<!-- slide -->

# Loading spinner

- une div englobant le contenu du body avec une animation gerant l'opacité
- une div avec une animation a la proprieté visibility contenant un loader ayant une animation de rotation et un texte pour le chargement

<!-- slide -->

# Liste des localisations

- une list avec une visibility hidden contenant des ancres
- un bouton avec une pseudo-classe focus et un combinateur adjacent

<!-- slide -->

# nombres de liste

- pseudo-elements before
- contenu personalisé (number)
- position absolute

<!-- slide -->

# Boutons

- pseudo-classe active
- éclaircissement du background
- box-shadow légerement plus sombre

<!-- slide -->

# Icones Coeurs

- pseudo-classe hover
- superposition de deux icones
- interchanger leur opacités
- utilisation d'une transition transform scale

<!-- slide -->

# underlines des menus

- pseudo-elements before / after
- contenu sans nom
- position absolu left et bottom 0
- width et height

<!-- slide -->

# apparition des produits

- un keyframes pour le conteneur ul des produits qui gère l'opacité et height des wrappers
- un keyframes pour les li avec translates sur axe Y et des délais pour chaque produits
- utilisation d'animation-fill mode:both pour un rendu naturel

<!-- slide -->

# produits (li)

- pseudo-classe hover
- overflow hidden

<!-- slide -->

## contenu des textes produits 

- balises h4 pour les noms des produit et balises p contenant deux spans pour les ingredients et leurs coûts 
- diminution du width via un calc des ingredients et leurs noms 

<!-- slide -->

## animation de l'icone de validation

- position absolute right proportionnel a sa largeur pour le conteneur
- rotation de l'icone avec une transition transform rotate 360 degrées 
