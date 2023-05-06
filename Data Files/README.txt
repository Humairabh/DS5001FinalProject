A collection of data files, each in CSV format, containing the F2 through F5 & the following core tables:

LIB.csv — Metadata for the source files.
CORPUS.csv — This is a tokens table annotated with statistical and linguistic features, such as TFIDF. It should include and index that represents the OHCO of the documents in your corpus.
VOCAB.csv — Annotated with statistical and linguistic features, such as DFIDF.
In addition, the following data sets, either as features in the appropriate core table or as separate tables. Note that all tables should have an appropriate index and, where appropriate, an OCHO index.

## Principal Components (PCA)

Table of documents and components.
Table of components and word counts (i.e., the “loadings”), either added to the VOCAB table or as a separate table with a shared index with the VOCAB table.

## Topic Models (LDA)

Table of document and topic concentrations.
Table of topics and term counts, either added to the VOCAB table or as a separate table with a shared index with the VOCAB table.
Word Embeddings (word2vec)

Terms and embeddings, either added to the VOCAB table or as a separate table with a shared index with the VOCAB table.

## Sentiment Analysis

Sentiment and emotion values as features in VOCAB or as a separate table with a shared index with the VOCAB table.
Sentiment polarity and emotions for each document.
