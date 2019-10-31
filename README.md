# Sentence-Classification-in-Keras
Predicts the mood of given list of sentence / sentences

## Dataset 
The dataset contains approx 60000 training corpus text and 40000 test corpus and each training sample is labeled with one of the classes 
'affection', 'achievement', 'bonding', 'enjoy_the_moment', 'leisure', 'nature', 'exercise'

## Goal
Goal is to predict each class for the test set containing 40000 samples

## Approach
The solution uses a pre-trained word embedding 'wiki-news-300d-1M.vec' to convert sentences to vectors. The pre-trained model can be downloaded here : https://fasttext.cc/docs/en/english-vectors.html

## Results
The trained model achieves 93% F1-score on training data and predicts specific class for each sample of test set

## Requirements

1. Python 3+
2. pandas
3. numpy
4. scikit-learn
5. keras
