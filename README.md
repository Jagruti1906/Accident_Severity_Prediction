# Accident_Severity_Prediction

Accident severity prediction is a crucial field that can help prevent accidents and minimize their impact by providing early warning to drivers, emergency responders, and other stakeholders. By using data and statistical methods, accident severity prediction models can accurately forecast the likelihood and severity of accidents and help stakeholders make informed decisions that can save lives and reduce the cost of accidents. With the potential benefits of machine learning techniques, this field will likely continue to evolve and contribute to improving road safety and saving lives.

### Methodology ###

1. Data Collection
2. Data Preprocessing
3. Model Development
4. Model Evaluation

### Dataset Description ###

This dataset covers car accidents all over the USA, including 49 states, from February 2016 to December 2021. The data is collected from sources like cameras, sensors, and user reports. It has details about where and how severe accidents are, including factors like weather and nearby locations. Features include accident times, severity, location (latitude, longitude), weather, distance to points of interest, and more.
The link of our dataset is: https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents

### Exploratory Data Analysis ###

![1](https://github.com/Jagruti1906/Accident_Severity_Prediction/assets/50952018/be06dd79-50e4-4b5e-8aaf-5f3b6c18b6a5)
![2](https://github.com/Jagruti1906/Accident_Severity_Prediction/assets/50952018/886cf131-10c5-4600-b037-f65940f2e8d3)
![3](https://github.com/Jagruti1906/Accident_Severity_Prediction/assets/50952018/13de643f-b1f0-4ff4-bca8-d1f9fd47c6bf)

### Algorithms with their accuracy ###

* Splitting the dataset into train and test
  ![4](https://github.com/Jagruti1906/Accident_Severity_Prediction/assets/50952018/6256d5ee-0306-4d8e-881f-f3f323e93c72)

1. Logistic Regression: Logistic regression is a statistical model that is used to predict the probability of a binary outcome (i.e., one that takes only two possible values, such as "yes" or "no") based on one or more predictor variables. It is a type of regression analysis that is commonly used in various fields, including medicine, social sciences, and business, for predicting binary outcomes such as disease diagnosis, customer churn, and loan default. The model works by estimating the coefficients of the predictor variables to predict the log odds of the outcome, which are then converted into probabilities using a logistic function.
 ![6](https://github.com/Jagruti1906/Accident_Severity_Prediction/assets/50952018/5d9efef5-12a0-437c-bfe3-a230c9970602)

2. Decision Trees: Decision Tree algorithm belongs to the family of supervised learning algorithms. Unlike other supervised learning algorithms, the decision tree algorithm can be used for solving regression and classification problems too. The goal of using a Decision Tree is to create a training model that can be used to predict the class or value of the target variable by learning simple decision rules inferred from prior data (training data). In Decision Trees, for predicting a class label for a record we start from the root of the tree. We compare the values of the root attribute with the record’s attribute. Based on comparison, we follow the branch corresponding to that value and jump to the next node.
![7](https://github.com/Jagruti1906/Accident_Severity_Prediction/assets/50952018/6ad59bfd-ad75-47c4-9e04-e3a441f66e34)

3. Random Forest A random forest system relies on various decision trees. Every decision tree consists of decision nodes, leaf nodes, and a root node. The leaf node of each tree is the final output produced by that specific decision tree. The selection of the final output follows the majority-voting system. In this case, the output chosen by most of the decision trees becomes the final output of the rain forest system.
![8](https://github.com/Jagruti1906/Accident_Severity_Prediction/assets/50952018/c5783810-30d8-440b-b151-7c211fc2a586)

### Conclusion ###

This project aimed to predict how bad accidents are using computer models. We tested different models like random forest, decision trees, and logistic regression. It involved several steps including data loading, pre-processing, visualization, feature reduction, and model development. The results show that these models can predict accident severity well, with random forest being the best. We also learned which parts of data matter the most. This can help make better rules to prevent bad accidents. Overall, this project shows how models can guess accident severity and reminds us to prepare data carefully for the best results.




