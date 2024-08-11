# Projeto: PySpark-ML-NLP

Este projeto utiliza PySpark para trabalhar com modelos de classificação, aplicando processamento de linguagem natural para classificar textos como positivos ou negativos.

## Funcionalidades

1. **Vetorização dos Dados**
   - Transformação dos dados em vetores para modelos de classificação.
2. **Modelos de Classificação**
   - Regressão Logística
   - Árvore de Decisão
   - Random Forest
   - Árvores de Gradiente
3. **Avaliação de Métricas**
   - Acurácia
   - Precisão
   - Recall
   - F1
4. **Validação Cruzada**
   - Aplicação de cross-validation para otimizar os modelos.
5. **Classificação de Comentários**
   - Criação de dados de entrada com comentários positivos e negativos para testar o modelo.

## Objetivo

Identificar o modelo de classificação mais preciso para categorizar respostas de usuários como positivas ou negativas.

## Dataset

O conjunto de dados se chama `imdb-reviews.csv` e está localizado na pasta `data`. É necessário atualizar o caminho de leitura do arquivo no código para garantir que o arquivo seja lido corretamente. O dataset também pode ser encontrado em: [Kaggle](https://www.kaggle.com/datasets/luisfredgs/imdb-ptbr).
