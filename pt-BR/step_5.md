## Colora os pixels

Este projeto usa três línguagens diferentes:

+ HTML é usado para organizar seu conteúdo
+ CSS diz ao conteúdo como ele deve se parecer usando os estilos
+ JavaScript é uma linguagem de programação que você pode usar para fazer uma página web responder às interações com ela

Vamos adicionar um código JavaScript para colorir um pixel automaticamente quando você clicar nele.

Vamos criar uma **função**. As funções são blocos de código denominados que executam uma tarefa específica. Podemos **chamar** uma função pelo seu nome quando queremos executar o código que ela contém.

+ Dentro do ` script.js ` arquivo, crie uma função com o nome ` setPixelColour ` (dar cor ao pixel). A função `setPixelColour` precisa ter um `pixel` como **entrada** para que ele pode mudar a cor deste pixel.

![Create function](images/create-function.png)

+ Adicione este código dentro da função para definir a cor de fundo do pixel:

![screenshot](images/pixel-art-set-pixel-colour.png)

Observe que `backgroundColor` usa a ortografia americana de 'cor'.

No momento, esse código não tem qualquer efeito.

+ Vá para `index. html` e adicione o seguinte código ao primeiro pixel para que quando você clicar neste pixel, a função `setPixelColour` seja chamada:

![screenshot](images/pixel-art-onclick.png)

O ` this` nos parênteses é a variável de entrada para a função` setPixelColour `, que permite saber qual pixel para terá cor definida, para - ` this` (este) pixel!

+ Teste seu código clicando no primeiro pixel. Ele deve ficar preto.

![screenshot](images/pixel-art-black.png)

Você adicionou código ` onclick ` apenas para o ** primeiro ** pixel, então clicar nos outros pixels não fará nada ainda.