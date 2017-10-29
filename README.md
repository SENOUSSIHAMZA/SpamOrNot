# SpamOrNot
This is a spam classifier program in python which can tell whether a given email is spam or not!

## Dependencies 

1.```nltk```

2.```pandas```

3.```numpy```

3.```math```

## Usage


* Clone the repository: 
```sh
git clone https://github.com/SENOUSSIHAMZA/SpamOrNot.git
cd spam_or_not
``` 
* Then type ```python spam_or_not```

## Dataset

The dataset used for this project is UCI SMS spam collection dataset. 
Link: https://www.kaggle.com/uciml/sms-spam-collection-dataset/

## Training the model : Bag Of Words vs. TF-IDF

### Bag Of Words ###

The bag-of-words model is a way of representing text data when modeling text with machine learning algorithms.
It is simple to understand and implement and has seen great success in problems such as language modeling and document classification.

### TF-IDF ###

A problem with scoring word frequency is that highly frequent words start to dominate in the document (e.g. larger score), but may not contain as much “informational content” to the model as rarer but perhaps domain specific words.

One approach is to rescale the frequency of words by how often they appear in all documents, so that the scores for frequent words like “the” that are also frequent across all documents are penalized.

This approach to scoring is called Term Frequency – Inverse Document Frequency, or TF-IDF for short, where:

* Term Frequency: is a scoring of the frequency of the word in the current document.
* Inverse Document Frequency: is a scoring of how rare the word is across documents.
The scores are a weighting where not all words are equally as important or interesting.
