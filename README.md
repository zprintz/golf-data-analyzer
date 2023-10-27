# Golf Data Analyzer
This project aims to harness the power of ChatGPT's Advanced Data Analysis to predict women's professional golf. Instead of relying on traditional methods, ChatGPT will autonomously select the optimal analysis approach to predict player finishes. The goal is to enhance prediction accuracy, showcasing the potential of ChatGPT in complex sports analytics.

Project Notes:

- Please remember to keep your repo private when you create it from this template.
- Be sure to create your report in the **intro-gen-ai** organization. 
- The name of the repo should be the name of the project, or a shortened version of the name.
- Each section should be completed by the deadline indicated. You submit by making a commit of this README.md file. Except for minor edits, please do no change the Proposal, Goals, or Metrics sections after the submission deadline.
- General guidance on formatting writing in markdown files (like this README.md file) is at https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax.
- There is a [recording of the the class discussion on the use of this template](https://vanderbilt.zoom.us/rec/share/RjihScz0Ti7RId0KMj7GWBc8XueS571_JnFqDQwli0AuKLsgaau0j_RcphBjwYtV.HP10ROf2TwPUn6TA?startTime=1697553005000).
- You can sign up for a time to discuss your ideas for the project at https://calendly.com/jesse-spencer-smith. We'll also be discussing project in class on Tuesday after Fall Break.
- Remember that there is an AI Showcase on December 1 (with prizes for Best in Show), so you might want to consider completing your project by then. 

## Project PI/Project Team 
**Due October 26, 11:59pm**

Zach Printz, zachary.h.printz@vanderbilt.edu, printzzh, PI

## Project Proposal 
**Due October 26, 11:59pm**

300-1000 words total across all of the sections below

### Description of Problem/Opportunity
Professional golf is extremely difficult to predict. There is a high level of variance from week-to-week and dozens of external factors that affect each player differently, all of which makes it extraordinarily challenging to determine the one person who will win an event on a given week. Predicting golf has been explored, but never mastered. Much attention has been given to the men's game, but with growing data available for the Ladies Professional Golf Association (LPGA), advanced data analysis in women's professional golf is now feasible. However, effectively interpreting this data to forecast player outcomes remains a challenge. Traditional methods might not fully capture the intricate patterns within the data, presenting an opportunity for more advanced analysis.

### Proposed Solution/Approach
I propose leveraging ChatGPT's Advanced Data Analysis to analyze strokes gained data. Strokes gained data is made available through KPMG Performance Insights and measures each golfer's performance compared to that of the average professional. Instead of pre-selecting a statistical method, ChatGPT will autonomously determine the optimal analysis approach, whether linear regression, random forest, or another method. This dynamic model selection, tailored to the data's specificities, aims to enhance prediction accuracy for future LPGA tournaments.

### Project Outline and Timeline
Data Collection and Pre-Processing (10/27 - 11/1): Gather KPMG Performance Insights from all 2023 LPGA tournaments through October 8's "The Ascendant LPGA". Clean, structure, and prepare the data for analysis, including handling missing values, outliers, and normalization.

Initial Model Selection with ChatGPT (11/2 - 11/6): Introduce the cleaned data to ChatGPT, allowing it to analyze and recommend an initial best-fit data analysis method.

Model Tuning (11/7 - 11/13): Refine and optimize the initially chosen model, adjusting parameters and features to enhance prediction accuracy.

Prediction (11/4 - 11/20): Utilize the tuned model to forecast finishes for the final 6 LPGA events of the season (October 14's "Buick LPGA Shanghai" - November 19's "CME Group Tour Championship".

Validation (11/21 - 11/28): Compare predictions with actual outcomes to assess the model's accuracy and effectiveness.

Finalization (11/29 - 11/30): Consolidate findings and refine the model based on validation feedback.

## Goals of project 
**Due October 26, 11:59pm**

Describe 1-5 goals of the project. 
1. Predictive Accuracy: Achieve a high degree of accuracy in forecasting player finishes in LPGA events, outperforming traditional forecasting methods.
2. Model Interpretability: Extract feature importance from the chosen model to understand key drivers of success on the LPGA tour.
3. Demonstrate ChatGPT's Capability: Showcase the prowess of ChatGPT in data analysis and model selection, emphasizing its adaptability and potential in handling complex sports analytics tasks.

## Project Metrics 
**Due October 26, 11:59pm**
   1. Accuracy in Predicting the #1 Player:
   
         A: Model predicts the #1 player in its top 30 4/6 times or more.

         B: Model predicts the #1 player in its top 30 3/6 times.

         C: Model predicts the #1 player in its top 30 2/6 times.

         D: Model predicts the #1 player in its top 30 1/6 times.

         F: Model never predicts the #1 player in its top 30.


   2. Accuracy in Predicting the Tournament's Top 10:
   
         A: For at least 4/6 tournaments, the model places 3 of the actual top 10 finishers within its top 40 predicted players.

         B: For 3/6 tournaments, the model places 3 of the actual top 10 finishers within its top 40 predicted players.

         C: For 2/6 tournaments, the model places 3 of the actual top 10 finishers within its top 40 predicted players.

         D: For 1/6 tournaments, the model places 3 of the actual top 10 finishers within its top 40 predicted players.

         F: The model never places 3 of the actual top 10 finishers within its top 40 predicted players.


## Self-Evaluation
**Due December 8, 11:59pm**

300-1000 words

Address each of the goals, and assess each of the metrics. Include a statement on each on what you achieved or did not achieve, give support for your assessments.

## Reflection on Learning
**Due December 8, 11:59pm**

500-1000 words

What do you take away from the project? Has this changed how you understand AI? Does and how does this affect future plans for learning, work, or otherwise?

## What's Next?
**Due December 8, 11:59pm**

100-500 words

Do you plan on continuing the project? What will you do with what you've learning?
