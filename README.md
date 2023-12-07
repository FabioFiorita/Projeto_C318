# Projeto C318

## Autores
- Avner José Guimarães Ribeiro
- Bernardo Dalboni Gandolpho
- Fábio Luiz Fiorita Pontes

## Contextualização do Problema

### Objetivos de Negócios:
O objetivo principal deste projeto é desenvolver um sistema de detecção de phishing eficaz que possa ajudar a proteger os usuários da internet contra fraudes cibernéticas. Com o aumento das atividades online e o crescente número de ataques de phishing sofisticados, é crucial criar um mecanismo de defesa robusto para identificar e bloquear URLs maliciosas.

### Objetivos de Ciência de Dados:
- Coletar e explorar um conjunto de dados de URLs com características relevantes para a detecção de phishing;
- Desenvolver modelos de Machine Learning capazes de identificar URLs suspeitas e distinguir entre URLs legítimas e URLs de phishing;
- Avaliar o desempenho dos modelos usando métricas apropriadas, como precisão, recall e F1-score.

### Descrição do Problema:
O phishing é uma das ameaças mais comuns e eficazes utilizadas por cibercriminosos para enganar os usuários e roubar informações pessoais e financeiras. Com a nossa crescente dependência da internet, tornou-se fundamental desenvolver uma solução de detecção de phishing que seja capaz de identificar URLs maliciosas de maneira precisa e eficiente.

O conjunto de dados fornecido contém 11.430 URLs e 87 características extraídas deles, sendo uma referência para sistemas de detecção de phishing baseados em Machine Learning. Essas características são divididas em três classes: características extraídas da estrutura e sintaxe das URLs, características extraídas do conteúdo das páginas correspondentes e características obtidas por meio de consultas a serviços externos. O conjunto de dados é equilibrado, com 50% das URLs representando phishing e 50% sendo URLs legítimas.

Este projeto visa desenvolver modelos de Machine Learning que possam analisar as características das URLs e determinar se são suspeitas ou não.

## Enquadramento do Problema
Neste projeto de ciência de dados e Machine Learning, estamos enfrentando o desafio de detectar e classificar URLs como legítimas ou suspeitas de phishing. Para abordar esse problema, escolhemos enquadrá-lo como um problema de **Aprendizagem Supervisionada - Classificação**.

A escolha de enquadrar o problema como classificação é apropriada, uma vez que temos um conjunto de dados que inclui URLs rotuladas como phishing ou legítimas. Nossa tarefa principal é treinar um modelo de Machine Learning capaz de classificar novas URLs com base em suas características em uma das duas classes: "Phishing" ou "Legítima".

Isso implica que nosso modelo deve aprender com exemplos de URLs previamente rotuladas e desenvolver a capacidade de discernir entre as características que são indicativas de uma URL de phishing e aquelas que são típicas de URLs legítimas.

## Importações e Configurações do NumPy e Pandas
Nesta seção, importamos as bibliotecas necessárias e configuramos algumas opções de exibição para facilitar a visualização dos dados.

## Carregando o Conjunto de Dados de Phishing
Aqui, carregamos o conjunto de dados de phishing a partir de um arquivo CSV.

## Verificação do conjunto de dados
Nesta seção, realizamos uma análise exploratória inicial dos dados para entender suas características.

## Separando o dataset em treino e teste
Nesta seção, dividimos o conjunto de dados em conjuntos de treinamento e teste. Isso nos permite avaliar o desempenho do nosso modelo em dados não vistos.

## Análise de correlação entre as features
Aqui, analisamos a correlação entre as diferentes características do conjunto de dados. Isso nos ajuda a entender quais características são mais relevantes para a nossa tarefa de classificação.

## Definindo uma função para avaliar a performance de cada modelo
Nesta seção, definimos uma função para avaliar o desempenho dos nossos modelos de Machine Learning. Isso nos permite comparar diferentes modelos e escolher o melhor.

## Criando Pipelines para o modelo
Aqui, criamos pipelines para automatizar o processo de treinamento e avaliação dos nossos modelos de Machine Learning.

## Avaliação dos Modelos
Nesta seção, treinamos e avaliamos nossos modelos de Machine Learning. Usamos tanto a validação cruzada quanto a busca em grade para otimizar os hiperparâmetros dos nossos modelos.

## Visualização dos Resultados
Finalmente, visualizamos os resultados dos nossos modelos de Machine Learning. Isso nos permite entender melhor o desempenho dos nossos modelos e identificar áreas para melhoria.