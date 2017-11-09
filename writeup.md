# Create a Tableau Story Titanic Data
[Initial: Tableau Story from Titanic Data](https://public.tableau.com/profile/byungcheon.ko#!/vizhome/Titanicinitial_0/Story1)
[Final: Tableau Story from Titanic Data](https://public.tableau.com/profile/byungcheon.ko#!/vizhome/TitanicSurvival_8/SurvivalStory)


## Summary
Titanic data contains demographics and passenger information from a subset of the 2224 passengers and crew on board the Titanic. I will create a visualization that shows the demographics or passenger information between those passengers who survived and those who died.

## Design
* I looked at how each factor(Gender, Ticket Class, Age Group, Embarked from) affect survival rate of the passenger. 
* I used a bar charts for looking at how each factor affect survival rates. Since we only have two variables(survival rate, factor), it is easy to compare survival rates. 
* I chose to put average survival rate on Y-axis and each factor(Gender, Ticket Class, Age Group, Embarked from) in X-axis so it is easy to compare average survival rate by looking at the height of the bar chart.


## Feedback
* Age visualization is a mass, it is really hard to tell what is going on
  * I grouped ages into three groups : minors(0-18), elders(60>), others
  * I display AVG(Survived) instead of SUM(Survived).
* In Embarked visualization, what does X axis signify? What is Null?
  * I removed Null values 
  * I change X axis to city where passengers embarked from
* What does 0 and 1 mean in Survived visualization?
  * I changed 0 to dead and 1 to alive
* In Pclass visualization, isn't it better to display percentage of people survived for each ticket class?
  * I changed Y-axis to display AVG(Survived) instead of SUM(Survived)
* I think more explanations are helpful
  * In captions, I put more explanations.
* Gender Graph looks too thin
  * I adjusted Gender graph to fit better on screen
* Embarked Graph looks too thin
  * I adjusted Embarked visualization to fit better on screen
* In your “Design” section please also explain: How did you make your initial visualization decisions? Please justify your decisions of the chart types, legends, etc in the visualization. For example, you can say "I chose bar charts for reasons A and B ..."
  * I changed Design section of the writeup
* Your visualizations are great. In order to evaluate this section we also need to compare your initial design to final design (after feedback revision) therefore for the next submission, please include 2 links in your write-up, one for the initial design and one for the final version and also please document the changes you've made more in detail in the write-up. For example, you can say based on Feedback "A", I decided to change the plot's type or any other modifications that you have made. We basically want to see how did you improve your project base on the received feedbacks.
  * I created two Tableau stories to show initial design and final design

## Resources
[Kaggle Titanic Data](https://www.kaggle.com/c/titanic)


## Data Files
[Titanic Data](https://www.google.com/url?q=https://d17h27t6h515a5.cloudfront.net/topher/2017/October/59d54e6d_titanic-data/titanic-data.csv&sa=D&ust=1510126640638000&usg=AFQjCNEjDygDOQLtgGE8sTgjyLhQ6SAg4Q)
