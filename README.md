# AI-Mushroom-project
This mini project is part of the artificial intelligence subject of King Mongkut's University of Technology North Bangkok's third year.

Comparative Analysis of K-Nearest Neighbors (KNN) and Random Forest for Mushroom Classification based on Appearance and Properties



                                                Abstract
This research project delves into the study of mushroom appearance and properties through the 
utilization of two distinct machine learning techniques: K-Nearest Neighbors (KNN) and Random Forest. 
By leveraging a comprehensive dataset, we aim to ascertain the efficacy of these methods in accurately 
classifying mushrooms based on their attributes.
Introduction

1.Background
Mushrooms, a diverse and nutritionally rich food, recently gained the attention recently, and so do I; 
machine learning techniques offer a powerful tool to streamline this process by data classification 
methods.

2.Objective
This study aims to employ KNN and Random Forest algorithms to classify based on appearance and 
properties
Data Preparation
Dataset Description
The dataset used in this study comprise comprehensive information such as color, odor, habitat, etc.

                                              Methodology

1. K-Nearest Neighbors (KNN)
K-Nearest Neighbors is a non-parametric algorithm widely used for classification tasks. It classifies a data 
point based on the class of its k nearest neighbors in the feature space. The KNN method was trained on 
preprocessing with varying of k: the optimal value of k was determined through cross-validation
1.1 Model Training
The KNN model was trained on the preprocessed dataset with varying values of k.
1.2 Results
The KNN model demonstrated remarkable accuracy, achieving an impressive 99.82%.

2. Random Forest
Random Forest is an ensemble learning method that builds multiple decision trees and merges their 
outputs to improve classification accuracy.
2.1 Model Training
Similar to KNN model – but utilizing an ensemble of decision trees with default hyperparameters.
2.2 Results
Surprisingly, the Random Forest model exhibited a perfect accuracy of 100%. While this may indicate a 
powerful predictive capacity, it raises concerns of potential overfitting, which necessitates further 
investigation.

                                               Conclusion
In our exploration, we delved into the effectiveness of two powerful tools, K-Nearest Neighbors 
and Random Forest, to discern mushrooms based on their distinct features. The KNN method showed 
remarkable promise, boasting an accuracy of 99.82%. This highlights its proficiency in accurately 
categorizing mushrooms. On the other hand, the Random Forest model astoundingly achieved a perfect 
score of 100%. While this might seem like a triumph, it also nudges us to question whether it's too good 
to be true. This remarkable accuracy raises a flag of caution, suggesting that the model might be overly 
specialized to our dataset. This potential overfitting calls for deeper scrutiny and fine-tuning to ensure it 
truly performs as well in the real world.
