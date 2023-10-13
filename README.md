# Calculando diferenças de datas no Power BI
Olá! Espero que esteja bem! No artigo de hoje, vou demonstrar como criar uma coluna com diferença de datas e como realizar agrupamentos com esses dados.

O cenário é o seguinte: você possui duas tabelas, uma contendo o Id único de cada cliente, o dia em que cada cliente recebeu o convite para acessar sua loja online e a data do acesso.
Na segunda tabela, há informações de data da venda realizada e Id único do cliente.
A modelagem dos dados é bem básica, realizando apenas a relação entre as duas tabelas utilizando o Id único do cliente como chave primária. 
Na tabela Acessos, foram criadas duas colunas: quantidade de dias entre o convite e acesso e agrupamento de clientes.
O agrupamento de clientes é referente a quantos dias cada cliente levou entre o convite e o acesso: no mesmo dia, de 1 a 5 dias e de 6 a 10 dias.

Na tabela Transacoes, temos a data da venda e o Id único de cada cliente. Nessa tabela, criei 3 colunas: a primeira trazendo a informação da data de acesso do cliente, a segunda com a quantidade de dias entre o acesso e a venda;
e o agrupamento de quantidade de dias, assim como na primeira tabela.
Uma dica: na fórmula de agrupamento de dias, repare que há espaço entre as aspas e o resultado que queremos: " Mesmo dia", "  1 a 5 dias" etc.
Isso é feito para colocar na ordem que queremos, sem ser necessariamente por ordem alfabética ou de valores. 
Faço a ordem que eu quero utilizando espaços, ou seja, um espaço pra quem eu queira que fique em primeiro, dois espaços pra quem eu quero que esteja em segundo e por aí vai.
Assim, é possível criar gráficos que demonstrem a relação entre os dias entre convite, acesso e vendas.

No nosso exemplo, podemos analisar que o tempo entre o recebimento do convite e acesso é bem dividido, com uma proporção um pouco maior de clientes que acessam no mesmo dia que recebem o convite. 
Em contrapartida, vemos que a maior parte das vendas ocorre entre 1 a 5 dias após o primeiro acesso, trazendo informações sobre comportamento de consumo dos clientes.
Esse tipo de análise e agrupamento também pode ser útil em definições de engajamento e churn, sendo bastante útil para o processo de tomada de decisão baseada em dados.

Espero que tenha gostado. Continuamos estudando e vamos em frente!  
