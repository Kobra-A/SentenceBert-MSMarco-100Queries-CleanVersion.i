# SentenceBert-MSMarco-Passage Ranking.i
In this project, we tried to solve passage ranking problem with Sentence-Bert.
The data set that we used is MS-Marco. We used the Top 1000 Dev folder in this task that contains 6,669,195 records including qid, pid, query, passage.
We processed the data set with NLK package and tekenized the passages into sentences.

# Ms-Marco
Ms-Marco is data set containing around 8.8 million passages suitable for question answering tasks. The dataset and related information can be found in following link.
https://github.com/microsoft/MSMARCO-Passage-Ranking

# Panda and NLTK
NLTK is a natural languane toolkit for handling texts. In this project, we used NLTK to process the dataset and tokenize the passages.The following link redirect you to the related web page https://www.nltk.org/   Panda is a data frame for handling huge data sets. We used Panda in this project to handle our data set. The following link redirect you to it's documentation https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.html.

# Sentence-Bert
Sentence bert is a BERT-based model proposed by Nils Reimers and Iryna Gurevych in 2019. This model is suitable for computing the embedding of sentences in an efficient amount of time. This model uses siamese and triplets networks to produce the embeddings. By having these sentence embeddings and computing the cosine similarity between them, we can compute a similarity scores for each pair of sentences.
The related paper for Sentence-Bert can be found in following link:
https://arxiv.org/pdf/1908.10084.pdf
