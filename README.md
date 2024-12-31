
# **Employee Burnout Analysis and Prediction**

## **Overview**
Employee burnout is a critical issue that affects productivity and well-being in organizations. This project focuses on analyzing and predicting burnout rates among employees using a machine learning model. By identifying high-risk employees, organizations can implement strategies to improve employee satisfaction and performance.

---

## **Dataset**
The dataset used for this project is sourced from [Kaggle - Are Your Employees Burning Out?](https://www.kaggle.com/datasets/blurredmachine/are-your-employees-burning-out).  
It contains the following features:
- **Employee ID:** Unique identifier for each employee.  
- **Date of Joining:** The date the employee joined the organization.  
- **Gender:** Male or Female.  
- **Company Type:** Service-based or Product-based company.  
- **WFH Setup Available:** Indicates if work-from-home is available.  
- **Designation:** Employee’s role level.  
- **Resource Allocation:** Workload assigned to the employee.  
- **Mental Fatigue Score:** Measure of employee mental fatigue.  
- **Burn Rate:** The target variable representing the employee's burnout level.  

---

## **Technologies Used**
- **Programming Language:** Python  
- **Libraries:**  
  - `pandas` for data manipulation  
  - `matplotlib` and `seaborn` for visualization  
  - `sklearn` for machine learning models and evaluation  

---

## **Approach**
1. **Data Loading and Cleaning:**  
   The dataset was loaded and preprocessed to handle missing values and irrelevant data.

2. **Exploratory Data Analysis (EDA):**  
   Key trends and patterns were visualized to understand the contributing factors to burnout.

3. **Feature Engineering:**  
   Selected features relevant to predicting the burnout rate.

4. **Model Building:**  
   Applied regression techniques to predict the burnout rate.  

5. **Model Evaluation:**  
   - Metrics used: RMSE, MAE, and R².  
   - RMSE: 0.08, R²: 92%  

---

## **Results**
- Visual insights revealed significant contributors to burnout, such as mental fatigue and workload.  
- The machine learning model achieved high accuracy in predicting employee burnout.  

---

## **Future Scope**
- Expand the dataset for more generalizable results.  
- Include additional features like performance ratings and manager feedback.  

---

## **How to Run**
1. Clone this repository:  
   ```bash
   git clone <repository-url>
   ```
2. Install the required libraries:  
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook for analysis:  
   ```bash
   jupyter notebook Employees_Burnout_Analysis_and_Prediction.ipynb
   ```

---

## **References**
1. [Kaggle - Are Your Employees Burning Out?](https://www.kaggle.com/datasets/blurredmachine/are-your-employees-burning-out)  
2. Python libraries: pandas, sklearn, matplotlib, seaborn  

---

## **Contact**
For any queries or suggestions, feel free to reach out to **Abdul Mahtab Sarban** at [your email/contact].  
# Employee-Burnout-Analysis-and-Prediction
