# AI Usage Data Analysis

## Project Overview

This project explores and analyzes student interactions with Artificial Intelligence tools using Python and Jupyter Notebook.

The objective of the analysis is to understand usage patterns, user satisfaction, session behavior, and the relationship between AI assistance levels and user experience.

The project includes data preprocessing, cleaning, feature engineering, normalization, exploratory data analysis (EDA), and data visualization.

---

## Dataset Information

The dataset contains records related to AI tool usage sessions and includes information such as:

- Student Level
- Academic Discipline
- Session Length
- Number of Prompts
- AI Assistance Level
- Task Type
- Satisfaction Rating

The dataset was analyzed to identify trends and patterns in AI adoption and effectiveness among students.

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

## Data Preprocessing

The following preprocessing steps were performed:

### Data Cleaning

- Removed unnecessary columns
- Renamed selected columns for better readability
- Checked data types
- Removed duplicate records
- Inspected missing values

### Feature Engineering

Categorical features were transformed into numerical representations, including:

- Student Level
- Academic Discipline

### Data Scaling

Numerical features were normalized using:

```python
MaxAbsScaler
```

Features scaled:

- SessionLengthMin
- TotalPrompts
- AI Assistance Level
- Satisfaction Rating

---

## Exploratory Data Analysis (EDA)

Several analyses were performed to gain insights into AI usage behavior.

### Student Distribution Analysis

Visualization of student levels to understand the composition of users.

### Academic Discipline Analysis

Investigation of AI adoption across different academic fields.

### Task Type Analysis

Analysis of the most common activities performed using AI tools.

### Satisfaction Analysis

Evaluation of user satisfaction levels.

### AI Assistance Impact

Exploration of the relationship between:

- Session Length
- AI Assistance Level
- User Satisfaction

Using scatter plots and comparative visualizations.

---

## Visualizations

The project includes visualizations such as:

- Pie Charts
- Scatter Plots
- Distribution Analysis

Example:

- Student Level Distribution
- Satisfaction vs Session Length
- AI Assistance Level Comparison

---

## Key Skills Demonstrated

This project demonstrates practical experience in:

- Data Cleaning
- Data Wrangling
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Visualization
- Data Normalization
- Python Programming
- Machine Learning Preprocessing Techniques

---

## How to Run

1. Clone the repository

```bash
git clone https://github.com/sina-msv99/AI_Usage_Data_Analysis.git
```

2. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

3. Launch Jupyter Notebook

```bash
jupyter notebook
```

4. Open:

```
AI Usage Data Analysis.ipynb
```

---

## Future Improvements

Possible enhancements:

- Predictive modeling
- Machine learning classification
- User satisfaction prediction
- Interactive dashboards using Power BI or Tableau
- Advanced statistical analysis

---

## Author

### Sina Mousavi

Computer Engineer

GitHub: https://github.com/http://sina-msv99
LinkedIn: https://linkedin.com/in/sina-msv99