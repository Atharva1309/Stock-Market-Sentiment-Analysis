# Stock-Market-Sentiment-Analysis
This is a dataset of news headlines of publicly held organizations. The headlines are preprocessed and converted into TF-IDF numeric vectors using NLTK.
TF-IDF is a statistical measure that evaluates how relevant a word is to a document in a collection of documents. 
TF-IDF (term frequency-inverse document frequency) was invented for document search and information retrieval. It works by increasing proportionally to the number of times a word appears in a document, but is offset by the number of documents that contain the word. 
So, words that are common in every document, such as this, what, and if, rank low even though they may appear many times, since they don’t mean much to that document in particular.
Implemented bag of words approach for vectorization and predicted the sentiment of a stock market of an organization using a RandomForest classifier with an accuracy of 82% to help customers to invest in ideal stock to gain high ROI
