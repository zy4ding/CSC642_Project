# Oral Temperature Prediction with Infrared Thermography Using Tree-based Regression Models

The paper "Oral Temperature Prediction with Infrared Thermography Using Tree-based Regression Models" by Zhixin Mao and Ziyi Ding delves into improving the accuracy of oral temperature measurements through infrared thermography (IRT), a crucial non-invasive diagnostic tool, particularly for infectious diseases like SARS and COVID-19. 

Focusing on the limitations of traditional linear regression models, the authors apply four advanced tree-based models, including bagging, random forests, gradient-boosting trees, and Bayesian additive regression trees (BART), to handle the high collinearity and complex relationships in clinical data effectively. 

Utilizing a dataset from a University of Maryland clinical study, they compare these models to determine which best predicts oral temperature under varying ambient conditions and measuring factors like gender, skin humidity, and hair density. The study finds that tree-based methods, notably BART and boosting, significantly outperform others in capturing the nuanced interactions of the predictors with the oral temperature, indicating a promising direction for enhancing the clinical accuracy of IRT measurements.

In the repository, docs contains the presentation and final report, data contains the dataset and daya dictionary used in the project, src contains the source code corresponding to random forest, bagging, boosting, bart models.
