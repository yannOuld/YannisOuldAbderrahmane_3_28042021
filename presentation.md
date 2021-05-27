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
<p>
 integrations de maquettes et d'animations avec Sass  
 </p>
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
- animations de l'index
- animations des menus
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
 - vide
<!-- slide -->
### Elements possédants des animations
- nombres de la liste de l'index 
- boutons 
- icones (coeurs)
- titres des menus 
- liste des produits 
- produits 
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
- pseudo-classe hover et active
- superposition de deux icones 
- interchanger leur opacités 
- utilisation d'une transition transform scale (1.15)
<!-- slide -->
# underlines des menus 
- pseudo-elements before / after
- sans contenu
- width et height 
- position absolu left et bottom 0
<!-- slide -->
# apparition des produits
- une animation / keyframes translate sur axe Y avec des délais pour chaque produit
- une animation / keyframes pour le conteneur des produits qui gère la taille et l'opacité 
- utilisation d'animation-fill mode:both pour un rendu naturel 
<!-- slide -->
# produits 
- pseudo-classe hover
- overflow hidden 
<!-- slide -->
## textes 
- diminution du width via un calc
<!-- slide -->
## div de l'icone
- position absolute right proportionnel a sa largeur  
- rotation de l'icone avec une transition transform rotate 