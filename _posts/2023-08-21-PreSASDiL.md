---
title: "Knowledge Grounding via Taxonomy Based Prompting"
date: 2023-08-21
permalink: /posts/2023/08/PreSASDiL/
tags:
  - Research
  - Vision
---

This is an ongoing project where we develop conversational AI techniques by prompting Large Language Models (LLMs) to build a natural language interface between humans and the AutoML tools (e.g., Scikit-Learn), which, in turn, can facilitate acquiring new predictive skills via self-directed learning. To achieve this, we recently introduced a new prompting taxonomy called TeLER to design diverse prompts that can unleash the full potential of LLMs with proper knowledge grounding.


Overview of Project "Knowledge Grounding via Taxonomy Based Prompting"
======
A big challenge in democratizing AI is that no single AI model can be pretrained to be skilled in all possible tasks a user may want to perform. Therefore, being able to learn new skills in an ad hoc fashion is essential. To address this challenge, we are developing a Conversational Data Science solution that is capable of acquiring new predictive skills on the fly through intuitive, natural conversations with the user. In our ACM Computing Surveys 2022 paper, we highlighted the core technical challenges that need to be addressed: 

<ol>
<li>Accurately understand and define the goal skill(s) to acquire (as defined by a human)</li>
    
<li>Formulate a precise and relevant Machine Learning (ML) task.</li>
    
<li>Curate data sets and assign model hyper-parameters accordingly.</li>
    
<li>Train AutoML models to learn the skill.</li>

<li>Apply the skill effectively.</li>

</ol>

However, one big hurdle in materializing Conversational Data Science is to ensure a conversation that is grounded in a unique data set that the user may provide from an unseen domain on the fly. To address this challenge, we recently proposed a prompting taxonomy called TeLER to design effective prompts for Large Language Models (LLMs) in order to build a natural language interface between humans and the AutoML tools (e.g., Scikit-Learn), which, in turn, facilitates acquiring new predictive skills via self-directed learning. Our experimental results (available on Arxiv) demonstrate the effectiveness of the proposed TeLER-taxonomy-based prompting technique for knowledge grounding.

<center>
  <div style='display: flex; justify-content: center;'><img src='/images/TELER.png' alt='Image not Loading'  align='middle'></div><br>
</center>
<br>


We designed the architecture of our "Conversational Data Science" framework with four dialogue states: Data Visualization, Task Formulation, Prediction Engineering, and Result Summary and Recommendation. Each state marks a unique conversation phase, impacting the overall user-system interaction. Multiple LLM instances, serving as "micro-agents'', ensure a cohesive conversation flow, granting us granular control over the conversation's progression. In summary, we designed and developed an end-to-end system that demonstrates the viability of "Conversational Data Science" by evaluating the potency of taxonomy-based prompting of LLMs in solving such an ill-defined complex task.

<center>
  <div style='display: flex; justify-content: center;'><img src='/images/VIDS.png' alt='Image not Loading' style='height:650px;' align='middle'></div><br>
</center>
<br>


