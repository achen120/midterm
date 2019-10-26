# Main Cause(s) of Poor Academic Performance in Baltimore City Public Schools 
By: Daisy Xu, Yixing Pan, Anqi Chen

          “Education is the premise of progress, in every society, in every family." --- Kofi Annan
### The Problem in Baltimore
According to the article, [Baltimore City is failing its children](https://www.baltimoresun.com/opinion/readers-respond/bs-ed-rr-student-test-scores-letter-20180410-story.html), students in Baltimore Public Schools scored near the bottom on math and reading compared to students in other large urban areas and cities under a 2017 national assessment referred to [Baltimore students trail in key U.S. assessment](https://www.baltimoresun.com/education/bs-md-nations-report-card-20180409-story.html). Only 11 percent of students from Baltimore Public Schools reached the proficient level in eighth grade Math test, whereas a limited 13 percent reached the proficient level in eighth grade reading test.

Our analysis in Education_and_Youth__2015__analysis.xlsx of the data [Education and Youth](https://data.baltimorecity.gov/Neighborhoods/Education-and-Youth-2015-/t7tk-reum) also indicates the education situation in Baltimore.

Additionally, by comparing the data with other cities, we can find that students in Baltimore city have the highest percent of low-performance level, lowest percent of high-performance level, and the least change from the previous year.

![alt text](https://github.com/achen120/midterm/blob/master/students%20bad%20performance.jpg)


### Why is this a Challenge?
Browsing through the web materials, a report [Baltimore's economy in black and white](https://money.cnn.com/2015/04/29/news/economy/baltimore-economy/) caught our attention. The poverty rate of Baltimore, which is approximately 24%, is amazingly high compared to 9.9% of Maryland and 11.8% of the U.S in 2019. We thus wonder if students' poor academic performance is correlated with the high poverty rate in Baltimore. Our Business Question is then: How Poverty Influences Student’s Performance in Baltimore City Public Schools?

With poor academic performance, students are more likely to drop out of school and are less possible to acquire new skills by going to higher institutions to further their studies. As shown in Chart 1, the unemployment rate gradually decreases as the degree of individual obtained increases. This explains the result shown in Chart 2, with a higher degree, the poverty rate is lower. For individuals who have a degree less then high school, the poverty rate is 33.68%. We can roughly conclude that education is the best way to eradicate poverty. According to J. Nyerere, “Education is not a way to escape poverty,it is a way to fight it."

However, poverty causes severe consequences, including:
 - Poor health condition due to lack of medication
 - Financial crisis
 - Poor living standards
 
If the poor education situation in Baltimore is a result of high poverty, it then leads back to poor education, which falls into a vicious cycle. The situation thus may even become worse in the future as this may hinder the development of Baltimore. 
We need to stop this vicious cycle!

![alt text](https://github.com/achen120/midterm/blob/master/Unemployment%20rate.jpg)

![alt text](https://github.com/achen120/midterm/blob/master/poverty%20vs%20education%20level.jpg)


From the data above, we find that Low education level is one of the factors for unemployment, which will let people in poverty.


### Our Solution
For the data analysis part, we want to see how poverty related with academic Performance. By linking the High school poverty rate chart with academic performance chart published by Baltimore city schools using VLOOKUP with School name, we successfully combine all factors and poverty rate on one chart. Then, we find the correlation and coefficient between factors and poverty by regression data analysis. 

Chart below shows each variables’ relationship with poverty rate. P-value for School Performance Measure (SPM) Index is 0.017532, which is smaller than 0.05. Thus, SPM has relation with poverty rate. Since coefficient is negative, this means as poverty rate increases, academic performance become worse. 

![alt text](https://github.com/achen120/midterm/blob/master/p-value%20for%20poverty%20and%20perform.JPG)

What's more, according to ['How Poverty Affects Classroom Engagement'](http://www.ascd.org/publications/educational-leadership/may13/vol70/num08/How-Poverty-Affects-Classroom-Engagement.aspx) by Eric Jensen, Students in poverty are exposed to food with lower nutritional value and are less likely to exercise and receive appropriate medications. In such an unfavorable condition, it's harder for them to listen, concentrate, and learn. This can hurt reading ability and other skills to achieve good academic standing. Also, poverty can cause vocabulary problem, which can leads to poor academic performance, because students who grow up in low socioeconomic conditions typically have a smaller vocabulary than middle-class students do, which raises the risk for academic failure. When students aren't familiar with words, they don't want to read and might think that school is not for them. In addition, many students don't want to be deappreciated by their peers, so they won't participate in class.

Based on students’ poor academic performance in Baltimore, they might need extra help on school work. However, since most of the students are in severe poverty, paying for extra help is difficult for them. Thus, government should assign more funding on this. And school can recruit more staffs to provide teaching.

### Future Suggestions
In order to come up with some more further suggestion on the issue, we tried to narrow down the idea of poverty into small pieces. Therefore, in second round analysis, we do linear regression multiple times to determined which factor caused by Poverty condition has the largest influence on the academic performance. 

From the chart below, we can clearly see that the p-value between Poverty and sense of safety is as low as 1.7E-5 which indicate an extremely high statistical significance. Meanwhile, the negative coefficient as -51.46 implies that the higher poverty rate typically in company with less sense of Safety.

![alt text](https://github.com/achen120/midterm/blob/master/p-value%20for%20safety%20and%20perform.jpg)

Based on the observation, we make our assumption that such sense of security has negative impact on student’s academic performance. Therefore, we do the linear regression again with sense of safety and academic performance. Chart below shows safety relationship with Academic performance. P-value for safety is 4.34E-37, which is smaller than 0.05. Thus, safety has relation with student’s Academic performance. Since coefficient is positive, this means as students have stronger sense of secure on the route to school, their academic performance rises.

![alt text](https://github.com/achen120/midterm/blob/master/Performance%20vs%20Safety.JPG)

Based on the Correlationship between these two variables, we do a further analysis of linear relationship between Academic Performance and student's sense of security. The graph below shows a clear linear relationship between them.

![alt text](https://github.com/achen120/midterm/blob/master/Trendline%20Performance%20vs%20Sense%20of%20security.JPG)

Consequently, we tried to find out why such sense of safety affect academic performance so much.
The attentiveness and efficiency in study is one of the factors. A recent study at Sainte-Anne’s University finds that the student who felt unsafe has more symptoms of depression, making them unhappy and difficult to enjoy themselves. Such low performance in engagement and attentiveness in the classroom have long-term negative effect on students, leading to lower academic performance.
Another factor is absence from class. A report out of University of Southern California found that the unsafe feeling “reduces school attendance”. For student, staying home from class is often the easiest way to avoid danger. Such absence from the class hinder student’s performance in understanding.

We then related these factors with Baltimore current situation. A model of the most efficient routes to school for Baltimore students indicates that those who commute through areas with double the average amount of crime are 6 percent more likely to miss school.

Considering all circumstances above, we come up with the suggestion for school to provide secure bus pick-up service to guarantee the safety of students and give them a sense of security so as to raise the student’s academic performance.




# Appendix

![alt text](https://github.com/achen120/midterm/blob/master/combined%20data%20chart.JPG)
