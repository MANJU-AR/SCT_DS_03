# SCT_DS_03
# 🧠 Customer Purchase Prediction Using Decision Tree Classifier

This project focuses on predicting whether a customer will purchase a product or subscribe to a service based on their **demographic and behavioral data**, using the **Bank Marketing Dataset** from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/bank+marketing).

---

## 📌 Objective

- Build a **Decision Tree Classifier (DTC)** to predict customer subscription behavior.
- Analyze and prepare the dataset through **data preprocessing**.
- Perform **exploratory data analysis (EDA)** to understand key patterns and trends.
- Evaluate model performance using classification metrics.

---

## 📁 Dataset Description

The dataset contains information on direct marketing campaigns of a Portuguese banking institution. The classification goal is to predict if the client will subscribe to a term deposit (`yes` or `no`).

### Features Include:

- `age`: Age of the client
- `job`: Type of job
- `marital`: Marital status
- `education`: Education level
- `default`: Has credit in default?
- `balance`: Average yearly balance
- `housing`: Has housing loan?
- `loan`: Has personal loan?
- `contact`: Contact communication type
- `day`, `month`, `duration`: Last contact date info
- `campaign`: Number of contacts during campaign
- `previous`: Number of contacts before this campaign
- `poutcome`: Outcome of the previous marketing campaign
- `y`: Target variable (subscribed: `yes` or `no`)

---

## 🧰 Tools & Libraries

- Python 3.x
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn
- Jupyter Notebook or any Python IDE

---

## 🔍 Steps Performed

### 1. 📥 Data Loading & Cleaning
- Handled missing values and inconsistent entries
- Converted categorical variables into numerical using encoding

### 2. 📊 Exploratory Data Analysis (EDA)
- Visualized target distribution (subscribed vs. not)
- Analyzed relationships between features and the target variable
- Used bar plots, histograms, and heatmaps to uncover patterns

### 3. 🌲 Model Building
- Built a **Decision Tree Classifier** using Scikit-learn
- Split the dataset into training and testing sets
- Trained and tuned the model

### 4. 📈 Model Evaluation
- Evaluated using accuracy, precision, recall, F1-score, and confusion matrix
- Visualized the Decision Tree using `plot_tree`

---

## 🖼️ Sample Visuals

- **Target class distribution** bar chart
- **Education vs subscription** bar plot
- **Correlation heatmap** of numeric features
- **Decision Tree visualization**

---

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/bank-marketing-dtc.git
   cd bank-marketing-dtc

2.Install dependencies:

  ```bash
        pip install pandas numpy matplotlib seaborn scikit-learn 
  ```

3.Download the dataset from UCI Repository, unzip it, and place bank-full.csv in the project folder.

4.Run the notebook or script:
```bash
jupyter notebook bank_marketing_dtc.ipynb

```
📂 Project Structure

bank-marketing-dtc/
│
├── bank_marketing_dtc.ipynb     # Main notebook
├── bank-full.csv                # Dataset
├── README.md                    # Project description
└── requirements.txt             # Optional: project dependencies

