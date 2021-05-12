# DSO-560-Group-White

**Please run the notebooks in the following order.**

## 1. Clean Data.ipynb
In this notebook, we cleaned the additional tags data and attributes for future features extraction.

This notebook outputs the 'cleaned_tags_for_future_use.csv' file that will be used in later notebooks.


## 2. Create Tags and Features.ipynb
In this notebook, we extracted valuable information from the 'Behold+product+data+04262021.xlsx' and 'usc_additional_tags USC.csv' and performed feature
engineering to help with the classification modeling and recommendation function later.

This notebook outputs the 'all_features.csv' file that will be used in later notebooks.

## 3. Model.ipynb
This notebook contains steps to preprocess the data and the classification model that predicts the brand of a new product.

## 4. Recommendation Feature Creation.ipynb
This notebook contains more feature creation steps for the recommendation function later.

This notebook outputs the 'final_feature.csv' file that will be used in later notebooks.


## 5. Recommendation Function.ipynb
This notebook contains the recommendation function, including a flowchart demonstrating the algorithm of the app (Algorithm.jpeg).

## Other files
### attribute_name2.csv
This file is used for feature engineering in notebook 2. Create Tags and Features.ipynb
