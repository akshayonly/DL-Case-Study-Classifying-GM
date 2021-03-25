# Classifying Genetic Mutation 

1. Packages

   1. Downloading Sent2Vec and Installing

2. Data gathering

   1. Downloading from Kaggle

3. Data Preprocessing

4. Primary data analysis

5. Data featurization

   1. Text Feature

      - Traditional NLP: tf-IDF vectors

      - Using pre-trained Sentence2Vector Deep learning model
        - Downloading BioSent2Vec
        - Loading BioSent2Vec
        - Applying BioSent2Vec on TEXT
   2. Categorical Features
      1. Response encoding
         1. Gene
         2. Variation
      2. One-hot encoding 
         1. Gene
         2. Variation

6. Secondary data analysis

   1. Visualizing high dimensional text features by t-SNE
   2. Visualizing Gene & Variation features by SVD

7. ML model building

   1. Dummy model (Baseline)
   2. Linear models
      1. SVM 
         1. RBF Kernel
         2. Linear kernel
      2. Logistic Regression (SGD)
   3. Tree base models
      1. Decision tree
      2. Random forest
      3. XGBoost

8. Conclusion
