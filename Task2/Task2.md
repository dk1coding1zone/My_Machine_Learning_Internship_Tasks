# Task2 :

### 1. List of critical parameters for the target variable. Why they are important?

After analyzing the trained Random Forest Classifier model, the following parameters were found to be critical for predicting the claim status:

                     Feature      		Importance
3                         Age         		    0.357909
0                    Duration     		        0.326140
1                   Net Sales     	          0.123239
2        Commision (in value)                 0.122734
127                  Gender_M   	            0.008149

a. Duration: The duration of the travel insurance policy is an important parameter as it can affect the likelihood of filing a claim. Longer durations may increase the chances of encountering unforeseen circumstances, leading to a higher probability of making a claim.

b. Net Sales: The net sales amount represents the total revenue generated from the travel insurance policy. Higher net sales could indicate a more comprehensive coverage plan, which may impact the probability of filing a claim.

c. Age: The age of the insured person is a crucial factor as it can influence the risk profile. Different age groups may have varying probabilities of making a claim based on their travel habits, health conditions, and risk tolerance.

d. Commision (in value): The commission earned by the insurance agent or company for selling the policy can indirectly reflect the complexity or coverage level of the insurance plan. Higher commission values might indicate more extensive coverage, potentially affecting the claim status.

These parameters are important because they provide insights into the insured person's characteristics, policy details, and travel duration, which can significantly impact the probability of claiming insurance. By considering these critical parameters, insurance providers can better assess the risk associated with a policyholder and make informed decisions.

### 2. Conclusion/s of the project:

The project aimed to analyze a travel insurance dataset and build a model to predict the claim status. The Random Forest Classifier model was employed to achieve this task. Here are the conclusions drawn from the project:

**The critical parameters for predicting the claim status were identified as duration, net sales, age, and commission (in value). These parameters were found to have a significant impact on the likelihood of filing a claim and provide valuable insights for insurance providers.**

**The Random Forest Classifier model demonstrated its effectiveness in predicting the claim status based on the selected features. The model achieved a certain level of accuracy, which can be further optimized through parameter tuning and exploring different machine learning algorithms.**

**The project highlights the importance of data preprocessing steps such as handling missing values, encoding categorical variables, and feature selection to ensure the quality and relevance of the input data for modeling.**

**The project's findings can be leveraged by insurance companies to assess the risk associated with travel insurance policies, streamline the claim process, and make informed decisions about policy approval and premium calculation.**

