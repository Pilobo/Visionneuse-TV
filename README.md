# Visionneuse-TV

Page d'affichage pour la télé (récepteur Google Cast personnalisé) de l'appli Android **Visionneuse**.

La télé charge cette page via Google Cast. L'appli du téléphone lui envoie la liste des photos, puis
la page gère seule le diaporama : fondus enchaînés, zoom lent, fond flouté pour les photos
verticales, date, album et horloge. Les photos sont lues directement sur le téléphone, par le Wi-Fi
de la maison : elles ne passent jamais par ce dépôt ni par Internet.

## Adresse à déclarer dans la console Google Cast

```
https://pilobo.github.io/Visionneuse-TV/
```

(GitHub Pages : *Settings* → *Pages* → *Deploy from a branch* → `main` / `(root)`.)

## Tester sur le téléphone (mode démo)

Ouvre <https://pilobo.github.io/Visionneuse-TV/?demo> dans le navigateur du téléphone, tenu à
l'horizontale : un diaporama de quelques photos d'exemple démarre, avec le même rendu que sur la
télé.

- Appui sur l'écran : pause / reprise
- Glisser vers la gauche ou la droite : photo suivante / précédente
- Sur ordinateur : flèches ← → et barre d'espace

Sans `?demo`, la page affiche seulement l'écran d'attente : le vrai diaporama démarre sur la télé,
depuis l'appli.
