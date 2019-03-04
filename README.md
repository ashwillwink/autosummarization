# Autosummarization
Python program that summarizes news articles from the Washington Post.

1. Find the most common words in the article (after eliminating stopwords)
2. Find the sentence in which the most common words occur most often

Algorithm:

1. Download the article from the URL
2. Get of everything other than the text string (use Beautiful Soup)
3. Using NLTK:
      - Split the text string into words (tokenization)
      - Elimate stop words
      - Find the frequency of each word
      - The higher the frequency of a word and the more important it is
      - For each sentence, find a score of how many important the words in the sentence are
      - Rank the sentences by that score
