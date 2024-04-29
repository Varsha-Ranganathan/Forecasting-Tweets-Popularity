Forecasting Tweet Popularity: A Comparative Analysis of Modeling Techniques and Feature Extraction

Description: This project proposes an approach to classify the virality of tweets with respect to the user group and provide a visual explanation on what features contribute to virality by utilizing two models – Named Entity Recognition (NER) with XGBoost and BERT Encoder with LSTM. It also aims to experiment with GAN (Generative Adversarial Networks), A reinforced learning approach and prompt engineering– based solution to optimize the tweets from results yielded through the analysis. The models’ performances were compared with base-line models at each step.

Dataset: The analyses are based on multiple datasets captured in .csv files
dataset.csv: Main dataset for model training 
dataset_score.csv: Scores for evaluation
dataset_viralscore.csv & dataset_viralscore_2.csv: Used for viral score prediction.

Files and Notebooks: 
EDA.ipynb: Exploratory Data Analysis of our datasets. 
ITIDF_LSTM_LIME.ipynb: Implementation of TFIDF with LSTM and LIME for model explainability. 
NER and Explainable AI.ipynb: Named Entity Recognition combined with XG Boost and explainable AI methods. 
generator-discriminator-final.ipynb: Exploration of Generative Adversarial Networks. 
prompt-engineering final.ipynb: Techniques in prompt engineering for better model training. 
sentiment_analysis_results.csv: Results of the sentiment analysis. 
feature_impact.csv: Analysis of feature impacts on the models.
