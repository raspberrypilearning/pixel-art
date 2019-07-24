## Ajoute une palette de couleur

As-tu trouvé ennuyeux de ne pas pouvoir changer la couleur d'un pixel en blanc si tu as commis une erreur? Corrigeons ça en créant un palette de couleurs, pour que tu puisses choisir entre les couleurs du pinceau en un clic.

+ Ajoute ce code en bas de ton fichier `style.css` pour créer un style de stylo :

![screenshot](images/pixel-art-pen.png)

+ Maintenant, crée une palette avec les couleurs noir et blanc pour le stylo, en utilisant le style du stylo que tu viens de créer. Puis suis le code d s ton `index.html` en dessous du tag `<body>` :

![screenshot](images/pixel-art-palette.png)

`style=` te permet d'ajouter du code CSS dans votre fichier HTML, ce qui est pratique ici.

Nous devons ajouter du code pour que lorsque l'une des couleurs de la palette est cliquée, la couleur du stylet change.

+ Passe maintenant à ton fichier `script.js` et crée une variable appelée `penColour` au haut du fichier. Définis sa valeur à `'black'`.

[[[generic-javascript-create-variable]]]

\--- hints \--- \--- hint \--- Ajouter le code suivant en haut du fichier :

![screenshot](images/pixel-art-pencolour.png) \--- /hint \--- \--- /hints \---

+ Sous la variable, crée une nouvelle fonction appelée `setPenColour` avec une entrée de `pen`. Regarde la fonction `setPixelColour` que tu as déjà créé pour t’aider.

[[[generic-javascript-create-a-function]]]

+ Dans la fonction `setPenColour` ,ajoute du code pour définir la variable `penColour` à la couleur `pen` fournie en tant qu'entrée.

![screenshot](images/pixel-art-set-pen.png)

Tu devras également utiliser la variable `penColour` lorsque tu changes la couleur d'un pixel.

+ Change la fonction `setPixelColour` pour utiliser la variable `penColour` au lieu de `noir`:
    
    ![screenshot](images/pixel-art-use-pen.png)

+ Dans le fichier `index.html` ajoute un code pour appeler la fonction `setPenColour` quand une couleur dans la palette est cliquée.

![screenshot](images/pixel-art-palette-onclick.png)

+ Teste que tu peux changer la couleur du stylet entre noir et blanc pour remplir ou supprimer des pixels.