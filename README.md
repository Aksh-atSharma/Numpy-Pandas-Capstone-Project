# Numpy---Pandas-Capstone-Project
Data Analysis Capstone Project: Handling Missing Values with NumPy &amp; Pandas

📌 Project Overview
This project demonstrates essential data manipulation and cleaning techniques using NumPy and Pandas. It focuses on identifying and handling missing or inconsistent data using real-world inspired employee datasets. The skills and methods applied here are foundational for any data analysis or machine learning workflow.

🔧 Technologies Used
Python 🐍

Pandas 📊

NumPy 🔢

Google Colab 💻



📁 Project Structure

 capstone-numpy-pandas/
│
├── data/
│   └── employee_dataset_for_capstone.csv         # Raw dataset with missing and infinite values
│   └── Cleaned_Employee_Dataset                  # Final cleaned output file
├── notebooks
│   └── analysis.ipynb            # Main notebook with data cleaning and analysis
├── README.md                     # This file
└── requirements.txt            



📊 Key Features & Operations
✅ Identified missing (NaN) and infinite (inf) values

🔁 Replaced missing values using:

Mean

Median

Interpolation

🧹 Removed or marked outliers and duplicates

🧾 Applied vectorized operations using NumPy

📌 Used np.where() and conditional filters

💼 Performed descriptive analysis using .describe(), .info(), and visual summaries

📌 Filtered records based on salary ranges, performance ratings, and more

🧠 Created clean, analysis-ready data for downstream insights


📷 Sample Output

| Emp ID | Name   | Age | Salary | City   | Department | Rating |
| ------ | ------ | --- | ------ | ------ | ---------- | ------ |
| 101    | Akshat | 26  | 50000  | Delhi  | Analytics  | 4.5    |
| 102    | Chetna | 33  | NaN    | Mumbai | HR         | 3.9    |
| ...    | ...    | ... | ...    | ...    | ...        | ...    |


💡 Learnings & Takeaways
Mastered the use of pandas and numpy for real-world data cleaning

Understood when to use mean, median, or interpolation

Practiced vectorization and broadcasting for performance

Developed confidence in filtering, transforming, and analyzing tabular data

📬 Contact
If you have any suggestions or feedback, feel free to connect:

📧 Email: akshat@1871998@email.com

💼 LinkedIn: https://www.linkedin.com/in/akshat-sharma-35aab1179/

