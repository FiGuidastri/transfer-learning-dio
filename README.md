# Classificação de Imagens - Desafio DIO: Cats vs Dogs com Transfer Learning
Este repositório contém uma solução para o desafio da Digital Innovation One (DIO), que consiste em implementar um classificador de imagens para diferenciar entre gatos e cachorros. O modelo utiliza Transfer Learning com a arquitetura pré-treinada MobileNetV2, uma técnica eficaz para tarefas de visão computacional quando há restrições de dados e tempo de treinamento.

## Visão Geral
Este projeto treina um classificador binário de imagens usando o dataset Cats vs Dogs disponibilizado pelo TensorFlow. A técnica de Transfer Learning foi aplicada ao modelo MobileNetV2, congelando a base do modelo e adicionando uma camada densa para fazer a classificação entre gatos e cachorros.

## Estrutura do Projeto
train_dataset: Dataset de treino, carregado a partir do diretório /train do dataset cats_and_dogs_filtered.
validation_dataset: Dataset de validação, carregado a partir do diretório /validation.
model: Modelo construído utilizando MobileNetV2, compilado para otimizar com Adam e minimizar a entropia cruzada binária.

## Pré-requisitos
Python 3.x
TensorFlow (>=2.x)
Matplotlib
