# Distance-Diagnosis
Website that implements a ML model to classify a medical diagnosis given symptoms and allows users to identify closest medical centre to treat said diagnosis. 


Using a dataset from kaggle, includes 30 different conditions, was difficult to find a large set of conditions to build a model off, but with this smaller set we can still develop a model and service which could eventually be upscaled. 

The first steps that came with this project was translating the written list of conditions to binary values indicating positive and negative symptoms, this will allow for easier training. The initial ML model considered was Bernoulli Naïve Bayees (BNB), this was due to the adjusted dataset satisfying the assumptions for MNB which were, Binary valued features, Conditional Independence, and Class Labels (Categorical Diagnosese). 
