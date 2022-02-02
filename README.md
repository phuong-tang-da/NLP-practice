# Representation
### Bag-of-Words: 
- a text (such as a sentence or a document) is represented as the bag (multiset) of its words, disregarding grammar and even word order
- **Drawbacks of a Bag of Words Model**
- If the new sentences contain new words, then our vocabulary size would increase and thereby, the length of the vectors would increase too.
- the vectors would also contain many 0s, thereby resulting in a sparse matrix (which is what we would like to avoid)
- We are retaining no information on the grammar of the sentences nor on the ordering of the words in the text. 
- We rely only on word frequency and throw all other relations and patterns out

### TF-IDF |term frequency-inverse document frequency
- numerical statistic that is intended to reflect how important a word is to a document in a collection 
- the columns represent single unique terms (unigrams) but the cell represents a weighting meant to represent how important a word is to a document.
### Word2Vec

# Modeling
### Sentiment analysis has also many other names — Opinion Mining, Sentiment Mining, or Subjectivity Analysis.

### Topic Models, in a nutshell, are a type of statistical language models used for uncovering hidden structure in a collection of texts. 

