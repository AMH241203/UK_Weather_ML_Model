# UK Energy Forecasting & ML Research

An end-to-end Machine Learning pipeline and data analysis project focused on predicting UK energy demand using weather data. This repository analyzes 70,272 hourly observations from the year 2024, achieving a high-accuracy forecasting model with an $R^2 \approx 0.973$. 

Alongside the practical pipeline, this project includes a comprehensive 55-page theoretical study covering Supervised, Unsupervised, and Reinforcement Learning concepts.

## 📊 Key Insights & Data Explorations
During the Exploratory Data Analysis (EDA) of the UK energy dataset, several core behavioral patterns were identified:
* **Daily Patterns:** Daily energy consumption exhibits a distinct **S-shaped** pattern, mapped by peaks and troughs at specific times of the day.
* **Weekly Patterns:** Contrary to typical weekday/weekend splits, the weekly energy usage pattern remains largely **the same for all days** within this dataset.
* **Key Drivers:** Strong correlation values were identified between energy usage and specific environmental/temporal variables, primarily **temperature, hour of the day, and month**.

## 📁 Repository Contents

* `UK_Energy_Usage_2024_ML_and_Data_Analysis.ipynb`: The core Jupyter Notebook containing the data preprocessing, exploratory data analysis (EDA), and the end-to-end machine learning forecasting pipeline.
* `UK_Energy_Usage_2024_with_Weather.csv`: The primary dataset containing 70,272 hourly observations of energy demand merged with UK weather metrics.
* `Theoretical Study on Machine Learning.pdf`: A 55-page deep dive into the theoretical mechanics of Supervised, Unsupervised, and Reinforcement Learning algorithms.
* `UK Energy Usage 2024 Summary Report.pdf`: A high-level summary of the analysis, visualizations, and model performance metrics.
* `index.html`: Web-based view or export of the analytical findings.
* `requirements.txt`: Python dependencies required to reproduce the environment and run the notebook.

## 🛠️ Technologies & Tools
* **Language:** Python
* **Environment:** Jupyter Notebook / HTML
* **Core Tasks:** Exploratory Data Analysis, Predictive Modeling, Energy Forecasting

## 🚀 How to Run

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/AMH241203/UK_Weather_ML_Model.git
    cd UK_Weather_ML_Model
    ```

2.  **Install dependencies:**
    It is recommended to use a virtual environment.
    ```bash
    pip install -r requirements.txt
    ```

3.  **Launch the Notebook:**
    ```bash
    jupyter notebook
    ```
    Open `UK_Energy_Usage_2024_ML_and_Data_Analysis.ipynb` to run the ML pipeline and view the data visualizations.

## 📖 Research Documentation
For a complete understanding of the theoretical background behind the models used in this pipeline, please refer to the attached `Theoretical Study on Machine Learning.pdf`.
