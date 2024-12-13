# Background
This project implements bias and sentiment analysis techniques on large language models, with a specific focus on legal documents and terminologies related to social justice. By analyzing these texts through advanced natural language processing (NLP) methods, we aim to uncover latent biases, sentiment trends, and linguistic patterns that may impact justice and representation within legal frameworks.

Our work leverages machine learning models to interpret and assess legal language in ways that align with principles of fairness and equity. This approach helps in identifying biases that could influence judgments, policy-making, and legal discourse, paving the way for more balanced and inclusive legal narratives

# Related Datasets
- [Amazon Generalized Fairness Metrics](https://github.com/amazon-science/generalized-fairness-metrics/tree/main)
- [NYQ BBQ Datasets](https://github.com/nyu-mll/BBQ)

# Files Included:
1) Exploratory_Data_Analysis: A notebook exploring and analyzing the data contained in the Amazon Generalized Fairness Metrics Dataset.
2) Sentiment_Analysis_Full: Performing sentiment analysis on the tweets/X posts, using a Gemini prompt, followed by testing that prompt on the Amazon dataset. Also includes metrics for both parts. 
3) Basic_Model: A logistic regression model for comparison of performance purposes to the prompt used in Sentiment_Analysis_Full.
4) Change_Of_Venue: Generating a synthetic dataset and prompting Gemini to detect the "change of venue" signal, then analyzing its performance.


# Project Description

## Introduction: 
AI legal software is revolutionizing the analysis of evidence in cases involving protected social classes by enabling efficient bias detection and sentiment analysis. These tools use advanced natural language processing (NLP) and machine learning techniques to identify discriminatory language, uncover implicit or explicit biases, and gauge emotional tones within documents or communications. They have the ability to enhance objectivity and accuracy by detecting patterns of prejudice and hostile sentiment that might otherwise go unnoticed, helping legal professionals build stronger, evidence-based cases. While offering significant advantages in efficiency and scalability, AI must be ethically implemented to avoid perpetuating biases, ensuring that its findings are transparent and aligned with the context of the evidence. This integration promotes fairness and strengthens the pursuit of justice for individuals from protected groups.

## Formal Statement:
We as Relativity 1C are examining a multitude of datasets, such as the Amazon Generalized Fairness Dataset, to train and create a model that performs sentiment analysis and bias assessment of ingested sentences. Sentiment analysis is the use of natural language processing (NLP) and machine learning techniques to analyze and determine the emotional tone, attitude, or sentiment expressed in text, such as positive, negative, or neutral. It helps identify opinions, emotions, and biases in written or spoken language, and it can ultimately be used to filter through evidence for legal teams. 

## Datasets we looked at:
- [Amazon Generalized Fairness Metrics](https://github.com/amazon-science/generalized-fairness-metrics/tree/main)
- [NYQ BBQ Datasets](https://github.com/nyu-mll/BBQ)
- [Twitter Sentiment Analysis Dataset](https://www.kaggle.com/datasets/abhi8923shriv/sentiment-analysis-dataset/data)

## Our Applications:
We developed a sentiment analysis model designed to assess bias by analyzing text and providing key performance metrics, including precision, F1 score, and sentiment strength scores. The model was trained using a labeled dataset to ensure it could accurately classify text as positive, negative, or neutral while identifying subtle nuances in tone. To evaluate its effectiveness, we incorporated a myriad of score calculations and metrics, ensuring it performed reliably in detecting bias within communications or documents. Additionally, we created a change of venue model that analyzed the linguistic and contextual features of evidence to assess factors influencing venue bias. This model helped quantify the likelihood of prejudice in specific jurisdictions, providing a comprehensive approach to bias assessment and decision-making.
