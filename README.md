# rf-energy-harvesting-ml
Machine learning-based RF Energy Harvesting Analysis snd Predicton System using Python
# Machine Learning-Based RF Energy Harvesting Analysis and Prediction System

## 📌 Project Overview

This project presents a Machine Learning-based system for analyzing and predicting DC output voltage generated through RF (Radio Frequency) energy harvesting.

The system uses parameters such as **frequency, distance, transmission power, RF power, network type, and area type** to predict the expected DC output voltage.

The project aims to analyze RF energy harvesting performance in different environments and use Machine Learning techniques to predict the output voltage efficiently.

## 🎯 Objectives

* To analyze RF energy harvesting using real-world inspired dataset parameters.
* To study the relationship between RF signal parameters and DC output voltage.
* To apply Machine Learning algorithms for DC output voltage prediction.
* To compare the performance of different Machine Learning models.
* To visualize RF energy harvesting results.
* To develop an interactive application for prediction and analysis.

## 🛠️ Technologies Used

* **Programming Language:** Python
* **Data Analysis:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-learn
* **Web Application:** Gradio
* **Development Environment:** Jupyter Notebook / Google Colab

## 🤖 Machine Learning Algorithms

The following Machine Learning algorithms were explored:

* Linear Regression
* Polynomial Regression
* Support Vector Regression (SVR)
* Random Forest Regression

Among the tested models, **Random Forest Regression** was used for effective prediction of DC output voltage.

## 📊 Dataset Features

The dataset contains the following attributes:

| Feature       | Description                             |
| ------------- | --------------------------------------- |
| Area_Name     | Name of the geographical area           |
| Area_Type     | Urban, Suburban, or Rural               |
| Network       | 2G, 4G, or 5G                           |
| Frequency_MHz | Signal frequency in MHz                 |
| Distance_m    | Distance from the transmitter in meters |
| Tx_Power_dBm  | Transmitter power in dBm                |
| RF_Power_dBm  | Received RF power in dBm                |
| DC_Output_V   | Predicted/target DC output voltage      |

## 🔄 Project Workflow

1. Dataset Collection
2. Data Preprocessing
3. Exploratory Data Analysis
4. Feature Selection
5. Machine Learning Model Training
6. Model Evaluation
7. Model Comparison
8. DC Output Voltage Prediction
9. Result Visualization
10. Interactive Application Development

## 📈 Model Evaluation

The Machine Learning models were evaluated using performance metrics such as:

* R² Score
* Root Mean Squared Error (RMSE)

These metrics were used to compare the prediction performance of the developed models.

## 💻 Application

An interactive application was developed using **Python and Gradio**. Users can provide input parameters such as:

* Area Type
* Network
* Frequency
* Distance
* Transmission Power
* RF Power

The system then predicts the expected **DC Output Voltage** based on the trained Machine Learning model.

## 📁 Project Structure

```text
RF-Energy-Harvesting-Analysis-and-Prediction/
│
├── RF-EH03.ipynb
├── hybrid_area_rf_dataset.csv
├── rf_model.pkl
├── gradio_app.py
├── requirements.txt
└── README.md
```

## 🚀 Future Enhancements

* Improve model accuracy using larger real-world datasets.
* Integrate real-time RF signal data.
* Add live geographical RF signal mapping.
* Deploy the application as a web-based platform.
* Explore Deep Learning models for improved prediction.
* Support additional wireless communication technologies.

## 👩‍💻 Author

**Abinaya R**

M.Sc Data Science

Interested in **Data Analytics, Python, Machine Learning, and Data Science**.
