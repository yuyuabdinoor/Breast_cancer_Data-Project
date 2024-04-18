Welcome to my GitHub repository on Using Predictive Analytics model to diagnose breast cancer.
Objective:
The repository is a learning exercise to:
    • Apply the fundamental concepts of machine learning from an available dataset
    • Evaluate and interpret my results and justify my interpretation based on observed data set
    • Create notebooks that serve as computational records and document my thought process. 
The analysis is divided into four sections, saved in juypter notebooks in this repository
    1. Identifying the problem  and Data Sources
    2. Exploratory Data Analysis
    3. Pre-Processing the Data
    4. Build model to predict whether breast cell tissue is  malignant or Benign
File 1: Identifying the problem and Use external data sources for data enrichment. Identify the types of information contained in our data set
In this notebook I used Python modules to import external data sets for the purpose of getting to know/familiarize myself with the data to get a good grasp of the data and think about how to handle the data in different ways. 
File 2: Exploratory Data Analysis.Explore the variables to assess how they relate to the response variable 
In this notebook, I am getting familiar with the data using data exploration and visualization techniques using python libraries (Pandas, matplotlib, seaborn. Familiarity with the data is important which will provide useful knowledge for data pre-processing)
File 3: Pre-Processing the data.Find the most predictive features of the data and filter it so it will enhance the predictive power of the analytics model
In this notebook I use feature selection to reduce high-dimension data, feature extraction and transformation for dimensionality reduction. This is essential in preparing the data before predictive models are developed.
File 4: Predictive model using Support Vector Machine (SVC).Construct predictive models to predict the diagnosis of a breast tumor 
In this notebook, I construct a predictive model using SVM machine learning algorithm to predict the diagnosis of a breast tumor. The diagnosis of a breast tumor is a binary variable (benign or malignant). I also evaluate the model using confusion matrix the receiver operating curves (ROC), which are essential in assessing and interpreting the fitted model. 
Notebook 1: Identifying the problem and Use external data sources for data enrichment.
Notebook goal: Identify the types of information contained in our data set
Identify the problem
Breast cancer is the most common malignancy among women, accounting for nearly 1 in 3 cancers diagnosed among women in the United States, and it is the second leading cause of cancer death among women. Breast Cancer occurs as a results of abnormal growth of cells in the breast tissue, commonly referred to as a Tumor. A tumor does not mean cancer - tumors can be benign (not cancerous), pre-malignant (pre-cancerous), or malignant (cancerous). Tests such as MRI, mammogram, ultrasound and biopsy are commonly used to diagnose breast cancer performed. 
Expected outcome
Given breast cancer results from breast fine needle aspiration (FNA) test (is a quick and simple procedure to perform, which removes some fluid or cells from a breast lesion or cyst (a lump, sore or swelling) with a fine needle similar to a blood sample needle). Since this build a model that can classify a breast cancer tumor using two training classification:
1= Malignant (Cancerous) - Present
0= Benign (Not Cancerous) -Absent
Objective 
Since the labels in the data are discrete, the predication falls into two categories, (i.e. Malignant or benign). In machine learning this is a classification problem. Thus, the goal is to classify whether the breast cancer is benign or malignant and predict the recurrence and non-recurrence of malignant cases after a certain period.  To achieve this we have used machine learning classification methods to fit a function that can predict the discrete class of new input
 ML Classification Method applied:
SVM - Support Vector Machine” (SVM) is a supervised machine learning algorithm which can be used for both classification and regression analysis. It segregates two classes using a hyper plane.
Identify data sources
The Breast Cancer datasets is available machine learning repository maintained by the University of California, Irvine. 
NB_2 Getting Started: 
    1- Load libraries and set options  – Import necessary libraries and offer explanation on each
    2- Obtaining Data- Data Set
The next step is to use the UCI Machine Learning Repository to load the Breast Cancer dataset that had 14 attributes and 48,842 instances with which to build a model. The hypothesis is that it is possible predict the recurrence and non-recurrence of malignant cases after a certain period, based upon breast cancer tumor attributes is benign or malignant. The suggested task is to build a binary classifier that can determine from the Breast Cancer dataset information whether or not a tumor is benign or malignant. .



























