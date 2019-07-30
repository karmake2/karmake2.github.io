---
title: "On Application of Learning to Rank for E-Commerce Search. "
collection: publications
Authors: 'Shubhra Kanti Karmaker Santu, Parikshit Sondhi, ChengXiang Zhai'
date: 8/1/2017
venue: 'ACM SIGIR'
paperurl: 'https://karmake2.github.io/files/Publications/2017/LETOR_ECOM.pdf'
presentationurl: 'https://karmake2.github.io/files/Publications/2017/SIGIRPresentation.pptx'
---

<a href='https://karmake2.github.io/files/Publications/2017/LETOR_ECOM.pdf'>Download paper here</a>

<div style='display: flex; justify-content: center;'><img src='https://karmake2.github.io/files/Publications/2017/Ecom.png' alt='Image not Loading' style='height:300px;' align='middle'></div><br>

E-Commerce (E-Com) search is an emerging important new application of information retrieval. Learning to Rank (LETOR) is a general effective strategy for optimizing search engines, and is thus also a key technology for E-Com search. While the use of LETOR for web search has been well studied, its use for E-Com search has not yet been well explored. In this paper, we discuss the practical challenges in applying learning to rank methods to E-Com search, including the challenges in feature representation, obtaining reliable relevance judgments, and optimally exploiting multiple user feedback signals such as click rates, add-to-cart ratios, order rates, and revenue. We study these new challenges using experiments on industry data sets and report several interesting findings that can provide guidance on how to optimally apply LETOR to E-Com search: First, popularity-based features defined solely on product items are very useful and LETOR methods were able to effectively optimize their combination with relevance-based features. Second, query attribute sparsity raises challenges for LETOR, and selecting features to reduce/avoid sparsity is beneficial. Third, while crowdsourcing is often useful for obtaining relevance judgments for Web search, it does not work as well for E-Com search due to difficulty in eliciting sufficiently fine grained relevance judgments. Finally, among the multiple feedback signals, the order rate is found to be the most robust training objective, followed by click rate, while add-to-cart ratio seems least robust, suggesting that an effective practical strategy may be to initially use click rates for training and gradually shift to using order rates as they become available.
