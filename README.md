

# What the Data Says About Heart Disease: An Exploratory Analysis


## About This Project

This project looks at a set of patient information to understand what might be linked to heart disease. Things like age, blood pressure, cholesterol, chest pain, and heart rate were explored to see how they relate to heart health. The goal is to spot patterns that could help identify who might be at risk.

---

## About the Data

The dataset contains both numbers and categories.

**Numbers and measurements**

* Age
* Resting blood pressure
* Cholesterol
* Maximum heart rate
* ST depression during exercise
* Number of major blood vessels affected

**Categories**

* Sex (male or female)
* Chest pain type
* Fasting blood sugar
* Heart rhythm readings
* Exercise-induced angina (yes or no)
* Slope of ST segment
* Type of thalassemia

**Target**

* Heart disease presence (0 means no, 1 means yes)

---

## What Was Done

* Cleaned the data by removing wrong or missing values.
* Changed number codes into understandable labels, like "male" instead of 1.
* Looked at how different features are distributed for people with and without heart disease.
* Checked which features are more connected to having heart disease.

---

## What Was Found

* People with lower maximum heart rates and higher ST depression are more likely to have heart disease.
* Age, cholesterol, and blood pressure are related but not as clearly.
* Chest pain type, exercise-induced angina, and thalassemia type can also help tell the difference.
* About half the patients have heart disease, which gives a good balance for analysis.

---

## Next Steps

* Try building models to predict heart disease.
* See which features are the most important for prediction.
* Explore the relationships between different categories and heart disease more closely.
* Look at different groups, like by age or gender, for more insights.

---

## Tools Used

* Python for data handling
* Pandas and NumPy for working with the data
* Matplotlib and Seaborn for making charts and plots

---

## Why This Matters

Looking at the data helps us see patterns that can point to heart disease risks. This is a first step in helping doctors and patients understand heart health better.

