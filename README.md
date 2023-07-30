# llm-t5
[LLM] - Tunando um LLM T5 para gerar resumos de textos em português

Baseado na documentação do HuggingFace: https://huggingface.co/docs/transformers/tasks/summarization 

Notebook com tutorial em Português no Google Colab:

[![Abra no Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/marcelotournier/llm-t5/blob/main/llm-t5-tuning-ptbr.ipynb)

ATENÇÃO - Tenha certeza de que você está rodando o notebook usando uma runtime de GPU (Eu usei T4)

### Dataset
O dataset usado é uma amostra aleatória de 1000 notícias brasileiras, extraído do original no Kaggle https://www.kaggle.com/datasets/marlesson/news-of-the-site-folhauol

Você pode modificar o notebook para um csv contendo as colunas `text` com os textos longos e `summary` com o resumo/titulo do texto
