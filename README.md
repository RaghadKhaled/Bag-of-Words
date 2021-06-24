# Bag of Words

Python implementation of (Bag of Words) which is an NLP technique commonly used in text classification. 

I will use this approach for the whole dataset in the SMS Spam Detection project, but now I built it from scratch in only 4 messages.
The goal of built it from scratch using a small set of messages to see how we can do this conversion and to understand the process before we applied into scikit-learn's library.

## Description
the Bag of Words(BoW) concept which is a term used to specify the problems that have a 'bag of words' or a collection of text data that needs to be worked with. The basic idea of BoW is to take a piece of text and count the frequency of the words in that text. It is important to note that the BoW concept treats each word individually and the order in which the words occur does not matter. 

Using a process which we will go through now, we can covert a collection of documents to a matrix, with each document being a row and each word(token) being the column, and the corresponding (row,column) values being the frequency of occurrance of each word or token in that document.




