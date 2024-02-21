# Project-1
This is the repo for Project 1 for UPENN Data Analytics Bootcamp.

The dataset analyzed in this notebook is a synthetic dataframe created by ChatGPT, the results that have been concluded based on these findings are not based in reality and should not be taken as fact.

Question: Is there a relationship between Review Rating and demographic factors (specifically Age Group and Gender)?

Hypothesis:  Male Millennials would have the highest average review rating, while Male Baby Boomers would give the lowest. Similarly, Female Baby Boomers would have the lowest review ratings, while Gen Z and Gen X give the highest review ratings.

Analysis: I created two separate boxplots for Males and Females of different Age Groups and their respective Age Group Review Ratings. The boxplot for average rating for Males of various Age Groups shows that Male Gen Z’s had the highest average Review rating, while Male Millennials had the lowest average Review Rating. Similarly, for average ratings for Females of different Age Groups, the boxplot shows that Female Baby Boomers give the highest Review Ratings. In contrast, Gen X and Millennials give the lowest Review Ratings.

Following the boxplot analysis, I completed an ANOVA T-Test for Males whereby the null hypothesis said the average Review Rating for the population of Males of different Age Groups is equal to the average Review Rating for samples of Males of different Age Groups. As the p-value was greater than α = 0.05, we can accept the null hypothesis. I also completed an ANOVA T-Test for Females whereby the null hypothesis said the average Review Rating for the population of Females of different Age Groups is equal to the average Review Rating for samples of Males of different Age Groups. As the p-value was greater than α = 0.05, we can accept the null hypothesis.

Question: What type of clothing is purchased most for each of the four seasons?

Hypothesis: Clothing and accessories were purchased the most during the Spring and Summer, while Outerwear and Clothing were purchased the most during the Fall and Winter.

Analysis: I created four bar charts for each season, with bars respective to each attire category. The bar charts for the four seasons showed that clothing had the highest number of purchases for all four months, with accessories as the second most-purchased attire category, footwear third, and outerwear fourth.

Question: Is there a relationship between Purchase Amount (USD) and Review Rating?

Hypothesis: There is a slightly positive correlation, whereby as the Purchase Amount (USD) increases, the Review Rating will increase because a higher price corresponds to improved quality.

Analysis: To solve this, I created a scatterplot with the Purchase Amount (USD) on the x-axis and the Review Rating on the y-axis. The scatterplot shows no relationship between Purchase Amount (USD) and Review Rating.

Question: Is there a relationship between Review Rating and Purchase Amount (USD)?

Hypothesis: There is a slightly positive correlation, whereby the higher the Review Rating, the higher the Purchase Amount (USD) because one would be willing to spend more money if they believed the product was of high quality.

Analysis: To solve this, I created a scatterplot with a Review Rating on the x-axis and a Purchase Amount (USD) on the y-axis. The scatterplot shows no relationship between Review Rating and Purchase Amount (USD).

Question: Is there a relationship between Previous Purchases and Purchase Amount (USD)?

First Scatterplot: Purchase Amount (USD) dependent on Previous Purchases

Hypothesis: There is a slightly negative relationship between Previous Purchases and Purchase Amount (USD).

Analysis: I created a scatterplot with Previous Purchases on the x-axis and Purchase Amount (USD) on the y-axis to solve this. However, the scatterplot shows no relationship between Previous Purchases and Purchase Amount (USD), and various factors, including income level, shopping habits, and personal preferences, primarily confound the results.

Second Scatterplot: Previous Purchases dependent on Purchase Amount (USD)

Hypothesis: There would be no relationship between the Purchase Amount (USD) and Previous Purchases, and the scatterplot proved my hypothesis.
Analysis: To solve this, I created a scatterplot with Purchase Amount on the x-axis and Previous Purchases on the y-axis. I hypothesized that there would be no relationship between purchase amount and Previous Purchases, and the scatterplot proved my hypothesis correct.

Question: Which age demographic spends the most money? 

Hypothesis: Younger generations, like Gen Z and Millennials, spend more money compared to older generations like Gen X and Baby Boomers.

