<h1>Employee Data Prediction System</h1>
Employee Data Prediction System is a machine learning project that predicts whether an employee is likely to leave the company based on job satisfaction, salary, age, work-life balance, training hours, bonuses, and other work-related factors. The goal is to analyze factors and build a reliable prediction system using supervised learning techniques.

<h2>Project Structure</h2>
<ul><li>employee_data.ipynb – Model for training and evaluation</li></ul>
<ul><li>employee_turnover.csv – Dataset used for training and evaluation</li></ul>

<h2>Models Used</h2>
The following models were trained and evaluated:<br>
<ul><li>Logistic Regression</li></ul>
<ul><li>Lasso & Ridge Regression</li></ul>

Model performance was compared using accuracy, precision, recall, F1-score, and support.

<h2>Model Comparison</h2>
<table>
<tr><th>Model</th><th>Accuracy (%)</th></tr>
<tr><td>Logistic Regression</td>	<td>85.92</td></tr>
<tr><td>Lasso Regression</td>	<td>87.03</td>	</tr>
<tr><td>Ridge Regression</td>	<td>85.92</td></tr>
</table>

<h2>Technologies Used</h2>
<ul><li>Python</li></ul>
<ul><li>Pandas, NumPy</li></ul>
<ul><li>Scikit-learn</li></ul>
<ul><li>Jupyter Lab</li></ul>

<h2>Future Work</h2>
<ul><li>Deploy the final model using Streamlit</li></ul>
<ul><li>Improve feature engineering</li></ul>
<ul><li>Add model interpretability and UI enhancements</li></ul>

<h2>Key Learnings</h2>
During this project, I learned and applied several important machine learning and data preprocessing concepts, including:
<ul><li>Predicting whether an employee is likely to leave the company based on job satisfaction, salary, age, work-life balance, training hours, bonuses, and other work-related factors</li></ul>
<ul><li>Building a baseline Logistic Regression model</li></ul>
<ul><li>Improving it using Regularization(L1&L2)</li></ul>
<ul><li>Comparing their performances and recommend the best model</li></ul>
