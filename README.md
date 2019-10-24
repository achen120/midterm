# Midterm Project -- Education and Poverty/Crime 
This repository is for the [Business Analytics Midterm Project](https://docs.google.com/document/d/1X4XwqZqIRkZgGsXuNKcdZtbkZ9x16xPFZLm7pMSUqCU/edit?usp=sharing)
# Explanatory Project Title
According to a report [Baltimore City is failing its children](https://www.baltimoresun.com/opinion/readers-respond/bs-ed-rr-student-test-scores-letter-20180410-story.html) from The Baltimore Sun, the Baltimore school students scored near the bottom on reading and math compared to students in other large urban areas and cities under a 2017 national assessment refered to [Baltimore students trail in key U.S. assessment](https://www.baltimoresun.com/education/bs-md-nations-report-card-20180409-story.html). In summary, only 13 percent of Batimore students reach the proficent level in eighth grade reading test while only 11 percent Baltimore students reach the proficent level in eighth grade Math test. 

Our analysis in Education_and_Youth__2015__analysis.xlsx of the data [Education and Youth](https://data.baltimorecity.gov/Neighborhoods/Education-and-Youth-2015-/t7tk-reum) also support the phenomenom indicating the poor education situation in Baltimore.

Browsing through the web materials, a report [Baltimore's economy in black and white](https://money.cnn.com/2015/04/29/news/economy/baltimore-economy/) caught our attention. The poverty rate of Baltimore which is approximately 24% is amazingly high compared to 9.9% of Maryland and 11.8% of U.S in 2019. This surprisingly high Baltimore poverty rate and poor education situation lead us to think about whether there's some correlation between these two phenomenon. Such problems is very critical since we all know that Education is the best way to eradicate Poverty because those in poverty can only change their condition by learning new things. According to J. Nyerere, “Education is not a way to escape poverty,it is a way to fight it”. Meanwhile, poor education can lead to more serious result:
 - Poor health condition for lack of Physiology Knowledge
 - Financial Crisis for lack of Personal Finance management skills
 - Poor living standard for limited mind and thought
 
If the poor education situation in Baltimore is a result of high Poverty plus the poor education can actually lead to higher poverty rate, the issue falls into a vicious cycle and the situation would becomes worse in the future; it would hinder the development of Baltimore. Therefore, in this project, we are trying to find where exactly the poverty affect Baltimore students from receiving good Education and what should government do within their capability. In 


# Why is this a Challenge/Problem?
Poverty can lead to poor academic performance, which can eventually lead to low education level. Low education level is one of the factors for unemployment. And unemployment will let people in poverty. This is a vicious cycle. We need to stop it!

<img src="https://github.com/achen120/midterm/blob/master/16.pic.jpg" width="600" height="300">

<img src="https://github.com/achen120/midterm/blob/master/8.pic.jpg" width="300" height="150">

<img src="https://github.com/achen120/midterm/blob/master/9.pic.jpg" width="400" height="200">


From the data above, we find that Low education level is one of the factors for unemployment, which will let people in poverty.

What is your business question and why is this important? This is obviously important to you because you’re working on the project, but why should the reader care about this problem as well? What other other industries (i.e. automotive, public sector, emerging technology), groups (i.e. executives, mechanics, accountants), or demographics (sex, gender, race, location) is this problem relevant for? What’s happening now because of this problem and what are potential bigger problems that can arise from nothing being done about this problem? You can use statistics and numbers to enforce your statements, but make sure to make these accessible to a general audience. Link to your sources, articles, datasets, etc. here for people to read more about specific issues that might be useful. This section should be no longer than a paragraph.

# Your Solution
Chart below shows each variables’ relationship with poverty rate. P-value for School Performance Measure (SPM) Index is 0.017532, which is smaller than 0.05. Thus, SPM has relation with poverty rate. Since coefficient is negative, this means as poverty rate increases, academic performance become worse. 
![alt text](https://github.com/achen120/midterm/blob/master/13.pic_hd.jpg)

What's more, based on [Childfund International Organization](https://www.childfund.org/Content/NewsDetail/2147489206/), children born or raised in poverty face a number of disadvantages, most evidently in education. Poverty reduces a child’s readiness for school because it leads to poor physical health and motor skills, diminishes a child’s ability to concentrate and remember information, and reduces attentiveness, curiosity and motivation.   

One of the most severe effects of poverty in the United States is that poor children enter school with this readiness gap, and it grows as they get older. Children feel alienated from society; suffer insecurities because of their socioeconomic status; fear the consequences of their poverty; endure feelings of powerlessness; and are angry at society’s inability to aid in their struggles.

Health and Nutrition, from ['How Poverty Affects Classroom Engagement'](http://www.ascd.org/publications/educational-leadership/may13/vol70/num08/How-Poverty-Affects-Classroom-Engagement.aspx) by Eric Jensen
Overall, poor people are less likely to exercise, get proper diagnoses, receive appropriate and prompt medical attention, or be prescribed appropriate medications or interventions. A study by two prominent neuroscientists suggested that intelligence is linked to health (Gray & Thompson, 2004). The poor have more untreated ear infections and hearing loss issues (Menyuk, 1980); greater exposure to lead (Sargent et al., 1995); and a higher incidence of asthma (Gottlieb, Beiser, & O'Connor, 1995) than middle-class children. Each of these health-related factors can affect attention, reasoning, learning, and memory.
Nutrition plays a crucial role as well. Children who grow up in poor families are exposed to food with lower nutritional value. This can adversely affect them even in the womb (Antonow-Schlorke et al., 2011). Moreover, poor nutrition at breakfast affects gray matter mass in children's brains (Taki et al., 2010). Skipping breakfast is highly prevalent among urban minority youth, and it negatively affects students' academic achievement by adversely affecting cognition and raising absenteeism (Basch, 2011).

According to ['America’s Poverty-Education Link'](https://www.huffpost.com/entry/americas-poverty-education_b_1826000) by Howard Steven Friedman,The link between poverty and education can be seen at all educational levels.  From the earliest stage, pre-primary education, poorer Americans start disadvantaged. Children of parents earning less than $15,000 a year have pre-primary enrollment rates about 20 percent lower than children of parents earning more than $50,000 a year.  This pre-school disadvantage for poor people has far-reaching impacts, since students who participated in preschool education were 31 percent less likely to repeat a grade and 32 percent less likely to drop out of high school.

What’s your business answer and how did you come to this conclusion from your data analysis? What is the impact of your findings? Tell your reader up front what you found, and then support your findings with summary statements about and links to your analysis that you’ve uploaded to your GitHub repository. In some cases, you won’t be able to “solve” the business question because this is related to a larger systemic challenge or something that relies on many outside forces to solve. That’s okay--explain why this might be the case, and use your data analysis to support these statements. Interpret your methods in big-picture analysis, simple linear regression, correlation, multiple linear regression, and clustering into words that a general audience can understand, and relate these findings back to your original business question. [Clear data visualizations](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) and data tables can easily help point out trends, outliers, and distributions. Initially you told us why we should care about the problem, now tell us what you, an industry, company, group, demographic, or the reader can do about it based on your analysis. Be specific about your business answer, but don’t get lost in the details. Instead of saying “the trend shows that there is a problem with employment,” specifically point out the decline/increase or use a data visualization to specifically point out problem points. However, don’t get too specific in providing context for your analysis--the audience might want to point out specific significant variables from a linear regression model, but you don’t need to post a screenshot of the result of your full analysis table or list out the prediction equation or exact p-values for each variable. This section is the “meat” of your executive summary, but this shouldn’t be longer than a couple paragraphs.

# Future Suggestions
More fundings or rearranging fundings to spend on facilities of staffs to let student feel more belonging to school.

Now that you told us what needs to happen for your problem as a result of your analysis, how does this come into play in the next 6 months? Year? Ten years? What would you recommend happens in this industry/situation from an organizational, policy, leadership, or some other type of shift or pivot? Why is the future brighter based on this change and why should people care about this? This is similar to a conclusion, but also gives a clear call-to-action to the designated group/people who can do something about your original business question. This section should be about one paragraph.

## Additional Notes and Useful Links:
### Exploring your business question
I suggest picking a business question that’s related to Baltimore City, Baltimore City Government as a “business,” or another city government that you may be familiar with as a “business” since most major cities have well-populated open data portals, however, if you wish to explore a different business question, and you can find enough valid data to help you explore this topic, then you may pursue that topic. Here are some resources that might help you explore civic issues in Baltimore City and related resources: 
 - [_The Baltimore Sun_](https://www.baltimoresun.com/)
 - [_Baltimore Magazine_](https://www.baltimoremagazine.com/)
 - [Baltimore City Government Website](https://www.baltimorecity.gov/)
 - [Baltimore City Government Open Data](https://data.baltimorecity.gov/)
 - [Baltimore Neighborhood Indicators Alliance- BNIA](https://data-bniajfi.opendata.arcgis.com/)
 - [American Community Survey](https://factfinder.census.gov/faces/nav/jsf/pages/index.xhtml)
 - [Baltimore Brew](https://www.baltimorebrew.com/)

### Data Analysis
While you don’t (and shouldn’t) list out the entirety of your data analysis in your executive summary, you’ll need to upload your excel/Python/other data analysis work to your GitHub profile for a complete project. You don’t need to write up an explanation for each document you upload, but it should be clear what kind of analysis you conducted, why you chose this type of analysis, and your findings from each analysis uploaded. You can also upload data analysis that didn’t directly contribute to your business answer and suggestions to provide a robust background on your research. It should be clear to anyone in the class who isn’t in your group how you came to your data conclusions. 

### GitHub Issues and Projects
Utilize the GitHub Issues and Project feature to track your progress, collaborate with your team, and keep accounts of different resources and findings throughout your project. You can read more about submitting issues [here](https://help.github.com/en/articles/creating-an-issue), [here](https://guides.github.com/features/issues/), and [here](https://help.github.com/en/articles/about-issues).

### Executive Summaries
This write-up is similar to a business plan executive summary if your “service” is your business solution. While there are sentence/paragraph suggestions in each section, try to keep the written part of your executive summary to less than 2 pages typed in a Word document. Here are some good resources on business plans to learn more about why they’re important and how you should approach writing them:
 - [Crafting a Powerful Executive Summary, HBS](https://hbswk.hbs.edu/archive/crafting-a-powerful-executive-summary)
 - [Executive Summary Template, Forbes](https://www.forbes.com/sites/alejandrocremades/2018/07/31/executive-summary-template-what-to-include/#2cd9f1f85ddf) 

