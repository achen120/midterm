# Main Cause(s) of Poor Academic Performance in Baltimore City Public Schools 
By: Daisy Xu, Yixing Pan, Anqi Chen

          “Education is the premise of progress, in every society, in every family." --- Kofi Annan
### The Problem in Baltimore
According to the article, [Baltimore City is failing its children](https://www.baltimoresun.com/opinion/readers-respond/bs-ed-rr-student-test-scores-letter-20180410-story.html), students in Baltimore Public Schools scored near the bottom on math and reading compared to students in other large urban areas and cities under a 2017 national assessment referred to [Baltimore students trail in key U.S. assessment](https://www.baltimoresun.com/education/bs-md-nations-report-card-20180409-story.html). Only 11 percent of students from Baltimore Public Schools reached the proficient level in eighth grade Math test, whereas a limited 13 percent reached the proficient level in eighth grade reading test.

Our analysis in Education_and_Youth__2015__analysis.xlsx of the data [Education and Youth](https://data.baltimorecity.gov/Neighborhoods/Education-and-Youth-2015-/t7tk-reum) also indicates the education situation in Baltimore.

Additionally, by comparing the data with other cities, we can find that students in Baltimore city have the highest percent of low-performance level, lowest percent of high-performance level, and the least change from the previous year.

![alt text](https://github.com/achen120/midterm/blob/master/students%20bad%20performance.jpg)


### Why is this a Challenge?
Browsing through the web materials, a report [Baltimore's economy in black and white](https://money.cnn.com/2015/04/29/news/economy/baltimore-economy/) caught our attention. It emphazies that the poverty rate of Baltimore, which is approximately 24%, is amazingly high compared to 9.9% of Maryland and 11.8% of the U.S in 2019. We thus wonder if students' poor academic performance is correlated with the high poverty rate in Baltimore. [Our Business Question is then: How Poverty Influences Student’s Performance in Baltimore City Public Schools?]

With poor academic performance, students are more likely to drop out of school and are less possible to acquire new skills by going to higher institutions to further their studies. As shown in the chart below, the unemployment rate gradually decreases as the degree of individual obtained increases. 

![alt text](https://github.com/achen120/midterm/blob/master/Unemployment%20rate.jpg)

This explains the result shown in the chart below, with a higher degree, the poverty rate is lower. 

![alt text](https://github.com/achen120/midterm/blob/master/poverty%20vs%20education%20level.jpg)

For individuals who have a degree less then high school, the poverty rate is 33.68%. We can roughly conclude that education is the best way to eradicate poverty. According to J. Nyerere, “Education is not a way to escape poverty,it is a way to fight it."

However, poverty causes severe consequences, including:
 - Poor health condition due to lack of medication
 - Financial crisis
 - Poor living standards
 
If the poor education situation in Baltimore is a result of high poverty, it then leads back to poor education, which falls into a vicious cycle. The situation thus may even become worse in the future as this may hinder the development of Baltimore. 
We need to stop this vicious cycle!

We came up with several data questions that would guide our analysis:
1. What data on Poverty & School Performance can we find and use?
- Poverty Rate by Schools, School Survey Data
2. What tools shall we use to derive the relationships between different factors?
- VLOOKUP, linear regressions, trendlines
3. How others perceive similar problems?
- Supportive articles and analysis


### Our Solution
To analyze the problem, we want to see how poverty is related to academic performance. By linking the High school poverty rate chart with academic performance chart published by Baltimore city schools using VLOOKUP with School name, we successfully combine all factors and poverty rates on one chart. Then, we find the correlation and coefficient between factors and poverty by regression data analysis. 

The chart below shows each variables’ relationship with the poverty rate. P-value for School Performance Measure (SPM) Index is 0.017532, which is smaller than 0.05. This gives us the Business answer that SPM has a relation with the poverty rate. Since the coefficient is negative, this means as the poverty rate increases, academic performance becomes worse. 

![alt text](https://github.com/achen120/midterm/blob/master/p-value%20for%20poverty%20and%20perform.JPG)

What's more, according to ['How Poverty Affects Classroom Engagement'](http://www.ascd.org/publications/educational-leadership/may13/vol70/num08/How-Poverty-Affects-Classroom-Engagement.aspx) by Eric Jensen, Students in poverty are exposed to food with lower nutritional value. They are less likely to exercise and receive appropriate medications. In such an unfavorable condition, it's harder for them to listen, concentrate, and learn. This can hurt reading ability and other skills to achieve good academic standing. Also, poverty can cause a vocabulary problem, which can leads to poor academic performance because students who grow up in low socioeconomic conditions typically have a smaller vocabulary than middle-class students do. This raises the risk of academic failure. When students aren't familiar with words, they don't want to read and might think that school is not for them. Besides, many students don't want to be unappreciated by their peers so that they won't participate in class.

All circumstances above confirm our business answer: the poor education condition of Baltimore is to some extent related to the condition of high poverty rate. From the study above we can further observe that poverty affect the education is related with limited family education and study environment. Based on the observation, we come up with a practical suggestion to the education department. Due to students’ poor academic performance in Baltimore, they might need extra help on school work. However, since most of the students are suffering from severe poverty, paying for an extra academic assistance is a burden for them. Thus, the school should should recruit some staff to provide additional help sessions for these students.

### Future Suggestions
To come up with some further suggestions, we tried to narrow down the idea of poverty into smaller pieces. In our second round analysis, we did linear regression multiple times to determine which factor caused by poverty condition has the largest influence on academic performance. 

From the chart below, we can see that the p-value between poverty and sense of safety on the route to school is as low as 1.7E-5, which indicates an extremely high statistical significance. Meanwhile, the negative coefficient as -51.46, implying that the higher poverty rate typically in company with less sense of safety.

![alt text](https://github.com/achen120/midterm/blob/master/p-value%20for%20safety%20and%20perform.jpg)

Based on the observation, we make our assumption that such a sense of security has an impact on a student’s academic performance. Therefore, we do the linear regression again between the sense of safeness and academic performance. As the P-value for safety is 4.34E-37, which is smaller than 0.05, there exists a correlation. And since the coefficient is positive, this means that as students have a stronger sense of security on the route to school, their academic performance rises.

![alt text](https://github.com/achen120/midterm/blob/master/Performance%20vs%20safety.jpg)

Based on the correlations between these two variables, we do a further analysis of the linear relationship between academic performance and student's sense of security on the route to school. The graph below shows a clear linear relationship between them.

![alt text](https://github.com/achen120/midterm/blob/master/Trendline%20Performance%20vs%20Sense%20of%20security.JPG)

Consequently, we tried to find out why such a sense of safety affects academic performance so much.
The attentiveness and efficiency is one of the factors. A recent study at Sainte-Anne’s University finds that the student who felt unsafe has more symptoms of depression, making them unhappy and difficult to enjoy themselves. Such low performance in engagement and attentiveness in the classroom have a long-term adverse effect on students, leading to lower academic achievement.
Another factor is absent from class. A report out of the University of Southern California found that the unsafe feeling “reduces school attendance”. For a student, staying home from class is often the easiest way to avoid danger. Such an absence from the class hinders student’s performance in understanding.

We then related these factors with Baltimore current situation. A model of the most efficient routes to school for Baltimore's students indicates that, for those who commute through areas with double the average amount of crimes, they are 6 percent more likely to miss school.

Considering all circumstances above, we come up with the suggestion for school to provide secure bus pick-up service to guarantee the safety of students and give them a sense of security to raise the student’s academic performance.




# Appendix

![alt text](https://github.com/achen120/midterm/blob/master/combined%20data%20chart.JPG)
