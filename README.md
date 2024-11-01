# Authorship and Topic Analysis in Italian Central Bank Communication

### Abstract

<p align="justify"> In this thesis, we apply machine learning and natural language processing (NLP)
 techniques to classify and analyze speeches delivered by the Governors of the Bank
 of Italy from 1990 to 2023. The study is structured around three main experiments.
 First, we classify the Governors based on the full text of their speeches, employing a
 combination of document embedding techniques such as TF-IDF and Doc2Vec, along
 with classification methods like Support Vector Machines (SVM), logistic regression,
 and fine-tuned Transformer-based models. The highest balanced accuracy of 91.01%
 is achieved by separately classifying English and Italian speeches, outperforming
 the models trained on the combined corpus. Second, we identify and analyze the
 underlying topics in the speeches using BERTopic, a state-of-the-art topic modeling
 technique. By running the algorithm on English and Italian documents separately,
 we detect a wide range of topics, including monetary policy, sustainable finance,
 cybersecurity, and the Covid-19 pandemic. We further concentrate on the evolution
 of the themes in the Governors’ final consideration speeches by leveraging BERTopic’s
 Dynamic Topic Modeling (DTM) functionality. Finally, we classify the Governors
 based on their distinctive writing styles by masking varying portions of content
related words identified through BERTopic. The highest balanced accuracy of 93.86%
 is again achieved by classifying English and Italian speeches separately, representing
 a 3% improvement over unmasked models. We find that masking content reduces
 the classifier’s reliance on specific topics and encourages the models to focus on
 stylistic features, improving classification performance. </p>

 
 **Keywords**: Bank of Italy, BERTopic, classification, central bank communication,
 machine learning, natural language processing, topic analysis, writing style.

