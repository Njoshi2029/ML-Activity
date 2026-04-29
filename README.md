# Simple Linear Regression - Student Performance Prediction

## Project Overview
This project is part of the **M.Sc. Data Science (Sem-II) Machine Learning Theory** credit activity. It demonstrates the implementation of a **Simple Linear Regression** model using Python. 

The primary objective of this mini-project is to predict a student's academic performance score based on their daily screen time (in hours). 

## Dataset
The project uses a custom dataset containing 40 student records with two primary variables:
- **Daily_Screen_Time_hrs (Independent Variable - X):** The average number of hours a student spends on screens (mobile, TV, laptop) for non-study purposes.
- **Academic_Score (Dependent Variable - Y):** The student's academic performance score out of 100.

## Technologies Used
- **Language:** Python 3
- **Environment:** Jupyter Notebook
- **Libraries:** 
  - `pandas` & `numpy` (Data manipulation and analysis)
  - `matplotlib` & `seaborn` (Data visualization)
  - `scikit-learn` (Machine learning model building and evaluation)

## Key Findings
- The model reveals a **strong negative correlation** between daily screen time and academic scores.
- The linear regression equation shows that for every additional hour spent on screens, the predicted academic score drops by approximately **7 points**.
- The model achieved an impressive **R² score of ~0.97**, indicating an excellent fit to the data with minimal prediction errors.

## How to Run the Project
1. Ensure you have Python installed on your system.
2. Install the required libraries by running the following command in your terminal:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn jupyter
   ```
3. Open the terminal or command prompt in the project directory.
4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
5. Open the `Simple_Linear_Regression.ipynb` file and run the cells sequentially to see the data processing, visualizations, and model predictions.

---
**Submitted By:** [Nandini Joshi ]  
**Class:** M.Sc. Data Science (Sem-II)  
**College:** Dr. D. Y. Patil Arts, Commerce & Science College, Pimpri
