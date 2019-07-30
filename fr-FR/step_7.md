## Ajoute une palette de couleur

As-tu trouvé ennuyeux de ne pas pouvoir changer la couleur d'un pixel en blanc si tu as commis une erreur? Corrigeons ça en créant une palette de couleurs, pour que tu puisses choisir les couleurs du pinceau en un clic.

+ Ajoute ce code en bas de ton fichier `style.css` pour créer un style de stylo :

![capture d'écran](images/pixel-art-pen.png)

+ Maintenant, crée une palette avec les couleurs noir et blanc pour le stylo, en utilisant le style du stylo que tu viens de créer. Ajoutes le code suivant à ton fichier `index.html` en dessous du tag `<body>` :

![capture d’écran](images/pixel-art-palette.png)

`style=` te permet d'ajouter du code CSS dans ton fichier HTML, ce qui est pratique ici.

Nous devons ajouter du code pour que lorsque l'une des couleurs de la palette est cliquée, la couleur du stylo change.

+ Passe maintenant à ton fichier `script.js` et crée une variable appelée `penColour` au haut du fichier. Définis sa valeur à `'black'`.

[[[generic-javascript-create-variable]]]

--- hints ---
 --- hint --- Ajouter le code suivant en haut du fichier :

![capture d'écran](images/pixel-art-pencolour.png)
--- /hint ---
--- /hints ---

+ Sous la variable, crée une nouvelle fonction appelée `setPenColour` avec une entrée de `pen`. Regarde la fonction `setPixelColour` que tu as déjà créé pour t’aider.

[[[generic-javascript-create-a-function]]]

+ Dans la fonction `setPenColour`, ajoute du code pour définir la variable `penColour` à la couleur `pen` fournie en tant qu'entrée.

![capture d'écran](images/pixel-art-set-pen.png)

Tu devras également utiliser la variable `penColour` lorsque tu changes la couleur d'un pixel.

+ Change la fonction `setPixelColour` pour utiliser la variable `penColour` au lieu de `noir`:
    
    ![capture d'écran](images/pixel-art-use-pen.png)

+ Dans le fichier `index.html` ajoute un code pour appeler la fonction `setPenColour` quand une couleur dans la palette est cliquée.

![capture d'écran](images/pixel-art-palette-onclick.png)

+ Teste que tu peux changer la couleur du stylo entre noir et blanc pour remplir ou supprimer des pixels.