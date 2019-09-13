## Problem Statement

In the USA, most colleges use two types of testing metric to measure a student's ability to solve complex problems within a limit amount of time. The SAT was the original intelligence based test to gauge an individual and see their ability use reason and logic to approach a given problem or situation. Eventually, the testing to ACT was introduce to test an individuals academic knowledge which aligned better for high level education institutions. Given the data of 2017 and 2018 average scores per State, I want to examine if the test scores have increased or decreased year on year and hypothesize the implications of the result. In addition, participation rate of each exam is sampled in order to examine the relevance of each test per state as well as identify if it contributes to the average of scores. Ultimately, I want to examine if the change in scores is related to their participation rates and if the scores are affect by the rates.  



----
## Relevant Files
* [Notebook](https://git.generalassemb.ly/tempyst/project_1/blob/master/code/starter-code.ipynb)


----
## Executive Summary
My initial thought before any data analysis was to look at the raw data and see if any trend can be seen just by looking at the numbers for just a particular year. Without performing any mathematical application to the data, a quick glance can give a good idea what I am looking at. Due to my lack to knowledge regarding how ACT testing methodology works, a quick research was necessary to understand how my comparison with modeling will be affected. After reading up on ACT and being up to speed, it was time to examine the data in aggregate. 

Initially, the data had some cleaning that needed to be done. Some of the columns within the data did not have the right datatype for mathematical analysis. Name consistency as well as score format was important so that modeling can stay consistent and the process will not show errors. Initially, I did the basic statistic summary which included finding the average, finding deviations from the mean, and looking at the minimum/maximum values of the data. This will give me a general idea of the spread in data points and see if anything looks out of the ordinary. Because ACT and SAT used different scaling, directly comparing them would be misleading. For easier maneuvering of data columns, names were changed to snake case and lower case to prevent any case senstive issues. The participation column was converted to an integer type but did not scale down the numbers into decimals since labeling the graphs with the appropriate scale will relieve any confusion of their size.

As I begin the modeling, I examined the overall distribution of scores for each year and each test. I noticed that the distribution renders a shape similar to a normal distribution curve and I suspect additional data will in fact, converse the shape toward a smooth curve. Next was overlaying the respective test scores over the 2 years and look for any observable differences without applying any statisical analysis to the numbers. Upon further discovery, it was concluded that the mean score for each test year on year did exhibit a decrease. 





## Conclusion and Recommendations
The research above showed that the rates of particiation is being influenced where their changes in rates from year to year is not by random chance, but a direct result of some actions. In addition to the participation rates, the ACT test scores appeared to be quite similar year on year as we have observed from the scatter plot.  Reviewing the boxplot gives us a r value of .94 which is very consistent. However, when performing the t-test to see if the averages were similar, it was discovered that it was not the case. There might be another factor to explain the difference, however misucule the deltas were for the composite scores year on year.

As the heatmap as well as the research in Ohio shows, higher participation rate is highly correlated with lower test scores. As explained above, this is can be attributed to have all students, rather they received enough preparation or not, take the exam and potentially lowering the average. From the data, it appears that Oregon has quite low rates for participation. This is caused by the state mandating the use of "Smarter Balance" (https://www.opb.org/news/article/oregon-schools-students-test-scores-2018-2017/) exams to gauge a student's proficientcy at academia. Because the Oregon has mutliple standardized test, each exam is trying to wrestle with each other for examinees across the state. 

I believe Oregon should vote to converge toward a single stanard for college admission exams. Because the exams themselves have different metric of measure how a particular student perform, it might be difficult for institutions to identify a student's ability. Therefore, I recommend all states, not just Oregon to adopt a single test policy, preferably SAT.
