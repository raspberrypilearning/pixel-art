## Créer une grille de pixels

Créons une grille de pixels que vous pouvez utiliser pour créer du pixel art. Le CSS fournit des styles de tableau pour les grilles et des agencements de tableau. 

Les tableaux contiennent des lignes qui contiennent des cellules. Vous allez créer un tableau avec un arrière-plan noir, puis placer des pixels blancs à l'intérieur. 

+ Ouvrez ce trinket : <a href="http://jumpto.cc/web-pixel" target="_blank">jumpto.cc/web-pixel</a>. 

	Le projet doit ressembler à ça :

	![screenshot](images/pixel-starter.png)

+ Ajouter le html suivant dans le `<body>` de votre fichier `index.html` pour créer une `<div>` comme conteneur de votre pixel art et donnez-lui un id `art` pour pouvoir y appliquer un style :

	![screenshot](images/pixel-art-art.png)

+ Maintenant, allez dans votre fichier `style.css` et ajoutez la stylisation de tableau pour l'art `<div>`.

	![screenshot](images/pixel-art-style.png)

	Cela crée un tableau avec une bordure et définit l'espacement à l'intérieur de la grille. 

	Il n'a pas l'air très intéressant pour l'instant, vous devez placer des lignes de pixels à l'intérieur. 

 + Maintenant, retournez à ton fichier `index.html` et ajoutez une ligne de 3 pixels à l'intérieur de l'art `<div>` :

	![screenshot](images/pixel-art-row.png)
	
	 Remarquez que les lignes de trois pixels sont les mêmes. Saisissez la première, puis faites un copier/coller pour créer les autres. 

 	Cette fois vous utilisez des classes pour styliser les divisions car il y en aura beaucoup. 

 + Ajoutez le style suivant pour les lignes et les cellules ;

	![screenshot](images/pixel-art-row-style.png)

 	Maintenant, vos pixels s'aligneront dans une grille avec des lignes noires autour. 

 + Ajoutez maintenant deux autres lignes de pixels pour créer une grille 3 x 3. Souvenez-vous d'utiliser la fonction copier/coller pour gagner du temps. 

	![screenshot](images/pixel-art-grid-3.png)
