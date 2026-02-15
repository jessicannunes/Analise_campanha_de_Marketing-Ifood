# 📊 Campanha 3 – Análise de Marketing | iFood
# Problema de Negócio
O iFood é o principal aplicativo de entrega de comida no Brasil. Em 2025, a empresa já atendia cerca de 55 milhões de clientes, com mais de 400 mil estabelecimentos parceiros e presença em 1.500 cidades.

Para sustentar sua posição de liderança, a empresa investe continuamente em campanhas de marketing com o objetivo de aumentar o engajamento dos clientes e maximizar o retorno financeiro dessas ações.

Apesar dos investimentos realizados, surge o desafio de entender quais perfis de clientes que respondem melhor às campanhas, identificar oportunidades de otimização e direcionar os esforços de marketing de forma mais eficiente.
# Contexto
O time de Marketing da iFood realiza campanhas recorrentes com o objetivo de aumentar o faturamento da empresa. No entanto, existe a necessidade de compreender quais ações geraram resultados positivos e quais tiveram desempenho abaixo do esperado, para que os aprendizados possam ser aplicados em iniciativas futuras.

Dessa forma, por meio da análise apresentada, é possível gerar insights relevantes para o time de marketing, apoiando decisões mais estratégicas e contribuindo para o aumento do faturamento nas próximas campanhas.
# Premissas da análise
Para a realização da análise, foram adotadas as seguintes premissas:

1. A campanha analisada aconteceu entre 15 de Março de 2025 até 30 de Março de 2025.
2. As análises foram feitas com foco em identificação de padrões, não em causalidade estatística.
3. Todos os produtos comprados com cupom foram removidos.
4. A análise considerou somente os produtos do catálogo da campanha.
   
# Estratégia da solução
Uma das estratégias escolhidas para a análise foi a modelagem de dados em fatos e dimensões, com essa estrutura, a análise permite identificar com mais clareza quais combinações trouxeram melhor desempenho, um exemplo seria quais canais geraram maior faturamento ou quais tipos de oferta funcionaram melhor para certos públicos.

Com essa estratégia aplicada o resultado é entregar ao time de marketing do iFood insights para planejar a próxima campanha de forma mais estratégica, priorizando ações com maior potencial de retorno e evitando investimentos em iniciativas que apresentaram baixo impacto.

## Passo 1:  Resumir o contexto em uma pergunta aberta
As perguntas abertas são um tipo de demanda muito comum, como essa solicitada, no qual a demanda pode ter N possíveis soluções, para buscar o objetivo deve-se escolher entre as possíveis questões a alternativa com o maior retorno e o menor esforço possível. Para essa análise foi definida a seguinte pergunta aberta:
**Como aumentar o resultado da próxima campanha de Marketing?**

## Passo 2: Transformar pergunta aberta em fechada
Aplicando o concieto de slice(fatiar) as alternativas possíveis para aumentar o resultado da próxima campanha precisa-se direcionar a análise para exatamente o que precisa ser feito. Foi
definido, para essa análise a seguinte pergunta fechada: 
**Quais são as características dos clientes que mais gastaram na campanha de Marketing?**

## Passo 3: Definição da Coluna Fato
O fato central da análise passa a ser a coluna MntTotal "GastoTotalClientes", que representa o valor total desembolsado por cada cliente durante a campanha. Esse indicador será o foco da investigação, já que o desafio de negócio está diretamente ligado ao aumento do faturamento nas próximas ações de marketing.

## Passo 4: Identificação das Dimensões
As colunas foram agrupadas em dimensões comuns que fornecem mais detalhes sobre o Fato que será analisado. Foram organizadas as seguintes dimensões:
***1. Cliente***
 - Salário
 - Idade
 - Faixa-Etária
 - Dias-Cliente
 - Estado-Civil
 - Formação
 - Crianças-Casa
 - Adolescentes-Casa

***2. Produto***
 - Qtde-Vinhos
 - Qtde-Frutas
 - Qtde-Carnes
 - Qtde-Peixes
 - Qtde-Doces
 - Qtde-Premium
 - 
***3. Comportamento de Compra***
 - Qtde-Compras
 - Qtde-Compras-Web
 - Qtde-Compras-Loja
 - Visitas-Site-Mes

## Passo 5: Hipóteses Analíticas
Fato (Medida) + Dimensão (Detalhes) + Comparação

As hipóteses analíticas são construídas a partir da combinação do fato com as dimensões, usando sempre uma valor de comparação como maior, menor ou igual
Fato + Dimensão: Cliente e Idade.

1. O faturamento dos clientes abaixo de 30 anos é maior do que nas outra faixas etárias.
2. O faturamento dos clientes entre 20 e 30 anos é maior do que nas outras faixas etárias.
3. O faturamento dos clientes acima dos 30 anos é maior do que nas outras faixas.

Fato + Dimensão: Cliente e Estado Civil

5. Clientes solteiros gastam mais do que os outros segmentos de clientes.
6. Clientes solteiros gastam menos do que os outros segmentos de clientes.
7. Clientes casados gastam mais do que os outros segmentos de clientes.

Fato + Dimensão: Cliente - Estado Civil e Idade

7. Clientes solteiros acima dos 30 anos gastam mais do clientes casados acima dos 30 anos.

Fato + Dimensão: Cliente e Formação Profissional

9. Clientes com formações avançadas (Doutora) gastam mais do que clientes com Ensino Fundamental
10. Clientes com maiores salários tem nível escolaridade maior.

## Passo 6: Critérios de Priorização
Critério 1: Dados disponíveis
Critério 2: Insights Acionáveis

## Passo 7: Priorização das Hipóteses Analíticas
- Hipótese 1: Clientes abaixo dos 30 anos gastam mais com produtos do Ifood do que as outras faixas etárias.
- Hipótese 2: Clientes solteiros gastam menos do que os outros segmentos de clientes.
- Hipótese 3: Clientes solteiros abaixo dos 30 anos gastam mais com produtos do Ifood do que as outras faixas etárias.
- Hipótese 4: Clientes com crianças em casa compram mais pelo Ifood.
- Hipótese 5: Clientes que compram mais carne também compram mais vinho.

## Insights da análise
## Resultados
Conclusão: O melhor segmento da campanha foram os clientes casado com idade entre 41 e 50 anos de idade, sem filhos em casa e com graduação completa.

O pior segmento de clientes foram os viúvos de todas as faixas etárias, clientes abaixo dos 30 anos de todos os estados civis com 2 ou mais crianças em casa e somente ensino fundamental.

Para maximizar o lucro da próxima campanha, o marketing precisa direcionar suas ações ao melhor segmento apresentado e reduzir o investimentos nos outros segmentos, especialmente o mencionado.

## Visualize a Análise Completa
https://lookerstudio.google.com/reporting/62f4bf15-8a99-46e6-9056-596d8a982490/page/Xb8nF

## Próximos passos
1 .Explorar mais características dos clientes
2. Automatizar a coleta e a análise para acompanhamento.
3. Agrupar os clientes em grupos de maior e menor faturamento para entender se há similiridades ou não.
4. Montar um dashboard de acompanhamento das métricas das futuras campanhas de marketing
