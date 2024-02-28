Dear Reviewer,

In our project, we've focused on preparing text data for sentiment analysis by normalizing and filtering words. We utilized NLTK to remove stopwords, convert words to lowercase, and retain only alphabetical characters, ensuring a clean and standardized dataset.

We generated frequency distributions for normalized words within both our training and testing datasets, and calculated the differences in these distributions between positive and negative reviews. Utilizing the `most_frequent_words` function, we identified the most common words associated with each sentiment.

To summarize, we preprocessed and analyzed our text data to extract the top 10 most frequent words indicative of positive and negative sentiments. This foundational step is crucial for building accurate sentiment analysis models.

Following this, we plan to develop a word list classifier based on these frequency distributions. This classifier will categorize reviews as positive or negative by evaluating the presence of these key words, leveraging our preprocessing work to effectively discern sentiment.

Best regards,
