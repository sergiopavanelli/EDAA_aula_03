# Análise de Complexidade Assintótica (Big-O)

**Disciplina:** Estruturas de Dados e Análise de Algoritmos  
**Aula:** 03 - Notação Assintótica  
**Professor:** Alexandre Montanha  

---

## Exercício 1
**Complexidade:** O(1)  
**Justificativa:** O algoritmo apenas verifica uma condição de tamanho e acessa o primeiro elemento da lista. Essas operações de acesso direto levam um tempo constante para serem executadas, independentemente do tamanho total da entrada.

## Exercício 2
**Complexidade:** O(n)  
**Justificativa:** A função possui um único laço de repetição que itera sobre todos os elementos da lista exatamente uma vez. Portanto, o tempo de execução cresce linearmente e de forma proporcional à quantidade de itens na entrada.

## Exercício 3
**Complexidade:** O(log n)  
**Justificativa:** Trata-se do algoritmo de busca binária. A cada iteração do laço, o espaço de busca é dividido pela metade. Isso significa que o número de passos necessários cresce proporcionalmente ao logaritmo do tamanho da lista.

## Exercício 4
**Complexidade:** O(n^2)  
**Justificativa:** O código utiliza dois laços de repetição aninhados que dependem do tamanho da lista. Como para cada elemento do laço externo o laço interno também percorre os elementos restantes, o número de operações cresce de forma quadrática.

## Exercício 5
**Complexidade:** O(n^2)  
**Justificativa:** O algoritmo possui um laço simples O(n) e, em seguida, dois laços aninhados O(n^2). Na análise do pior caso da notação assintótica, o termo de maior grau sempre domina, resultando em uma complexidade total quadrática.

## Exercício 6
**Complexidade:** O(log n)  
**Justificativa:** A variável de controle começa em 1 e é multiplicada por 2 a cada iteração. Como o valor dobra a cada passo, ele atinge o limite `n` muito rapidamente, o que caracteriza um tempo de execução logarítmico.

## Exercício 7
**Complexidade:** O(2^n)  
**Justificativa:** Cada chamada da função gera duas novas chamadas recursivas, criando uma árvore de recursão binária. Isso faz com que o número de operações dobre a cada incremento na entrada, gerando um crescimento exponencial.

## Exercício 8
**Complexidade:** O(n^2)  
**Justificativa:** O algoritmo Bubble Sort utiliza dois laços aninhados para comparar e trocar elementos adjacentes. No pior caso (uma lista ordenada de forma decrescente), o número de operações é proporcional ao quadrado do tamanho da lista.

## Exercício 9
**Complexidade:** O(n^3)  
**Justificativa:** A multiplicação de matrizes iterativa utiliza três laços totalmente aninhados, todos percorrendo o tamanho `n`. Assim, a instrução mais interna é executada `n * n * n` vezes, resultando em um tempo cúbico.

## Exercício 10
**Complexidade:** O(n log n)  
**Justificativa:** O algoritmo Merge Sort divide a lista pela metade recursivamente em `log n` níveis. Em cada um desses níveis, o processo de mesclagem percorre todos os `n` elementos uma vez, resultando na complexidade linearítmica.