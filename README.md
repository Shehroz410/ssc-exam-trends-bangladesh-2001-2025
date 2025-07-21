# 📊 SSC Exam Result Trends in Bangladesh (2001–2025)

This project provides a comprehensive analysis of SSC (Secondary School Certificate) exam results in Bangladesh over a span of 25 years, from 2001 to 2025. It explores trends in the number of examinees, pass rates, and GPA 5 achievers. The goal is to visualize educational progression and academic outcomes through clear and insightful plots using Python.

## 📁 Dataset Overview

- **Source**: [Kaggle Dataset](https://www.kaggle.com/datasets/hasanulbannahimel/ssc-exam-result-trends-in-bangladesh-20012025)
- **Total Entries**: 25
- **Columns**:
  - `Year`: Exam year
  - `Total_Examinees`: Total students who appeared
  - `Pass_Rate`: Percentage of students who passed
  - `GPA_5_Count`: Students who scored GPA 5

## 🧹 Data Cleaning

The dataset originally had numeric columns in object format due to characters like commas and percentage signs. The following steps were performed:

- Removed commas from numbers and '%' signs from percentages.
- Converted `Total_Examinees`, `Pass_Rate`, and `GPA_5_Count` to appropriate numeric types.
- Handled `'Null'` values using interpolation for consistency.
- Ensured the dataset has no missing values after preprocessing.

## 📊 Key Insights

- 📈 **Total Examinees**: Increased steadily from 2001 to 2025, reflecting greater participation in SSC exams.
- 🎓 **Pass Rate**: Varied slightly across the years, with some significant drops likely due to academic reforms or national disruptions (e.g., COVID-19).
- 🏆 **GPA 5 Achievers**: Show fluctuations that may relate to curriculum difficulty or grading policy changes.

## 📈 Visualizations

The following charts were created using Matplotlib and Seaborn:

- **Line Plot**: Pass rate over the years.
- **Area Chart**: Growth in GPA 5 achievers over time.
- **Combined Subplots**: Year-wise comparison of examinees, pass rate, and GPA 5 count.

These visualizations help uncover trends and anomalies in Bangladesh’s education system performance over time.

## 🛠️ Tools Used

- **Python**
- **Pandas** for data manipulation
- **Matplotlib & Seaborn** for visualization
- **Jupyter/Kaggle Notebook** environment

## 📂 Folder Structure

ssc-exam-trends-bangladesh/
│
├── ssc_exam_analysis.ipynb # Main analysis notebook
├── cleaned_dataset.csv (optional)
├── README.md # Project documentation


## 🚀 How to Use

1. Clone the repository:

```
git clone https://github.com/your-username/ssc-exam-trends-bangladesh.git
cd ssc-exam-trends-bangladesh
'''

Open the Jupyter notebook (ssc_exam_analysis.ipynb) locally or in a Kaggle environment.

Run the notebook cells to view preprocessing steps and final visualizations.

🧠 Future Improvements
📅 Add forecasting using Prophet to predict future pass rates or GPA 5 achievers.

🧩 Combine SSC with HSC or PSC datasets for a complete education lifecycle trend.

💻 Build an interactive dashboard using Streamlit or Plotly Dash.

📜 License
This project is released under the MIT License — free to use, distribute, and modify with attribution.

👏 Acknowledgments
Dataset by: Hasanul Banna Himel on Kaggle

Analysis by: [Your Name or GitHub Handle]

🙌 If you find this project useful, don't forget to ⭐️ the repository!
