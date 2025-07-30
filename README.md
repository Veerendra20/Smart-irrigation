# Smart-irrigation
Project Overview
           A machine learning-based smart irrigation system designed to optimize water usage in agriculture. It uses environmental data (like temperature, humidity,     and soil moisture) to predict appropriate irrigation actions — improving crop yield and promoting sustainable farming.

 Objectives:-
          Automate irrigation decisions using AI.
          Conserve water and improve efficiency.
          Support farmers with intelligent, real-time recommendations.

 Problem Statement:-
         Traditional irrigation methods are inefficient, leading to water wastage and reduced crop productivity due to the lack of real-time, data-driven decisions.

 Solution:-
        Train a Random Forest Multi-Label Classifier on environmental data to predict irrigation needs (on/off, quantity, timing), then save and deploy the model     for real-time usage.

Technologies Used:-
        Python, Pandas, NumPy
        Scikit-learn (RandomForest, MultiOutputClassifier)
        Matplotlib, Seaborn
        Joblib (Model Saving)

 Dataset:-
       Source: irrigation_machine.csv
       Features: Temperature, humidity, soil moisture, pH, etc.
       Labels: Irrigation decisions (multi-output)

  Methodology:-
      Data Cleaning and Preprocessing
      Feature Scaling with MinMaxScaler
      Model Training using Random Forest
      Multi-Output Prediction
      Model Evaluation
      Model Saving using joblib

 Results:-
     Model tested with classification reports.
     Achieved high accuracy on multiple irrigation-related outputs.






 
