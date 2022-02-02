# Representation
Represent words in a numeric format that is understandable by the computers
### Bag-of-Words: 
- a text (such as a sentence or a document) is represented as the bag (multiset) of its words, disregarding grammar and even word order (a dictionary of unique words from the corpus, or each word in the sentence, add 1 in place of the word in the dictionary and add zero for all the other words that don't exist in the dictionary)
- **Drawbacks of a Bag of Words Model**
- If the new sentences contain new words, then our vocabulary size would increase and thereby, the length of the vectors would increase too.
- the vectors would also contain many 0s, thereby resulting in a sparse matrix (which is what we would like to avoid)
- We are retaining no information on the grammar of the sentences nor on the ordering of the words in the text. 
- We rely only on word frequency and throw all other relations and patterns out

### TF-IDF |term frequency-inverse document frequency
- add floating numbers that contain more useful information compared to zeros and ones 
- the columns represent single unique terms (unigrams) but the cell represents a weighting meant to represent how important a word is to a document.
- Term frequency: frequency of a word in a document (Term frequence = (Number of Occurences of a word)/(Total words in the document))
- Inverse Document Frequency: how rare the word is across document. The rarer the words, the higher the score. Log((Total number of documents)/(Number of documents containing the word))
### Word2Vec

# Modeling
### Sentiment analysis has also many other names — Opinion Mining, Sentiment Mining, or Subjectivity Analysis.

### Topic Models, in a nutshell, are a type of statistical language models used for uncovering hidden structure in a collection of texts. 

