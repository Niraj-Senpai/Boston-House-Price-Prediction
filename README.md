
# Boston House Price Prediction

This project employs machine learning techniques to predict housing prices in Boston using the Boston Housing dataset. It encompasses data preprocessing, exploratory data analysis (EDA), model training, and evaluation to understand the factors influencing house prices.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The primary objective of this project is to build a predictive model that estimates the price of houses in Boston based on various features. The project follows these key steps:

1. **Data Loading**: Importing the dataset into the environment.
2. **Exploratory Data Analysis (EDA)**: Understanding the data distribution and relationships between variables.
3. **Data Preprocessing**: Handling missing values, encoding categorical variables, and feature scaling.
4. **Model Training**: Implementing regression models to predict house prices.
5. **Model Evaluation**: Assessing the performance of the models using appropriate metrics.

## Dataset

The dataset used is the [Boston Housing dataset](https://archive.ics.uci.edu/ml/datasets/Housing), which contains information collected by the U.S Census Service concerning housing in the area of Boston Mass. It includes 506 instances with 13 features and a target variable (MEDV) representing the median value of owner-occupied homes in $1000's.

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Niraj-Senpai/Boston-House-Price-Prediction.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd Boston-House-Price-Prediction
   ```

3. **Create a virtual environment (optional but recommended)**:

   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

4. **Install the required dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

   *Note: If `requirements.txt` is not provided, ensure the following packages are installed:*
   - pandas
   - numpy
   - matplotlib
   - seaborn
   - scikit-learn
   - jupyter

## Usage

1. **Launch Jupyter Notebook**:

   ```bash
   jupyter notebook
   ```

2. **Open the notebook**:

   Navigate to `Boston House Price Prediction.ipynb` and open it.

3. **Run the cells**:

   Execute each cell sequentially to perform data loading, EDA, preprocessing, model training, and evaluation.

## Project Structure

```
Boston-House-Price-Prediction/
├── Boston House Price Prediction.ipynb
├── BostonHousing.csv
├── README.md
└── requirements.txt
```

- **Boston House Price Prediction.ipynb**: Jupyter Notebook containing the implementation of the project.
- **BostonHousing.csv**: Dataset file used for training and evaluation.
- **README.md**: Project documentation.
- **requirements.txt**: List of required Python packages.

## Results

The regression model developed in this project demonstrates a strong ability to predict housing prices in Boston.

- **Significant Features**: Certain features such as the number of rooms, proximity to the Charles River, and low crime rates have a notable impact on housing prices.
- **Model Performance**: The model achieves a high R-squared value, indicating a good fit to the data.

*Note: For detailed results and visualizations, refer to the Jupyter Notebook.*

## Contributing

Contributions are welcome! If you have suggestions for improvements or enhancements, feel free to fork the repository and submit a pull request.
