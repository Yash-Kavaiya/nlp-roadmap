# Text Representation Using Bag Of n-grams


This video is the first episode of a series on natural language processing (NLP) tutorial for beginners in Python. It introduces the concept of bag of n-grams, which is a way of representing text as a vector of word combinations. It also shows how to use scikit-learn library to implement bag of n-grams and apply it to a news category classification problem.

**Highlights**:
**The motivation for bag of n-grams**
    * Bag of words model ignores the order of words in a language
    * Bag of n-grams captures the relationship between words by using pairs, triples, or more words as tokens
    * Bag of words is a special case of bag of n-grams where n is one
**The implementation of bag of n-grams**
    * Use count vectorizer class from scikit-learn library
    * Specify the n-gram range parameter to control the size of n-grams
    * Fit the count vectorizer on a corpus of text and transform new text into vectors
**The news category classification problem**
    * Use a Kaggle dataset of news articles and their categories
    * Handle the class imbalance problem by using undersampling technique
    * Split the data into train and test sets using stratify parameter
    * Use a pipeline object to combine count vectorizer and multinomial naive bayes classifier
    * Evaluate the model performance using classification report

 how to use n-gram range and pre-processing techniques to improve the text classification model. It covers the steps of creating bi-grams and tri-grams, comparing the performance of different models, and applying a pre-process function to the text data.

**Highlights**:
**Using n-gram range**
    * Shows how to create 1-gram and bi-gram features
    * Compares the performance with bag of words model
    * Finds that bi-grams perform slightly worse than 1-grams
**Making predictions**
    * Shows how to use x test and y test data to make predictions
    * Evaluates the accuracy of the model on the test data
    * Finds that the model makes some mistakes in classification
**Using pre-processing**
    * Shows how to create a new column with pre-processed text
    * Applies the pre-process function to the text data
    * Trains the same model with pre-processed text
**Comparing the performance**
    * Compares the performance of the model with pre-processed text and raw text
    * Finds that pre-processed text improves the performance in most cases
    * Recommends to do pre-processing for text classification
**Plotting a confusion matrix**
    * Shows how to plot a confusion matrix to visualize the errors
    * Provides a code snippet for plotting the confusion matrix
    * Gives a link to the notebook and exercises in the video description

    