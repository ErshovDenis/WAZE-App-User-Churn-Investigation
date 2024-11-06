# WAZE-App-User-Churn-Investigation
Project devoted to the investigation of the WAZE app user churn.

This project is the combination of 5 sub-projects, which were concluding each course of Google Advanced Data Analytics program to demonstrate specifically the skills acquired within a given course. Each sub-project contained main steps given by the course creator to make it easier for the learner to navigate within the complex data and speed up the analysis/modeling.

Project Overview: The dataset summarizing the behavior of every user of the navigation app WAZE was used for the project. It included about 15 thousand rows (one row per user) with the key characteristics describing the user's behavior. This data was a basis for the detailed exploratory data analysis, data cleaning, visualisation, two-sample hypothesis testing, as well as modelling (both regression and machine learning). The resulting were not able to predict with the high recall-score a possible user churn.

Business Understanding: The company WAZE is trying to analyze how to keep the app users as engaged as possible and to avoid their churn (deletion of the app or long-term stop of usage), thus gaining more users and increasing the business. Data analysis of the existing user database is crucial to predict the potential churns and take some actions to avoid them.

Data Understanding: The dataset contained about 15 thousand rows. 700 rows had no label values of whether the user churned or not. Therefore, these rows were removed for training the models. The dataset contained many valuable characterstics to describe how the user behaves, how much he/she drives, how many times opens the app within the month and many more. The finals models has shown that despite the complexity of the dataset, it is not sufficient to answer the main question if the user would churn or not.

Modelling and Evaluation: For the hypothesis testing, the number of drives per device type was analysed; t-test has shown that there is not a statistically significant difference in mean number of rides per device type (iPhone vs. Android). Regression modelling for the churn predictions has resulted in poor results, which cannot be used for major decision of the strategy creation on how to keep the users engaged. Even though ML models (XGBoost and Random Forest) were found to be better than the regression model, they are still of a low quality and thus cannot be used for the important financial decisions, however, ML model - XGBoost can grant some insights on which features affect the most the user churn of the WAZE app (see below):

![image](https://github.com/user-attachments/assets/b530fe23-dbef-4f02-89bb-0037a7b5699a)

Conclusion: The analysis and modelling have shown that the available data is definitely not sufficient for precise modelling of the user churn. There can be several reasons behind: data has no predictive power, dataset is not sufficiently big, dataset does not have enough features which may have result in a more accurate model. Recommendation for stakeholders: do not user the data for any financial decisions; make the second iteration of the project with more data.
