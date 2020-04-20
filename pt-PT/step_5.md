## Colorir os pixeis

Este projeto utiliza três linguagens diferentes:

+ HTML é usado para organizar o teu conteúdo
+ CSS informa o conteúdo sobre qual a aparência que deve ter com estilos
+ JavaScript é uma linguagem de programação que tu podes usar para fazer uma página de Internet responder quando interages com ela

Vamos adicionar algum código JavaScript para colorir um pixel automaticamente quando clicas nele.

Vamos criar uma **função **. As funções são blocos de código, com um nome, que executam uma tarefa específica. Podemos ** chamar ** uma função pelo seu nome quando queremos executar o código que ela contém.

+ Dentro do ficheiro ` script.js `, cria uma função com o nome ` setPixelColour `. A função ` setPixelColour ` precisa de ter um `pixel ` como uma **entrada ** para que ele possa mudar a cor desse pixel.

![Criar função](images/create-function.png)

+ Adiciona este código dentro da função para definir a cor de fundo do pixel:

![captura de ecrã](images/pixel-art-set-pixel-colour.png)

Observa que ` backgroundColor ` usa a ortografia americana de 'cor (color)'.

Neste momento, este código não tem qualquer efeito.

+ Vai para ` index.html ` e adiciona o seguinte código ao primeiro pixel para que, quando clicares nesse pixel, a função ` setPixelColour ` ser chamada:

![captura de ecrã](images/pixel-art-onclick.png)

O ` this` (este) entre parênteses é a entrada para a função ` setPixelColour `, que lhe permite saber qual é o pixel a quem vai definir a cor - ` this `(este) pixel!

+ Testa o teu código clicando no primeiro pixel. Se funcionar o pixel vai ficar preto.

![captura de ecrã](images/pixel-art-black.png)

Apenas adicionaste código ` onclick ` para o ** primeiro ** pixel, pelo que clicar nos outros pixeis ainda não fará nada.