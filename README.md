# Páginas a serem imprimidas

Gosto de ler textos em papel físico, mas a fim de tentar reduzir meu consumo de papel, costumo imprimir de um modo particular. Uso a página física em modo paisagem, e imprimo de modo que ela contenha 2 páginas virtuais em modo retrato. Dessa forma, imprimindo frente e verso cada folha física acaba ficando com 4 páginas virtuais.

No entanto, minha impressora não imprime frente e verso automaticamente. Por isso, eu precisava ficar manualmente especificando as páginas que deveriam ser impressas. Sendo assim, para imprimir um documento eu começo imprimindo as páginas que corresponderão à frente, inverto as folhas manualmente, e depois imprimo o verso. Para um documento com 10 páginas, por exemplo, eu imprimiria primeiro as seguintes páginas do documento:

1,2,5,6,9,10 (frente)

e, depois de inverter as folhas manualmente na impressora, as seguintes:

3,4,7,8 (verso)

Para automatizar essa tarefa, eu criei uma função no R que recebe como entrada o número da primeira e da última página do documento que busco imprimir e retorna o número das páginas da frente e do verso que devem ser impressas. O primeiro argumento da função, o número da última página que busco imprimir do documento, é obrigatório. Já o segundo, o número da primeira página que busco imprimir do documento, é opcional. Caso só seja fornecida uma entrada, esse valor é autmaticamente como 1.
