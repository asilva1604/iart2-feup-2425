

# Bank Customer Churn Prediction

## Project Overview
This project predicts customer churn in the banking sector using machine learning models. By identifying customers at risk of leaving, banks can implement targeted retention strategies to improve customer lifetime value.

## Dataset
The analysis uses data from the [Kaggle Playground Series - Season 4, Episode 1 (2024)](https://www.kaggle.com/competitions/playground-series-s4e1/data), containing customer attributes such as:
- Demographics (age, gender, location)
- Account details (balance, credit score)
- Relationship information (tenure, number of products)
- Activity metrics (active status, credit card ownership)

## Requirements
- Python 3.11
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - jupyter

## Installation & Setup
1. Clone this repository:
   ```
   git clone https://github.com/asilva1604/iart2-feup-2425
   cd bank-churn-analysis
   ```

2. Install required packages:
   ```
   pip install -r requirements.txt
   ```

3. Download the dataset from Kaggle and place it in the `data` folder.

## Running the Analysis
1. Launch Jupyter Notebook:
   ```
   jupyter notebook
   ```

2. Open `bank_churn_analysis.ipynb` and run all cells sequentially.

## Project Structure
- `bank_churn_analysis.ipynb`: Main notebook with complete analysis
- `data/`: Folder containing the dataset
- `README.md`: Project documentation
- `presentation.pdf`: Summary presentation (10 slides)

## Analysis Pipeline
1. **Data Exploration**: Understanding distributions and relationships
2. **Outlier Analysis**: Detecting and handling outliers in numerical features
3. **Feature Engineering**: Creating new features and transforming existing ones
4. **Preprocessing**: Scaling, encoding, and preparing data for modeling
5. **Model Training**: Implementing multiple classification algorithms
6. **Evaluation**: Comparing model performance using multiple metrics
7. **Conclusions**: Actionable insights for business implementation

## Models Implemented
- Decision Tree
- Random Forest
- Neural Network (MLP)
- K-Nearest Neighbors (KNN)
- Gradient Boosting



## Contributors
* Alexandre Silva => up202206633
* Bruno Fortes => up202209730
* Beatriz Remondes => up202204353
