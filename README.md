# Logistics Cost Prediction: China to Africa 🚢🌍

## Project Overview
This project aims to predict shipping costs for trade routes between China and Africa using Machine Learning. By analyzing 10,000 records (refined to 7,879 high-quality rows), I developed a model to help businesses optimize their financial planning and reduce uncertainty in international logistics.

## Key Achievements
* **Data Cleaning:** Processed a raw dataset of 10,000 entries, performing rigorous cleaning to ensure data integrity.
* **Accuracy:** Achieved an **R² Score of 0.95**, explaining 95% of the cost variance.
* **Impact:** Reduced the Mean Absolute Error (MAE) from ~$70k to **$14,954 USD**.
* **Model Selection:** Compared KNN, Decision Trees, and Random Forest, with the latter being the most robust after hyperparameter tuning.

## Tech Stack
* **Language:** Python
* **Libraries:** Pandas, Scikit-learn, Matplotlib, Seaborn
* **Tool:** Google Colab

## How to use
1. Clone this repository to your local machine or open the notebook directly in Google Colab.
2. Dataset Setup (Google Drive):
   
-Ensure the file china_africa_trade.xlsx is uploaded to your Google Drive in the path: MyDrive/.
-The notebook is configured to mount Google Drive and read the data from /content/drive/MyDrive/china_africa_trade.xlsx.

4. Install dependencies: Run the first cell in the notebook to install necessary libraries: !pip install --upgrade --force-reinstall fitter.
5. Execute the analysis: Run all cells in the ML_Log_China_Africa.ipynb notebook to reproduce the results and model selection.

## Feedback
I am in the early stages of my Machine Learning journey. I am open to suggestions, corrections, and any feedback that helps me improve my technical skills!
