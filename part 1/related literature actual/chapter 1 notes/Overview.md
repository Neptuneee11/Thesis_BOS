"POS Tagging can be used to search for subject word classes from a series of sentences in news articles to find out which subject has the most significant role in influencing society"

From: 
[[Analysis of Telkom University News Subjects on Popular Indonesian News Portals Using a Combination of Hidden Markov Model (HMM) and Rule Based Methods.pdf]]

We're going with political framework.
Given that we're working with how different news reports are from one admin to another, we're gonna need a POS-tagger in order to make some sort of a mask to the words used in a report.  For example, the word 'COVID-19' wouldn't make sense to a machine trained with 2010 - 2016 data. But, it can still consider it as a health report if tagged correctly.

This [[2021.findings-acl.401.pdf|paper]] just talk about training a model to recognize biases. It cites that
> ...bias is often expressed through informational choices ([[1909.02670.pdf|Fan et al]]., 2019)

Media Bias sounds really good on paper but the papers I'm finding are made out of news reports for a polarized USA.  It's easy to put the criteria into a line where there's a left and right. Informational bias is a good word but we haven't narrowed down what political framework we're working with

# Interdisciplinary
From 
> [1]Felix Hamborg, Karsten Donnay, and Bela Gipp. 2019. Automated identification of media bias in news articles: an interdisciplinary literature review. International Journal on Digital Libraries 20, 4 (2019), 391–415.

Different types of bias:


Framing is also another word for perspective.

"Journalists use framing when presenting a topic in order to promote a particular interpretation[55]"

Spin bias - overall bias because there's so many ways bias can a news article due to the processes behind its making.

Soc Sci approaches

For event selection, there's a way to measure bias using two datasets. One contains the daw data of the event and the other one is the articles using the aforementioned first dataset.

affinity propagation
news aggregation

information reuse across articles

committed and omitted information

do news articles parrot a politicians phrase more often that other politicians'? Why?
This part of news article analysis hasn't been fully automated. We could look into plagiarism detection software for this.
Centering resonance analysis. Make a node of words and see how many Noun Phrases they're connected to in order to know how influential this term is. Tagging can be automated but annotating is still manual.

labeling and word choice
CRA works here
there's also sentiment analysis but this requires a lot of context. Sentiment analysis is crap when it comes to news articles

Placement and size allocation

Kind of like how youtubers milk an event til its irrelevant
news may be well balanced and objective but they're allocating a lot of space and time for people to read the article

picture selection and explanation is not relevant

I wish it were but that requires image recognition.

Spin: the vagueness of media bias

spin refers to the overall perception of the article. 

methods that require user opinion would make the machine scrape social media filth

Manual annotation is still the way

kulang pa ng dataset

There are 3 findings:
1. There are few approaches in the field of cs when it comes to media bias analysis
2. Social Science people love using their manual ways of analysis. 
3. There's a lot of potential for both disciplines coming together

#### effect of media shutdown

## Revision 1
New note, focus kayo sa cs contributions. Probably a combination of new acgorithms

I want to go back to sentiment analysis due to that one paper talking about words that would try to figure out words that affect the sentiment score the most. This requires BERT and POS-Tagging.
Students almost always go for bert dun sa mga research paper nila. The model they made is called "Polarity POS BERT"
##### Agendas to advance Political Viewpoints identification
Political framing detection was told here. It mostly done using traditional techniques of Topic modelling, word2vec, and n-grams.
##### What is a frame in Journalism?
Framing is how a reporter selects which pieces of data are to be presented in a story. It is usually implicit. Its subtlety can eb used to manipulate the reader's opinion.
Framing is called "second-order agenda setting" and it difficult to detect.
##### Low resource language methods
