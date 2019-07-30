## Colorier les pixels

Ce projet utilise différents langages :

+ Le HTML est utilisé pour organiser ton contenu
+ Le CSS indique à quoi doit ressembler ce contenu avec les styles
+ Le JavaScript est un langage de programmation que tu peux utiliser pour faire une page web qui répond quand tu interagis avec

Allons ajouter un peu de code JavaScript pour colorier un pixel automatiquement dès que tu cliques dessus.

Tu créeras une **fonction**. Les fonctions sont des blocs de code qui exécutent une tâche particulière. Nous pouvons **appeler** une fonction par son nom quand nous voulons exécuter le code qu'elle contient.

+ Dans le fichier `script.js` crée une fonction avec le nom `setPixelColour`. La fonction `setPixelColour` doit prendre un `pixel` en tant que **entrée** pour qu'elle puisse changer la couleur de ce pixel.

![Créer une fonction](images/create-function.png)

+ Ajoutes ce code dans la fonction pour définir la couleur d'arrière-plan du pixel :

![capture d'écran](images/pixel-art-set-pixel-colour.png)

Note que `backgroundColor` utilise l'orthographe américaine de 'color'.

Pour le moment, ce code n'a aucun effet.

+ Va dans le fichier `index.html` et ajoutes le code suivant au premier pixel afin que lorsque tu cliques sur ce pixel, la fonction `setPixelColour` soit appelée :

![capture d'écran](images/pixel-art-onclick.png)

Le `this` dans les crochets est l'entrée de la fonction `setPixelColour` qui lui permet de savoir quel pixel définir la couleur pour — `this` pixel!

+ Teste ton code en cliquant sur le premier pixel. Il devrait devenir noir.

![capture d'écran](images/pixel-art-black.png)

Tu n'as ajouté que le code `onclick` au **premier pixel** et cliquer sur les autres pixels ne fera rien encore.
