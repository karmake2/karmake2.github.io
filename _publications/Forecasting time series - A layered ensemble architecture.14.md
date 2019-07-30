---
title: "Forecasting time series - A layered ensemble architecture"
collection: publications
Authors: 'Md. Mustafizur Rahman, Shubhra Kanti Karmaker Santu, Md. Monirul Islam, Kazuyuki Murase'
date: 10/1/2014
venue: 'IJCNN'
paperurl: 'https://karmake2.github.io/files/Publications/2014/IJCNN_TSF.pdf'
presentationurl: ''
---

<a href='https://karmake2.github.io/files/Publications/2014/IJCNN_TSF.pdf'>Download paper here</a>

Time series forecasting (TSF) have been widely used in many application areas such as science, engineering and finance. The characteristics of phenomenon generating a series are usually unknown and information available for forecasting is only limited to the past values of the series. It is, therefore, necessary to use an appropriate number of past values, termed lag, for forecasting. This paper presents a layered ensemble architecture (LEA) for TSF problems. Our architecture is consisted of two layers, each of which uses an ensemble of neural networks. Unlike most previous studies on TSF, LEA puts emphasis on both accuracy and diversity among individual networks in an ensemble. While the ensemble of the first layer tries to find an appropriate lag of a given time series, it of the second layer makes forecasting using the obtained lag. The use of the appropriate lag signifies LEA&apos;s effort in producing accurate networks for constructing the ensemble. In order to maintain diversity among networks in the ensemble, LEA trains each network in the ensemble using a different training set. The proposed architecture uses a clustering based selection method that considers both accuracy and diversity in selecting networks to construct the ensemble. Accuracy is maintained here by selecting the best networks from each cluster. On the other hand, diversity is ensured by using the variance information in constructing clusters. LEA has been tested extensively on the time series data sets of NN3 competition. In terms of prediction accuracy, our experimental results have showed clearly that LEA is better than other ensemble and non-ensemble algorithms.

<img src='https://karmake2.github.io/files/Publications/2014/IJCNN_TSF.png' alt='Image not Loading'>
