# Pilot supervided model for predicting FDA molecule approval
Testing multiple supervised model types and fine tuning hiper parameters to find the most accurate model for predicting the approval or rejection of a molecule based on it's ADMET properties.

I have implemented 6 supervised learning algorithms, KNN, DWNN, Decision Tree, Random Forest, Logistic Regression and SVM over a dataset of 22527 molecules of pharmaceutical interest, approved, in analysis or rejected by the FDA (Food and Drug Administration). The proprietary dataset was obtained as a part of my course conclusion project in partnership with the Federal University of Bahia's AI lab, LabIA, and was enriched with ADMET properties calculated using the model vNN-ADMET. Then, it was pre processed performing multiple analysis (duplicate analysis, correlation matrix analysis and graph generation to understand noise and data balacing), row and column cleaning, binarization and normalization. 

The model fine-tuning resulted in having the Random Forest as the model with the best accuracy, 0.68, and the SVM as the model with the lowest accuracy, 0.59. Over the Random Forest the confusion matrix was calculated, showing great balancing of precision among the classes. 

This pilot project was the first step in my course's conclusion project. Now we are woring with a bigger dataset exploring different pre processing strategies, models and approches to fine tuning.
