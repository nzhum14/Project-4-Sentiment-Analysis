# Project-4-Sentiment-Analysis
"Deep Convolutional Neural Networks for Sentiment Analysis of Short Texts"

Reproduced by Kassymkhan Tengel and Nagima Chalkarova


This work is aimed to reproduce the paper of Santos and Gatti called “Deep Convolutional Neural Networks for Sentiment Analysis of Short Texts”. In their work, the aim is to do sentiment classification of short texts like Twitter messages which is challenging task. Because it usually contains limited contextual information. They used a deep convolutional network. The proposed network is called Character to Sentence Convolutional Neural Network (CharSCNN).The strenght of this network is that it analyzes the data in character level, in other words more deeper than others. It uses two convolutional layers. .One is aimed to extract related features from words and another is used to extract related features from sentences. The next model is called SCNN, which stands for Sentence Convolutional Neural Networks. It is in some way similar to previous model, but the difference is that it dpes not analyze the data in character level, just in sentence level. It is assumed that the first one is more accurate than latter.

#DATA

Two datasets were used in this paper. They are Twitter posts, which are from Stanford Twitter Sentiment (STS) corpus and movie reviews, which are proposed by Stanford Sentiment Treebank (SSTb). STS corpus has 1.6 million Twitter messages with class labels positive or negative. In the experiment we took randomly 80,000 tweets for training set and 20% of training set (16,000) was taken for validation set. Test set which was manually picked consists of 498 tweets. SSTb corpus contains fine grained (5 classes) sentiment labels for 215,154 phrases in the parse trees of 11,855 sentences. Training set contains 8544 sentences, validation set contains 1101 sentences and test set has 2210 sentences.
