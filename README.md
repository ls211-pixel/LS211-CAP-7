# Heart Failure Prediction using Machine Learning

## Introduction

In this era or generation, we observe that many people are experiencing various health issues, one of the most critical being **Heart Failure** — including **Cardiovascular Diseases (CVDs)**. These conditions can lead to fatal outcomes at any stage of life. Heart failure diseases are prevalent across the globe, making it essential to find effective solutions.

To address this issue, various medical techniques and methods are being utilized. In addition, advancements in **computer technology** — including **Machine Learning (ML)**, **Deep Learning (DL)**, and other computational methods — have shown great promise in tackling heart failure problems.

Our research focuses on leveraging these technologies, looking into previous studies, research papers, and methodologies developed by experts in the field. Furthermore, we analyze patient data to identify the angles and factors at which individuals are most affected by CVDs. **Machine Learning** emerges as a powerful tool for predicting heart failure with high accuracy and speed, making it a critical asset in modern medical research.

This research also explores how **Machine Learning** and **Deep Learning algorithms** can be applied to CVDs, offering innovative approaches to combat heart failure. Training and learning from these algorithms allow us to create effective strategies, not only for heart disease prevention but also for future medical innovations and AI developments aimed at saving lives and advancing healthcare.

In the current medical landscape, several models and methods are utilized, such as:

- **Neural Networks (NN)**
- **Random Forests (RF)**
- **Decision Tree Models**
- **Logistic in Regression (LR)**
- **K-Nearest Neighbors (KNN)**


These models play a crucial role in accurately predicting heart failure.

According to the **World Health Organization (WHO)**, approximately **18.9 million people** are affected by CVDs globally. Alarmingly, **33% of deaths** are caused by cardiovascular diseases, and among these, **75% of cases** are directly related to heart conditions. The primary causes include **hypertension**, **low blood pressure (BP)**, and various infections.

The most effective approach lies in using **Machine Learning** to detect complex datasets, medical algorithms, hidden patterns, and underlying logic related to heart failure. Ultimately, this research highlights how **Machine Learning** can significantly reduce mortality rates by predicting heart illness early. It also showcases the vast potential of AI and ML in identifying and combating heart diseases, driving innovation and saving countless lives.

## Pictures

<img width="551" alt="image" src="https://github.com/user-attachments/assets/64e66b8e-80cd-46f2-816b-b69d44b7a129" />


## Mathematical or Statistical Methods

NAIVE BAYES:

Naïve bayes is a guided learning method that can solve any kind of classification models by applying the probability of the bayes theorem.This model is only trained for only and especially for the large and big data sets or the algorithms but coming to this method it will not correlated with one to another.
Its useful for the feature engineering.
This theorem also predicts based on the patient condition is he or she having good cholestral or any illness it shows very fast.
## Bayes' Theorem


In this project, **Bayes' Theorem** is applied to know the probability of heart failure based on the data. The theorem is represented by the following formula:

\[
P(b \mid a) = \fra{P(y \mid a) \timees P(y)}{P(a)}
\]

so,
- \( P(y \mid a) \): Is should be probability of heart failure occurring given the data \( a \)
- \( P(a \mid b) \): Is should be the probability of observing the data \( a \) if heart failure has occurred
- \( P(b) \):  Is should be The prior probability of heart failure happening
- \( P(a) \): The overall probability of the data \( a \) being observed

## Logistic Regression:
Methods like Machine learning and deep learning in that logistic regression is the model which can solve the classification problems this also is based on the probability. This model computes the logarithm of risks after converting probability to risks. 
Hence here is the mathematical form,
## Logistic Regression Formula

In our study, we model the association between patient data and the likelihood of heart failure using **Logistic Regression**. The formula can be written as follows:

\[
\log\left(\frac{q_i}{1 - q_i}\right) = \beta_0 + \beta_1 Y_{i1} + \beta_2 Y_{i2} + \dots + \beta_m Y_{im}
\]

Where:
- \( q_i \): The probability of heart failure for the \( i \)-th patient
- \( \beta_0 \): The intercept term
- \( \beta_1, \beta_2, \dots, \beta_m \): Coefficients representing the effect of each predictor variable
- \( Y_{i1}, Y_{i2}, \dots, Y_{ik} \): Predictor variables (such as age, blood pressure, cholesterol level, etc.) for the \( i \)-th patient

  Its also converts any maximum value to zero to one by using a sigma function.This function is seems to be in S shaped curve.

The **log-odds** of heart failure are on the left side of the equation, whereas a linear combination of the predictors is on the right. This model aids in our comprehension of the ways in which different factors influence the risk of heart failure.

## Random Forest 

Ensemble learning which uses multiple classifiers to solve a single task and enhance the model accuracy is based on the Random Forest classifier. It combines a number of decision trees to the input data and sums up the results to smooth out the errors. 
In contrast to a single decision tree, random forest requests forecast from every tree and makes prediction based on the majority vote of the projections. There is less overfitting and the number of trees boosts the accuracy.

Let's we can say the  model RP, the input  , and the goal variable Y.
Given decision of forest is N, the predicted of R⁢P can be expressed as here is:

RP(y)=MODE(Tree(y),Tree2(y),....,TreeN(y))

## Decision Tree
This method decision tree is used for heart failure prediction moreover its also a machine learning model it supposed be like tree like structure either the patient is having a heart disease on their previous data.This model is so helpful due to its interpreability which can handle both numerical and categorical data.

Moreover for this method risk factors are very high.Apart from that there accuracy rate is more than 90% which is so unique in all the classification methods.
Each of the one algorithm splits into the subsets based on their dataset of their attributes,every node will be pointed a decision point based on thier attributes.
This attributes chooses to split the one at each node on thier metrics like "Gini" this separates the either the patient having heart disease or no heart disease.
This model is very easy to understand when its compared to the other model.

Here is the flow chart of decision tree model :

<img width="314" alt="image" src="https://github.com/user-attachments/assets/b0d74c42-2633-45db-914c-8537924664d8" />

So,here we can say these are Methods that is used for Heart failure prediction by using Machine learning Methods.Without these we can unable to find the data or patients list either they are having CVDs diseases like heart failure....






---

