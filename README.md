# Modelo de Analise de Sentimentos

Este projeto é um modelo simples de Rede Neural para analise de sentimentos **simples** de textos positivos e negativos. Este projeto visa mesmo apenas estudo, pois estou começando a aprender sobre a Biblioteca Pytorch.


# Descrição

Este projeto é simples conforme dito. Ele foi treinado utilizando o Dataset "Sentiment140 dataset with 1.6 million tweets" disponibilizado no Kaggle para o treinamento.

O processo para o desenvolvimento do modelo pode ser separado em:

- Analise dos dados
- Tratamento dos dados 
- Processamento de Linguagem Natural usando modelo de Embedding disponível na biblioteca Hugging Face
- Treinamento utilizando Rede Neural (MultiLayer Perceptron Classifier) do Pytorch
- Teste simples utilizando o modelo para previsão de textos através de um programa simples.

# Tecnologias usadas

- Linguagem Python
- Bibliotecas: Pandas, Numpy, Sklearn, Sentence_Transformers, Pytorch
- Modelo de Embedding: 'granite-embedding-278m-multilingual'
- Jupyter Notebook

# Outras informações

Disponibilizei o Jupyter Notebook com todas as células para qualquer um poder consultar. A princípio ele está cheio de comentários nas células para estudo meu, pois parti dos codigos simples do QuickStart no site da biblioteca Pytorch. Não espere um código avançado, pois estou iniciando na biblioteca e quis realizar algo simples.

