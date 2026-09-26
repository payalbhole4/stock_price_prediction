# 📈 Stock Price Prediction using Machine Learning

This project analyzes historical stock market data to predict future **Stock Prices** using Machine Learning. The entire workflow—from data preprocessing and Exploratory Data Analysis (EDA) to model training and evaluation—has been developed and executed inside **Google Colab**.

---

## 📁 Project Structure

This repository contains the following files:

*   **`Stock_Price_Prediction.ipynb`**: The primary Google Colab Notebook containing the complete Python source code for data cleaning, visualization, model implementation, and testing.
*   **`stock_price_prediction_dataset.csv`**: The dataset containing historical stock records (Date, Open, High, Low, Close prices, and Volume).
*   **`Stock Price Prediction Report.pdf`**: A comprehensive project report highlighting the methodology, evaluation metrics, charts, and final conclusions.

---

## 🛠️ Dependencies & Libraries

Since this project runs on Google Colab, most core libraries come pre-installed. The notebook leverages the following major Python packages:
*   `pandas` - For data manipulation and structured analysis.
*   `numpy` - For high-performance mathematical operations.
*   `matplotlib` & `seaborn` - For generating interactive charts and data visualizations.
*   `scikit-learn` - For building, training, and validating the Machine Learning model.

---

## 💻 How to Use

1. Click the **Open In Colab** badge at the top of this page.
2. Download the `stock_price_prediction_dataset.csv` file from this repository to your local computer.
3. In Google Colab, open the left sidebar panel, click on the **Files** icon, and upload the downloaded `.csv` file.
4. Go to the **Runtime** menu at the top bar and click **Run all** to see the results.

---

## 📊 Project Workflow

*   **Data Preprocessing:** Cleaning missing data, scaling features, and parsing date-time formats.
*   **Exploratory Data Analysis (EDA):** Plotting line charts and candlesticks to observe historical price volatility and market trends.
*   **Model Training:** Training regression or time-series machine learning models on historical splits.
*   **Evaluation:** Testing model efficiency using metrics like Mean Absolute Error (MAE) or R-squared (R²) score.
