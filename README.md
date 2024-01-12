# Fellow-placement-prediction-Pathrise-program
Pathrise is an online program that provides 1-on-1 mentorship, training, and advice to help job seekers get the best possible jobs in tech. 
Every two weeks, Pathrise welcomes a new cohort of fellows. If a candidate is interested in joining the program and successfully passes all stages of admission process, they receive an offer to join Pathrise and become a fellow. 
The first 2 weeks in the program are called a free trial period and a fellow can withdraw within this free trial period without any penalty. After 2 weeks, a fellow needs to sign an ISA (Income Share Agreement) with the pathrise if they want to stay in the program. The entire program lasts up to a year, including 8 weeks of the core curriculum. If a fellow is unable to find a job within a year after joining Pathrise, his/her contract is terminated. However, there might be some exceptions. For instance, if someone was on a break, they may extend their contract for the period of the break. 
On average, for fellows who stay with pathrise after their free trial period, it takes about 4 months to receive a final job offer. However, there is a lot of variation in fellows’ outcomes. Being able to predict how fast every single fellow is going to find a job is crucial for this business. In this exercise pathrise provide you with a sample of information they collected from their fellows from the moment they joined our program. Please don’t expect this data set to be perfect, it never happens in the real world.

**The main goal of this analysis is to derive insights around:
1- if a fellow will ultimately be placed at a company
2- and how long until a placement can be expected.**

> Data collected from Company Database
> The ‘Placed’ feature shows that successfulness of fellow placement at the end of program.
> Data explored using visualization. Gathered relevant columns to be used as  features. Changed all categorical variables to binary using scikitlearn label encoder.  Standardized data and used GridSearchCV to find best parameters for machine learning models. Visualize accuracy score of all models.
> Four machine learning models were produced: Logistic Regression, Decision Tree Classifier, and K Nearest Neighbors, and Random forest classification. Find Random Forest Classification with better results with accuracy rate of about 58.312%. 
