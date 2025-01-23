# Titanic-EDA

This repository contains an exploratory data analysis (EDA) project on the Titanic dataset. The goal of this project is to analyze and visualize patterns in the data, such as survival rates based on gender, age, and class, using Python libraries like pandas, matplotlib, and seaborn.

## 📂 File Structure

```
Titanic-EDA/
|-- README.md
|-- Titanic_EDA.pbix
|-- Titanic_Exploratory_data_analysis.ipynb
|-- train.csv
|-- train_Cleaned.csv
```

### 📄 Files Explanation

- **README.md**: Provides an overview of the repository and instructions for usage.
- **Titanic_EDA.pbix**: A Power BI file for additional data visualization and reporting.
- **Titanic_Exploratory_data_analysis.ipynb**: A Jupyter Notebook file containing the Python code for EDA on the Titanic dataset.
- **train.csv**: The original dataset used for the analysis.
- **train_Cleaned.csv**: The cleaned dataset after processing and handling missing values.

## 📝 Code Explanation

The EDA notebook (`Titanic_Exploratory_data_analysis.ipynb`) covers the following steps:

1. **📥 Data Loading and Overview**:
   - Load the Titanic dataset (`train.csv`) using pandas.
   - Display the dataset structure, data types, and statistical summaries.

2. **🧹 Data Cleaning**:
   - Handle missing values in the `Age` and `Embarked` columns.
   - Drop the `Cabin` column due to a high proportion of missing values.
   - Save the cleaned dataset to `train_Cleaned.csv`.

3. **📊 Exploratory Data Analysis**:
   - Generate various visualizations to explore the dataset, including:
     - Age distribution and survival rates.
     - Survival counts by gender and passenger class.
     - Correlation heatmap for numerical columns.
     - Scatter plots and box plots for further insights.

4. **📚 Visualization Libraries**:
   - Use `matplotlib` and `seaborn` for generating plots.

## 🚀 How to Clone and Run the Code

### 📂 Clone the Repository

```bash
git clone https://github.com/jha-aman09/Titanic-EDA.git
cd Titanic-EDA
```

### 📋 Requirements

Make sure you have the following Python libraries installed:

- pandas
- numpy
- matplotlib
- seaborn

You can install the dependencies using pip:

```bash
pip install pandas numpy matplotlib seaborn
```

### ▶️ Run the Notebook

1. Open the notebook in Jupyter Notebook or Google Colab.
2. Run the cells sequentially to execute the code.

Alternatively, you can access the notebook directly in Google Colab:

[Titanic EDA](https://colab.research.google.com/drive/1aL8dNGQl9K0qjzDQ2T6C831DeZdOypRi?usp=sharing)

## 👤 Author

**Aman Kumar Jha**

- **Field**: Data Science (BCA Student at GGSIPU)
- **Skills**: Data Analysis, Python, Power BI, Machine Learning, and more.
- **GitHub**: [Aman Jha](https://github.com/jha-aman09)

## 💬 Feedback

Feel free to create issues or pull requests for suggestions and improvements. Thank you for exploring the Titanic EDA project!
