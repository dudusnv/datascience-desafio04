# Construção de um Modelo de Regressão para Marketing

I - Contexto

  Este projeto foi elaborado como parte de um desafio no curso de Formação em Ciência de Dados, com o propósito de aplicar técnicas de regressão para analisar dados de campanhas de marketing. 
  O objetivo central foi construir um modelo preditivo capaz de estimar o retorno em vendas a partir dos investimentos em publicidade.

  A empresa fictícia utilizada no desafio realiza investimentos mensais em plataformas como YouTube, Facebook e jornais impressos. O desafio consistiu em compreender como esses investimentos influenciam o retorno   em vendas, identificar os fatores mais impactantes na geração de leads e criar um modelo preditivo confiável para orientar decisões estratégicas.

II - Estrutura do Projeto

  O projeto foi dividido em quatro etapas principais, descritas a seguir:

  *1. Análise Descritiva
  
   O trabalho inicial envolveu uma exploração preliminar do conjunto de dados para entender suas características gerais e identificar possíveis problemas.    
   Nesta etapa foram realizadas as seguintes atividades:
    
   - Cálculo de estatísticas descritivas das variáveis;
   - Detecção de dados ausentes ou inconsistentes.
    
  *2. Análise Exploratória
  
   Com foco em aprofundar a compreensão das relações entre as variáveis, realizou-se uma análise exploratória. 
   O objetivo foi detectar correlações e padrões que pudessem auxiliar no desenvolvimento do modelo. As ações realizadas incluíram:

   - Análise das correlações entre os investimentos e o retorno de vendas;
   - Criação de gráficos de dispersão para identificar possíveis relações lineares entre as variáveis.
      
  *3. Modelagem
  
   Nesta fase, o modelo de regressão foi desenvolvido para prever os retornos de vendas com base nos investimentos em publicidade. 
   As atividades principais incluíram:

   - Divisão do conjunto de dados em partes de treinamento e teste;
   - Desenvolvimento e treinamento de um modelo de regressão linear;
   - Avaliação do modelo utilizando métricas de desempenho adequadas.
     
 *4. Predição
 
  Com o modelo finalizado, utilizou-se novos dados para realizar previsões e avaliar a precisão do modelo.
  As ações desenvolvidas nesta etapa incluíram:

   - Estimativa do retorno em vendas para diferentes níveis de investimento;
   - Cálculo de métricas de desempenho, como RMSE (Erro Quadrático Médio da Raiz) e R² (Coeficiente de Determinação).

III - Requisitos

  Para reproduzir o projeto, é necessário:

   - Python 3.x
   - Jupyter Notebook
   - Instalar as seguintes bibliotecas:
   - pandas
   - numpy
   - matplotlib
   - seaborn
   - scikit-learn
