# NLP_Project
Use NLP to determine password strength. Data and project from Udemy
- https://gale.udemy.com/course/data-science-real-world-projects-in-python-x/learn/lecture/24477790#overview
- Uses TF-IDF (term frequency - inverse document frequency)
- Term Frequency looks at how many times a "term" is used in a document. 

1. Raw Count
2. TF adjusted for length of document
3. Log scale (log(1+ raw count))
4. Boolean Frequency ( 1 if "term" occurs, 0 if does not)

- Inverse Document Frequency
- Looks at how common or not common a word is in a corpus (collection of documents. 
1. t = term, N = number of documents (d) in corpus (D)


TF-IDF is one of many ways to vectorize text. Can also use Bag of Words, Word2Vec, BERT (Bidirectional Encodr Representation

- Pros of TF-IDF
1. Simple and Easy to Use
2. Computationally cheap

- Cons of TF-IDF
1. cannot carry semantic meaning
2. ignores word order
3. can suffer memory inefficiency due to dimensionality

