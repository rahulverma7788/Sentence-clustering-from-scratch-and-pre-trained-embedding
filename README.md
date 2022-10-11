# Sentence-clustering-from-scratch-and-pre-trained-embedding


In this project I am using 40000+ sentences, I want to make clusters of sentences that have similar meanings. for this project, I first preprocessed the data and then applied different types of methods for creating sentence embedding. I also applied fast clustering because I didn't know how many clusters will be made.


Sentence Embedding - I used the 4 methods for sentence embedding. 
 
1 - In this method, I used doc2vec from scratch for creating sentence embedding then I applied the clustering method.

2 - In this method, I used the Word2vec value of each word multiplied by the TF-IDF value of that word and summed up, then divided by the sum of the TF-IDF values of the sentence for creating sentence embedding then applied the clustering method. I am creating it from scratch.

3 - In this method, first I calculated word embedding with bpemb (pre-trained word sub-word embedding) then I used the RNN layer to calculate the new vector of embedding by summing them up their dimensions to know the distance between sentences then applied the clustering method.

4 - In this method, I used Infersent, siamese BERT- Network, and Elmo for creating sentence embedding then applied clustering method.


Clustering - For clustering, I used the fast clustering method because i don't want to give the number of clusters while making a cluster of sentences that is why I used this method.

