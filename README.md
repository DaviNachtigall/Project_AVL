# Implementação de Árvore AVL em C
Uma implementação eficiente e autobalanceada de Árvore Binária de Busca (Árvore AVL) escrita em C. Este projeto trata a inserção dinâmica de nós, atualização automática de altura e balanceamento da árvore por meio de rotações simples e duplas. Também inclui suporte à visualização via Graphviz.

<img width="1444" height="712" alt="image" src="https://github.com/user-attachments/assets/deb396ea-0d1e-4c1f-9274-11fa82694ce8" />

## Funcionalidades
- **Operações de Autobalanceamento**: Implementa rotações à Esquerda, à Direita, Esquerda-Direita e Direita-Esquerda para manter uma altura de $O(\log n)$.
- **Gerenciamento Dinâmico de Memória**: Inclui rotinas para alocação de nós e liberação completa da memória da árvore, prevenindo vazamentos.
- **Exportação para Graphviz**: Gera automaticamente um arquivo `.dot` para renderizar visualmente a estrutura da árvore.
- **Prevenção de Duplicatas**: Rejeita valores duplicados para manter as propriedades padrão de uma Árvore AVL.

## Como Começar
### Pré-requisitos
- Um compilador C (ex.: `gcc` ou `clang`)
- [Graphviz](https://graphviz.org/) *(opcional, necessário apenas para renderizar a árvore visualmente)*

### Compilando e Executando
1. Compile o código-fonte:
```bash
   gcc -o avl_tree AVLTreeNumber.c
```
