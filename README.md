# Word-Embeddings----NaturalLanguageProcessing

Word Embeddings are numeric representations of words in a lower-dimensional space, capturing semantic and syntactic information.
Need for Word Embedding?
* To reduce dimensionality
* To use a word to predict the words around it.
* Inter-word semantics must be captured.

Approaches for Text Representation
1. Traditional Approach
   a. One-hot encoding: In this encoding scheme, each word in the vocabulary is represented as a unique vector, where the dimensionality of the vector is equal to the size of the vocabulary.
   b. Bag of words (BOW): A text representation technique that represents a document as an unordered set of words and their respective frequencies.
   c. Term frequency-inverse document frequency (TF-IDF): Term Frequency measures how often a term (word) appears in a document. Inverse Document Frequency measures the importance of a term across a collection of documents. The higher the TF-IDF score for a term in a         document, the more important that term is to that document within the context of the entire corpus.
2. Neural Approach
   a. Word2Vec https://www.geeksforgeeks.org/python-word-embedding-using-word2vec/
   b. Continuous Bag of Words(CBOW) https://www.geeksforgeeks.org/continuous-bag-of-words-cbow-in-nlp/
   c. Skip-Gram https://www.geeksforgeeks.org/implement-your-own-word2vecskip-gram-model-in-python/
3. Pretrained Word-Embedding
   a. GloVe https://www.geeksforgeeks.org/pre-trained-word-embedding-using-glove-in-nlp-models/
   b. Fasttext https://www.geeksforgeeks.org/fasttext-working-and-implementation/
   c. BERT (Bidirectional Encoder Representations from Transformers) https://www.geeksforgeeks.org/how-to-generate-word-embedding-using-bert/
