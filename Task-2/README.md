### Exploratory Data Analysis (EDA)

```markdown
# Titanic Dataset - Exploratory Data Analysis (EDA)

This repository contains an Exploratory Data Analysis (EDA) project on the Titanic dataset. The goal is to understand the dataset using statistical summaries and data visualizations.



## 📊 Project Objectives

1. Generate summary statistics (mean, median, std, etc.)
2. Create histograms and boxplots for numeric features
3. Use pairplot and correlation matrix to explore feature relationships
4. Identify patterns, trends, or anomalies in the data
5. Make basic feature-level inferences from visuals



## 🧰 Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn


## 📁 Files in the Repo

| File            | Description                                     |
|-----------------|-------------------------------------------------|
| `eda_titanic.py`| Python script containing the full EDA workflow  |
| `titanic.csv`   | Titanic dataset (download separately from Kaggle) |
| `README.md`     | This file explaining the project                |



## 🔗 Dataset

Download the Titanic dataset CSV from Kaggle:  
**[Click here to download](https://www.kaggle.com/datasets/yasserh/titanic-dataset)**

Save the file as `titanic.csv` in the same directory as the script.



## ▶️ How to Run

1. **Clone this repo**:
   ```bash
   git clone https://github.com/yourusername/titanic-eda.git
   cd titanic-eda
   ```

2. **Install required libraries**:
   ```bash
   pip install pandas matplotlib seaborn numpy
   ```

3. **Run the script**:
   ```bash
   python eda_titanic.py
   ```

4. **Output**:
   - Summary statistics will print in the terminal
   - All plots will display inline (no files saved)



## 💡 Sample Inferences

- **Females had a higher survival rate** than males.
- **First-class passengers survived more** often than third-class.
- **Passengers paying higher fare** were more likely in 1st class and survived more.
- **Age distribution** shows younger passengers had higher survival.



## 📌 Notes

- Make sure to have `titanic.csv` in the same directory.
- You can use Jupyter Notebook to run step-by-step and visualize better.
