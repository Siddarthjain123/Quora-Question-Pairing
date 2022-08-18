# Quora-Question-Pairing
Objective is to predict which of the provided pairs of questions contain two questions with the same meaning. The ground truth is the set of labels that have been supplied by human experts.
## Overview 
• Pre-Processed text with tokenization, stemming, stopword removal and visualised data using TSNE.

• Performed feature extraction and extracted 20+ features with tf-idf weighted word2vec and fuzz ratio.

• Implemented models with Randomised Search CV and obtained best f1 score as 0.86 and log-loss error of 0.36
