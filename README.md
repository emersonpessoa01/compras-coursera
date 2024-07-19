# Praticar tarefa avaliada por colega: Compra Parcelada com Juros

<p>Crie uma classe chamada Compra que recebe o valor da compra no construtor e o armazena em um atributo. Essa classe deve possuir o método total() que retorna o valor total da compra.

Crie uma subclasse chamada CompraParcelada que estende a classe Compra. Essa classe deve receber no construtor também as informações da quantidade de parcelas e o juros mensal. Crie uma nova implementação do método total() na subclasse que faz o cálculo utilizando juros compostos.

Crie testes de unidade para 1, 2, 5 e 10 parcelas.</p>
--

<details><summary>Visão geral dos critérios de avaliação</summary>

Serão verificados se os itens pedidos no enunciado foram cumpridos. Procure entregar um código organizado pois isso também será avaliado.

</details>

<details><summary>Juros Compostos</summary>

Diferente dos juros simples, o juro composto é calculado sobre o montante obtido no período anterior. Somente no primeiro período é que os juros são calculados sobre o capital inicial.

Através da fórmula abaixo, poderemos calcular o montante adquirido ao longo do tempo em que certa quantia fica submetida ao regime de juros compostos.

Montante (M)     -     Capital (C)     -     Taxa (i)       -      Período de tempo (t)

M = C * (1 + i) elevado a t

</details>
