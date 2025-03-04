# Data Analysis on Frailty and Students Performance Datasets

In this assignment, we performed data analysis on two datasets:

1. **Frailty Dataset**
2. **Students Performance Dataset**

The following sections outline the folder structure and step-by-step approach used in this project.

## Folder Structure

Here’s the folder structure created for both datasets:

PSD assignment/ │ ├── Frailty/ │ ├── Data_Raw/ │ ├── Data_Clean/ │ └── Results/ │ └── StudentsPerformance/ ├── Data_Raw/ ├── Data_Clean/ └── Results/


### Folder Descriptions:

- **Data_Raw**: Contains the original raw data files.
- **Data_Clean**: Stores the cleaned datasets after preprocessing.
- **Results**: Contains the visualizations and analysis results.

---

## Frailty Dataset Analysis

### Step 1: Loading the Data
- We loaded the **Frailty dataset** into the `Data_Raw` folder.

### Step 2: Folder Structure
- Created the required folder structure to organize data, cleaned data, and visualizations:
Frailty/ ├── Data_Raw/ ├── Data_Clean/ └── Results/


### Step 3: Cleaning the Data
- We performed data cleaning, including:
- Handling missing values
- Encoding categorical variables (e.g., converting `Y/N` for frailty to `1/0`)
- Removing any unnecessary columns and rows.

### Step 4: Saving the Cleaned Data
- The cleaned data was saved in the `Data_Clean` folder as `frailty_data_clean.csv`.

### Step 5: Visualizing the Data
- We created various visualizations to understand the relationships in the dataset:
- Distribution of scores (e.g., grip strength vs. frailty)
- Gender-based analysis

### Step 6: Saving the Visualization Results
- All visualizations were saved in the `Results` folder as image files (e.g., `frailty_boxplot.png`).

---

## Students Performance Dataset Analysis

### Step 1: Loading the Data
- We loaded the **Students Performance dataset** into the `Data_Raw` folder.

### Step 2: Folder Structure
- Similar to the Frailty dataset, we created a folder structure to organize the raw data, cleaned data, and visualizations:

StudentsPerformance/ ├── Data_Raw/ ├── Data_Clean/ └── Results/


### Step 3: Cleaning the Data
- Data cleaning steps included:
- Handling missing values
- Encoding categorical variables (e.g., gender, test preparation course)
- Standardizing column names

### Step 4: Saving the Cleaned Data
- The cleaned dataset was saved in the `Data_Clean` folder as `students_performance_clean.csv`.

### Step 5: Visualizing the Data
- Visualizations were created to analyze the relationships between:
- Math, reading, and writing scores
- Gender, parental education level, and performance
- The impact of test preparation courses

### Step 6: Saving the Visualization Results
- The generated visualizations were saved in the `Results` folder (e.g., `scatter_math_reading.png`).

---

## Technologies Used

- Python
- Pandas (for data manipulation)
- Seaborn & Matplotlib (for data visualization)


