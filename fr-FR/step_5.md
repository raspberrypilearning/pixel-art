## Colorie les pixels

Ce projet utilise différents langages :

+ Le HtML est utilisé pour organiser ton contenu
+ Le CSS indique au contenu à quoi ressembler avec les styles
+ Le JavaScript est un langage de programmation que tu peux utiliser pour faire une page web qui répond quand tu interagis avec

Allons ajouter un peu de code JavaScript pour colorier un pixel automatiquement dès que tu cliques dessus.

Tu créeras une **fonction**. Les fonctions sont des blocs de code qui exécutent une tâche particulière. Nous pouvons **appeler** une fonction par son nom quand nous voulons exécuter le code qu'il contient.

+ Dans le fichier `script.js` crée une fonction avec le nom `setPixelColour`. La fonction `setPixelColour` doit prendre une `pixel` en tant que **entrée** pour qu'elle puisse changer la couleur de ce pixel.

![Créer une fonction](images/create-function.png)

+ Ajoutes ce code dans la fonction pour définir la couleur d'arrière-plan du pixel :

![screenshot](images/pixel-art-set-pixel-colour.png)

Note que `Background Color` utilise l'orthographe américaine de 'color'.

Pour le moment, ce code n'a aucun effet.

+ Va dans le fichier `index.html` et ajoutes le code suivant au premier pixel afin que lorsque tu cliques sur ce pixel, la fonction `setPixelColour` soit appelée :

![screenshot](images/pixel-art-onclick.png)

La fonction `ce` dans les crochets est l'entrée de la fonction `setPixelColour` qui lui permet de savoir quel pixel définir la couleur pour — `ce` pixel!

+ Teste ton code en cliquant sur le premier pixel. Il devrait tourner noir.

![screenshot](images/pixel-art-black.png)

Vous n'avez ajouté que `onclick` code au **premier pixel** et cliquez sur les autres pixels ne fera rien encore.