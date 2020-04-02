# Project 2 - Predicting Outcomes Using Data

This time around, you will be making use of a dataset to create predictive models. 
Make sure that you focus on making the most accurate **out-of-sample** prediction possible. 
I will introduce new techniques each week in order to help you develop more accurate predictions of the outcome of interest. 
The write-up for this project should again be 2-3 pages long, not including any visuals or screenshots that you choose to utilize.

1) **(After Completing Topic 5)** Using the data provided, come up with your best explanation of how to predict the outcome of interest using visualizations, analysis, or sorting algorithms on the data. 
You should only use Excel, Google Sheets, or Tableau if you choose to use software to aid you in this step. 
    - In your writeup, describe your manual procedure for deciding how to classify new observations, then use that procedure to make predictions based on a small sample of the data provided (around 30 observations).
        - How accurate are your team's predictions?
        - What was the biggest problem that your team encountered when trying to make accurate predictions?
        - What would your team change if you attempted to made predictions like this again?

2) **(After Completing Topic 6)** Implement two different classification algorithms to make the same predictions that you tried to make in Step 1 (For this week, avoid using Random Forests and AdaBoost classifiers; we will discuss those kinds of models in detail next week). 
Experiment by using different attributes in each implementation, and compare the results to your most successful models. Discuss the following in your writeup:
    - Which models did you choose, and why?
    - How well do decision trees and other classifiers do in predicting the dependent variable?
    - What was the accuracy reported by each of your team's classifiers? 
        - Were there any techniques that improved the accuracy of those classifiers (such as modifying the sensitivity of the algorithms)?
    - What challenges did your team face while implementing the classifiers?
    - What strengths (and shortcomings) in statistical models have you observed while using these classification algorithms?

3) **(After Completing Topic 7)** Create a random forest (or other ensemble algorithm). Experiment by generating your forests using different numbers of trees, and by varying the other available parameters. In your writeup,
    - Compare the results of your ensemble models to the results from part (2)
    - Is a random forest, or an ensemble model in general, an improvement from your previous classifiers? Is it superior to your procedure from Step 1?
    - What do you think makes random forests and ensemble models more powerful than a single classifier?
    - Does a random forest solve any of the shortcomings of decision trees? 
        - If it does, describe how it is able to use the same information to reach better outcomes.
    - Do ensemble models in general seem to be an improvement over simple classifiers, or does your team find that these advantages only exist for specific models?