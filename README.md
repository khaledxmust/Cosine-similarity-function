# Cosine similarity function
Building a Preprocessing, TF-IDF, CosineSimilarity functions from scratch

Considering the following simple documents:

Doc1: "So far in this course, we have studied association rule mining and we learned about frequent itemsets"

Doc2: “During the past couple of weeks, we started learning about Text Mining"

Doc3: "Data Mining and Text Mining are fun topics!"

Doc4: "Holidays are fun! I can’t wait till my next holiday…"

a) Write a function preprocessCorpus(corpus) that takes in a text corpus represented as a list of strings (each string represents a document). The function should return a similar list which contains a copy of the original data after applying casefolding, stepword removal, and stemming.

b) Write a function getTF-IDF(corpus) that takes in a text corpus (represented as a list of strings) and returns a matrix representing the TF-IDF weights of the corpus. Each column in the matrix should represent a word in the vocabulary (sorted alphabetically) and each row should represent a document. You may use the Python CountVectorizer but you may not use the TFIDFVectorizer.

c) Write a function Sim1(v1, v2), that takes in two vectors and returns the cosine similarity between them as described in the lecture notes. Please note that you will need to import the math library and use the log10 function for this problem.

d) Use the function implemented in step c, to calculate the similarity between all documents and the query “Text mining”. Sort the similarities in descending
order.
