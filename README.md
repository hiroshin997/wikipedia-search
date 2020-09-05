# Wikipedia Search
This notebook(WikipediaSearch.ipynb) is to experiment to build search index of Wikipedia and the interfaces to retrieve similar documents to requested text by a user. Here are the traits
* All words and phrases in documents are translated to word embedings using word2vec
* Building binary tree index from document vectors using k-means clustering
* Beam search to traverse the binary tree to retrieve similar documents fast
