# Stemming and Lemmatization
## Stemming
Uses fixed rules such as remove able,ing etc. to derive a base word

## Lemmatization
Use knowledge of a language (a.k.a linguistic knowledge) to derive a base word

Stemming and Lemmatization are two important techniques in natural language processing (NLP) that are used to reduce words to their base forms. This can be helpful for tasks such as text classification, information retrieval, and machine translation.

Stemming is a rule-based approach that removes affixes (prefixes and suffixes) from words. For example, the word "talking" can be stemmed to "talk" by removing the -ing suffix. However, stemming can sometimes produce incorrect results, such as stemming the word "ability" to "abil".

Lemmatization is a more sophisticated approach that uses a dictionary or morphological analysis to identify the base form of a word. For example, the word "talking" can be lemmatized to "talk" by identifying that it is the present participle form of the verb "talk". Lemmatization is generally more accurate than stemming, but it can also be more computationally expensive.

In the video, the speaker uses the NLTK library to perform stemming and lemmatization in Python. He first shows how to use the Porter stemmer to stem a few words. Then, he shows how to use the spaCy library to lemmatize a few words. Finally, he shows how to customize the spaCy lemmatizer to lemmatize the words "bro" and "bra" to "brother".

- Stemming is a rule-based approach that removes affixes from words.
- Lemmatization is a more sophisticated approach that uses a dictionary or morphological analysis to identify the base form of a word.
- Lemmatization is generally more accurate than stemming, but it can also be more computationally expensive.
- The NLTK library can be used to perform stemming in Python.
- The spaCy library can be used to perform lemmatization in Python.
- The spaCy lemmatizer can be customized to lemmatize specific words.

Code :- https://github.com/codebasics/nlp-tutorials/blob/main/6_stemming_lematization/6_stemming_lematization.ipynb