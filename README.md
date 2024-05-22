Task 2 Respiratory Model

1. APPROACH TO FIND DATASET:
 I used the Medical Data Repositories website called PhysioNet and Kaggle and found the required Datasets with sufficient rows in PhysioNet.
 Link to the website: https://physionet.org/

2. Data Preprocessing
Steps:
- **Cleaning:** Removed rows with missing values to ensure data quality.
- **Feature Engineering:** Created new features based on domain knowledge.
- **Normalization:** Standardized numerical features for better model performance.
- **Encoding:** Converted categorical variables like Sex(M/F) into numerical format using one-hot encoding.
-  I HAVE ATTACHED THE CODE I HAVE USED FOR THIS (Data_Processing.ipynb)

3. HOW TO RUN MY CODE
  download the Model_Building file into your system and execute it in colab or on your cmd. The combined_first_rows.csv file is the processed final dataset.
  Ensure the datset is in the same directory as your executing code. The model along with dataset has been attached in my repo.

4.SCREENSHOTS ,FLOWCHART OF MODEL

 ![image](https://github.com/atrytone7Cytheria/TASK-2-PCLUB_Secy_Recruitment/assets/142889877/eca971a4-80bd-41fb-93a4-4e66cbbbbc1d)
 ![image](https://github.com/atrytone7Cytheria/TASK-2-PCLUB_Secy_Recruitment/assets/142889877/0462b593-79dd-4d09-b9a6-0757913ec416)
 ![image](https://github.com/atrytone7Cytheria/TASK-2-PCLUB_Secy_Recruitment/assets/142889877/3f1e2802-974b-4eed-a60a-60cb581bf2d9)


5. ROAD BLOCKS AND PERSONAL EXPERIENCE
   To tackle the task of predicting lung tidal volume, my approach began with a comprehensive search for a suitable dataset.
   This involved scouring various medical databases, research papers, and online repositories to find a dataset containing relevant features
   such as age, gender, height, and symptoms related to lung function. However, I encountered the challenge of data insufficiency, as it was
   difficult to find a dataset with a sufficient number of samples and all the necessary features.
   To overcome this hurdle, I employed several strategies. First, I explored data augmentation techniques to artificially increase the dataset's
   size by generating synthetic data points based on existing samples. This approach helped to diversify the dataset and improve the model's robustness.
   Additionally, I performed extensive feature engineering to extract valuable insights from the available data.
   By creating new features based on domain knowledge and medical literature, I aimed to capture additional information that could influence lung tidal volume prediction.
   Once I curated and preprocessed the dataset, I moved on to model selection and training.
   I experimented with various machine learning algorithms, including Linear Regression, Decision Trees, and Random Forests, to identify the most suitable model for the task.
   However, I encountered challenges related to model overfitting and feature selection. Models were initially prone to overfitting due to the complexity of
   the dataset and insufficient regularization. To address this, I employed techniques such as cross-validation, early stopping, and regularization to prevent overfitting and improve model generalization.
   Furthermore, feature selection posed another roadblock, as identifying the most relevant features that significantly impact lung tidal volume prediction was challenging.
   To tackle this issue, I leveraged domain knowledge, statistical analysis, and feature importance techniques to select the most informative features and discard irrelevant ones.
   Additionally, I explored ensemble learning techniques such as bagging and boosting to combine multiple models' predictions and improve overall accuracy.
   Throughout the process, I prioritized model interpretability to gain insights into the factors influencing lung tidal volume. 
 



 
