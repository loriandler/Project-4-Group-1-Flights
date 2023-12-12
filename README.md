# Flight Cancellation Prediction Project

## Project Overview

This project aims to develop and train a machine learning model to predict flight cancellations in the United States. The dataset used for this project spans the years 2022 and 2023 and is sourced from [Kaggle](https://www.kaggle.com/datasets/patrickzel/flight-delay-and-cancellation-dataset-2019-2023). Due to the large file sizes, the dataset files are not included in this repository. You can access the dataset [here](https://www.kaggle.com/datasets/patrickzel/flight-delay-and-cancellation-dataset-2019-2023).

## Data Source

The project relies on the following dataset files:

- [2022.csv](https://www.kaggle.com/datasets/patrickzel/flight-delay-and-cancellation-dataset-2019-2023)
- [2023.csv](https://www.kaggle.com/datasets/patrickzel/flight-delay-and-cancellation-dataset-2019-2023)

To merge and process the data, we referred to the [GeeksforGeeks guide on merging two PySpark DataFrames](https://www.geeksforgeeks.org/merge-two-dataframes-in-pyspark/).

## Cleaning and Loading

### Data Cleaning

The project includes data cleaning steps, addressing null or NaN values, and merging data from different years into a consolidated DataFrame.

### Machine Learning

For the machine learning model, we adopted a supervised learning approach, leveraging the fact that we had labeled data indicating whether flights were canceled.

## Analysis

### Overview

Here are some initial insights derived from the analysis:

- **Cancellation Frequency:** Analyzed the overall frequency of flight cancellations to understand the distribution.

- **Correlation Analysis:** Explored correlations between different features and the likelihood of flight cancellations.

- **Time Analysis:** Investigated whether there are specific times of the day, days of the week, or months with higher cancellation rates.

### Future Work

- **Model Optimization:** Document the optimization process, including iterative changes made to the model and their impact on performance. Consider using tools like MLflow to track parameters and metrics during training.

- **Visualization:** Enhance the project with visualizations to better understand data patterns, model predictions, and evaluation metrics.

- **Explainability:** Consider techniques like SHAP values for explaining model predictions, adding transparency to the decision-making process.

- **Scaling:** Assess the scalability of the solution, especially if the dataset grows significantly. Ensure the code and model perform efficiently.


## Acknowldgements:

### Thank you to everyone that helped us out on this project.
- Tutor:
  - Limei Hou
- TA's:
  - Randy & Sam
- Instructor:
  - Hunter Hollis
