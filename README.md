# NLP_SherlokHolmes

This project is a team project, the team members are mentioned at the beginning of the chapter one. We collectively worked with it in the month of November-December of 2019. 

This project was aimed at wroking on on the book- The Adventures of Sherlock Holmes by Arthur Conan Doyle.
The porject has the following sections-
(iypnb files is a notebok that provides interactive computational environment used by jupyter notebook)

## 1. _Separating_Chapters.ipynb-
As the title speaks for itself, here, each chapter in the book is separated using a regular-expression. The book has 12 Chapters in total. 

## 2. _POS_and_Counts.ipynb- 
Used nltk 'punkt' libraries to determine the parts of speech, tf-idf to determine how important the word is to a document in collection or corspe, NMF(non-negative matrix factorization) is a decomposition technique used for topic extraction.

## 3. _Summerizing.ipynb- 
As an attempt to summerize each chapter, we used sumy package to summerise.
### 3.1 LexRank 
LexRank is an unsupervised approach to text summarization based on graph-based centrality scoring of sentences

### 3.2 LuhnSummariser
Luhn’s algorithm is a naive approach based on TF-IDF and looking at the “window size” of non-important words between words of high importance. It also assigns higher weights to sentences occurring near the beginning of a document.

### 3.3 LsaSummarizer 
Latent Semantic Analysis is a algorithm which combines term frequency with singular value decomposition.

### 3.4 TextRankSummarizer
Text Summarizer based on the ideas of PageRank

### 3.5 KLSummarizer
The KLSum algorithm is a greedy method which adds sentences to the summary as long as the KL Divergence (a measure of entropy) is decreasing.

### 3.6 ReductionSummarizer
The Reduction algorithm is another graph-based model which values sentences according to the sum of the weights of their edges to other sentences in the document.

## 4. _Summerizing_with_LDA.ipynb
## 5. _Sentiment_Analysis.ipynb
## 6. _last_Sherlock_with_Cloud_TPUs_and_Keras.ipynb
