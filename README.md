# Daily Bike Share Prediction

This project is aimed at predicting daily bike share rentals using machine learning techniques. It utilizes a dataset containing various features such as temperature, humidity, and weather conditions to predict the number of bike rentals for a given day.

## Dataset
The dataset used in this project is sourced from MicrosoftDocs and contains information about daily bike share rentals. It includes features such as temperature, humidity, season, and more.

## Dependencies
- pandas
- matplotlib
- numpy
- scikit-learn

## Usage
1. Clone the repository or download the project files.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the Jupyter notebook `bike_share_prediction.ipynb` to explore the dataset, visualize data distributions, train the machine learning model, and evaluate its performance.

## Code Overview
- **Data Loading and Preprocessing:** The dataset is loaded using pandas, and preprocessing steps include converting date strings to datetime objects and extracting day features.
- **Exploratory Data Analysis (EDA):** Visualizations are created to understand the distribution of rentals, explore correlations between features and rentals, and visualize categorical feature counts.
- **Model Training:** A linear regression model is trained using scikit-learn on the features extracted from the dataset.
- **Model Evaluation:** The trained model is evaluated using mean squared error (MSE), root mean squared error (RMSE), and R-squared (R2) metrics.

## Results
The trained linear regression model achieves an R2 score of approximately 0.60, indicating moderate predictive performance for the bike rental predictions.

## Contact:
For any inquiries or feedback regarding this project, please feel free to contact Dominic Makana Ocharo at ocharodominic01@gmail.com or via phone at +254746073062.
