##Desafio 1##

  Função 'traverse' Recursiva: A solução utiliza uma função chamada 'traverse' que percorre a árvore de forma recursiva. Isso significa que a função é chamada repetidamente, explorando cada nó da árvore de maneira estruturada.

  Cálculo da Diferença Absoluta: Durante a travessia, a função calcula a diferença absoluta entre o valor alvo e o valor do nó atual. Essa diferença representa o quão próximo o valor do nó está do valor alvo.

  Atualização do Valor Mais Próximo ('closest_value'): Inicialmente, é assumido que não há um valor mais próximo definido. Conforme a travessia progride, se a diferença calculada for menor do que a diferença atualmente registrada em 'closest_value', o 'closest_value' é atualizado com o valor do nó atual. Isso garante que 'closest_value' sempre contenha o valor mais próximo encontrado até o momento.

  Determinando o Próximo Nó a Ser Explorado: A direção da travessia na árvore é determinada com base na relação entre o valor do nó atual e o valor alvo. Se o valor alvo for menor que o valor do nó atual, a próxima etapa da travessia será pela esquerda. Caso contrário, será pela direita.

  Início da Travessia no Nó Raiz: A travessia começa no nó raiz da árvore, pois é a partir dele que toda a estrutura da árvore é explorada de forma recursiva.

##Desafio 2##

Função de Traversão em Ordem Invertida:
A função in_order_reverse_traversal(node, values) é definida dentro da função principal. Ela ajuda a percorrer a árvore em ordem reversa, coletando os valores dos nós em uma lista.

Traversão In-Order Invertida:
A função chama recursivamente a si mesma para percorrer o ramo direito do nó atual (node.right_child) antes de adicionar o valor do nó atual à lista.
Em seguida, visita o ramo esquerdo do nó atual (node.left_child), continuando a travessia em ordem reversa.

Inicialização da Lista de Valores Ordenados:
Uma lista vazia (sorted_values) é inicializada para armazenar os valores dos nós em ordem reversa.

Traversão In-Order Invertida da Árvore:
A função principal chama a in_order_reverse_traversal a partir do nó raiz da árvore (tree.root) para preencher a lista sorted_values com os valores dos nós em ordem reversa.

Verificação da Validade de k:
A função verifica se o valor de k está dentro do intervalo válido de valores de nós na lista sorted_values.
Se k estiver dentro do intervalo, a função retorna o k-ésimo maior valor da lista sorted_values (considerando que k começa em 1, não em 0).
Se k estiver fora do intervalo válido, a função levanta uma exceção de ValueError indicando que k é inválido.
