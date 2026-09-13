# Student Performance Analysis

Analyzing 1,000 students' exam scores to understand what factors most 
influence academic performance — using EDA, statistical hypothesis testing, 
regression, classification, and clustering.

## 📊 Dataset
- 1,000 student records, 8 original columns
- Source: [where you got it, e.g., Kaggle link]
- Features: gender, race/ethnicity, parental education, lunch type, test 
  prep completion, and scores in math/reading/writing

## 🔍 Key Findings
- Parental education has the largest effect on scores (Cohen's d = 0.78), 
  ahead of lunch type (0.63) and test prep completion (0.55)
- Test prep completion is the only factor students can control, and it 
  produces a real, statistically significant score boost
- A 3-feature model performs nearly as well as a 9-feature model (R² 0.687 
  vs 0.698) — most predictive power comes from just a few variables
- Unsupervised clustering independently rediscovered the lunch-type 
  performance gap without ever seeing that column

## 🛠️ Methods Used
EDA, t-tests, ANOVA, chi-square, Cohen's d, Linear Regression, Logistic 
Regression, Decision Trees, K-Means Clustering

## 📁 Files
- `Untitled-1.ipynb` — full analysis notebook
- `studentperfomance.csv` — dataset

## 🚀 How to Run
1. Clone this repo
2. Install dependencies: `pip install pandas numpy matplotlib seaborn scipy scikit-learn`
3. Open `student_performance_FINAL.ipynb` in Jupyter and run all cells
