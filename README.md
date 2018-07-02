# Exercices HTML/CSS 2

## Démarrage

```bash
git clone https://github.com/simplon-roanne/html-css-2
cd html-css-2
docker-compose up
```
Server will be ready on http://localhost:8080

## Exercice 
Mettre en oeuvre les media queries pour différencier l'affichage des élements du site en fonction du support utilisé.
Ouvrez les fichiers index.html et style.css, et complétez le fichier CSS selon les consignes suivantes:

#### Affichage sur Smartphones
* Ne pas afficher l'élément aside sur smartphones
* Ajouter les media-queries selon les breakpoints communs de supports actuels pour un affichage sur Tablettes et Desktops

#### Affichage sur Tablettes
* Modifier la largeur du body à 75%

Element aside
* Afficher l'élément avec la propriété display: flex; 
* Une hauteur de 150px
* Une couleur de fond #00ff99
* Affichage sur Desktops

#### Affichage sur Desktops
* Attribuer une position relative à la div de class container (Pour que les éléments enfants en position absolue se placent par rapport à cet élément)

Element aside
* Une largeur de 23%
* Une position absolue
* Placer l'élément en haut à droite de son parent
* Pas de marge extérieure en haut
* Une hauteur de 100%

Element section
* Une largeur de 70%
* Une hauteur de 220px

## Accomplissement
Réduisez, agrandissez votre fenêtre et observez les changements s'opérer ;)

## Recherches utiles
* media queries for common device breakpoints
* guide to flexbox css
