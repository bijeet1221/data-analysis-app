# 🧼 Data Cleaning and Visualization Tool

A web-based application designed to make data cleaning and visualization faster, smarter, and easier! This tool enables users to handle missing data, remove outliers, clean text, create visualizations, and much more — all from a user-friendly interface powered by Streamlit.

---
## 🚀 Live Demo

🌐 Check out the live app here:  
👉 [data-analysis-app.streamlit.app](https://data-analysis-app-4vudwhmzx2uruamawrhgtc.streamlit.app)

---

## ✨ Features

### 🎯 Data Cleaning

- **Fill Missing Values:** Choose from mean, median, or mode imputation.
- **Remove Duplicates:** Automatically remove duplicate rows.
- **Outlier Detection and Removal:** Uses IQR (Interquartile Range) to filter outliers.
- **Text Cleaning:** Strips whitespace, converts to lowercase, and standardizes text data.
- **Spelling Correction:** Automatically fixes common typos in text columns.
- **Format Correction:** Ensures numeric and datetime formats are accurate.
- **Binning:** Groups numeric columns into bins for analysis or visualization.

### 📊 Data Visualization

- **Histograms:** Visualize the distribution of numeric columns.
- **Boxplots:** Easily detect outliers and understand data spread.
- **Correlation Heatmaps:** Display relationships between numeric features.

### 🌐 Multilingual Support

- Currently available in **English** and **Hindi**.
- Users can select the language using the **sidebar dropdown**.
- **Planned:** Support for additional languages will be added in future updates to make the tool more accessible to a wider audience.

### 📂 File Handling

- Supports `.csv`, `.xlsx`, and `.xls` formats for uploading datasets.
- Cleaned datasets can be downloaded in CSV format.
- Visualizations can be downloaded as PNG images.

### ⚡ Ease of Use

- Interactive, no-code interface powered by **Streamlit**.
- Sidebar controls for all data cleaning and visualization options.
- Immediate feedback and preview for uploaded and cleaned datasets.

---

## 🔧 Tech Stack

- **Python:** Core programming language.
- **Streamlit:** For building the web-based user interface.
- **Pandas:** Data manipulation and cleaning.
- **NumPy:** Numerical operations.
- **Seaborn & Matplotlib:** Data visualization.
- **Scikit-learn:** Preprocessing, imputation.

---

## 🚀 Installation

Clone this repository:

```bash
git clone https://github.com/bijeet1221/data-analysis-app.git
cd data-analysis-app
