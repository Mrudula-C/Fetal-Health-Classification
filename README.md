**Overview**

This project focuses on the classification of fetal health conditions using machine learning algorithms. The objective is to develop a predictive model that can accurately classify the health state of a fetus based on various features extracted from cardiotocographic (CTG) measurements.

**Dataset**

The dataset used in this project is the Fetal Health Classification dataset, which contains 2126 instances of fetal health data with 21 features. The features include measurements such as baseline value, accelerations, fetal movement, and uterine contractions, among others. The target variable is the fetal health status, categorized as:

Normal
Suspect
Pathological

**Project Structure**

The repository contains the following files:

FetalHealthClassification.ipynb: Jupyter Notebook containing the entire workflow of the project, including data exploration, preprocessing, model training, and evaluation.
README.md: Project overview and documentation (this file).

**Requirements**

To run the code in this repository, you need the following Python libraries:

* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn
* tensorflow
* jupyter

You can install these dependencies using the following command:

  pip install pandas numpy matplotlib seaborn scikit-learn tensorflow jupyter

**Usage**

1. Clone the repository:

     git clone https://github.com/your-username/FetalHealthClassification.git

2. Navigate to the project directory:

     cd FetalHealthClassification

3. Launch Jupyter Notebook:

     jupyter notebook

4. Open the FetalHealthClassification.ipynb notebook and run the cells to execute the code

**Methodology**

The project follows these main steps:

  **Data Exploration:**
  
    Inspecting the dataset
    Visualizing the distribution of features
    Checking for missing values
    
  **Data Preprocessing:**
    
    Normalizing feature values
    Splitting the data into training and testing sets
    
  **Modeling:**
    
    Training machine learning models (e.g., Decision Trees, Random Forest, Support Vector Machine, Neural Networks)
    Hyperparameter tuning using GridSearchCV
    
  **Evaluation:**
    
    Assessing model performance using accuracy, precision, recall, and F1-score
    Plotting confusion matrices

**Results**

The results of the trained models, including their performance metrics and confusion matrices, are presented in the notebook. The best performing model is identified and its parameters are discussed.

**Contributing**

Contributions to this project are welcome. If you have any suggestions or improvements, please create an issue or submit a pull request.

**Contact**

For any questions or feedback, please contact Mrudula Challagonda
