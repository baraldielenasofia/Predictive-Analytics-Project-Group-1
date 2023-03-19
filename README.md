# Predictive-Analytics-Project-Group-1

*Repository to work in parallel on the Predictive Analytics group project (Group 1)*

**Predictive Analytics Group Assignment**

  1. Please work in your study groups on the attached Grosse Pointe Associates case, undertake the analysis required, and write a report for the management based on your analytical insights and your recommendation.
  2. Each group will submit one written report only. The report should be a maximum of 10 pages (+ optionally, Appendix) long in Word doc or PDF format and submitted on eLearning. Please give your files a name according to the convention: Name of group_MiM2021_PA_Group_Assignment.
  3. Please clearly state any assumptions you need to make, support your statements with statistical arguments, and interpret your findings from a practical perspective.
The report is due on Monday, 20 March, at 09:00 a.m.

**Assessment criteria**

The main assessment criteria will be:
• Quality of the report
• Analysis of the model
• Interpretation and insights

**Grosse Pointe Associates and the "Microvan"**

The case describes Grosse Pointe Associates (GPA) project investigating the potential market for "microvans". The project started with focus groups, demonstrating interest and generating a list of desirable attributes for the microvan. GPA then tested the microvan concept with 30 questions on its in-house panel. A small separate test panel was conducted prior to the entire panel survey.

**The objectives of this case are:**

1. To give you experience applying multivariate analysis, grouping variables, and segmenting
customers in a market
2. Based on the data analysis, determine which segment(s) would be good to target.
3. To relate the segment(s) to demographic variables potentially helpful in targeting
4. To enable you to make recommendations on which characteristics are most important for
creating favorable customer perceptions
This "capstone" case melds many multivariate techniques (e.g., regression, factor analysis, cluster analysis) in a decision-oriented setting. The survey data needed for the analysis are available on eLearning in the file microvan.csv.

**Background:**

The U.S. auto industry is always looking ahead to the next big trend in automotive design. Lead times are lengthy – several years from concept to prototype and several more to the dealer floor – with total costs for a new model line often topping $1 billion. Primary consumer research is the main method for detecting such trends, typically starting with targeted focus groups and proceeding to medium- and eventually large-scale surveys. These surveys serve at least two purposes: (1) to verify the "wants and needs" of a particular consumer group/niche and (2) to overlay purchase intent, sometimes along with other demographic or profit-based data.
Grosse Pointe Associates (GPA) is a boutique consulting firm located in Dearborn, Michigan. GPA chose its location for the proximity to major automotive company headquarters and its name because it called to mind upscale Grosse Pointe, an affluent suburb of Detroit and home to many industry executives. GPA's core business is dedicated to sleuthing out auto industry trends and then conducting exploratory marketing research to understand what is behind them. Although not exclusively an automotive consulting or market research shop, more than 70 percent of their annual revenue is generated from the auto industry.

Based on their ongoing biannual consumer panel surveys, GPA noted an intriguing trend: affluent couples with children (typically between one and three children) indicated an increased purchase intent for minivans. The traditional profile of minivan users encompassed a relatively undifferentiated market, middle to upper-middle- class families, usually with multiple young children in the household. Although GPA was not yet sure whether they had detected a statistical blip, a fad, or something more enduring, their data seemed to suggest that there was a luxury-oriented niche market of smaller families that still wanted the "kids and their friends" orientation of traditional minivans but with tighter size dimensions. Indeed, when asked about minivans currently on the market and why they had not purchased one, some of their panel respondents commented explicitly about not wanting a "tank" or a "boat".
GPA executives were seasoned market researchers and had extensive experience with the automotive market and manufacturers. A friendly debate emerged about what was "driving" the preferences for this potential new subcategory. Everyone agreed that smaller families among the educated and relatively affluent were a trend validated by detailed government census data. Were the emerging preferences arising from a desire to have their own version of the minivan (similar to those who wanted a small SUV)? Or were they perhaps spurred by the environmental movement, which sensitized consumers to excess and waste and produced blockbuster models like the Toyota Prius? It was likely a combination of these factors, with different families having distinct preferences for different minivan "attributes".

GPA started looking at precedents in the industry and quickly latched onto the "microvan". These were closely related to "K-cars", which were popular in Japan. Also called "Kei cars" and "keijidōsha", these are literally "light automobiles" and comprise an entire line of different car types – sedans, (micro)vans, and even light trucks – with the distinguishing feature that they were all diminutive, a major selling point in the Japanese market. The Kei cars emerged in Japan to skirt laws requiring vehicle owners to demonstrate that adequate parking is available. Still, they became popular as less-costly alternatives to their full-sized cousins as Japan rapidly urbanized in the 1960s and the ensuing decades. Some of the most prominent players among Japanese manufacturers produce K-cars, including Honda, Mitsubishi, Nissan, and Subaru. However, none had made an attempt to crack the U.S. market, which was perceived as not wanting to compromise on performance or size.

