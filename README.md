# Master's Thesis Project - Investigating bias in different language editions of Wikipedia

This repository contains the code and associated files for my Master's Thesis in the field of Natural Language Processing, submitted to the University of Melbourne. The research conducted for this thesis involved a detailed exploration of Wikipedia in different language editions, and the results have been documented thoroughly in the accompanying report.

## Abstract

Digital information can be inherently biased due to the varying perspectives, cultural
contexts, and editorial practices of its contributors. Biases can emerge even on
popular platforms like Wikipedia, which is supposed to be neutral. This thesis
investigates biases in different language editions of Wikipedia, focusing on English,
Hindi, Afrikaans, and Chinese.
Sentences from these language editions were aligned through content alignment
techniques, followed by the application of a pre-trained sentiment analysis model
to detect divergences in sentiments. Various metrics such as Jensen-Shannon divergence
were used to quantify these divergences. Further to this, Named Entity
Recognition (NER) was used to identify common entities within the texts to aid
with the stance detection process. Stance detection was then conducted through
the use of Large Language Models (LLMs). These LLMs were used to assess the
stance of authors towards the common entities. These divergences of stances were
quantified by the Stance Divergent Score (SDS) across texts. A round-trip translation
baseline was prepared to ensure that divergences were due to the text rather
than translation artifacts. Additionally, human validation was applied in content
alignment and stance detection to assess the efficacy of our approach.
The findings reveal the presence of biases in Wikipedia articles on controversial
issues and war-related topics across different language editions. It is worth
noting that while sentiment analysis and stance detection are closely related, the
observed sentiment divergence does not necessarily correlate with stance divergence.
For instance, the English-Hindi language pair exhibited lower sentiment divergence
but higher stance divergence. Furthermore, language pairs involving Chinese frequently
demonstrated higher divergences in both sentiment and stance. This research
demonstrates the nuanced nature of biases in multilingual Wikipedia articles.

## Project Structure


- `Thesis_1.pdf`: Full thesis report as a PDF.