Analysis: To find the answer to this problem, a bar chart was created that sorts the four different age groups by the average amount they spend per purchase. As the bar chart concluded, the four age groups's average spending amount was nearly identical, with a slight lead in Gen Z over the others.

Question: How frequently do specific age demographics shop (bi-weekly, bi-monthly, ect)? 

Hyopthesis: Younger generations may shop more frequently, while older generations shop less frequently.

Analysis: To solve this, we first separate each age group into its own dataset, then create bar and pie charts based on the frequency of their purchases. We concluded that Baby Boomers and Gen Z most frequently shop annually, Gen X most frequently shops monthly, and Millennials most frequently shop every 3 months. Overall, the most frequent frequency of purchase is every 3 months, while the least frequent frequency of purchase is weekly.

Question: What is the correlation, if any, between the colors of items purchased and the season they were purchased in?

Hypothesis: In contemporary society, the notion of parading and wearing certain colors that act as a celebratory zeitgeist is widespread. For many, colors serve as a proxy to symbolize the unique energy and spirit that each season delivers. For example, in the Fall, it is common to see others adorn clothing, accessories, and decorations with red, yellow, bronze, and orange. However, in winter it is presumably more acceptable to wear colors such as grey, steel, gray, and blue to represent the coldness of the atmosphere. As such, I sought to further analyze these trends using statistical techniques such as aggregation and summary statistics to better understand the totality of consumer consumption and cultural acuity. Essentially, I sought to answer one question: how much do different consumer bases subscribe to sociocultural norms that specifically dictate clothing is "in season" and "out of season."? 

Analysis: According to my analysis, the data is inconclusive in answering any of the aforementioned questions. There were no proven patterns among seasons and colors of items purchased that would deduce a relative and statically significant correlation between the two variables. This could possibly be because the -dataset used contains synthetic AI-generated data as opposed to "real-world" data. I accept the null hypothesis.

Question: Do certain age demographics subscribe to a similar cultural coloring phenomenon?

Analysis: To answer this question, I sought to analyze the consumption -patterns of various generations to deduce if any of them obey the cultural and social norms that surround color conformity. However, according to the data, no such conclusions could be drawn as no statistically significant correlation could be corroborated. In such a case, I accept the null hypothesis.

Question: How often do certain age groups shop?

Analysis: When reviewing the online shopping habits of different generations, it was determined that Baby Boomers (Ages 60+) spend the most time shopping virtually. Millennials were a close second with Gen-z and Gen-x listed as the generations least likely to shop online.

Question: What region spends the most frequently?

Analysis: Alternately, when reviewing states who shop online the most, it was determined that Montana and California had a higher frequency of data points when compared to 30+ states in which the study collected data. My initial hypothesis was not reflected in the data. I anticipated the younger generations to spend more time online-this was not the case. In addition, I did not expect Montana to spend the most time online.

Question: How does the average online shopping expenditure of Gen Z compare to that of Millennials?

Hypothesis: Gen Z (13-26) and Millennials (27-42) exhibit higher average spending on purchases compared to older generations, such as Gen X (43-59) and Baby Boomers (60-69).

Analysis: Upon analyzing the provided data on average spending by generation group, it appears that across different generation groups reveal a remarkably consistent pattern, with minimal variation in purchase amounts ranging from approximately $60.29 to $60.85 across Gen Z, Millennials, Gen X, and Baby Boomers. This suggests a similar level of consumer expenditure among these demographics.

Question: Which age group or generation tends to make more purchases when discounts or promotions are offered?

Hypothesis: Younger generations, such as Gen Z and Millennials, are more likely to apply discounts compared to older generations like Gen X and Baby Boomers.

Analysis: The analysis of discount application by generation group indicates a consistent trend across different age demographics, with a slight variation in the count of discounts applied between “No” and “Yes” categories. Specifically, Baby Boomers demonstrate a higher count of discounts applied compared to other generations, suggesting a notable propensity for seeking out and utilizing discounts among this demographic.
