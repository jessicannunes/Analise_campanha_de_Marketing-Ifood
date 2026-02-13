# 📊 Campanha 3 – Análise de Marketing | iFood
# Problema de Negócio
O iFood é o principal aplicativo de entrega de comida no Brasil. Em 2025, a empresa já atendia cerca de 55 milhões de clientes, com mais de 400 mil estabelecimentos parceiros e presença em 1.500 cidades.

Para sustentar sua posição de liderança, a empresa investe continuamente em campanhas de marketing com o objetivo de aumentar o engajamento dos clientes e maximizar o retorno financeiro dessas ações.

Apesar dos investimentos realizados, surge o desafio de entender quais perfis de clientes que respondem melhor às campanhas, identificar oportunidades de otimização e direcionar os esforços de marketing de forma mais eficiente.
# Contexto
O time de Marketing do ifood faz campanhas recorrente para aumentar o faturamento da empresa. Porém existe uma necessidade de entender as ações que trouxeram resultados positivos e negativos para aprender e replicar nas futuras campanhas com o objetivo de aumentar o faturamento.

Nesse contexto, a análise de dados que será feita tem um papel fundamental para coletar, analisar e gerar insights para o time de marketing, a fim de ajudá-la à aumentar o faturamento nas próximas campanhas.
# Premissas da análise
Para a realização da análise, foram adotadas as seguintes premissas:

1. A campanha analisada aconteceu entre 15 de Março de 2025 até 30 de Março de 2025.
2. As análises foram feitas com foco em identificação de padrões, não em causalidade estatística.
3. Todos os produtos comprados com cupom foram removidos.
4. A análise considerou somente os produtos do catálogo da campanha.
   
# Estratégia da solução
Foi aplicado o Princípio de Pareto, ou regra 80/20, onde afirma que cerca de 80% dos efeitos (resultados) advêm de 20% das causas.
Para alcançar o nosso objetivo de análise e ajudar o time de marketing a ter maior sucesso na próxima campanha, foi usado essa técnica de pareto para separar 20% dos clientes que trouxeram mais resultados, (80%), nessa campanha. 
Foi estudado as características desses clientes para informar ao time de marketing para que busquem no mercado ou na base que já se tem, pessoas com essas características que funcionaram nessa campanha.

## Passo 1:  Resumir o contexto em uma pergunta aberta
Onde estudar e avaliar as possibilidades e escolher a alternativa com o maior retorno e o menor esforço possível. Para essa análise foi definida a seguinte pergunta aberta:
Como aumentar o resultado da próxima campanha de Marketing?

## Passo 2: Transformar pergunta aberta em fechada
Filtrando entre todas as alternativas possíveis para aumentar o resultado da próxima campanha e direcionar a análise para exatamente o que precisa ser feito. Foi
definido, para essa análise a seguinte pergunta fechada: 
Quais são as características dos clientes que mais gastaram na campanha de Marketing?

## Passo 3: Definição da Coluna Fato
O fato central da análise passa a ser a coluna MntTotal "GastoTotalClientes", que representa o valor total desembolsado por cada cliente durante a campanha. Esse indicador será o foco da investigação, já que o desafio de negócio está diretamente ligado ao aumento do faturamento nas próximas ações de marketing.

## Passo 4: Identificação das Dimensões
As colunas foram agrupadas em dimensões comuns que fornecem mais detalhes sobre o Fato que será analisado. Foram organizadas as seguintes dimensões:
1 .Cliente
Salário
Idade
Faixa-Etária
Dias-Cliente
Estado-Civil
Formação
Crianças-Casa
Adolescentes-Casa
Recência
2. Produto
Qtde-Vinhos
Qtde-Frutas
Qtde-Carnes
Qtde-Peixes
Qtde-Doces
Qtde-Premium
3. Comportamento de Compra
Qtde-Compras
Qtde-Compras-Web
Qtde-Compras-Loja
Visitas-Site-Mes
4. Comportamento de Mkt
Reclamações.

## Passo 5: Hipóteses Analíticas
Fato (Medida) + Dimensão (Detalhes) + Comparação
