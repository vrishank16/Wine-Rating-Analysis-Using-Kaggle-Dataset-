# Wine-Rating-Analysis-Using-Kaggle-Dataset

This projected involved us selecting from a list of real world scenario datasets, exploring it and finding 'useful' insights from it. Those “insights” should address the business problem that the dataset relates to.

### Rules Given for the project:
1. Review the case and identify the business problem to address. This problem should be worded as a QUESTION that addresses the identified business problem. 
eg:  How can we increase sales using the provided data?  


2. It is recommended that you split this problem into sub-steps or sub-problems that would allow you to gradually build the solution: <br>
Subquestion 1: which customer characteristics predict the item they purchase? <br>
Subquestion 2: how can the volume of sales be predicted using the item characteristics? <br> 
You need to have at least two subquestions: one will be solved using the regression model and another one will be solved using the classification model. 
You need to demonstrate how this deconstruction addresses the overarching problem solution (i.e. your QUESTION). 


3. Use data wrangling and data viz approaches to explore the dataset in relation to the identified QUESTION and SUBQUESTIONS. Each data manipulation and data viz needs to add value to resolve the identified problem and help with decision making.  
This step forms the part of your written report which you prepare as a Word document and submit as part of your report. 
You need to explain what your new insights your data wrangling and data viz provide. 


4. Develop at least 2 models addressing the problem using regression and classification approaches. The development of the model should be based on your knowledge, additional research and the problem to address. It should NOT be based only on the availability of data.  
Explain your reasoning in developing your models and justify them. 
You must use at least one classification and one regression algorithm 
This step forms the part of your written report which you prepare as a Word document and submit as part of your report. 


5. Evaluate your developed models and discuss how they “answer” your QUESTION and SUBQUESTIONS and help to resolve the identified business problem. 
This step forms the part of your written report which you prepare as a Word document and submit as part of your report. 


6. Develop a communication document (business report) with your findings for your stakeholder/s. You need to report your findings in easy to understand and visually supported way - this IS your report which should be prepared using business report style.

## Our Findings

The dataset used in this project can be found here: https://github.com/rfordatascience/tidytuesday/tree/master/data/2019/2019-05-28

The detailed report and jupyter notebook have been attached. The following sections are exercepts from the final report.

### Problem Statement
The main business problem is, “How can we optimise the wine selection process and customer’s wine buying experience, in order to curate an inventory that would ultimately lead to increased customer satisfaction and revenue of this particular winery?”.
Today one of the key challenges that wineries face is inventory curation and understanding which wines must be stocked (Maurel et al. 2019). This is a critical decision since customer satisfaction and revenue depend heavily on this. Overstocking wine can cause financial strains and storage problems. Understocking wines and wine unavailability can cause customer dissatisfaction and lose revenue in this regard.
Furthermore, customers have a variety of tastes (Navarro, Pedraja-Inglesias and Marta 2010)
and different financial budgets when making a purchasing decision regarding wine(Gustafson, Lybbert and Sumner 2016).<br>

Based on this understanding, the main problem was further broken down into 2 sub problems to create a regression model and a classification model: 

Sub-Problem 1: Regression Model: “How can we predict the price of wine effectively to enhance our inventory curation for better customer experiences and stock control?”
As mentioned above, predicting wine prices accurately could benefit wineries and ensure that these prices are marked according to the market demands and in a profitable manner. This would help to understand which wines must be stocked to increase revenue, customer satisfaction and manage storage in wineries. <br>

Sub-Problem 2: Classification Model: “How can we classify wines into ‘value picks’ and ‘premium choices’ for our inventory, to cater to our customers' diverse preferences and budgets?”
Since customers have different preferences and budgets, this would help wineries to curate their inventories in an efficient manner and help customers and even employees to easily identify which wine varieties to be suggested must faster to customers based on their budgets. This would also save time when providing recommendations and also enhance customer experience. For this particular problem, we have made an assumption that wines priced above $200.00 is considered as premium picks and wines below $200 as value picks.

### Findings and Conclusions
Through our intensive analysis of wine data, we conducted regression analysis to predict wine prices and employed a logistic regression model to classify wines into "Value Picks" and "Premium Picks." Our results and findings gave us valuable insights into the wine industry based on which the findings offer valuable insights for the business in the wine industry.
Regarding our regression analysis, Model 2 was more accurate than Model 1. It had a lower MSE and MAE, indicating a superior ability to predict wine prices. Moreover, the higher R-squared (R2) value also showed that Model 2 explains a greater proportion of price variance.

Secondly, our logistic regression model successfully classified wines into "Value Picks" and "Premium Picks" based on various attributes. This classification can significantly enhance our inventory curation, ensuring that customers have access to wines that align with their preferences and budget constraints.
The integration of the regression and classification models allows predicting wine prices and classifying them accurately. This holistic approach empowers us to optimize our product offerings, improve customer experiences, and tailor our inventory to meet diverse demands. It is crucial to maintain ongoing model monitoring and exploration of alternative modelling techniques to ensure sustained business success in the dynamic wine market.
