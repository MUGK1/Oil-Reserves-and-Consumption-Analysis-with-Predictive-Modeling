# Oil Consumption and Reserves Analysis Project

## Overview
This project aims to analyze trends in oil consumption and reserves across various countries using data from 1965 to 2023. The main objective is to predict future oil consumption patterns, providing insights that could guide countries in their transition to sustainable energy. We developed multiple machine learning models to understand oil consumption patterns and assess the sustainability impact of these trends.

## Project Scope
- **Data Sources**: World's Largest Oil Reserves & Consumption Dataset from Kaggle (1995-2022 for Oil Reserves and 1965-2023 for Oil Consumption).
- **Models Used**: Polynomial Regression, Ridge Regression, and Random Forest Regressor.
- **Analysis**: Conducted Exploratory Data Analysis (EDA), model development, and evaluation.
- **Sustainability Focus**: Aligns with Sustainable Development Goals (SDGs) by predicting when countries should transition to renewable energy sources.

## Dataset
- **Source**: [Kaggle](https://www.kaggle.com/datasets/muhammadroshaanriaz/oil-reserves-and-consumption-from-1995-to-2022).
- **Key Features**:
  - **Country**: Names of countries or regions.
  - **Year**: Annual data points from 1965 to 2023.
  - **Oil Reserves**: Quantities of proven oil reserves (in billion barrels).
  - **Oil Consumption**: Annual oil consumption (in TWh).

## Getting Started
### Prerequisites
Ensure you have the following installed:
- **Python 3.8+**
- **Pip** for installing dependencies

### Installation
1. Clone this repository:
   ```
   git clone https://github.com/MUGK1/Oil-Reserves-and-Consumption-Analysis-with-Predictive-Modeling.git
   ```
2. Navigate to the project directory:
   ```
   cd oil-consumption-analysis-code
   ```
3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

> **Note**: If you are using Google Colab, simply upload the provided `.ipynb` notebook and datasets to your Colab environment and run the cells sequentially.

### Usage
To run the analysis and predictions locally, use the following commands:
1. **Run the main script**
  
2. **Jupyter Notebook**: If you prefer using a Jupyter Notebook, open the provided `.ipynb` file and execute the cells sequentially.

### Example
You can predict future oil consumption for a specific country:
1. Enter the **country name**.
2. Enter the **start year** and **end year** for prediction.

The script will output:
- Predicted oil consumption over the specified years.
- Visualizations comparing the actual and predicted consumption.


## Results
The key results for Finland include:
- **Model Performance**:
  - **Random Forest Regressor**: Overfitting with an R² score of 0.89.
  - **Polynomial Regression**: Better generalization for the data with moderate performance.
  - **Ridge Regression**: Yields stable predictions but does not capture non-linear trends effectively.
- **Insights**: Predicted decline in oil consumption for Finland, aligning with global sustainability goals.

## Limitations
- Lack of economic and demographic features in the dataset limits the model's ability to account for external factors.
- Limited data availability for newer years reduces the prediction's reliability for long-term trends.

## Future Improvements
- **Feature Expansion**: Include economic and renewable energy adoption indicators.
- **Model Optimization**: Experiment with additional machine learning models like LSTM or Gradient Boosting.

## Acknowledgments
- **Dataset**: Muhammad Roshaan Riaz on Kaggle.
- **Libraries**: Pandas, Numpy, Scikit-Learn, Matplotlib, Seaborn.

## Contact
- **Author**: Khaled Almansour & Naif Aba Alrous
- **Email**: 221110083@psu.edu.sa, 222110926@psu.edu.sa
