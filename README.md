# CareerPredictor

A machine learning project designed to predict job placement outcomes for graduates using logistic regression. 
This project demonstrates skills in data preprocessing, exploratory data analysis (EDA), and predictive modeling to uncover actionable insights.

---

## **Overview**

This project analyzes factors influencing job placements for graduates, including academic performance, specialization, and work experience. Using logistic regression, the model classifies students as `Placed` or `Not Placed`, providing a data-driven approach to understanding placement trends.

---

## **Key Features**

- **Data Preprocessing**:
  - Cleaned and handled missing values.
  - Addressed outliers using the IQR method with an adjusted multiplier.
  - Converted categorical variables to numeric representations.
- **Exploratory Data Analysis (EDA)**:
  - Visualized trends in placement outcomes by specialization, work experience, and academic scores.
- **Modeling and Evaluation**:
  - Built a logistic regression model with a testing accuracy of 93%.
  - Evaluated performance using confusion matrices and classification metrics.

---

## **Results**

- **Training Accuracy**: 100%  
  *Explanation*: The small dataset size led to perfect training accuracy, but the model’s generalizability is validated by testing metrics.
- **Testing Accuracy**: 93%  
- **Key Insights**:
  - Higher academic scores correlate strongly with placement success.
  - Graduates with work experience and specific specializations have higher placement rates.

---

## **Visualizations**

- Histograms of academic scores categorized by placement outcomes.
- Bar charts showing placement trends by specialization and work experience.
- Confusion matrices for training and testing datasets.

---

## **Files in This Repository**

1. **`CareerPredictor.ipynb`**: Jupyter Notebook containing the full analysis, model, and visualizations.
2. **`Job Placement_data.csv`**: Dataset used for training and testing the model.
3. **`Data description.xlsx`**: Detailed explanation of dataset features and their meanings.
4. **`requirements.txt`**: List of Python libraries required to run the project.

---

## **Libraries Used**

This project uses the following Python libraries:

- **pandas**: For data manipulation and preprocessing.
- **numpy**: For numerical operations.
- **matplotlib**: For data visualization.
- **seaborn**: For enhanced visualizations.
- **scikit-learn**:
  - Data splitting with `train_test_split`
  - Logistic regression with `LogisticRegression`
  - Preprocessing with `StandardScaler` and `OneHotEncoder`
  - Metrics like `confusion_matrix`, `accuracy_score`, and `classification_report`.

---

## **How to Run**

1. Clone the repository:
   ```bash
   git clone https://github.com/PredictAnalytics/CareerPredictor.git
   cd CareerPredictor
2. Install the required Python libraries:
   pip install -r requirements.txt
3. Open the Jupyter Notebook:
   jupyter notebook CareerPredictor.ipynb

Run the notebook to explore the analysis, model, and results.


## **Contact**
Feel free to connect or collaborate:
- **GitHub:**
[PredictAnalytics](https://github.com/PredictAnalytics) 
- <img src="https://upload.wikimedia.org/wikipedia/commons/c/ca/LinkedIn_logo_initials.png" alt="LinkedIn Logo" width="16"/>  **LinkedIn: [Joshua Davydov](https://www.linkedin.com/in/joshua-davydov/)**

