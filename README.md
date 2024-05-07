# Water-Quality-Assessment-Using-Ensemble-Technique
This repository contains a machine learning project that classifies water samples into various categories such as Excellent, Good, Average, Bad, and Poor based on the Water Quality Index (WQI) calculated from various chemical components present in the water.

Dataset
The dataset used in this project consists of real-time samples of water collected from various sources by the water board.

Methodology
1.Data Preprocessing: The real-time dataset undergoes preprocessing steps including handling missing values and outliers to prepare it for model training.
2.Model Training: Several machine learning models such as Decision Trees, Random Forests, ANN are trained on the preprocessed dataset.
3.Soft Voting Ensemble: The predictions from individual models are combined using the Soft Voting Ensemble Technique, which aggregates the results to make the final classification decision.
