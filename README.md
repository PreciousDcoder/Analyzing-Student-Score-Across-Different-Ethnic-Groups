# Student Score Analysis

# Project Overview
This project is about analyzing students' scores using Python. Various Python libraries were used to analyze this dataset and gain insights into key factors affecting students' scores across various subjects.

# Dataset Overview
The following libraries were imported to work on this project:

![Screenshot 2024-10-22 122001](https://github.com/user-attachments/assets/0d0707dc-e2f4-4542-a838-892f530eec4a)


Various Python methods such as .head, .describe, .info, and .shape were employed to understand the dataset structure

![Screenshot 2024-10-22 122107](https://github.com/user-attachments/assets/bb15924d-fd1f-467e-a810-c1cc2e5e97f8)

# Data Cleaning

- The column Unknow: 0 was dropped.
- -There were no whitespaces in the columns.
- -The column name was updated from 'NrSiblings': 'NumberOfSiblings'
- Missing values were discovered, visualized using missingno, and handled appropriately
- Outliers were discovered and handled using Z-score and IQR

![outliersseen](https://github.com/user-attachments/assets/fa8136bb-bc6c-40d6-b58c-6fd811c4999a)

![Outliers handled](https://github.com/user-attachments/assets/b75a0d10-b5eb-45d4-9e5d-ffb7655acec3)


# Data Transformation

Data was scaled using MinMaxScaler

# Exploratory Data Analysis

The following are the Univariate EDA performed
![Uni analysis](https://github.com/user-attachments/assets/18487473-5296-49d0-916b-8ec9a40c652d)

![Screenshot 2024-10-22 122659](https://github.com/user-attachments/assets/8d4d36ca-a6a5-4962-aae0-6718eb6cafd9)

# Bivariate Analysis


![bar chart](https://github.com/user-attachments/assets/49440180-0dd8-4c45-b33c-118047a38552)


![scatterplot](https://github.com/user-attachments/assets/1f0346c9-315e-43ae-a170-bf9c8dcb88ec)

![HeatMap](https://github.com/user-attachments/assets/c8b6b4b3-ff91-4b5e-8a7e-642b96fb244d)

# Multivariate Analysis

- ANOVA ANALYSIS
![ANOVA ANALYSIS](https://github.com/user-attachments/assets/4ac2f77e-c58e-433a-abb1-a9a726d3c4a9)

- TWO WAY ANOVA ANALYSIS


![TWO WAY ANOVA ANALYSIS](https://github.com/user-attachments/assets/50a97c83-0086-4259-997e-dec44454664a)


![Screenshot 2024-10-22 123108](https://github.com/user-attachments/assets/b20738a3-bfe1-42a4-8521-4ee578026f30)

# FULL PROJECT
You can view full project on: https://colab.research.google.com/drive/1qYWCAABFiBcYjYJfWL_XEyuuUIMBPgkh#scrollTo=vT2nwGBWLXAo

