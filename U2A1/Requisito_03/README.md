# Análise de Redes de Coautoria

## Tabela de Métricas das Redes

| Rede  | Qtd Vértices | Qtd Arestas | Degree Assortativity Coefficient  | Qtd Comp. Conectados | Tamanho do Comp. Gigante (GCC) | Coef. de Clustering (avg_clustering)  |
|-------|--------------|-------------|---------------------------------- |----------------------|--------------------------------|---------------------------------------|
| Rede 1| 1167         | 4654        | 0.8566516522006032                | 173                  | 158                            | 0.8906764543336186                    |
| Rede 2| 2097         | 39679       | 0.9974344905747734                | 207                  | 247                            | 0.910669587666282                     |
| Rede 3| 438          | 1636        | 0.9019800693971588                | 61                   | 54                             | 0.884334416003303                     |
| Rede 4| 954          | 6121        | 0.9358899603464406                | 122                  | 159                            | 0.9278803101690397                    |


## Interpretação dos Resultados

### Rede 1
A Rede 1 apresenta 1167 vértices e 4654 arestas, o que indica uma rede relativamente densa com um bom número de colaborações entre os autores. O coeficiente de assortatividade de grau é 0.8567, sugerindo que autores com muitos coautores tendem a colaborar com outros autores também bem conectados. Este valor alto de assortatividade pode indicar uma estrutura hierárquica ou a formação de grupos de pesquisa especializados. Com 173 componentes conectados e um coeficiente de clustering médio de 0.8907, observamos uma tendência significativa de formação de clusters dentro da rede.

### Rede 2
A Rede 2 mostra um número significativamente maior de vértices (2097) e arestas (39679), indicando uma rede muito mais densa. O coeficiente de assortatividade de grau é extremamente alto (0.9974), sugerindo uma forte tendência de autores de grau similar se conectarem entre si. Esta rede também possui 207 componentes conectados e um coeficiente de clustering médio de 0.9107. O tamanho do componente gigante é de 247, o que indica uma grande interconexão entre a maioria dos autores, formando uma rede coesa e bem conectada.

### Rede 3
A Rede 3, com 438 vértices e 1636 arestas, apresenta um coeficiente de assortatividade de grau de 0.9020. Este valor indica uma alta tendência de autores com graus similares se conectarem, similar às outras redes. Com 61 componentes conectados e um coeficiente de clustering médio de 0.8843, a Rede 3 também demonstra uma estrutura de colaboração coesa, embora em uma escala menor comparada à Rede 2.

### Rede 4
A Rede 4 tem 954 vértices e 6121 arestas, com um coeficiente de assortatividade de grau de 0.9359. Este valor alto reflete uma rede altamente modular, onde os autores tendem a colaborar dentro de grupos bem definidos. Com 122 componentes conectados e um coeficiente de clustering médio de 0.9279, esta rede apresenta uma estrutura muito densa de colaboração, com um tamanho de componente gigante de 159, indicando uma grande quantidade de autores interconectados.

## Conclusão
A análise das redes de coautoria para as quatro ODS revela diferenças significativas nas estruturas de colaboração entre os autores. As métricas calculadas fornecem insights valiosos sobre a densidade, coesão e padrões de conectividade em cada rede. Redes com altos coeficientes de assortatividade e clustering tendem a indicar colaborações fortes e bem definidas, enquanto redes com menores tamanhos de componentes gigantes podem sugerir uma menor interconectividade geral. Essas informações podem ser utilizadas para melhorar a compreensão sobre como os autores colaboram e para identificar possíveis áreas de fortalecimento nas colaborações futuras.


