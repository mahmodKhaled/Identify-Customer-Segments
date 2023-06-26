# Identify-Customer-Segments

## Project Overview

In this project, I will apply unsupervised learning techniques on demographic and spending data for a sample of German households. I will preprocess the data, apply dimensionality reduction techniques, and implement clustering algorithms to segment customers with the goal of optimizing customer outreach for a mail order company.

## Datasets Descriptions

There are four data files associated with this project:

- `Udacity_AZDIAS_Subset.csv`: Demographics data for the general population of Germany; 891211 persons (rows) x 85 features (columns).
- `Udacity_CUSTOMERS_Subset.csv`: Demographics data for customers of a mail-order company; 191652 persons (rows) x 85 features (columns).
- `Data_Dictionary.md`: Detailed information file about the features in the provided datasets.
- `AZDIAS_Feature_Summary.csv`: Summary of feature attributes for demographics data; 85 features (rows) x 4 columns

## Project Instructions

### Step 1: Preprocessing

In this step, I will load in the demographics data, assess missing data, and clean the dataset for analysis.

### Step 2: Feature Transformation

In this step, I will perform feature scaling on the cleaned dataset.

### Step 3: Dimensionality Reduction

In this step, I will apply principal component analysis to identify the relationships between variables in the dataset, and then use those components to identify the areas of largest variability in the dataset.

### Step 4: Clustering

In this step, I will apply clustering techniques to identify groups in the general population that form the core customer base for the company. I will then apply the same clustering model to the customer dataset to see how market segments differ between the general and customer populations.

### Step 5: Compare Customer Data to Demographics Data

In this step, I will compare the distribution of people by cluster for the customer data to the distribution by cluster in the general population.

## Conclusion

![Screenshot 2023-06-26 174912](https://github.com/mahmodKhaled/Identify-Customer-Segments/assets/54672453/a259f9a4-e41f-4c35-a3b1-f4373291b7bd)


From the anaylsis above, it can be seen that

**Cluster 5** is overrepresented in the customers data compared to general population data. Some characteristics of the group of population that are relative popular with the mail-order company:

- in areas where gender is male (ANREDE_KZ = 0.941486).
- in areas where Neighborhood quality is average neighborhood (WOHNLAGE =  2.992780).
- in areas where Small office / home office flag is no small office/home office (SOHO_KZ = 0.009234)

**Cluster 26** is underrepresented in the customers data. Some characteristics of the segment of the population that are relatively unpopular with the company:

- in areas where gender is female (ANREDE_KZ = 0.958381).
- in areas where Insurance typology is individualistic-accepting risks (VERS_TYP = 1.527328).
- in areas where Neighborhood quality is poor neighborhood (WOHNLAGE =  3.669332).
