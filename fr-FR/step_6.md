## Ajouter une palette de couleur

Avez-vous trouvé ennuyeux de ne pas pouvoir modifier la couleur d'un pixel pour la rendre blanche à nouveau en cas d'erreur ? Corrigeons cela en créant une palette de couleurs, pour que vous puissiez cliquer sur une couleur et changer le feutre. 

+ D'abord, créez un style de feutre. 

	Ajoutez le code suivant au bas de votre fichier `style.css` :

	![screenshot](images/pixel-art-pen.png)

+ Maintenant, créez des couleurs de feutre noire et blanche qui utilisent ce style. 

	Ajoutez le code suivant à votre fichier `index.html` après le `<body>` :

	![screenshot](images/pixel-art-palette.png)

	`style=` vous permet d'ajouter du CSS à l'intérieur de votre HTML, ce qui est pratique ici. 

+ Vous voulez pouvoir modifier la couleur du feutre lorsqu'une couleur de la palette est cliquée. 

	Des variables sont utilisées pour stocker les informations. Créons une variable penColour dans `script.js`.

	Ajoutez le code suivant au sommet du fichier :

	![screenshot](images/pixel-art-pencolour.png)

	Puis ajoutez une fonction pour modifier la penColour :

	![screenshot](images/pixel-art-set-pen.png)

+ Il vous faudra aussi utiliser la couleur du feutre lorsque vous modifiez la couleur d'un pixel. 

	Modifiez la fonction `setPixelColour` pour utiliser la variable `penColour` au lieu de `black` :

	 ![screenshot](images/pixel-art-use-pen.png)

+ Vous devez maintenant faire appel à la fonction `setPenColour` lorsqu'un feutre de couleur est cliqué. 

	Ajoutez le code `onclick` en surbrillance à vos couleurs de feutre :

	![screenshot](images/pixel-art-palette-onclick.png)

+ Maintenant, voyez si vous pouvez faire basculer la couleur du feutre du noir au blanc pour remplir ou supprimer des pixels.
