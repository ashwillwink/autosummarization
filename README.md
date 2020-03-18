# Autosummarization
Python program to summarize news articles from the Washington Post.

1. Find the most common words in the article (after eliminating stopwords)
2. Find the sentence in which the most common words occur most often

Algorithm:

1. Download the article using the URL
2. Remove everything but the text string (use Beautiful Soup)
3. Using NLTK:
  - Split the text string into words (tokenization)
  - Elimate stop words
  - Find the frequency of each word (the higher the frequency of a word and the more important it is)
  - For each sentence, find a score of how many important the words are present
  - Rank the sentences by that score
