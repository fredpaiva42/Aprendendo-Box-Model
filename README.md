# Aprendendo Box Model no CSS

No **box-model**, todos os elementos HTML são tratados como uma caixa com quatro áreas. Pensando no modelo como uma caixa de uma encomenda o `conteúdo` (content) é o item que vem na caixa ou no nosso caso o conteúdo do nosso site.

![](https://cdn.freecodecamp.org/curriculum/css-box-model/diagram-1.png)

O conteúdo é cercado por um espaço chamado `preenchimento` (padding), do mesmo modo que um plástico de bolha separa um item da caixa ao seu redor.

Já a `borda` (border) é a caixa em que o produto foi enviado.

![](https://cdn.freecodecamp.org/curriculum/css-box-model/diagram-2.png)

A `margem` (margin) é a área fora da caixa e pode ser usada para controlar o espaço entre outras caixas ou elementos.

![](https://cdn.freecodecamp.org/curriculum/css-box-model/diagram-3.png)

Mesmo que uma `<div>` não tenha texto, ela ainda é tratada como uma caixa com conteúdo;

Quando tivermos um elemento extrapolando a margin que que queremos para ele, podemos usar a propriedade `overflow: hidden;`.

A propriedade `border-radius` aceita até quatro valores para arrendodar os cantos superior esquerdo, superior direito, inferior direito e inferior esquerdo.