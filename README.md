# Crab Age Prediction - Regression

This repository contains code and resources for predicting the age of crabs using machine learning techniques. The goal is to develop accurate models that can estimate the age of crabs based on their physical attributes. The project includes data preprocessing, feature scaling, model selection, and evaluation using regression algorithms such as Random Forest, Linear Regression, and XGBoost.

## Dataset

The dataset used in this project is the "Crab Age Dataset". It contains the following features:

- `id`: Unique identifier for each crab specimen.
- `Sex`: Categorical variable indicating the sex of the crab.
- `Length`: Measurement of the crab's length.
- `Diameter`: Measurement of the crab's diameter.
- `Height`: Measurement of the crab's height.
- `Weight`: Measurement of the crab's weight.
- `Shucked Weight`: Measurement of the weight of the shucked crab.
- `Viscera Weight`: Measurement of the weight of the crab's viscera.
- `Shell Weight`: Measurement of the weight of the crab's shell.
- `Age`: Target variable representing the age of the crab.

The dataset is split into a training set and a test set.

## Dependencies

The following dependencies are required to run the code:

- numpy
- pandas
- seaborn
- matplotlib
- xgboost
- scikit-learn

You can install the dependencies using pip:

```shell
pip install numpy pandas seaborn matplotlib xgboost scikit-learn
```

## Code Structure

- `train.csv` and `test.csv`: Input data files containing the crab age dataset.
- `crab-age.ipynb`: Jupyter Notebook containing the code for data preprocessing, feature scaling, model selection, and evaluation.
- `README.md`: This README file providing an overview of the project.

## Usage

To use this repository, follow these steps:

1. Clone the repository:

```shell
git clone https://github.com/your-username/Predicting-Crab-Age-Using-Machine-Learning
```

2. Navigate to the project directory:

```shell
cd Predicting-Crab-Age-Using-Machine-Learning
```

3. Open the `crab-age.ipynb` Jupyter Notebook using Jupyter or JupyterLab.

4. Execute the cells in the notebook sequentially to preprocess the data, perform feature scaling, and evaluate the regression models.

5. Feel free to modify the code, experiment with different algorithms, or add your own improvements to enhance the accuracy of age prediction.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request. Let's collaborate to make this project better!

## License

This project is licensed under the MIT License. See the [LICENSE](https://opensource.org/license/mit/) file for more details.

## Acknowledgments

Special thanks to the creators of the "Crab Age Dataset" for providing the dataset and inspiring this project.


Author: **amyrmahdy**

Date: **22 June 2023**

