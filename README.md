
#    Resumo das Aulas – Processamento de Linguagem Natural

Este repositório contém os notebooks desenvolvidos ao longo do curso de PLN, organizados por aula. Abaixo estão os resumos das aulas 2 a 12.

---

## Aula 2 – Pré-processamento de Texto

###   Objetivos
- Realizar a limpeza e normalização de textos brutos.
- Preparar os dados textuais para a vetorização e modelagem.

###    Técnicas
- Remoção de stopwords, pontuações e acentuação.
- Tokenização de sentenças e palavras.
- Aplicação de stemming.

###    Bibliotecas Usadas
- `nltk`
- `re`
- `unidecode`

---

## Aula 3 – Representação de Texto (BoW e TF-IDF)

###   Objetivos
- Converter textos em representações numéricas para uso em modelos de machine learning.

###    Técnicas
- Vetorização utilizando Bag of Words.
- Representação TF-IDF (Term Frequency-Inverse Document Frequency).
- Visualização das features criadas.

###    Bibliotecas Usadas
- `sklearn.feature_extraction.text` (`CountVectorizer`, `TfidfVectorizer`)
- `pandas`

---

## Aula 4 – Classificação de Texto

###   Objetivos
- Treinar modelos de machine learning para classificação de textos.
- Identificar e-mails spam e ham com base no conteúdo textual.

###    Técnicas
- Divisão de dados em treino e teste.
- Classificação usando Naive Bayes e Regressão Logística.
- Avaliação de modelos com matriz de confusão.

###    Bibliotecas Usadas
- `sklearn.model_selection`
- `sklearn.naive_bayes`
- `sklearn.linear_model`
- `sklearn.metrics`

---

## Aula 5 – Avaliação de Modelos de Classificação

###   Objetivos
- Analisar o desempenho de classificadores de texto de forma detalhada.

###    Técnicas
- Cálculo de métricas: Acurácia, Precisão, Recall e F1-score.
- Geração de relatório de classificação.
- Interpretação da matriz de confusão.

###    Bibliotecas Usadas
- `sklearn.metrics`
- `sklearn.model_selection`

---

## Aula 6 – Word Embeddings com Word2Vec

###   Objetivos
- Representar palavras de forma vetorial com base em seu contexto semântico.
- Comparar palavras semanticamente semelhantes com embeddings.

###    Técnicas
- Treinamento de Word2Vec com o modelo Skip-gram.
- Busca de palavras similares.
- Visualização de embeddings com t-SNE.

###    Bibliotecas Usadas
- `gensim.models.Word2Vec`
- `matplotlib`
- `sklearn.manifold.TSNE`

---

## Aula 7 – Embeddings Pré-treinados (GloVe e FastText)

###   Objetivos
- Utilizar embeddings pré-treinados para representar palavras.
- Comparar diferentes tipos de embeddings na tarefa de similaridade semântica.

###    Técnicas
- Carregamento de vetores GloVe e FastText.
- Construção de dicionários de palavras e vetores.
- Cálculo de similaridade por cosseno entre palavras.
- Visualização com PCA.

###    Bibliotecas Usadas
- `numpy`
- `sklearn.metrics.pairwise`
- `matplotlib`
- `sklearn.decomposition.PCA`

---

## Aula 10 – Análise de Sentimentos

###   Objetivos
- Aplicar classificação de sentimentos em textos reais (positivos e negativos).

###    Técnicas
- Pré-processamento com `nltk`.
- Vetorização com TF-IDF.
- Treinamento de modelos de classificação (Naive Bayes, SVM, etc.).
- Avaliação com métricas e matriz de confusão.

###    Bibliotecas Usadas
- `nltk`
- `sklearn` (`TfidfVectorizer`, `MultinomialNB`, `SVC`, etc.)
- `pandas`, `matplotlib`, `seaborn`

---

## Aula 11 – Machine Learning com Textos

###   Objetivos
- Consolidar técnicas de ML aplicadas a dados textuais.
- Comparar diversos algoritmos de classificação textual.

###    Técnicas
- Pré-processamento textual completo.
- Comparação entre Naive Bayes, Regressão Logística, KNN, Árvores e Random Forest.
- Validação cruzada.
- Visualização dos resultados.

###    Bibliotecas Usadas
- `sklearn` (`LogisticRegression`, `KNeighborsClassifier`, `DecisionTreeClassifier`, `RandomForestClassifier`)
- `nltk`, `pandas`, `matplotlib`, `seaborn`

---

## Aula 12 e 13 – Redes Neurais: Modelagem com RNN

###   Objetivos
- Construir um modelo de linguagem baseado em Redes Neurais Recorrentes (RNN).
- Prever a próxima palavra em uma sequência textual.

###    Técnicas
- Tokenização e vetorização com `Keras Tokenizer`.
- Padding de sequências.
- Criação de embeddings densos com `Embedding`.
- Construção de modelo RNN com `SimpleRNN`.
- Treinamento e avaliação de modelo sequencial.

###    Bibliotecas Usadas
- `TensorFlow` / `Keras`
- `numpy`
