---
title: "[1] An improved graph convolutional neural network for EEG emotion recognition"
collection: publications
category: manuscripts
permalink: /publication/2024-10-01-paper-title-number-1
excerpt: 'This paper is about EEG emotion recognition by an improved graph convolutional neural network.'
date: 2024-10-01
venue: ' Neural Computing and Applications'
#slidesurl: 'http://academicpages.github.io/files/slides2.pdf'
paperurl: 'https://link.springer.com/article/10.1007/s00521-024-10469-8'
citation: 'Xu, B., Zhang, X., Zhang, X. et al. An improved graph convolutional neural network for EEG emotion recognition. Neural Comput & Applic 36, 23049–23060 (2024). https://doi.org/10.1007/s00521-024-10469-8.'
---

Dynamic uncertainty of the relationship among brain regions is an important limiting factor in electroencephalography (EEG)-based emotion recognition. This uncertainty stems from individual differences and emotional volatility, which needs further in-depth study. In this paper, we propose a new emotion recognition method, which is named graph convolutional neural network with spatio-temporal modeling and long short-term memory (STLGCNN). The proposed method aims to address the instability of emotion intensity and underutilization of EEG biotopological information. The method consists of an attention module, a bi-directional long short-term memory network (BiLSTM), a graph convolutional neural network (GCNN) and a long short-term memory module (LSTM). The attention mechanism is utilized to reveal correlations between different time periods and to reduce emotional temporal volatility. The BiLSTM is employed to learn spatio-temporal features. Then, the GCNN learns the biotopological information of multi-channel EEG signals and extracts effective graph domain features. These features are then fed into the LSTM to integrate the graph-domain information and extract valid temporal information. To verify the effectiveness of the STLGCNN method, we conducted experiments on the DEAP and SEED datasets. The average accuracies on the two datasets are 93.95 and 96.78%, respectively. The results show that the STLGCNN method has better performance than existing methods.
