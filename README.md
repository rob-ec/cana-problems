# Resoluções de problemas em C.A.N.A.
Três resoluções de problemas de Construção e Análise de Algoritmos

## Requisitos

- [ ] **Prazo 10/12/2023 às 23:59**;
- [ ] Cada problema deve ser resolvido uma técnica diferente:
  - [ ] Divisão e Conquista;
  - [ ] Abordagem Gulosa;
  - [ ] Programação Dinâmica;
- [ ] As soluções dos problemas deverão ser escritas em **Portugol**;
- [ ] **Relatório** apresentando dificuldades e aprendizados encontrados durante a execução do trabalho.
      
## Questões

### Super Inversão

Dado um vetor $v$ de $n$ inteiros distintos, defina uma super inversão como sendo $i < j$ e $v[i] > 2v[j]$. Escreva um algotimo $O(n \log n)$ que dado vetor $v$ com $n$ termos conta o número de super inversões. Generalize seu algoritmo para o caso no qual a definição de super inversão considera $i < j$ e $v[i] > kv[j]$. Seu algoritmo vai ser sempre $O(n \log n)$ para todo $k$?  
_Justifique._

### Mini-triatlon

Seu amigo está trabalhando como coordenador de atividades de um centro esportivo, e ele foi escolhido para organizar um mini-triatlon, onde cada participante deve primeiro nadar $20$ voltas na piscina, depois andar $15km$ de bicicleta, e finalmente correr $5km$. O plano é mandar os competidores, que não são muitos, em diferentes estágios, de acordo com a seguinte restrições: apenas uma faixa da piscina pode ser usada para o mini-triatlon, ou seja, apenas um competidor pode nadar de cada vez. O primeiro participante é liberado para nadar suas $20$ voltas e, apenas quando ele termina, um segundo competidor é autorizado a nadar suas $20$ voltas. Competidores podem fazer o percurso de bicicleta e a corrida ao mesmo tempo sem problemas. Apenas o uso da piscina tem essa restrição particular. Cada competidor tem um tempo esperado que leva para nadar suas $20$ voltas, um tempo esperado para fazer $15km$ de bicicleta e um tempo esperado para correr $5km$. Seu amigo, de posse dessa informação, deve montar um escalonamento dos competidores, que diz o horário previsto para cada competidor começar uma das três fases da prova. O término da competição é o primeiro instante em que todos os competidores terminaram as três fases da prova. Qual é a ordem em que os participantes devem: iniciar sua primeira prova de maneira a que a competição termine o mais cedo possível? Mais precisamente, dê um algoritmo eficiente que produza um escalonamento dos competidores cujo tempo previsto de término seja o menor possível. (Considere que cada participante vai gastar o seu tempo previsto para efetuar cada etapa da prova.) Por fim, mostre que, se os participantes pudessem fazer as suas provas em uma ordem arbitrária, ou seja, se fosse permitido que um participante corresse, depois nadasse, depois andasse de bicicleta, ou qualquer outra ordem das três provas, então a sua abordagem não funcionaria nessa situação, ou seja, mostre uma situação no qual o seu algoritmo não produzirá a solução ótima. Isto ocorre, pois com essa última restrição o problema se torna NP-difícil.

### Balsa

Uma balsa leva carros de um lado do rio para o outro. A balsa tem duas pistas para colocar os carros. Cada pista tem tamanho de $L$ metros. Os carros que querem entrar na balsa estão em fila e devem ser colocados na ordem da fila. A fila tem $n$ carros $C_1, C_2, ... , C_n$ com tamanhos $T_1, T_2, ... , T_n$. Os tamanhos podem ser bastante diferentes. Queremos colocar o maior número de carros na balsa decidindo em qual faixa cada carro deve ser colocado. Elabore um algoritmo que resolva esse problema.
Generalize seu algoritmo para o caso que temos $k$ faixas na balsa.
