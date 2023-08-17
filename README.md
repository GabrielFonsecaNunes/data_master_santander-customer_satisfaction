# Case Satisfação Clientes Santander
* <b> Problema de Negócio </b>

O Banco Santander quer identificar clientes insatisfeitos no inicio do relacionamento. Isso
irá permitir que o Santander adote medidas proativas para melhorar a felicidade de um cliente
antes que seja tarde demais.
A partir do Dataset: https://www.kaggle.com/c/santander-customer-satisfaction/data

Para resolver este case será usado um conjunto de dados sintéticos contendo um > grande número de variáveis numéricas. A coluna TARGET é a variável resposta. > Ela é igual a 1 para clientes insatisfeitos e igual a 0 para clientes > satisfeitos. Duas bases são dadas, uma para treino e uma para avaliação. Três > são as tarefas a serem realizadas.

Um falso positivo ocorre quando classificamos um cliente como insatisfeito, mas ela não se comporta como tal. Neste caso, o custo de preparar e executar uma ação de retenção é um valor fixo de 10 reais por cliente. Nada é ganho pois a ação de retenção não é capaz de mudar o comportamento do cliente. Um falso negativo ocorre quando um cliente é previsto como satisfeito, mas na verdade ele estava insatisfeito. Neste caso, nenhum dinheiro foi gasto e nada foi ganho. Um verdadeiro positivo é um cliente que estava insatisfeito e foi alvo de uma ação de retenção. O benefício neste caso é o lucro da ação (100 reais) menos os custos relacionados à ação de retenção (10 reais). Por fim, um verdadeiro negativo é um cliente insatisfeito e que não é alvo de nenhuma ação. O benefício neste caso é zero, isto é, nenhum custo, mas nenhum lucro.

A primeira tarefa deste case é maximizar o lucro esperado por cliente considerando o contexto descrito no parágrafo acima.

A segunda tarefa consiste em dar uma nota de 1 a 5 para cada cliente da base teste, respeitando a variável TARGET, isto é, o seu nível de satisfação, sendo 1 o mais insatisfeito e 5 o mais satisfeito. Ao dar essa nota deve-se ter em mente que somente os clientes com nota 1 serão alvos de uma ação de retenção e que o objetivo dessa ação é maximizar o lucro esperado por cliente (usando os mesmos valores da primeira questão).

* <b> Objetivos </b>

* <b> Metodologia </b>

*   
