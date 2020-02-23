# Satellite Collision Avoidance Challenge

Deep Learning project based on the ESA competition, [Collision Avoidance Challenge](https://kelvins.esa.int/collision-avoidance-challenge/).

This project consists in modeling potential satelite collisions in advance using ML & DL techniques. 
Main technologies: Python -> Keras, Scikit-learn, Pandas, Numpy, FeatureTools, Keras-Tuner, Seaborn, and Plotly.

My methodology included six steps:

Study on Specific Knowledge -> Complex topic that needed previous understanding to get started, the main source was the competition webpage.
Data Wrangling -> Feature description and cleansing. The data provided by the competition was really raw and needed a lot of processing to be useful.
Exploratory Data Analysis (EDA) -> Heatmaps, boxplots, scatterplots 2D-3D PCA & t-SNE plots were analyzed to find patterns in the data.
Feature Engineering & Selection -> Brute Force, and time-related feature engineering techniques were applied. Wrapping, Filtering, and Embedded feature selection techniques were also applied.
Deep Learning Modeling ->  This problem can be classified as an anomaly detection problem, so balanced CNN, balanced RNN, Autoencoders and Siamese Networks were developed. Some hyperparameter-tuning techniques were used.
Results and model comparison -> Models were compared robustness and accuracy wise. CNN & RNN gave better accuracy and scores in the competition, but Siamese Networks were more stable.

You can find the full documentation in docs. There are two reports, one for the theorical analaysis and another for the code implementation. It was co-written with my colleagues [Jaime Pérez](https://github.com/jaimeperezsanchez), and [Carlos Ándres](https://github.com/carlosaramiro).

Project proposed also for the subjects: predictive and descriptive learning (PRDL) and machine learning laboratory (MLLB).  ETSIT-UPM.
