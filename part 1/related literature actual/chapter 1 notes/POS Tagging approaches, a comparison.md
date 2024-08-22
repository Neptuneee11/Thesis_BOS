APA:
>Kumawat, D., & Jain, V. (2015). POS tagging approaches: A comparison. _International Journal of Computer Applications_, _118_(6).

I'm trying to see if I can summarize this paper bcs it looks like it contains everything we need to know about POS tagging

## Glossary

#lexical-class-marker : a label or tag to a word in a collection. Examples could be 'N' for Noun, 'ADJ' for adjective etc. 
#HMM : Also known as **Hidden Markov Model**. It is a graph where nodes are probability distributions over labels and edges give the probability of transitioning from one node to the other. It is takes in a sequence of inputs and spits out a sequence of outputs. Said outputs are calculated using aforementioned nodes that rely on probability. [Source](https://www.sciencedirect.com/topics/medicine-and-dentistry/hidden-markov-model#:~:text=Hidden%20Markov%20models%20(HMMs)%20are%20sequence%20models.,one%20node%20to%20the%20other.)
#n-gram: In this context, predicting the next #lexical-class-marker based on the past n markers.

# POS Tagging
Parts-of-speech tagging is labelling words on in a collection. How it's tagged, the processes behind it, the different approaches, are what was discussed.

## Significance
It is one of the first things to do in text processing in order to figure out the rules of the language.

## Models used
This study used a Hidden markov model and a trigram in order to predict what tag a certain word is in a sentece

## Implementations
They tested two methods of POS-tagging: HMM's and Trigrams. The corpus comprised of Hindi text of 3000 sentences where 1000 of these belong to the topic of tourism, 1000 belong to the topic of Health, and the last 1000 belongs to the general domain.

# Results
### HMM
Tourism Sentence Accuracy: 95.27%
Health Sentence Accuracy: 96.64%
General Sentence Accuracy: 94.46%
**Average Accuracy: 95.45%**
### Trigram
Accuracy: 93.38%
Health Sentence Accuracy: 92.93%
General Sentence Accuracy: 92.65%
**Average Accuracy: 92.98%**
## Conclusion
POS-tagging is one of the simplest ways to analyze and search for information in text. Both models performed well and they believe that this can be expanded.

#### Problems, weakness, and limitations

Some manual work of writing down the rules of the language has to be done in order to set the course of the AI correctly.