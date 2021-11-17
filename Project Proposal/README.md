# **Online Shoppers Intention Analysis**


### **Abstract:**

The goal of this project is to use classification models to analyze the Customer's Intentions based on the transactions, duration made online in a year , And to create a model that can predict the purchasing intentions of customers.

### **Design:**

This project is one of the T5 Data Science BootCamp requirements. Data obtained from Kaggle website. [Source](https://www.kaggle.com/henrysue/online-shoppers-intention)

### **Data:**

The dataset obtained from Kaggle website. This data set consists of 18 features belonging to 12,330 shopping sessions.The 'Revenue' attribute is the target feature.There are no missing values.

### **Algorithms:**

#### **Feature Engineering:**

1. Converting categorical attributes to ordered factor variables and are numerically encoded.
2. Normalize numerical variables of the dataset for clustering and scale for classification methods.


### **Models Used:**
Logistic Regression.
KNeighbors Classifier
Decision Tree 
Gradient Boosting
Naive Bayes 
Random Forest
**Hyperparameters used:**
GridSearchCV and RandomizedSearchCV


### **Tools:**

1. Numpy and Pandas for data manipulation.
2. Scikit-learn for modeling.
3. Matplotlib and Seaborn for plotting.
