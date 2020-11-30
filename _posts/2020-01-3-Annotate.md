---
title: 'Project Annotate: Concept Annotation from Users Perspective'
date: 2020-10-01
permalink: /posts/2020/01/Annotate/
tags:
  - Research
  - Vision
---

Information retrieval and Knowledge mining become much easier if data is categorized and annotated precisely. With the rapid growth of Big-data, it is infeasible to perform manual annotation, as it is slow and expensive. Although the area of text annotation is not in the nascent phase, it has not been well-studied from a user-centric point of view, which is the goal of this project.

Overview of Project Annotate
======
Text data is highly unstructured and can often be viewed as a complex representation of different concepts, entities, events, sentiments etc. For a wide variety of computational tasks, it is thus very important to annotate text data with the associated concepts / entities, which can put some initial structure / index on raw text data. However, It is not feasible to manually annotate a large amount of text, raising the need for automatic text annotation. 
  
In this project, we focus on concept annotation in text data from the perspective of real world users. Concept annotation is not a trivial task and its utility often highly relies on the preference of the user. Despite significant progress in natural language processing research, we still lack a general purpose concept annotation tool which can effectively serve users from a wide range of application domains. Thus, further investigation is needed from a user-centric point of view to design an automated concept annotation tool that will ensure maximum utility to its users. To achieve this goal, we created a benchmark corpus of two real world data-sets, i.e., "News Concept Data-set" and  "Medical Concept Data-set", to introduce the notion of user-oriented concept annotation and provide a way to evaluate this task. The term "user-centric" means that the desired concepts are defined as well as characterized by the users themselves. We proposed a new approach based on generative feature language models that can mine the implicit concepts more effectively through unsupervised statistical learning. The parameters are optimized automatically using an Expectation-Maximization algorithm. 


This is the high level architecture of Concept Annotation:
<div style='display: flex; justify-content: center;'><img src='https://karmake2.github.io/files/Publications/2016/ImplicitFeature.png' alt='Image not Loading' style='height:300px;' align='middle'></div><br>



Impact of Project Annotate
======
Concept Annotation can be viewed as adding topic-related metadata to a text article. The idea of concept annotation is not new and several researchers have studied this problem from different perspectives in the past. Still, concept annotation is not a trivial task and its utility often relies highly on the preference of the user. Indeed, the ultimate goal of any intelligent tool is to serve the need of the end users and thus, its design principles should primarily focus on the real-world application scenarios involving the end users. Despite significant progress in natural language processing research, we still lack a general purpose concept annotation tool which can effectively serve users from a wide range of application domains. The main reason behind this limitation is the absence of a user-centric study of the concept annotation task encompassing a more realistic scenario. Thus, further investigation is needed from a user-centric point of view to design an automated concept annotation tool that will ensure maximum utility to its users.



