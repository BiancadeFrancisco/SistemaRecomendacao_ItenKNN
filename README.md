# SistemaRecomendacao_ItenKNN

## Descrição Projeto

**Conjunto de dados:**
Dataset MovieLens. Conjunto de dados que contém avaliações de usuários de filmes.
- ratings.parquet: avaliações dos usuários para filmes
- movies.parquet: metadados dos filmes

**Arquivo:** .parquet

**Objetivo:**
Explorar, analisar e encontrar itens recomendados em um dataset de filmes através de um item alvo, utilizando o ItemKNN (algoritmo de filtragem colaborativa, baseado na similaridade de itens).

**IDE:** Colab

**Linguagem:** Python 

**Principais bibliotecas utilizadas:**
•	Surprise, biblioteca do Sklearn que possui diversos algoritmos de recomendação;
•	Numpy, para realizar cálculos numéricos;
•	Pandas, para manipulação e tratamento dos dados;
•	Scikit-learn, aprendizado de máquina;
•	Google.colab, para importar arquivos da núvem.

**Sequencia processos:**
1° Instalar bibliotecas;
2° Instalar datasets;
3° Definir datasets de treino e validação;
4° Treinar o modelo;
5° Avaliar o treinamento;
6° Predição do conjunto de validação;
7° Gerando recomendações;
8° Analisando algumas recomendações (K vizinhos próximos).

**Resultado:**
Através da sequência de processos realizadas para analisar e explorar o algoritmo de recomendação ItemKNN, foi possível gerar recomendações de filmes através de um item alvo.
