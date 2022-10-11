# Sentence-clustering-from-scratch-and-pre-trained-embedding
In this project i am using the 40000+ sentences, i want to make cluster of sentences those have similar meanings. for this project first i preprocessed the data then applied different types of methods for creating sentence embedding. I also applied fast clustering because i don't know that how many cluster will be make.
 
Sentence Embedding - I used the 4 methods for sentence embedding. 
 
1 - In this method,I used the doc2vec from scratch for creating sentence embedding then i applied clustering method.

2 - In this method,I used the Word2vec value of each word is multiplied by the TF-IDF value of that word and summed up, then divided by the sum of the TF-IDF values of the sentence for creating sentence embedding then applied clustering method. I am creating it from scratch.

3 - In this method, first I calculated word embedding with bpemb (pre-trained word sub-word embedding) then I used the RNN layer to calculate the new vector of embedding by summing them up their dimensions to know distance between sentences then applied clustering method.

4 - In this method, I used Infersent, siamese BERT- Network, and Elmo for creating sentence embedding then applied clustering method.


Clustering - For clustering, i used the fast clustering method beacause i don't want to give number of cluster while making the cluster of sentences that is why i used this method.

