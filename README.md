
# Black Friday Dataset: Exploratory Data Analysis (EDA) and Feature Engineering

This project delves into **Exploratory Data Analysis (EDA)** and **Feature Engineering** on the Black Friday dataset. As part of my learning journey, I applied fundamental data science techniques, focusing on data cleaning, gaining insights, and preparing the dataset for machine learning model development.

## Project Overview

The Black Friday dataset provides customer purchase information, offering an opportunity to:
- Explore and uncover patterns within the data.
- Engineer meaningful features for predictive modeling.
- Prepare the dataset for machine learning by handling missing values and scaling features.

### Key Steps in the Project

1. **Data Loading and Preprocessing**
   - The dataset was loaded using `pandas`.
   - Missing values were addressed by segmenting rows with missing purchase data into separate test and train sets.
   
2. **Exploratory Data Analysis (EDA)**
   - Performed descriptive statistics to summarize the dataset and gain a better understanding of the variables.
   - Utilized visualizations such as bar charts and histograms to analyze customer demographics, product preferences, and purchase behaviors.
   
3. **Feature Engineering**
   - Removed redundant columns, such as `Product_ID`, that did not add significant predictive power.
   - Introduced new features based on existing ones, such as aggregating customer data by demographic groups.
   - Scaled numerical features using **StandardScaler** to ensure consistency in data for machine learning models.

4. **Train-Test Split**
   - Split the data into training and test sets using `train_test_split` from `sklearn`, with the `Purchase` column as the target variable.
   - All other relevant columns were used as features for predictive modeling.

5. **Feature Scaling**
   - Applied feature scaling to standardize the dataset, which is crucial for models like Logistic Regression, SVMs, and Neural Networks.

### Future Steps
- The dataset is now preprocessed and ready for machine learning model training. The next step involves applying various algorithms to predict customer purchase behavior.

## Libraries and Tools Used

- `pandas` for data manipulation and analysis
- `numpy` for numerical operations
- `matplotlib` and `seaborn` for data visualization
- `scikit-learn` for data preprocessing and splitting

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/Aishjahan/Black-Friday-EDA-and-Feature-Engineering.git

2. Install the required libraries::
   ```bash
   pip install -r requirements.txt
   
3. Open and run the Jupyter notebook to explore the analysis and feature engineering steps:
   ```bash
   jupyter notebook BlackFriday EDA and Feature Engineering.ipynb

