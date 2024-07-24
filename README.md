## Exploring Heart disease
In this data analysis project, I explore a heart disease dataset using hypothesis testing techniques to uncover significant associations and correlations between various demographic factors and the risk of developing heart disease. By investigating these relationships, the aim is to better understand the underlying factors contributing to heart disease and potentially identify preventative measures. 
## Understanding the Data
The dataset consists of information from patients who were evaluated for heart disease at the Cleveland Clinic Foundation. The dataset comprises 14 attributes, each providing valuable insights into the patient’s health profile:

**Age (age):** Patient’s age in years.

**Gender (sex):** Patient’s gender. (1 = Male, 0 = Female)

**Chest Pain Type (cp):** Chest pain type. (Values: ATA, NAP, ASY, TA)

**Resting Blood Pressure (trestbps):** Resting blood pressure in mm Hg.

**Serum Cholesterol (chol):** Serum cholesterol in mg/dl.

**Fasting Blood Sugar (fbs):** Fasting blood sugar > 120 mg/dl. (0 = True, 1 = False)

**Resting Electroencephalographic Result (restecg):** Resting electroencephalographic result. (Values: Normal, ST, LVH)

**Maximum Heart Rate (thalach):** Maximum heart rate achieved.

**Exercise-Induced Angina (exang):** Exercise-induced angina. (N = No, Y = Yes)

**ST Depression (oldpeak):** ST depression induced by exercise relative to rest.

**Slope of the ST Segment (slope):** Slope of the peak exercise ST segment. (Values: Up, Flat, Down)

**Number of Major Vessels (ca):** Number of major vessels (0–3) colored by fluoroscopy.

**Thalassemia (thal):** Thalassemia type. (0 = normal; 1 = fixed defect; 2 = reversible defect)

**Heart Disease Occurrence (target):** Presence of heart disease. (0 = No, 1 = Yes)While the data was downloaded from the Heart Disease Dataset on Kaggle

## Usage

>1. Is the average cholesterol level (chol) for patients who were diagnosed with heart disease higher than 240 mg/dl (the level of cholesterol which is considered as “high”)?

>2. Does the average Maximum Heart Rate (thalach) tend to be lower for patients without heart disease comparing to those who have the disease?

>3. Is there a significant difference in resting blood pressure (trestbps) among patients with different types of chest pain (cp)?

>4. Is the proportion of individuals with high fasting blood sugar (fbs) withing the dataset significantly different from a certain value (0.2)?

>5. Is there a significant association between the type of chest pain (cp) and the presence of exercise-induced angina (exang)?

## Associate Methods for the given questions respectively..........

**1. One-sample test:** Compares the average of one group to a known value or standard to see if they are different.

**2. Two-sample test:** Compares the averages of two groups to see if they are different from each other.

**3. ANOVA test:** Compares the averages of three or more groups to see if at least one is different from the others.

**4. Binomial test:** Checks if the number of successes in a set number of trials is different from what we'd expect based on a given probability.

**5. Chi-square test:** Checks if there is an association between two categorical variables (e.g., if knowing one helps you predict the other).

## Acknowledgment
- [One vs Two Sample T-Test](https://medium.com/@bragadeeshs/do-you-know-the-differences-between-one-sample-and-two-sample-testing-8db1f85c4b4d)
- [One-Tailed or Two-Tailed Test???](https://medium.com/stackademic/hypothesis-testing-one-tailed-vs-two-tailed-test-dcf55f6d477d)
- [ANOVA Test](https://medium.com/towards-data-science/anova-test-simply-explained-c94e4620ec6f)
- [Binomial Distribution](https://medium.com/cantors-paradise/the-binomial-distribution-explained-8dd2bfbefe77)
