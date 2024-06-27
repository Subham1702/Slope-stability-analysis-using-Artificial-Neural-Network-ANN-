# Slope-stability-analysis-using-Artificial-Neural-Network-ANN-
## Project Overview:
•	The core objective of the project was to train an Artificial Neural Network using a comprehensive dataset of slope-related parameters and historical slope failure cases.
•	In the proposed model, several important parameters including, height of the slope (H), cohesion (C), angle of internal friction (φ), angle of the slope (β) and unit weight of soil (γ) were used as input parameters whereas the FOS was used as the target value.
## ANN Dataset:
•	The ANN dataset includes parameters such as Density, Cohesion, Angle of internal friction, Height of the slope, Slope angle, and Factor of Safety (FOS).
•	The dataset was used to analyze various slopes and develop the prediction model for slope stability.
## Methodology and Analysis:
•	Imported the dataset with the help of Pandas (pd.read()) module.
•	From linear model of the scikit-learn library, imported the LinearRegression module.
•	The data was split into training set (80%) and testing set (20%).
•	Factor of Safety (FOS) was the dependent variable in our analysis.
## ANN structure:
The ANN structure consisted of an input layer, one hidden layer, and an output layer, optimized through a back-propagation learning algorithm. The predictive performance was evaluated using performance indices such as R², demonstrating the model's effectiveness and accuracy.
## Size of Input layer:
The input layer of the Artificial Neural Network (ANN) used in the project was designed to accommodate several key slope stability parameters. Specifically, the input layer contained five neurons, each corresponding to one of the following input parameters:
Height of the slope (H)
Cohesion (C)
Angle of internal friction (Φ)
Angle of the slope (α)
Unit weight of soil (γ)
These parameters were used to predict the Factor of Safety (FOS) in the network's output neuron.
## Output:
Predicted Factor of Safety (FOS) value = 4.125 (88% accuracy rate)









