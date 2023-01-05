# Páginas que devem ser impressas

Gosto de ler textos em papel físico, mas a fim de tentar reduzir meu consumo de papel, costumo imprimir de um modo particular. Uso a página física em modo paisagem, e imprimo de modo que ela contenha 2 páginas virtuais em modo retrato. Dessa forma, imprimindo frente e verso cada folha física acaba ficando com 4 páginas virtuais.

No entanto, minha impressora não imprime frente e verso automaticamente. Por isso, eu precisava ficar manualmente especificando as páginas que deveriam ser impressas. Sendo assim, para imprimir um documento eu começo imprimindo as páginas que corresponderão à frente, inverto as folhas manualmente, e depois imprimo o verso. Para um documento com 10 páginas, por exemplo, eu iria imprimir primeiro as seguintes páginas do documento:

1,2,5,6,9,10 (frente)

depois de inverter as folhas manualmente na impressora, eu imprimiria:

3,4,7,8 (verso)

Para automatizar essa tarefa, eu criei uma função no R que recebe como entrada o número da última e da primeira página do documento que busco imprimir e retorna o número das páginas da frente e do verso que devem ser impressas.
