# Big-Data-Project-Apache-Spark-Iris-Classification
This project explores Big Data processing and machine learning using Apache Spark on the Iris dataset. It includes data loading, SQL analytics, feature engineering, and classification with Spark MLlib, evaluating Naïve Bayes, Decision Tree, Random Forest, and MLP in a scalable environment.

### 📌 Overview

This project demonstrates data processing, analysis, and machine learning using Apache Spark.
It involves:

- Data ingestion & exploration

- DataFrame transformations

- SQL analytics with Spark SQL

- Machine Learning using Spark MLlib

- Model evaluation & comparison

 ### 📂 Iris Dataset

The dataset contains measurements of Iris flowers and their species classification.

***🧾 Schema***
```
 |-- sepal.length: double
 |-- sepal.width: double
 |-- petal.length: double
 |-- petal.width: double
 |-- variety: string
```
### 🔍 Description

***Features***

- Sepal.length

- Sepal.width

- Petal.length

- Petal.width

***Target***

Variety → (Iris-setosa, Iris-versicolor, Iris-virginica)

✔️ Clean dataset

✔️ Balanced classes

✔️ Suitable for classification tasks

### ⚙️ Steps Completed 
***1️⃣ Spark Session Creation***

Spark environment initialized and validated.

***2️⃣ Data Loading & Exploration***

Loaded CSV file into a Spark DataFrame

Displayed schema and descriptive statistics

***3️⃣ Data Manipulation***

Column selection

Filtering conditions (>, BETWEEN, logical conditions)

Feature understanding and preparation

***4️⃣ Spark SQL***

Created temporary SQL table

Executed SQL queries including:

Counting distinct species

Counting frequency of each species

### 🤖 Machine Learning — Spark MLlib
***🔧 Data Preparation***

Encoded variety label

Feature vector assembly

Train-Test split

***📊 Model Accuracy Results***
| Model                | Accuracy |
| -------------------- | -------- |
| Naïve Bayes          | **100%** |
| Decision Tree        | **100%** |
| Random Forest        | **96%**  |
| Neural Network (MLP) | **96%**  |

***🧠 Model Insights***

Naïve Bayes & Decision Tree

Achieved 100% accuracy

Strong classification performance

Random Forest

96%

Excellent balance between robustness and precision

MLP (Neural Network)

96%

Slightly lower but still strong performance
