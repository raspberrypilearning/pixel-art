## Créer une grille de pixels

Créons une grille de pixels que tu pourras utiliser pour créer un pixel art.

La grille ressemblera à un tableau. Les tableaux contiennent des lignes qui contiennent elles-mêmes des cellules qui représenteront les pixels.

+ Ouvre le [trinket de démarrage](http://jumpto.cc/web-pixel).

Le projet doit ressembler à ça :

![capture d'écran](images/pixel-starter.png)

Commençons par écrire du code pour créer un tableau avec un arrière-plan noir, puis y insérer des pixels blancs.

+ Ajoute ce code dans le `<body>` de ton fichier `index.html` pour créer un `<div>`:

![capture d'écran](images/pixel-art-art.png)

Un `<div>` est une boîte invisible à laquelle tu peux donner un **style**. Cette `<div>` a l'ID `art`, dont tu auras besoin pour ajouter des styles à la boîte.

+ Accède maintenant à ton fichier `style.css` et ajoute la table de style pour le `<div>` appelé `art`.

![capture d'écran](images/pixel-art-style.png)

Cela crée un tableau avec une bordure et définit l'espacement à l'intérieur de la grille.

Cela ne semble pas encore très intéressant, tu dois donc y insérer des rangées de pixels.

+ Retourne à ton fichier `index.html` et ajoute une ligne de trois pixels **à l'intérieur** la case `art`. Si tu veux gagner du temps, tu peux taper la première ligne puis la copier-coller pour créer les autres.

![capture d'écran](images/pixel-art-row.png)

Note que tu utilises ici une **classe** au lieu d'un ID pour faire les divs. C'est parce qu'il y aura beaucoup d'entre eux, donc une classe est plus utile.

+ Passe au fichier `style.css` et ajoute les styles suivants pour les lignes et les pixels dans chaque ligne :

![capture d'écran](images/pixel-art-row-style.png)

Maintenant, les pixels vont s'aligner dans une grille avec des lignes noires autour d'eux.

+ Dans ton fichier `index.html` ajoute deux autres sections de pixels pour créer une grille de 3×3 pixel. Tu peux utiliser le procédé du copier-coller à nouveau pour gagner du temps.

\--- hints \---

\--- hint \---

Find the `<div>` tag with the class `row` and copy it, including the three rows labelled `pixel` which are inside it, up to and including its matching `</div>` tag.

Paste this code immediately below the section you just copied to create another row. Repeat once more so that you have three rows of three pixels each.

You can check whether your table looks right by looking at the result area on the right.

\--- /hint \---

\--- hint \---

Here is how your code should look:

![screenshot](images/pixel-art-grid-3.png)

\--- /hint \---

\--- /hints \---