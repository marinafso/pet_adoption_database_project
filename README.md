# pet_adoption_database_project

INTRODUCTION 

This project explores data from the “Pet Adoption Records with Animal & Adopter Data” dataset by @Sanika Chaudhari, which includes detailed information about pets available for adoption and the people who adopt them.

STRUCTURE

* Data Cleaning and Preparation: The raw dataset was reviewed and cleaned to ensure consistency and accuracy. This included handling missing values, standardizing categories (such as date values, and gender), and preparing the data for analysis and modeling.
* Dashboard Development: After preparing the data, a Looker Studio dashboard was created to provide a visual summary of the adoption center’s pet profiles. It highlights key metrics such as the distribution of animal types, colors, genders, and adoption status, allowing for quick and interactive exploration.
* Exploratory Data Analysis: With the help of SQL queries, we analyzed patterns and relationships between animal characteristics and adopter information. This step helped identify trends and potential factors that may affect the likelihood of adoption.
* Predictive Modeling: A machine learning model was built to estimate the probability that an animal will be adopted, based on its characteristics.

LIBRARIES

# base
os
pandas
numpy

# import
kagglehub: KaggleDatasetAdapter

# visual
matplotlib
seaborn
IPython.display

# statistical
sklearn
graphviz

# data conversion
datetime
gender-guesser
