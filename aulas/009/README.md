# Entendendo um pouco sobre posicionamento dos elementos

### Position: static

- _`É o valor predeterminado do atributo e o posicionamento normal dos elementos na página. Significa que os elementos se colocarão segundo o fluxo normal do HTML, ou seja, segundo estejam escritos no próprio código HTML. Dito de outra maneira, static não provoca nenhum posicionamento especial dos elementos e portanto, os atributos top, left, right e bottom não se levam em conta.`_

### position: absolute

- _`O valor absolute no atributo position permite posicionar elementos de maneira absoluta, isto é, de maneira definida pelos valores dos atributos top, left, bottom e right, que indicam a distância em relação a um ponto. As camadas ou elementos com posicionamento absoluto ficam à parte do fluxo normal do HTML, isto significa que não são afetados pelo lugar onde apareçam no código HTML e que também não afetam outros elementos que façam parte do fluxo normal do HTML.`_

### position: relative

- _`O valor relative no atributo position indica que a camada sim faz parte do fluxo normal de elementos da página, razão pela qual sua posição dependerá do lugar onde esteja no código e do fluxo HTML. Além disso, as camadas com posicionamento relative, admitem os valores top e left para definir a distância em que se colocam em relação ao ponto onde esteja nesse momento o fluxo normal do HTML. Como afetam o mencionado fluxo do HTML, os elementos colocados depois das camadas relative, levarão em conta suas dimensões para continuar o fluxo e saber onde se colocar. No entanto, não se levam em conta os top e left configurados.`_

### position: fixed

- _`Este atributo serve para posicionar uma camada com posicionamento absoluto, mas sua posição final será sempre fixa, ou seja, embora se desloque o documento com as barras de rolagem do navegador, sempre aparecerá na mesma posição. O lugar onde se "ancorará" a camada sempre é relativo ao corpo (o espaço disponível do navegador para a página). Se utilizamos top e left, estaremos marcando sua posição em relação ao canto superior esquerdo e se utilizamos bottom e right sua posição será relativa ao canto inferior direito.`_
