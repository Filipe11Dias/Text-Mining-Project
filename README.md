# Text-Mining-Project

Text Tranlations: 

Russian into English/
German into English/
Czech into English/
Chinese into English/
English into Chinese/
English into Finish/

Abstract

An ever-evolving area of NLP is MT evaluation, with new metrics being developed every year. A brief study of previously developed metrics applied to a corpus with translations from 6 different languages is presented. Furthermore, we also present a metric, that uses LASER embeddings from translation, reference, and engineered features as input to a feed-forward neural network. Finally, we correlated the predictions made on test set with the ground truth.

Introduction

This project proposal is a development of a text metric based on the Statistical Machine Translation (WMT) competition called Metrics shared task, whose goal is to create a metric that correlates with the human quality assessment. Traditionally.
MT evaluation requires human judgement of certain quality metrics, however, this approach becomes quite expensive and biased, and so, more recently, automatic metrics have been coming into vogue to try and solve these problems. The most basic metrics are the similarity distances, such as cosine similarity, Jaccard similarity coefficient and Dice similarity coefficient, other automatic metrics include, for example, BLEU score, ROUGE or WER, ultimately, we have the powerful trained embedding layers, LASER from Facebook is the embedding layer used in this project. All these metrics will be discussed in later sections of this report.
