# Highland-code
This repository includes python and R code that reads in data from the Highland Invasive Plant Species Mapping Project, cleans data, performs visualizations, and performs machine learning techniques.

Augmented_Algorithms includes the data cleaning, testing, and optimization for different supervised learning techniques.
Compartment_Predict reads in data from the supervised dataset and the new dataset (unsurveyed polygons). Then, after training the already optimized algorithm on the entire supervised dataset, the MLP Classifier predicts overall invasion for compartments (polygons) in the new dataset.
MIVI_RFC performs a similar procedure, instead using a Random Forest Classifier, to predict the abundance of one species: Microstegium Vimineum.
