# India-vs-USA-Difference-in-data-science-Scenario-
This repository uses the data from [Kaggle 2018 ML\DS survey](https://www.kaggle.com/kaggle/kaggle-survey-2018). 

Ever since I've been interested in Data Science , I've thought of the differences in this field in India and USA. There have been certain norms regarding the differences that have been set during the years, what remains to be seen is whether the survey complies with those norms or contradicts them.

The kernel.ipynb file actually has the python code to analyse and visualize this data(and from where I get the plots shown below). Since most of the plots that I made were using plotly,
they are not rendered in the file so I'll show them here with the insights I got from them. Although you can find some plots that I made with matplotlib in the code file itself.

## Country-wise contribution in the survey. ##

![alt text](https://github.com/Ibtastic/India-vs-USA-Difference-in-data-science-Scenario-/blob/master/vis/countrywise%20contribution.png)

As it appears, India has the second highest reponse after America.

## ML/DS Education preferences of Indians and Americans . ## 

![alt text](https://github.com/Ibtastic/India-vs-USA-Difference-in-data-science-Scenario-/blob/master/vis/ML%20education%20preference.png)

* Going to universities is more popular in USA than India apparently due to the much higher number of Data Science courses offered in American universities. Only a few universities in India offer Data Science courses.
* Quite Strikingly, more Indians consider Kaggle Competitions as a way of learning than Americans.
* More Americans learn at work than Indians (probably due to greater number of data science jobs in America than India).
* The "Self-Taught" and "Online Course" pattern could be considered the same beacuse more respondents are Americans.

## MOOC preference differences. ##

![alt text](https://github.com/Ibtastic/India-vs-USA-Difference-in-data-science-Scenario-/blob/master/vis/MOOC.png)

* Undoubtedly **Coursera** is the most popular MOOC and is almost equally preferred among both the groups.
* **Datacamp** is less popular in America than India.
* **Udemy** and **Kaggle Learn** are preferred by Indians more 

## Difference in Time engaged in various tasks. ##

![alt text](https://github.com/Ibtastic/India-vs-USA-Difference-in-data-science-Scenario-/blob/master/vis/time%20engaged%20in%20tasks.png)

* More Indians spend time in Model Building while more Americans spent time in Finding Insights in the data and communicating to the stakeholders. This difference could be attributed to the fact that the data science community in USA is more mature as compared to the Data Science Community in India.

## Gender-wise Participation in the survey ##

![alt text](https://github.com/Ibtastic/India-vs-USA-Difference-in-data-science-Scenario-/blob/master/vis/gender.png)

There are more Male Indian participants and more Female American Participants.

Now, let's remove the respondents who have **not disclosed their Annual Compensation** and see if the graph remains the same.

![alt text](https://github.com/Ibtastic/India-vs-USA-Difference-in-data-science-Scenario-/blob/master/vis/gender%20after%20filtering.png)

Whoa! **A lot of Indian Males haven't disclosed their annual compensation**.

## Compensation Difference


![alt text](https://github.com/Ibtastic/India-vs-USA-Difference-in-data-science-Scenario-/blob/master/vis/compensation.png)

* Most of the Indians are paid in the salary range 0-10, 000 while most of the Americans are paid in the range 100-125,000.
* The salary curve for Indians decreases exponentially as the salary range increases.

## Gender Pay Gap ##

Now we will calculate the Average Yearly Compensation and visualize the gender pay gap in both the countries.

![alt text](https://github.com/Ibtastic/India-vs-USA-Difference-in-data-science-Scenario-/blob/master/vis/gender%20pay%20gap.png)

* American males are paid more than American females.
* The graph shows that Indian Females are paid more than India Males which may be due to the fact that a lot of Indian males haven't disclosed their salaries.

## Average Salary Diferrence for the same experience level ##

![alt text](https://github.com/Ibtastic/India-vs-USA-Difference-in-data-science-Scenario-/blob/master/vis/compensation%20for%20same%20experience.png)

* As we can see there is a huge compensation difference in both the countries for the same experience level.
* What is unsettling is for India , *how can the average salary decrease as the experience level increases , like in the range 3-4 years and 15-20 years*.

**The huge compensation difference for both the countries could be attributed to the fact of difference in cost of living in both the countries. So let's remove that factor by normalizing the salary and then plotting**.

![alt text](https://github.com/Ibtastic/India-vs-USA-Difference-in-data-science-Scenario-/blob/master/vis/Normalized%20compensation%20for%20the%20same%20experience%20level.png)

The difference in compensation reduces but it still remains.

## Average Salary as per the job title. ##

![alt text](https://github.com/Ibtastic/India-vs-USA-Difference-in-data-science-Scenario-/blob/master/vis/Normalized%20compensation%20for%20the%20same%20experience%20level.png)

* Another astonishing revealation - Data Journalist jobs pay the most in India , even more than the Chief Officer post in US.

## Average Salary as per the age group ##

![alt text](https://github.com/Ibtastic/India-vs-USA-Difference-in-data-science-Scenario-/blob/master/vis/Average%20salary%20as%20per%20age%20group.png)

* In India the highest paying age group is 55-59 while in America it is 45-49 (over a decade's difference )
* The salary for Americans increase with increase in age group while it's not the same for Indians ,40-44 age group sees a decrease in average yearly compensation and for the 60-69 age group too.

## Average Salary as per the years spent writing code to analyze data. ##

![alt text](https://github.com/Ibtastic/India-vs-USA-Difference-in-data-science-Scenario-/blob/master/vis/Average%20salary%20as%20per%20the%20years%20spent%20writing%20codes%20to%20analyze%20data.png)

People with 40+ years of experience in writing code are paid the most in both the countries(as expected )

# Conclusion 

To sum up we can say that Data Science is a mature field in USA while it's still in the developing phase in India. Most of the above differences can be explained by this fact.






















