# BEAT AML ML project

This repo contains all of the Jupyter notebooks for the BEAT AML machine learning project by Ravi Patel. This ReadMe contains some information about the project and what is contained in each of the notebooks.

**Purpose:** The goal here is to do my first ever machine learning project tackling a problem that I really care about. Hopefully this will result in a models that can be used to learn about drug response in AML patients.

**Background:** Acute Myeloid Leukemia (AML) is a devastating type of cancer that I study in my day job as a graduate student at the University of Pittsburgh. AML treatment has remained mostly the same for the majority of patients for nearly 50 years. One of the reasons treatment has not advanced is because AML patients are so diverse that it is very difficult to know which patients are likely to respond to new potential treatments. Recently Tyner et al. published a seminal study in which they tested 122 potential therapies against 363 well-characterized patient biopsies. Those findings were published in Nature and can be found [here](https://www.nature.com/articles/s41586-018-0623-z). If you want to follow along with this notebook you can download the data by going to the 'Supplementary information' section and clicking "Supplementary Tables” link. Alternatively, [this link](https://static-content.springer.com/esm/art%3A10.1038%2Fs41586-018-0623-z/MediaObjects/41586_2018_623_MOESM3_ESM.xlsx) will direct you to the download page. Alternatively, that data is found in the 'All_Data.csv' file in this repo.  Although, the dataset is somewhat small for a machine learning project, I do think this is a unique opportunity to understand which features are predictive of sensitivity to specific drug candidates.

**Main Question: Which features of the tumor are predictive of response to certain drug candidates?**

## What is in these notebooks?
Notebook 1- Contains the cleaning of the datasets and some exploratory data analysis      
Notebook 2- My attempt at making a classifier to identify the responders and non-responders to a particular drug       
Notebook 3- Making a regression model to determine the extent of response to a particular drug, also the interpretation of that model       
Notebook 4- Automating the process of optimizing gradient boosting decision trees for several more drugs. Comparing feature importances from models predicting response to multiple different drugs.     
