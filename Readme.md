# Predective Modeling for agriculture

This project aims to assist farmers in selecting the best crop for their fields based on soil conditions. By analyzing the nitrogen, phosphorous, potassium content, and pH value of the soil, we can predict the optimal crop to maximize yield.

## Dataset

The dataset `soil_measures.csv` contains the following columns:
- `N`: Nitrogen content ratio in the soil
- `P`: Phosphorous content ratio in the soil
- `K`: Potassium content ratio in the soil
- `pH`: pH value of the soil
- `crop`: Categorical values representing various crops (target variable)

### Prerequisites

Ensure you have the following libraries installed:
- pandas
- scikit-learn

You can install them using pip:
```sh
pip install pandas scikit-learn
```

### Running the Notebook
- Open notebook.ipynb in Jupyter Notebook or any compatible environment.
- Run the cells sequentially to load the dataset, preprocess the data, train the models, and evaluate their performance.

### Model Training and Evaluation
The notebook trains a logistic regression model for each soil feature (N, P, K, pH) to predict the crop type. The performance of each model is evaluated using the F1-score.

### Results
The best predictive feature for crop selection is identified based on the model performance.

## License
This project is licensed under the terms and conditions of DataCamp.

## Acknowledgments
DataCamp for providing the dataset and project structure.