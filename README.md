# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

Bem-vindo ao desafio de projeto "Previsão de Estoque Inteligente na AWS com SageMaker Canvas". Neste projeto, você aprenderá a usar o SageMaker Canvas para criar previsões de estoque baseadas em Machine Learning (ML). Vamos detalhar todo o processo, desde a seleção do dataset até a análise dos resultados de previsão.

## 📋 Pré-requisitos

Antes de começar, certifique-se de ter uma conta na AWS. Se precisar de ajuda para criar sua conta, confira nosso repositório [AWS Cloud Quickstart](https://github.com/digitalinnovationone/aws-cloud-quickstart).


## 🎯 Objetivos Deste Desafio de Projeto (Lab)

![image](https://github.com/digitalinnovationone/lab-aws-sagemaker-canvas-estoque/assets/730492/72f5c21f-5562-491e-aa42-2885a3184650)

O objetivo deste desafio é utilizar o Amazon SageMaker Canvas para construir um modelo de previsão de estoque. Através deste projeto, você vai:

 - Selecionar e importar um dataset relevante.
 - Treinar um modelo de machine learning.
 - Analisar as métricas de performance do modelo.
 - Fazer previsões e analisar os resultados.


## 🚀 Passo a Passo

### 1. Selecionar Dataset

-   Navegue até a pasta `datasets` deste repositório. Esta pasta contém os datasets que você poderá escolher para treinar e testar seu modelo de ML. Sinta-se à vontade para gerar/enriquecer seus próprios datasets, quanto mais você se engajar, mais relevante esse projeto será em seu portfólio.
-   Escolha o dataset que você usará para treinar seu modelo de previsão de estoque.
-   Faça o upload do dataset no SageMaker Canvas.

  Para este projeto, utilizei o dataset `vendas_consoles_brasil.csv`, que contém dados de vendas de consoles no Brasil. O dataset inclui informações como a data da venda, o tipo de console, a quantidade vendida, o preço unitário e a receita total.

### 2. Construir/Treinar

-   No SageMaker Canvas, importe o dataset que você selecionou.
-   Configure as variáveis de entrada e saída de acordo com os dados.
-   Inicie o treinamento do modelo. Isso pode levar algum tempo, dependendo do tamanho do dataset.

### 3. Analisar

-   Após o treinamento, examine as métricas de performance do modelo.
-   Verifique as principais características que influenciam as previsões.
-   Faça ajustes no modelo se necessário e re-treine até obter um desempenho satisfatório.

### 4. Prever

-   Use o modelo treinado para fazer previsões de estoque.
-   Exporte os resultados e analise as previsões geradas.
-   Documente suas conclusões e qualquer insight obtido a partir das previsões.

###   Análise dos Resultados
Aqui estão os resultados da previsão gerada pelo modelo:

4. Prever
Utilize o modelo treinado para fazer previsões de estoque. Aqui estão os resultados de previsão gerados pelo modelo:

|Console	|Probabilidade
Nintendo Switch	18.93%
PlayStation 4	18.95%
PlayStation 5	18.90%
Xbox One	18.94%
Xbox Series X	24.29%
## 🤔 Dúvidas?

Esperamos que esta experiência tenha sido enriquecedora e que você tenha aprendido mais sobre Machine Learning aplicado a problemas reais. Se tiver alguma dúvida, não hesite em abrir uma issue neste repositório ou entrar em contato com a equipe da DIO.
