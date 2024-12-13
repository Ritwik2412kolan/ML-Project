# **Future of Seoul Air - Air Quality Prediction**  

## **Overview**  
This project focuses on analyzing and predicting air quality levels in Seoul using data collected from various monitoring stations. It includes clustering to identify pollution hotspots, exploratory data analysis (EDA), and time series forecasting using advanced machine learning models like LSTM.  

## **Table of Contents**  
1. [Dataset](#dataset)  
2. [Preprocessing and Analysis](#preprocessing-and-analysis)  
3. [Machine Learning Models](#machine-learning-models)  
4. [Results and Evaluation](#results-and-evaluation)  
5. [How to Run](#how-to-run)  
6. [Collaborators](#collaborators)  

---

## **Dataset**  
The datasets used in this project are publicly available and consist of pollution and weather-related data collected in Seoul. The datasets include:  
- Measurement summary: Pollution measurements over time.  
- Measurement info: Metadata about the monitoring stations.  
- Item info: Item descriptions and measurement units.  
- Station info: Geographical details of the monitoring stations.  

---

## **Preprocessing and Analysis**  
1. **Data Cleaning**  
   - Handled missing and invalid values.  
   - Merged datasets to create a unified view.  
   - Dropped irrelevant columns for concise analysis.  

2. **Exploratory Data Analysis (EDA)**  
   - Visualized pollution trends over time.  
   - Created correlation heatmaps to understand relationships between features.  

3. **Clustering**  
   - Applied KMeans clustering to identify pollution hotspots.  
   - Determined optimal cluster count using Silhouette scores.  

---

## **Machine Learning Models**  
### **Random Forest Regressor**  
- Built and evaluated using features like SO2, NO2, O3, PM10.  
- Achieved an R² score of XX% on the test set.  

### **LSTM (Long Short-Term Memory)**  
- Used for time series forecasting of PM2.5 levels.  
- Trained with a sequence of past 30 days to predict future values.  
- Achieved an R² score of YY% on the test set.  

---

## **Results and Evaluation**  
### **Clustering**  
- Optimal number of clusters: `k = X`  
- Average Silhouette Score: `Y.Z`  

### **Model Performance**  
| Model            | R² Score | Notes                          |  
|-------------------|----------|--------------------------------|  
| Random Forest     | XX%      | Based on feature engineering. |  
| LSTM (Time Series)| YY%      | Predicted PM2.5 levels.       |  

---

## **How to Run**  
### **Requirements**  
- Python 3.7+  
- TensorFlow  
- Pandas, NumPy, Seaborn, Matplotlib  
- Scikit-learn  

### **Steps**  
1. Clone this repository:  
   ```bash  
   git clone https://github.com/YourUsername/YourProjectName.git  
   ```  
2. Navigate to the project folder:  
   ```bash  
   cd YourProjectName  
   ```  
3. Install required packages:  
   ```bash  
   pip install -r requirements.txt  
   ```  
4. Open and run the Google Colab notebook:  
   [Colab Notebook](https://colab.research.google.com/your-notebook-link)