GPA ran several focus groups among potential buyers of such cars. These included heads-of-household in affluent, smaller families and those outside the supposed target group, for instance, city dwellers pressed for parking space and small business owners needing an economical way to make one-off deliveries. The focus group results were encouraging: many respondents were excited by the prospect, which was described as a potential "concept car" with specific attributes likely to wind up in the first U.S. microvans. But they also raised various concerns about power, acceleration, durability, space, novelty, reliability, etc., along with a "wish list" of capabilities and accessories that might tax engineers' ingenuity. The upside was that these groups indicated not only strong purchase interest but also a willingness to pay a premium over comparable vehicles currently on the market, such as smaller pickups, SUVs, or standard minivans, the last of which were often seen as too bulky and, notably, as conveying the "wrong image".

Given these encouraging results, GPA enlisted its in-house panel to test the "microvan" concept more rigorously. Their panel consisted of a large cross-section of the general US adult population with different stages of "lifestyle" and "buyer readiness". Because many demographic variables (age, income, education, etc.) were already available for household members, these would not need to be collected afresh. One of the felicities of using a panel is that a small or moderate number of questions could be added to their biannual online survey without the need for a special email drive; it also avoided calling particular attention to the topic of study, which could cause "yea-saying" (i.e., people will say they like something if asked only about that thing). GPA's surveys usually contained 150-200 total questions, and panelists agreed to respond within 7 days of receipt. When possible, results were compared to known distributions from the U.S. Census to ensure that respondent households were broadly representative of the population of potential auto buyers.
GPA looked over a lengthy list of potential "attributes" that could be important to prospective microvan purchasers and lifestyle statements (e.g., psychographics) validated by their extensive past research in the auto industry. Based on detailed notes taken during the focus group phase, they settled on a set of 30 attributes that seemed to capture the nature of the discussion and essential psychographic variables. They aimed to use these attributes to capture the key dimensions important to potential buyers and identify segments that auto companies could target [These 30 questions appear at the end of the case]. GPA also decided to include one additional question about the overall attractiveness of the product concept. That seemed more appropriate than asking about "purchase likelihood," which could be confounded with many other variables, such as whether one was in the market for a new vehicle or the ability to achieve financing during tough economic times.

