# Student Performance Analysis

This repository contains the final project for the **Data Science e Laboratorio** course (A.A. 2025/2026). The project explores demographic and background factors that influence students' test scores, with a particular focus on predicting math scores using Machine Learning.

## 📁 Project Structure

As required by the course guidelines, this repository includes the following components:

*   **`Dataset/`**: Contains the `StudentsPerformance.csv` dataset used for the analysis.
*   **`project_students_performance.ipynb`**: The main Jupyter Notebook containing the source code for data cleaning, Exploratory Data Analysis (EDA), and the Linear Regression model.
*   **`presentation.ipynb` & `presentation.slides.html`**: The slide deck created for the final 8-minute oral presentation.
*   **`output.png`, `output2.png`, `output3.png`, `output4.png`**: Various charts and visualizations exported during the analysis to be used cleanly in the presentation slides.

## 📊 Dataset Description

The analysis is based on the **Students Performance in Exams** dataset. It includes variables such as:
*   Gender
*   Race/Ethnicity
*   Parental Level of Education
*   Lunch type (standard vs. free/reduced)
*   Test Preparation Course completion
*   Scores (Math, Reading, and Writing)

## 🚀 How to Run

1. Clone this repository to your local machine.
2. Ensure you have Python and Jupyter Notebook installed.
3. Install the required data science libraries (`pandas`, `matplotlib`, `seaborn`, `scikit-learn`).
4. Open and run `project_students_performance.ipynb` to reproduce the full analysis and model training.
5. To view the presentation, simply open `presentation.slides.html` in any modern web browser.

## 📌 Key Findings

*   **Exploratory Data Analysis:** Factors such as completing a test preparation course, having standard lunch, and higher parental education levels are strongly correlated with higher overall test scores. 
*   **Modeling:** The Linear Regression model successfully identifies the relationship between these categorical background variables and the students' final math scores, highlighting the significant impact of socioeconomic and preparation factors on academic performance.
