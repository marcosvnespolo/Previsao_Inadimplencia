# Previsao_Inadimplencia 📉💸 (Projeto em Andamento)



Este repositório contém um projeto de Ciência de Dados desenvolvido com base em um conjunto de dados fornecido por uma empresa de cartão de crédito. O projeto tem como objetivo criar um modelo preditivo para a inadimplência de contas de cartão de crédito.

# Descrição do Projeto 📝
- [x] O conjunto de dados é composto por informações financeiras e demográficas de uma amostra de 30.000 titulares de contas.
- [x] Cada linha do conjunto de dados representa uma conta de cliente única. Ou seja, as informações são apresentadas em nível de conta de crédito.
- [x] O objetivo do projeto é desenvolver um modelo de Machine Learning que seja capaz de prever se uma conta de cartão de crédito ficará inadimplente no próximo mês.
- [x] Essa previsão é baseada em dados demográficos e históricos dos titulares de contas.

# Conjunto de Dados 📊📚
- [x] O conjunto de dados já foi preparado e está disponível na pasta do projeto.
- [x] Inclui uma variedade de dados demográficos e históricos financeiros, o que proporciona uma base robusta para a criação de um modelo preditivo eficaz.

# Conclusões 🔍
Modelos de classificação como a regressão logísticas, podendem ser bastante útieis para empresas do segmento financeiro, permitindo uma tomada de decisão mais eficiente e minimizando prejuízos por inadimplência. Na prática, poderiamos aplicar este modelo em diversos cenários, como:

- [x] REDUÇÃO DE RISCOS

Um modelo como este seria bastante útil em empresas que oferecem cartões de crédito, servindo como uma triagem inicial para identificar contas com alto risco de inadimplência.

- [x] PERSONAIZAÇÃO DE OFERTAS

Através da anáise do risco de inadimplência, poderiam ser oferecidos serviços personalizados para clientes específicos. Por exemplo, contas consideradas pelo modelo com baixo risco de inadimplência, poderiam receber mehores ofertas de produtos financeiros, como condições de empréstimo mais interessantes, ou até mesmo um maior imite de cartão de crédito.

- [x] EFICIÊNCIA OPERACIONAL

A adoção de um bom modelo de classificação pode melhorar de forma significativa a eficiência operacional do negócio, reduzindo o tempo e o esforço gastos com uma análise manual de contas, o que poderia liberar recursos para o desenvolvimento de outras áreas relevantes, como atendimento ao cliente ou desenvovimento de novos produtos.

# Limitações

- [x] Os dados fornecidos para a variável "PAY_1" parecem pouco consistentes, sendo que apenas o primeiro mês são representativos para previsões futuras.

- [x] A métrica ROC AUC observada está próxima de 0,5, o que sugere um classificador pouco eficiente, o que indica que o modelo poderia não performar da maneira desejada em uma aplicação real.

# Próximos Passos

- [x] REFINAMENTO DAS VARIÁVEIS

Durante a fase de desenvolvimento e avaliação do modelo de previsão de inadimplência, ficou claro que a seleção e o tratamento das variáveis têm um impacto significativo no desempenho do modelo. Inicilmente, foquei na variável "EDUCATION" para treinamento. Porémo, a análise sugere que o desempenho do modelo poderia ser melhorado através de uma seleção mais criteriosa das variáveis utilizadas.

- [x] ENGENHARIA DE VARIÁVEIS

A criação de novas variáveisS derivadas das já existentes ou mesmo a criação de interações entre elas pode enriquecer o conjunto de dados, possibilitando que o modelo identifique relações mais complexas. Por exemplo, a combinação de idade e renda pode criar uma nova característica que represente o risco financeiro de forma mais precisa.

- [x] APRIMORAMENTO NA SELEÇÃO DAS VARIÁVEIS

Ao invés de utilizar todas as variáveis disponíveis, uma abordagem mais criteriosa poderia ser realizada para identificar e manter apenas as variáveis que mais contribuem para a previsão. Técnicas como importância de variáveis baseada em árvore ou até mesmo métodos de regularização poderiam ser utilizados para este fim.
