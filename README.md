# Task 3: Decision Tree Classifier for Term Deposit Prediction

Welcome to my GitHub repository for Task 3 of my internship at Prodigy Infotech! In this project, I developed machine learning models to forecast whether customers will subscribe to a term deposit based on their demographic and behavioral data gathered from direct marketing campaigns conducted by a Portuguese banking institution.

## Overview
The primary aim of this project is to build predictive models that can aid banking institutions in identifying clients who are likely to subscribe to term deposits. By effectively targeting potential subscribers, these institutions can enhance their marketing strategies and improve the success rate of their campaigns.

## Dataset
The dataset utilized in this project relates to direct marketing campaigns (specifically phone calls) carried out by a Portuguese bank. It includes various attributes such as customer demographics, past marketing interactions, and the final outcome of the marketing efforts (whether or not the client subscribed to a term deposit).

### Dataset Variables
- **age**: Client's age (Integer)
- **job**: Client's occupation (Categorical: e.g., 'admin.', 'blue-collar', 'student', etc.)
- **marital**: Client's marital status (Categorical: e.g., 'single', 'married', etc.)
- **education**: Client's education level (Categorical: e.g., 'university.degree', 'high.school', etc.)
- **default**: Indicates if the client has credit in default (Binary)
- **balance**: Average yearly balance (in euros)
- **housing**: Indicates if the client has a housing loan (Binary)
- **loan**: Indicates if the client has a personal loan (Binary)
- **contact**: Type of communication used (Categorical: e.g., 'cellular', 'telephone')
- **day_of_week**: Last contact day of the week (Date)
- **month**: Last contact month (Categorical: e.g., 'jan', 'feb', etc.)
- **duration**: Duration of the last contact (in seconds)
- **campaign**: Number of contacts made during this campaign for the client (Numeric)
- **pdays**: Days since the client was last contacted in a previous campaign (Numeric; -1 if not previously contacted)
- **previous**: Number of contacts made before this campaign for the client
- **poutcome**: Outcome of the previous marketing campaign (Categorical: e.g., 'success', 'failure', etc.)
- **y**: Indicates if the client subscribed to a term deposit (Binary)

## Results
The project successfully created decision tree classifiers utilizing both Gini impurity and entropy as criteria. The models demonstrated impressive accuracy in predicting term deposit subscriptions, with the Gini impurity method achieving slightly better performance compared to the entropy method regarding testing accuracy and recall for the positive class.

## Conclusion
This project highlights the efficacy of machine learning models in predicting term deposit subscriptions in the context of direct marketing campaigns. By leveraging predictive analytics, banking institutions can refine their marketing approaches and improve customer engagement.

### Final Insights
- **High Accuracy for Both Criteria**: Both the Gini impurity and entropy methods yielded high training and testing accuracy, with training accuracies near 93.6% and testing accuracies around 93.3% for Gini and 93.2% for entropy.
- **Performance Metrics**: The Gini criterion achieved slightly higher testing accuracy and a better recall rate for the positive class, indicating its effectiveness in identifying true positive instances. Conversely, the entropy criterion resulted in fewer false positives but more false negatives compared to Gini.

## Contact Information
For any questions or feedback related to this project, please feel free to reach out to me:

**Anushka Kadam**  
Email: anushkapkadam@gmail.com
