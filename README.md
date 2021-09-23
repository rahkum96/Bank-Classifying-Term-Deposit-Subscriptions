# Bank-Classifying-Term-Deposit-Subscriptions
The classification goal is to predict whether the client will subscribe (1/0) to a term deposit (variable y).
# Data set Link:
https://www.kaggle.com/gowthamchowdry/bank-classifying-term-deposit-subscriptions

## Approach:
1) Data import 
2) Exploratory Data Analysis
3) Feature Enineering
4) Features selection: Used correlation, Anova, Chi2, Features_importance
5) Build the model and predict on test data
6) Error plot

#### EDA
- What proportion( percent ) of potential clients accepted to suscribe to term deposits vs. refused to suscribe to term deposits are the questions to be answered.
- Is there a significant difference between clients who subscribe to term deposits and those who are denied deposits?

#### Summary:
- 52.6 percent said they would not subscribe to term deposits, while 47.4 percent said they would. Our labels are dispersed rather evenly.
- May was the month with the most marketing activity (25.3 percent), while December had the least marketing activity (0.985 percent ).
- During the month of May, there is a significant difference between rejected and accepted term deposit subscriptions. (See the Plot of Distribution)
- May had the highest amount of activity, but the lowest ratio (negative), indicating that there were more rejected term deposit subscription requests than accepted requests.
- Despite the fact that the largest ratios were in March, September, October, and December, marketing activity (requested offers from the marketing department) was               substantially lower.
- The majority of the bank's potential clientele are between the ages of 30 and 35.
- Clients in their twenties and thirties: Approximately 60% of potential clients in this age group subscribed to term deposit suscriptions.
- 30s - 50s: Term deposit accounts were subscribed to by around 40% of potential clients in this age group.
- Term deposits for those in their 60s and older are around 76 percent subscribed!
- The population segments with the youngest and oldest members were the most likely to open a term deposit account.
-Management, blue-collar employees, and technicians received the most term deposit subscription proposals from the marketing department.
- The marketing department made the fewest offers to students, entrepreneurs, and housemaids.
- 74.7 percent of students signed up for term deposits (Which was expected since the youngest segment of the population is most likely to be a student)
- 66.3 percent of pensioners were inclined to subscribe to term deposits (This was also expected since the oldest segment of the population is most likely to be retirees).