After running a small pre-test on a separate panel to work out any kinks in the question wording, GPA unleashed its complete panel survey. Within a week, they had many thousands of responses. Some of these were from demographic groups unrelated to the target markets identified by the focus groups, and others were in a state of low purchase readiness (that is, they either had recently purchased a vehicle or explicitly expressed that they were not looking). Careful screening allowed GPA to identify households from appropriate target markets who indicated a non-zero likelihood of purchasing a new car in the next year. Data on a random sample of 400 of these respondents are included here for analysis, along with seven additional demographic and behavior-based questions, as listed at the end of this case (specifically: the respondent's age, household income, gender, number of children, educational level, miles driven per year, and self-reported recycling activity).

GPA's management aimed for massive data reduction and increased understanding and communicability of the survey results. They started with 400 responses to 30 attribute questions, each measured on a 1-9 Likert scale (12,000 pieces of data in all), and were hoping to compress them into a much smaller number of factors and clusters. For example, using (say) 6 factors and 4 clusters means representing the 12,000 pieces of data with just 24 numbers, a 500-fold reduction. But this would be pointless if the representation discarded vital features of the data or helped explain the "concept liking" variable dramatically less well.
Based on the analysis, the team needs to prepare a report for upper management discussing the viability of the microvan concept and the different profiles of the potential segments that would help elucidate its potential for success in the U.S. market.


**Case questions:**

*1. Data verification*
--> Perform an exploratory analysis of the data. Check that there are no problems with the variables themselves, especially outliers that can unduly influence results. You can accomplish that by looking at frequency distributions or histograms for each variable and an overall correlation matrix. Flag any observations that seem wildly different from the others, perhaps indicating a misunderstanding of the task or lack of involvement by the respondent.

*2. Establish a relationship*
--> It is critical to determine whether there is a relationship between the 30 attributes (independent variables) and the target (dependent) variable. That can be accomplished via regression in several stages.
A. First, regress the concept liking variable (mvliking) against all 30 attribute variables. What
does the regression output indicate?
B. Next, try to find the "best" model by running stepwise regression, again using the 30 attribute
variables as regressors. Does this model make good sense? Is anything left out that appears critical or anything included that seems tangential? Be sure to run a separate, final regression on just the "retained" variables to have a complete set of regression statistics and diagnostics. You may wish to generate a residual plot to visually assess whether the "errors" appear to be randomly distributed or whether they "clump" in a way that might indicate omitted explanatory variables.
Hint: Theols_step_both_pfunction from theolsrrpackage performs a stepwise model selection. Use the criteria of p-value, by which only variables with a significant p- value enter the model.

*3. Data reduction*
--> Thus far, the analyses show how well the 30 attribute variables explain the concept liking variable. These results may potentially be improved by uncovering the degree of redundancy in the 30 attribute variables. That can be evaluated via factor analysis in several stages:
A. First, do a factor analysis and use the scree plot to help determine the appropriate number of factors. What would you use: principal component analysis or common factor model? Explain. 
B. Next, extract that number of factors using some rotation method to help with factor
interpretation.
C. Finally, based on your examination of the "factor loadings", provide descriptive names for the factors. Once you are satisfied with these results, save the factor scores for further analysis.
Remember to discuss all crucial decisions on each step of factor analysis (e.g., number of factors, rotation method).

*4. Explanation*
--> Run another regression, this time using the saved factor scores in place of the original attribute variables and again using concept liking as the dependent variable. What does this new regression suggest compared with the prior regression results?

*5. Segmentation*
--> Please segment the market using cluster analysis based on the factor scores obtained previously – also, remember to interpret and discuss the meaning of the clustering solution. Discuss all crucial decisions on each step of cluster analysis (e.g., clustering variables, number of clusters, linkage methods, a clustering method).

*6. Interpretation of the results*
--> Finally, we can relate clusters to the self-reported respondent demographics to run a "reality check". Please explore the demographic profile of each of the clusters. Given your findings about the "needs and wants" of each cluster, do the clusters make sense? How do the seven demographic variables relate to (i) the original 30 attribute variables and (ii) the factors for the entire sample and clusters (Hint: for example, you may look at the correlation matrix).

The data is available in the file microvan.csv. If you are running the analyses in R, please use the following code at the beginning to read in the data and convert all integer variables into numeric ones for further work:
microvan <‐ read.csv("microvan.csv", sep = ";") library(data.table)
microvan <‐ as.data.table(lapply(microvan, as.numeric))

**Questions and codes used in the panel survey**

- **v01 kidtrans** --> We need a car that helps transport our kids and their friends.
- **v02 miniboxy** --> Current minivans are simply too boxy and large.
- **v03 lthrbetr** --> Leather seats are dramatically better than cloth.
- **v04 secbiggr** --> If we got a second car, it would need to be bigger than a standard sedan. 
- **v05 safeimpt** --> Auto safety is very important to me.
- **v06 buyhghnd** --> We tend to buy higher-end cars.
- **v07 pricqual** --> Car prices strongly reflect underlying production quality.
- **v08 prmsound** --> A premium sound and entertainment system helps on long car trips.
- **v09 perfimpt** --> Performance is very important in a car.
- **v10 tkvacatn** --> We try to take as many vacations as possible.
- **v11 noparkrm** --> Our current residence doesn't have a lot of parking room.
- **v12 homlrgst** --> Our home is among the largest in the neighborhood. 
- **v13 envrminr** --> The environmental impact of automobiles is relatively minor. 
- **v14 needbetw** --> There needs to be something between a sedan and a minivan.
- **v15 suvcmpct** --> I like SUVs more than minivans since they're more compact.
- **v16 next2str** --> My next car will be a two-seater.
- **v17 carefmny** --> We are careful with money.
- **v18 shdcarpl** --> I think everyone should carpool or take public transportation.
- **v19 imprtapp** --> Most of our appliances are imported.
- **v20 lk4whldr** --> Four-wheel drive is a very attractive option.
- **v21 kidsbulk** --> Our kids tend to take a lot of bulky items and toys with them.
- **v22 wntguzlr** --> I will buy what I want even if it is a "gas guzzler".
- **v23 nordtrps** --> We don't go on road trips with the family.
- **v24 stylclth** --> We tend to purchase stylish clothes for the family.
- **v25 strngwrn** --> Warranty protection needs to be strong on a new car.
- **v26 passnimp** --> Passion for one's job is more important than pay.
- **v27 twoincom** --> Our family would find it hard to subsist on just one income.
- **v28 nohummer** --> I am not interested in owning a vehicle like a Hummer.
- **v29 aftrschl** --> We engage in more after-school activities than most families.
- **v30 accesfun** --> Accessories really make a car more fun to drive.

- **age** --> Age of respondent in years
- **income** --> Annual household income in thousands of dollars
- **miles** --> Total annual amount driven by household members in thousands of miles
- **numkids** --> number of children (aged 0-18) residing in household 
- **female** --> Whether or not the respondent is a female
- **educ** --> Education level of respondent (1 = High School, 2 = Some College, 3 = Undergraduate Degree, 4 = Graduate Degree)
recycle Self-reported recycling compared to average (1 = Much Less, 2 = Somewhat Less, 3 = Average, 4 = Somewhat More, 5 = Much More)
