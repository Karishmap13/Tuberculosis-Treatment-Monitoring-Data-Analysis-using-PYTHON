# Tuberculosis-Treatment-Monitoring-Data-Analysis-using-PYTHON
This project analyzes a synthetic Tuberculosis (TB) dataset from the DOTS program using Python. The goal is to clean, integrate, and analyze healthcare data to generate statistical insights and visualizations related to TB diagnosis, treatment, and outcomes.

**Project Overview**

The analysis focuses on understanding patterns in TB patient data, including disease type, treatment dosage, comorbidities, and outcomes. Python libraries were used to perform data cleaning, manipulation, statistical testing, and visualization.

**Tech Stack**

1. Python

2. Pandas – data cleaning and manipulation

3. NumPy – numerical operations

4. SciPy – statistical analysis

5. Matplotlib – data visualization

**Dataset Structure**

The dataset simulates a DOTS TB program database consisting of four main tables:

Patient – demographic and clinical information

Diagnosis – TB type and drug resistance details

Treatment – medication dosage and treatment duration

Outcome – treatment results

**Data Processing Workflow**

Key data engineering steps included:

1. Importing and cleaning raw healthcare datasets

2. Removing duplicates and validating missing values

3. Merging relational tables using left and right joins

4. Creating a derived Risk-Level variable based on drug resistance and comorbidities

5. Updating categorical variables using conditional logic

6. Appending new patient observations

**Analytical Questions**

The analysis addressed several healthcare-focused questions:

1. What proportion of patients have Pulmonary vs Extra-Pulmonary TB?

2. How does drug dosage vary by drug resistance category?

3. Are there state-wise differences in treatment outcomes?

4. What are the minimum and maximum HRZE drug dosages administered?

**Statistical Analysis**

The project applies inferential statistical methods to examine potential relationships in the dataset.

**Normality Testing** :
Evaluated whether patient age distribution follows a normal distribution.

**Independent Samples T-Test**:
Compared mean age between Pulmonary and Extra-Pulmonary TB patients.

Result: No statistically significant difference observed.

**Pearson Correlation**: Examined relationship between age and drug dosage.

Result: Weak negative correlation.

**Linear Regression**: To predict drug dosage using age and comorbidities.

Result: Predictors were not statistically significant in this dataset.

**Data Visualizations**

1. Pie Chart: Distribution of TB types

2. Scatter Plot: Relationship between age and drug dosage

3. Box Plot: Minimum and maximum HRZE drug doses

4. Bar Chart: Treatment duration across comorbidity groups

**Key Insights**

- Pulmonary TB represents a significant proportion of cases in the dataset.

- Age shows minimal influence on treatment dosage.

- Drug dosage variation appears to depend on multiple clinical factors beyond age or comorbidities.
