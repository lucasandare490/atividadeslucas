# atividadeslucas
O código da Atividade 1 é responsável por gerar um array de números aleatórios. Ele recebe três parâmetros: o tamanho do array, o valor mínimo e o valor máximo que um número no array pode ter. A função inicializa um array vazio e, através de um loop, preenche o array com números aleatórios gerados dentro do intervalo especificado. Para gerar um número aleatório dentro do intervalo, a função usa a fórmula Math.floor(Math.random() * (valorMaximo - valorMinimo + 1)) + valorMinimo. Esta fórmula garante que o número gerado esteja entre valorMinimo e valorMaximo, inclusive. Ao final do loop, o array preenchido é retornado.

Na Atividade 2, a função determina o elemento que aparece com maior frequência em um array. Primeiro, a função verifica se o array está vazio e, se estiver, retorna uma mensagem indicando que não há um elemento mais frequente. Caso contrário, a função cria um objeto para contar a frequência de cada elemento. À medida que percorre o array, atualiza a contagem no objeto. A função também mantém um controle sobre o elemento com a maior frequência encontrada. Após contar as frequências, verifica se há apenas um elemento com a frequência máxima; se houver um único elemento mais frequente, ele é retornado. Se houver um empate ou se o array estiver vazio, a função retorna uma mensagem indicando a ausência de um elemento mais frequente.

A Atividade 3 foca em remover elementos repetidos de um array. Para isso, a função conta a frequência de cada elemento usando um objeto. Após contar, percorre o array novamente e adiciona ao resultado apenas aqueles elementos que aparecem exatamente uma vez. Se o array resultante (com elementos únicos) tiver o mesmo tamanho que o array original, significa que não há elementos únicos e a função retorna null. Caso contrário, retorna o array contendo apenas os elementos que aparecem uma vez.

A Atividade 4 tem como objetivo combinar dois arrays em um único array. A função utiliza o método concat, que une os dois arrays fornecidos em um novo array. O método concat não altera os arrays originais, mas retorna um novo array que inclui todos os elementos dos arrays fornecidos na ordem em que aparecem.

A Atividade 5 apresenta a função main, que serve para demonstrar o uso das funções das atividades anteriores. Primeiro, ela gera um array aleatório usando a função da Atividade 1 e exibe esse array. Em seguida, determina e exibe o elemento mais frequente no array usando a função da Atividade 2. Depois, filtra e exibe os elementos únicos do array utilizando a função da Atividade 3. Por fim, concatena o array gerado com um array adicional [100, 200, 300] usando a função da Atividade 4 e exibe o resultado. A função main integra todas essas operações e exibe os resultados para verificar o funcionamento das funções criadas.

-----------------------------------
Passando pela função do Exercício 1
Entrada: array [4,9,2,4,6,8,5,8,7,3]
Saída: Não há elemento mais frequente
-----------------------------------
-----------------------------------
Passando pela função do Exercício 3
Entrada: array [4,9,2,4,6,8,5,8,7,3]
Saída: array [9,2,6,5,7,3]
-----------------------------------
-----------------------------------
Passando pela função do Exercício 4
Entrada: array [4,9,2,4,6,8,5,8,7,3] e array [100, 200, 300]
Saída: array [4,9,2,4,6,8,5,8,7,3,100,200,300]
-----------------------------------
