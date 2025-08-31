# Student Performance Analysis  

This project analyzes student performance data, focusing on data cleaning, transformation, and exploratory data analysis (EDA). The dataset provides insights into study habits, gender distribution, and other factors influencing student performance.  

---

## 📂 Project Files  

- **`Student_data.ipynb`** – Jupyter Notebook containing the full analysis and code implementation (https://colab.research.google.com/drive/1bNvjAmm6hLHb10bMo6Ijs5jNdAZa-ONh#scrollTo=RTUHtvliv_w6)  
- **`Student_performance_data_.csv`** – Raw dataset used for analysis (https://www.kaggle.com/datasets/rabieelkharoua/students-performance-dataset)  
- **Images** – Visualizations generated during EDA.
- 
- **Visual 1**
- <img width="756" height="568" alt="image" src="https://github.com/user-attachments/assets/2c265350-7639-4d29-9703-d6d18e617e9b" />
**Interpretation:**  
- GPA varies slightly across grade classes.  
- Students in **Grade Class 0 and 3** have the highest GPA (~4.0).  
- **Grade Class 1 and 2** show slightly lower GPA (around 3.6), which may indicate differences in academic difficulty or student performance.  
- Overall, most grade classes maintain a **high GPA close to 4.0**.
- 
**Visual 2**
  <img width="741" height="560" alt="image" src="https://github.com/user-attachments/assets/06baa338-e0b8-4fbd-8673-1ecc4534ddd2" />
  **Interpretation:**  
- There is a **slight positive correlation** between weekly study time and GPA.  
- The regression line (in red) indicates that **increasing study hours generally leads to higher GPA**, though the relationship is not very strong.  
- The green dots (Actual) show some variability, meaning other factors besides study time also affect GPA.


---

## 🔍 Overview  

The main steps in this project include:  

1. **Data Cleaning** – Handling missing values and removing unnecessary columns.  
2. **Data Transformation** – Modifying string values for better clarity and consistency.  
3. **Exploratory Data Analysis (EDA)** – Understanding patterns such as gender distribution and study hours.  

---
## Tools and Analysis Summary
- pandas: Data manipulation and analysis
- numpy: Numerical computations
- matplotlib: Data visualization
- seaborn: Statistical data visualization
- scikit-learn: Machine Learning algorithms and evaluation
- kaggle: dataset
