## Colorer les pixels

Le HTML est utilisé pour organiser votre contenu et le CSS pour le styliser. Le JavaScript est un langage de programmation qui peut être utilisé pour modifier une page Web et la façon d'interagir avec. 

Vous pouvez utiliser le HTML et le CSS pour définir la couleur de l'arrière-plan des pixels individuels, mais ce sera très long ! Au lieu de ça, vous allez ajouter un peu de code en JavaScript pour colorer les pixels automatiquement lorsque vous cliquez dessus. 

+ En JavaScript, le code est placé dans une `function` qui peut être appelée quand nous souhaitons faire appel à ce code. 

	Vous allez créer une fonction appelée `setPixelColour`

	La fonction `setPixelColour` doit savoir de quel pixel il faut modifier la couleur, c'est un `input`.

	Ajoutez le code suivant au fichier `script.js` pour définir la couleur d'arrière-plan d'un pixel :

	![screenshot](images/pixel-art-set-pixel-colour.png)

	Remarquez que `backgroundColor` utilise les dénominations de couleur américaines. 

+ Nous devons maintenant faire appel à cette fonction pour qu'elle intervienne lorsqu'on clique sur un pixel.

	Le HTML utilise `onclick` pour appeler une fonction lorsqu'un élément est cliqué. Vous allez devoir faire de 'this' l'entrée pour que votre fonction sache de quel pixel il faut modifier la couleur. 

	Allez dans `index.html` et ajoutez le code suivant au premier pixel :

	![screenshot](images/pixel-art-onclick.png)

+ Testez votre code en cliquant sur le premier pixel. Il devrait devenir noir :

	![screenshot](images/pixel-art-black.png)

	Vous n'avez ajouté que le code `onclick` au premier pixel, donc ça ne fonctionnera pas encore pour les autres pixels. 
