---
title: 'Decision Advantage with AI in Urgent Scenarios'
date: 2025-10-12
permalink: /posts/2025/10/DecisionAdvantage/
tags:
  - Research
  - Vision
---

Urgent Decision-Making refers to the process of swiftly selecting an appropriate course of action under conditions of intense time pressure, high stakes, and often incomplete, fragmented, or unreliable information. These scenarios demand not only speed but also precision. Effective decision-making in such contexts hinges on the rapid synthesis of diverse and sometimes conflicting data sources into reliable, holistic summaries that support timely and informed responses. Technically, this task presents multiple challenges: information may arrive in real time from heterogeneous sources (e.g., news reports, social media, radio dispatches), its credibility may be uncertain, and the operational environment may evolve faster than systems can adapt. While recent advances in AI have shown remarkable capabilities in general-purpose summarization, current methods fall short in urgent contexts, where the integrity of available information is often under question, and latency, even by a few minutes, can result in irreversible consequences.

To address these limitations, our group is currently focusing on the following two core research problems.


Project 1: Rapid Summarization in Urgent Scenarios
======
Imagine Florida’s Gulf Coast bracing for the impact of a powerful Category 5 hurricane rapidly approaching the shore. At Clearwater Bay’s Emergency Operations Center, Sheriff Maria Alvarez is mobilizing her team for an urgent response. As preparations unfold, a sequence of escalating events occurs as follows:

<center>
  <div style='display: flex; justify-content: center;'><img src='/images/Rapid.png' alt='Image not Loading' style='height:450px;' align='middle'></div><br>
</center>
<br>

- **[6:30 PM]** As she listens to the news on TV, the anchor reports, “The hurricane has intensified to 165
mph and is expected to make landfall two hours ahead of schedule”.
- **[6:35 PM]** Social media is exploded with frantic posts: “Flooding at Clearwater Marina!”; “Trapped in
Cedar Pines Retirement Home!”; “We’re stuck-no buses moving!”.
- **[6:46 PM]** Maria’s deputy Jim radios in: “A school bus carrying 26 children is stranded near marina”.
- **[6:47 PM]** Sheriff Maria Alvarez looks through the window, and all she sees is a dark blue sky.
- **[6:48 PM]** A 911 call from an unidentified source reports that several seniors at the retirement home are
refusing to evacuate as floodwaters rapidly climb.
- **[6:52 PM]** The National Weather Service issues a dire alert: “Evacuate immediately. Bridge expected to
close within 40 minutes”.

Now, imagine Maria, who is tasked with swiftly selecting an appropriate course of action under conditions of time pressure, high stakes, and incomplete or fragmented information, including unverified information. Things can quickly become intractable as a continuous influx of new information is received and the situation changes rapidly. This type of high-stakes, time-sensitive scenario exemplifies what is known as Urgent Decision-Making—the process of rapidly identifying and executing the most appropriate course of action despite limited, unreliable, or evolving information. Such scenarios are common during crises like natural disasters, public health emergencies, and security threats, and have historically resulted in significant loss of life and economic damage in the USA. In fact, multiple U.S. federal agencies estimate that inadequate urgent responses continue to cost the nation between <b>$500 billion</b> and <b>$1.5 trillion</b> annually, with each minute of faster action having the potential to save over <b>149,000 lives</b> and prevent billions in losses. This project is focused on addressing these challenges by establishing the first comprehensive computational framework for <b>_Rapid Synthesis of Reliable Holistic Summaries_</b>.

<br>
<br>

Project 2: Holistic Situational Awareness with Multi-Perspective Narrative Understanding (Funded by AFOSR)
======
Multi-Perspective Narratives (MPNs) are ubiquitous and very useful for verifying information from different alternative narratives, and thus, MPNs facilitate more informed decisions by providing a concise overall picture of the current situation. Despite great progress in the area of natural language processing (NLP), computers still struggle to analyze multi-perspective narratives accurately; addressing this limitation is the focus of this project.

In this ongoing project, we are developing a novel human-AI collaborative framework called CAMPeN ("Collaborative Analytics of Multi-Perspective Narratives''), where the AI, given multiple alternative narratives as input, first extracts a set of candidate clauses w.r.t. the Overlap-Unique-Conflict criteria, separately, in a zero-shot fashion. Next, the human actively verifies clauses that were labeled with low confidence by the AI. Finally, the machine braids the high-confidence/verified clauses to construct the ultimate Overlap-Unique-Conflict style summary, which will be presented to the user. The major benefits of the proposed framework are two-fold: 1) it enables domain experts in fields other than machine learning/NLP (e.g., a military general) to quickly dig out/verify interesting hypotheses from multiple alternative narratives/descriptions without worrying about the underlying computational techniques and thus, democratizes AI, and 2) it can quickly verify facts and claims about real-world events by analyzing alternative narratives and braid them into a single narrative with a higher degree of Information Assurance.

<center>
  <div style='display: flex; justify-content: center;'><img src='/images/CAMPeN.png' alt='Image not Loading' style='height:450px;' align='middle'></div><br>
</center>
<br>

This project adopts both zero-shot and reinforcement learning approaches for extracting overlapping, unique, and conflicting information from alternative narratives that can be trained in a self-supervised fashion without requiring a large collection of training data; therefore, the proposed framework needs minimal human supervision in comparison to the existing Multi-Document Summarization techniques. Additionally, the project borrows intuitions and insights from classical set theory and applies the properties of set operators to develop novel reward/loss functions to enable effective training of reinforcement learning-based extraction networks.
