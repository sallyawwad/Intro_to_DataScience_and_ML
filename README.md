# Analysis of Arrest Records 🐦

This project analyzes arrest records, detailing information such as the date and time of the arrest, the arrestee's personal information, the statute they were arrested under, and demographic information. The dataset provides a comprehensive analysis of arrest trends, potentially revealing insights into the criminal justice system and social factors influencing arrests.

# Dataset Source

The dataset used in this project is sourced from  [data.gov](https://data.gov/).

# Project Structure
## Load Dataset 💻

The project involves working with two datasets: the original dataset and an updated one. The updated dataset is utilized after the API part of the code.

## Summary Statistics

This section provides summary statistics of the dataset, offering a snapshot of the data's key characteristics.

## Data Transformation

The data undergoes several transformations to prepare it for analysis, ensuring that it is in a format suitable for the intended analysis.

## visualisation 
### Word Cloud:
![Word Cloud](https://github.com/user-attachments/assets/bc0fbf4e-ec83-4e6a-b7af-c60c3b9eb21f)

### summary:
![Top 5 Most Common Crimes](https://github.com/user-attachments/assets/250ecdbb-fa4d-4e5e-88c2-1f977b3f50ce)
![Distribution of Most Common Crimes Among Top 5 Repeat Offenders](https://github.com/user-attachments/assets/0a279c9e-0d8e-4696-a672-3de09e5364c1)
![Top 10 Street Frequency Count](https://github.com/user-attachments/assets/6cb98af6-0e1c-4bd7-811e-16f8ac3ef9b9)

### Time Series:
![Daily Arrests Over Time with Rolling Average](https://github.com/user-attachments/assets/183ba72d-51e6-4b82-ad97-58f6c3889539)

### Maping:
![Map1](https://github.com/user-attachments/assets/00a8bb0a-82e3-452f-9c57-967ceeb54a70)

## Modeling:
Tow **Logistic Regression** models, first used to predict the race of an individual based on various features related to their arrest. Here’s a detailed breakdown. Second used to predict the street name (Street) where an arrest occurs, based on various categorical features related to the individuals involved in the arrests. The goal is to understand how well certain attributes can predict the specific location of an arrest.

One **Random Forest Regressor** used to predict the number of crimes that occur on a particular street, based on several features extracted from arrest data.
![Actual vs  Predicted Crime Counts(Model 2)](https://github.com/user-attachments/assets/c2f74c34-857f-43be-9f99-eb6f5d296711)
![Map2](https://github.com/user-attachments/assets/39adc8d8-baad-42e6-88b4-7edcb43120b5)

One **Clustering techniques** (K-means and DBSCAN) to group arrest data based on geographical and temporal features. The purpose of clustering is to identify patterns or groupings in the data that might not be obvious, such as hotspots for crime or trends in certain areas.
![K-means Clusters](https://github.com/user-attachments/assets/e26e4bde-aeb3-4145-92e4-319ded8d97db)
![DBSCAN Clusters](https://github.com/user-attachments/assets/0139ae6f-5dcf-4d6b-87a2-bc79d96c7583)

# Setup Instructions
To set up this project on your local machine, you need to install the following dependencies:

`pip install pandas matplotlib seaborn plotly folium`
`pip install wordcloud`
`pip install scikit-learn`
`pip install branca`



# Usage

To run the analysis, simply execute the cells in the Jupyter notebook. The notebook is structured to guide you through loading the dataset, generating summary statistics, and performing data transformations.
