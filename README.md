# Indicium - Projeto de Precificação de Veículos Usados

Este repositório contém o código e os arquivos necessários para o projeto de precificação de veículos usados para o desafio da Indicium.

O objetivo do projeto é analisar os dados fornecidos e criar um modelo preditivo que estime os preços dos carros com base nas informações disponíveis. Isso permitirá definir preços mais competitivos para melhorar o desempenho na área de revenda de automóveis usados.

## Descrição dos Datasets

### O projeto inclui dois datasets:

**cars_training**: Este dataset é composto por 29584 linhas e 28 colunas de informações (features). Cada linha representa um veículo usado e a coluna "preco" é a variável a ser prevista.

**cars_test**: Este dataset contém 9862 linhas e 28 colunas, sendo que a coluna "preco" não está presente, uma vez que é a variável que desejamos prever com o modelo treinado.

### Estrutura do Repositório

O repositório está organizado da seguinte forma:

**datasets/**: Nesta pasta estão os arquivos CSV com os dados de treinamento (cars_training.csv) e teste (cars_test.csv).


## Configuração do Ambiente

Para reproduzir os resultados e executar o projeto, siga as instruções abaixo:

1. Clone este repositório para o seu ambiente local:

        git clone https://github.com/guioliveiras/Lighthouse-Indicium

2. Certifique-se de ter as seguintes bibliotecas instaladas em seu ambiente Python:

        pip install -r requirements.txt

## Executando o Projeto

## Análise Estatística e EDA

## Previsão de Preços

Para realizar a previsão do preço a partir dos dados, foi utilizado um modelo de regressão linear. Foram escolhidas variáveis relevantes e feitas transformações adequadas durante o pré-processamento para melhorar o desempenho do modelo. A métrica de performance escolhida para avaliar o modelo é o erro médio absoluto (MAE), que mede a diferença média entre as previsões e os preços reais.

## Resultado Final

O resultado final do modelo, contendo as previsões de preços para os dados de teste, está disponível no arquivo ***predicted.csv*** na pasta **results/**.

## Contribuição

Este projeto foi desenvolvido por Guilherme Oliveira. Se você deseja contribuir, sinta-se à vontade para enviar pull requests com melhorias ou correções.

## Agradecimentos

Agradeço aa Indicium pela oportunidade de trabalhar neste projeto e a toda a equipe envolvida.
