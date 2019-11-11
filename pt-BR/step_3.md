## Crie uma grade de pixels

Vamos criar uma grade de pixels que você pode usar para criar pixel art.

A grade será parecida com uma tabela. As tabelas contêm linhas e as linhas contêm células que representam os pixels.

+ Abra [este trinket](http://jumpto.cc/web-pixel).

O projeto deve ficar assim:

![screenshot](images/pixel-starter.png)

Primeiro, vamos escrever um código para criar uma tabela com um fundo preto e colocar pixels brancos nela.

+ Adicione este código ao `<body>` do seu arquivo ` index.html` para criar um `<div>`:

![screenshot](images/pixel-art-art.png)

A tag `<div>` é uma caixa invisível à qual você pode atribuir um **estilo**. Este `<div>` tem o ID `art`, que você precisa, então você pode adicionar estilos para a caixa.

+ Agora vá para o seu arquivo `style.css` e adicione o estilo de tabela para o `<div>` chamado `art`.

![screenshot](images/pixel-art-style.png)

Isto cria uma tabela com uma borda e define o espaçamento dentro da grade.

Não parece muito interessante ainda, então você precisa colocar linhas de pixels dentro dela.

+ Volte para o seu arquivo `index.html` e adicione uma linha de três pixels **dentro** da caixa `art`. Se você quiser economizar tempo, digite a primeira linha e copie e cole para criar as outras.

![screenshot](images/pixel-art-row.png)

Observe que aqui você está usando **class** em vez de ID para dar estilo aos divs. Isto é porque haverão muitos deles, portanto uma classe é mais útil.

+ Alterne para o arquivo `style.css` e adicione os seguintes estilos para as linhas e os pixels dentro de cada linha:

![screenshot](images/pixel-art-row-style.png)

Agora seus pixels se alinharão em uma grade com linhas pretas ao redor deles.

+ No seu arquivo `index.html`, adicione outras duas seções de pixel para criar uma grade de pixel 3×3. Você pode usar novalmente o copiar e colar para economizar tempo.

\--- hints \--- \--- hint \--- Encontre a tag `<div>` com a classe `row` e copie, incluindo as três linhas marcadas com `pixel` que estão dentro dela, até a que inclui sua tag`</div>` correspondente.

Cole este código imediatamente abaixo da seção que você acabou de copiar para criar outra linha. Repita mais uma vez para que você tenha três linhas de três pixels cada.

Você pode verificar se sua tabela está certa observando a área de resultados à direita. \--- /hint \--- \--- hint \--- Aqui está como seu código deve parecer:

![screenshot](images/pixel-art-grid-3.png) \--- /hint \--- \--- /hints \---