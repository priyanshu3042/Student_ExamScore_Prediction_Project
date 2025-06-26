#  Student Exam Score Prediction

This project uses **Machine Learning (Linear Regression)** to predict students' final exam scores based on key academic features like:
-  Hours Studied
-  Previous Exam Scores
-  Attendance

The project also includes data visualization using **Seaborn** to explore relationships between features and assess correlations.

---
##  Technologies Used
- Python
- Jupyter Notebook / Google Colab
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn

---
##  Files Included
- `student_exam_score_prediction.ipynb` – Main notebook with all code, data processing, visualizations, and model predictions  
- `student_scores.csv` – Dataset containing features like hours studied, attendance, and previous scores  
- `requirements.txt` – All required Python libraries to run the notebook in Google Colab or locally  
- `.gitignore` – Excludes unnecessary files like cache, system files, and checkpoints from version control  
- `LICENSE` – MIT License to allow open-source usage with attribution

---
##  Features
- Pairplot to visualize relationships between features
- Correlation matrix heatmap
- Linear regression model training & testing
- Actual vs. predicted score comparison
- Model evaluation using MSE and R² score

---
##  How to Run
You can run this notebook either locally or in Google Colab:

### ▶ Google Colab (Recommended)
[Open in Colab](https://colab.research.google.com/) and upload the `.ipynb` file.

### 🖥 Local
```bash
pip install -r requirements.txt
jupyter notebook student_exam_score_prediction.ipynb
