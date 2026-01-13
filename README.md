# Distance-Diagnosis
Website that implements a ML model to classify a medical diagnosis given symptoms and allows users to identify closest medical centre to treat said diagnosis. 


Using a dataset from kaggle, includes 30 different conditions, was difficult to find a large set of conditions to build a model off, but with this smaller set we can still develop a model and service which could eventually be upscaled. 

The first steps that came with this project was translating the written list of conditions to binary values indicating positive and negative symptoms, this will allow for easier training. Additionally, Gender was also assigned binary values, 0 for male, and 1 for female, with this we can now begin producing a model. In our case a Multinomial Loistic Regression (MLR) model was considered as it handles binary and numeric features, and performs well on sparse features.
