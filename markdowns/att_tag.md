# Balises avec attribut

## Ressources
|Balise|Lien|
|------|----|
|`img`|[images](https://www.w3schools.com/tags/tag_img.asp)|
|`a`|[liens/ancres](https://www.w3schools.com/tags/tag_a.asp)|

## Exercice 1

Insérer une [images](https://www.w3schools.com/tags/tag_img.asp) avec ses attributs obligatoires dans la page. Les 5 images suivantes sont disponnibles dans le répertoire `images` : `concert.jpg`, `mer.jpg`, `paysage.jpg`, `route.jpg` et `urbain.jpg`.

@[Images]({"stubs": ["vide.html"], "command": "/bin/bash run.sh vide .*img-alt;src-.*"})

## Exercice 2

Insérer un [liens](https://www.w3schools.com/tags/tag_a.asp) vers *https://rouen.fr/*.
@[Liens]({"stubs": ["vide.html"], "command": "/bin/bash run.sh vide .*a-href=https://rouen.fr/-.*"})
