# Vehicle Prediction Using Machine Learning 

This project predicts vehicle types using a machine learning model trained on annotated data.

##[Open in Google Colab]
https://colab.research.google.com/drive/16NPurXBaV13H7dH_mDKtikBmo0G2d4qk
 
Objective
The goal of this project is to build a machine learning model that can predict vehicle prices using various vehicle features such as make, model, engine type, mileage, and more. This can help both buyers and sellers better estimate fair prices in the automobile market.

Dataset Description
The dataset contains detailed information on a variety of vehicles. Below are the key columns used:

name: Full name of the vehicle

description: Summary of features

make: Manufacturer (e.g., Ford, Toyota)

model: Model name

year: Manufacturing year

price: Vehicle price (target variable)
Technical specs:engine, cylinders, fuel, mileage, transmission
Design and style features:trim, body, doors, exterior_color, interior_color, drivetrain

Data Preprocessing
Missing Value Handling: Filled missing values using forward fill.

Label Encoding: Converted categorical features to numerical using Label Encoding.

Feature Selection: Selected relevant features that affect price:

engine, mileage, year, cylinders, fuel, transmission, make, model, body.

 Model Building
Chosen Algorithm: Random Forest Regressor
Why? It handles both linear and non-linear data well and reduces overfitting by combining many decision trees.

Conclusion
This project successfully demonstrated how machine learning can be applied to predict vehicle prices. After processing the data and using a Random Forest Regressor, the model achieved strong performance metrics and can generalize well to unseen data.

## Tools Used
- Python
- Google Colab
- Pandas
- scikit-learn
## Results
- Accuracy: 93%
- F1 Score: 0.89
