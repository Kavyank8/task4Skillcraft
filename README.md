
# 🧠 SkillCraft Data Analysis Project
This project focuses on performing **data cleaning, preprocessing, and exploratory data analysis (EDA)** on the **SkillCraft dataset**, which contains player performance metrics from the game *StarCraft II*.
The goal of the project is to understand player behavior, identify key performance factors, and prepare the dataset for future ML modeling.

## 📁 Project Structure

```
Skillcraft-Analysis/
│
├── task4Skillcraft.ipynb        # Main analysis notebook
├── skillcraft.csv               # Dataset (uploaded inside notebook)
└── README.md                    # Project documentation
```

## 🎯 Project Objectives

* Load and inspect the SkillCraft dataset
* Clean missing or inconsistent data
* Analyze important player performance metrics
* Visualize relationships between features
* Prepare data for future ML tasks
---
#🛠️ Technologies Used

| Tool / Library             | Purpose                      |
| -------------------------- | ---------------------------- |
| **Python**                 | Core programming             |
| **Pandas**                 | Data manipulation & cleaning |
| **NumPy**                  | Numerical operations         |
| **Matplotlib**             | Data visualization           |
| **Seaborn**                | Statistical plotting         |
| **Google Colab / Jupyter** | Notebook environment         |

---

## 📥 Dataset Description
The dataset typically contains player attributes such as:
* APM (Actions Per Minute)
* Select/Hotkey usage
* Map exploration
* Worker management
* Complex decision-making metrics
* User skill level
These help understand how players behave and perform in gameplay.

### **1️⃣ Importing Required Libraries**
Loaded pandas, NumPy, matplotlib, seaborn, etc.
### **2️⃣ Loading the Dataset**
Used file upload in Google Colab to load `skillcraft.csv`.
### **3️⃣ Inspecting the Dataset**
* `head()` and `tail()
* `info()`
* Missing value count
* Statistical summary

### **4️⃣ Data Cleaning**
* Removed/filled missing values
* Treated invalid or inconsistent entries
* Handled duplicates
* Converted columns to appropriate datatypes
### **5️⃣ Exploratory Data Analysis**
Key analyses performed:
* Distribution of performance metrics
* Correlation between features
* Heatmaps to observe relationships
* Player skill level vs performance
* Visualizations:

  * Histograms
  * Boxplots
  * Scatter plots
  * Countplots

### **6️⃣ Feature Understanding**
Examined which attributes impact skill level, such as:

* High APM
* More hotkey usage
* Better map exploration
* Faster actions
* Better resource management
## 📈 Key Visualizations

* **APM Distribution**
* **Skill Level vs Key Features**
* **Heatmap for Correlated Metrics**
* **Scatterplots for predictive features**

These plots help understand the structure and behavior of players in the dataset.

---

## 🚀 How to Run the Project

1. Download or open the notebook (`task4Skillcraft.ipynb`)
2. Run it in **Google Colab** or **Jupyter Notebook**
3. Upload `skillcraft.csv` when prompted
4. Execute all cells sequentially

## 📌 Future Enhancements

* Build ML models to classify player skill level
* Feature engineering for gameplay insights
* Predictive analytics using:

  * Random Forest
  * Logistic Regression
  * Neural Networks

## 🙌 Credits

Dataset Source: SkillCraft1 Master Table
Project Author: *Kavya*


Just send me the notebook contents or tell me your preferred style!
