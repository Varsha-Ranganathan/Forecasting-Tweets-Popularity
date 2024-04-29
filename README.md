Final Project: NLP Analysis (Group 20)
Overview: This repository contains the work of Group 20's final project focusing on various aspects of Natural Language Processing (NLP). The project explores techniques such as TFIDF, LSTM, and NER, combined with machine learning models like XGBoost and approaches in explainable AI.

Project Description: This project proposes an approach to classify the virality of tweets with respect to the user group and provide a visual explanation on what features contribute to virality by utilizing two models – Named Entity Recognition (NER) with XGBoost and  BERT Encoder with LSTM. It also aims to experiment with GAN (Generative Adversarial Networks), A reinforced learning approach and prompt engineering– based solution to optimize the tweets from results yielded through the analysis. The models’ performances were compared with base-line models at each step.

Dataset: Our analyses are based on multiple datasets captured in .csv files:
dataset.csv: Main dataset for model training.
dataset_score.csv: Scores for evaluation.
dataset_viralscore.csv & dataset_viralscore_2.csv: Used for viral score prediction.

Files and Notebooks:
EDA.ipynb: Exploratory Data Analysis of our datasets.
ITIDF_LSTM_LIME.ipynb: Implementation of TFIDF with LSTM and LIME for model explainability.
NER and Explainable AI.ipynb: Named Entity Recognition combined with XG Boost and explainable AI methods.
generator-discriminator-final.ipynb: Exploration of Generative Adversarial Networks.
prompt-engineering final.ipynb: Techniques in prompt engineering for better model training.
sentiment_analysis_results.csv: Results of the sentiment analysis.
feature_impact.csv: Analysis of feature impacts on the models.


Team members and contributions:

• Pazin Tarasansombat: TF-IDF + FNN, BERT Encoder+ LSTM, GAN, Slides, Report, Code Cleanup
• Varsha Ranganathan: Exploratory Data Analysis, SentimentAnalysis with LSTM, TF-IDF + FNN, Slides, Report, Code Cleanup
• Adithya Vibakar: GAN, Prompt Engineering, Slides, Report, Code Cleanup
• Anirudh Krishnan Venkatanathan: TF-IDF + XGBoost, XGBoost + NER, Slides, Report, Code Cleanup

Acknowledgments
We would like to thank our instructors and peers for their guidance and feedback throughout the course of this project.
