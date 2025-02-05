# GDP Growth Prediction for Germany

📊 Project Overview

This project focuses on predicting Germany's GDP growth for the year 2025 using machine learning techniques. The process involves data collection, preprocessing, model training, and final prediction.

🔍 Data Collection and Preprocessing

The data was collected from various reliable financial and economic sources (Mostly from the World Bank API), ensuring comprehensive coverage of Germany's economic indicators. After collection, the data was manually reviewed to correct any inconsistencies, and missing values were filled using verified external data sources. This preprocessing step ensures data quality and accuracy for the predictive model.

🤖 Model Development

The model was built using the XGBoost Regressor, a robust and efficient machine-learning algorithm for regression tasks. Initially, the data was split into training and testing sets to evaluate the model's performance. After validating the model with promising results, the final model was trained on the entire dataset to enhance its predictive power.

🚀 How to Use This Project

Prerequisites

Python 3.x

Required libraries: pandas, numpy, xgboost, sklearn

Running the Project

Clone the repository:

git clone https://github.com/hjsarker/gdp-growth-prediction.git
cd gdp-growth-prediction

Upload the dataset:
When prompted, upload the provided dataset file.

Run the final prediction code:
Open gdp_prediction.ipynb and execute the final prediction cell to get the GDP growth prediction for 2025.

Example

After running the code and uploading the dataset, you'll receive the GDP growth prediction for Germany for 2025.

📦 Files Included

gdp_prediction.ipynb: Contains all the code for data processing, model training, and final prediction.

Germany Financial Data.xlsx: The dataset used for training and prediction.

⚡ Key Insights

The model was trained on a comprehensive dataset, ensuring accurate predictions.

Manual data correction and filling in missing values improved data quality.

The XGBoost algorithm provided strong predictive performance.

📬 Contact

For any inquiries, please reach out hilloltud@gmail.com or www.linkedin.com/in/hjsarker


