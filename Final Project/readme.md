# Exploring the Titanic Dataset
## by Erik Portillo 


## Dataset

The dataset pertains to information of 887 out of the 2229 passengers who boarded the Titanic. The variables from the dataset are: pclass, survived, name, age, Siblings/Spouses, Parents/Children, sex, and fare. All the variables were categorical except age and fare. There were originally 8 variables but I removed one since it was not needed(Fare). I also had to change the name of two variables, to make it easier to manipulate:
"df_1.rename(columns={'Siblings/Spouses Aboard': 'Siblings/Spouses', 'Parents/Children Aboard': 'Parents/Children'}, inplace=True)".

The dataset was found through a link from a page in Stanford's website:
http://web.stanford.edu/class/archive/cs/cs109/cs109.1166/problem12.html

## Summary of Findings
From the start of the Univariate exploration, I found that my main focus will be on the survived variable. My Bivariate exploration led me to analyze the additional three variables: gender, p_class, and age as it relates to the survived variable.Females were given more priority than males based on my exploration shows that females had a survival rate of 68.13% which is lot higher than males. Females of upper class and middle class received the highest priority because Pclass exploration shows that females of upper and middle class had a survival rates of more than 90%.Evermore, females whose ages ranged 50 and older had the lowest recorded deaths and it is interesting to note those in their mid 30's also had lower deaths. To conclude, being female, having a higher p_class, and being older age (or in mid 30's), increased chances of surviving. 

> 
For the presentation, I plan to highlight my multivariate exploration since the observations made in my Univariate and bivariate exploration both add up to form the questions I pose in my multivariate exploration. The only visual I would add is the histogram that shows the ages of all the passengers, to make clear why many deaths came from the late teenage years to early 30's age range. 


## Key Insights for Presentation

The two main threads for my exploration will be the 1) Female and male causalities as it relates P_class and 2) female and male casualties as it relates to age. To begin, I separate male and female and showcase the causalities between 1st, 2nd and 3rd p_class. It is evident that those at the 1st and 2nd p_class had a higher rate for survival and this was greater for females. Second, I also separate female and male deaths as it pertains to age. For females, those age 50 and older had the lowest recorded deaths. It is also interesting to note that females in their mid 30's also had lower deaths.For males, those around pre-teenage and teenage years and older than 50 had a greater chance for survival.
I also add a final visual to show the ages of all 887 passengers, the most falling around late teenage years up to early 30's  




