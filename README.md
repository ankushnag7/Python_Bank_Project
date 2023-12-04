# Python_Bank_Project

# Executive Summary

The results of an analysis done to forecast client attrition are presented in this report. The pre-pruned decision tree model performed better than expected, scoring 80% on the F1 accuracy metric and 94% on the accuracy metric overall. Targeted retention methods, individualised marketing efforts, and proactive customer involvement are made possible by the model's capacity to properly identify clients at risk of churn. This research' consequences include the necessity of data-driven decision making and the incorporation of prediction models into operational procedures. By taking into account other features, investigating ensemble techniques, and performing routine model updates, further advancements might be accomplished. By putting these suggestions into practise, you can find that your customer retention is better, your profits are higher, and your competitive edge is greater.
Introduction
Five fundamental ideas make up the BACCM: Change, Need, Solution, Stakeholder and Value. All fundamental ideas are equally crucial and significant.
1.	Change - Recently, the company has noted an increased customer attrition rate. That is the current change the company is experiencing and the past and the future will be closely monitored by analysing why there is attrition in the present to improve retention.
2.	Need - Identifying the root causes of attrition, such as dissatisfaction with services or products, poor service to customers, competitor issues, or shifting market dynamics, is necessary to achieve this.
3.	Solution - Examine possible ways to reduce customer attrition. This may involve a mix of tactics and creating retention initiatives. To effectively meet the issues, consider existing solutions and brainstorm new ones by analysing the data and building models.
4.	Stakeholder - Determine the parties with an interest in lowering customer attrition or who will be affected by it. Customers themselves, executives, sales and marketing teams, customer service agents, product managers, and any other pertinent parties are all included in this. Include them in the analysis and solution-development process by being aware of their viewpoints, areas of interest, and worries around attrition.
5.	Value - Analyse the advantages, disadvantages, risks, and effects of each solution. Consider variables like customer happiness, churn rates, revenue growth, cost reductions, and overall business viability. To prioritise options and decide which ones to pursue, quantify the potential value of each one.

# Approach 

In order to solve the problem of growing customer attrition in the business, a machine learning approach was used in the project. Machine learning is a potent technique that makes it possible to create predictive models by looking at historical data and spotting trends. Building a model with the ability to precisely forecast which clients are most likely to leave in the future was the aim.
Data Sources and Preparation:
Data source was the complete data which was considered for the machine learning approach. Pre-processing and data purification are essential processes in getting data ready for analysis. The aforementioned model encountered the following issues and notes:
•	Handling missing values – It was checked and there were no missing values. 
•	Converting Categorical to numerical data: The data had many categorical variables present in. After building charts to understand them and after comparing them with the dependent variable they were all converted to numerical by using get dummies.
•	Dropped the irrelevant variables – in this case the ‘Customer ID’ was irrelevant for the analysis and was dropped from the further analysis.
•	Feature engineering can improve the performance of the model by transforming and choosing the right features. Scaling, encoding categorical variables, and developing new features based on domain expertise were some of the methods used. Finding the most predictive variables for the model required sifting through the available characteristics in order to obtain useful data.
•	The most difficult parts were trying to check the findings after converting each classified variable to a numerical form. Get Dummies converted each categorical variable at the end.


# Model selection, evaluation, and comparison:

Pre-pruned decision tree classifier, post-pruned decision tree classifier, and KNN classifier were among the machine learning models that were put to the test in the analysis mentioned above. Pre-pruned decision trees had an accuracy of 94% and an F1 of 80%; post-pruned decision trees had an accuracy of 89% and an F1 of 61%; and KNN classifiers had an accuracy of 81% and an F1 of 54%.
The maximum accuracy (94%) and F1 score (80%) were achieved by the pre-pruned decision tree model, demonstrating its efficacy in predicting customer attrition. This makes it the best model for determining whether clients are at risk of leaving and for putting in place focused retention measures.
Results and interpretation
Implementing a pre-pruned decision tree model for forecasting client attrition is the suggested ultimate solution. This model's excellent accuracy (94%) and F1 score (80%) allowed us to pinpoint clients who would leave. We can lower attrition rates and increase customer loyalty by proactively engaging with these customers and executing tailored retention strategies, which will eventually boost business performance.
The pre-pruned decision tree model performed well, displaying high accuracy and an F1 score, demonstrating its efficacy in foretelling client attrition. The advantages include precise predictions and specialised retention techniques. Potential overfitting and the requirement for ongoing model modifications as consumer behaviour shifts may be disadvantages.

# Recommendations and conclusions

•	Based on the findings, business applications that are suggested include proactive customer engagement programmes, tailored marketing efforts, and client retention tactics.
•	In line with the value promise of long-term business sustainability and growth, the possible benefits to stakeholders include higher customer retention, increased profitability, enhanced customer happiness, and a stronger competitive edge.
•	The analysis has several ramifications, including the requirement to develop data-driven decision making, enhance customer retention tactics, and incorporate predictive models into business procedures. By taking into account other features, investigating ensemble techniques, and performing routine model updates, further advancements might be accomplished.
