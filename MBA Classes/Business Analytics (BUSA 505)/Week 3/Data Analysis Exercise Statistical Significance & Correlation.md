#BusinessAnalytics
1. Explain what a p value is. When is it used and what insight does it provide?
	1. P-value tells how likely a result happened by chance. We use it to figure out if finding are statistically significant, they're not random.
2. What does p < 0.05 mean?
	3. There is less than 5% chance of this result, this prompts rejecting the null hypothesis and accepting the alternative.
3. What is confidence level? For example, if I have a 95% confidence level, what does that mean?
	1. A measure that suggests the probability of something. A 95% confidence level means that you are 95% confident that the result lies within an expected range.
4. Sometimes p values are attributed to giving a false positive. What does this mean and how might it be avoided?
	1. A false positive appears true but is false, this can be avoided with stricter p-value and multiple tests. 
5. What is a null hypothesis and how does it relate to p value?
	1. The null hypothesis is a statement that there is no significant difference between two variables. The p-value helps to inform the decision to reject the null hypothesis, and accept the alternative hypothesis. 
6. If your p value is high (above 0.05) what does this mean?
	1. There isn't enough reason to reject the null hypothesis, there is a not a big difference between the two groups being compared.
7. If your p value is low (below 0.05) what does this mean?
	1. There is enough reason to reject the null hypothesis, there is a big difference between the two groups being compared. 
8. Is a p value the same as an error rate? Explain your answer.
	1. No, p-value is related to the probability of making an error rate, the error rate is the proportion of times errors occur.
9. Below are the actual results of a study that was done with an organization to determine if there was a difference between how two different divisions viewed leaders. In other words, were there certain attributes one division looked for in their leaders that were significantly different than the other divisions? Understanding this was important to the organization to determine why one division was outperforming the other division. It was hypothesized that a difference exists between the two divisions in terms of the attributes they looked for in their leaders, which ultimately resulted in different performance outcomes.
	1. What problem is this organization trying to solve?  
		1. Why one division is outperforming the other. They think that differences in the leadership attributes valued by each division might be a contributing factor.
	2. Review the data set and determine which attributes demonstrate statistical significance (p < 0.05) and which do not. Hint: this output is from a 2-tailed t-test. You’ll learn more about t-tests in the next module, but this should guide you on where to look for the p value in the table.
		1. Statistically Significant Attributes (p < 0.05): Self-protective, Participative
		2. Not Statistically Significant Attributes (p > 0.05): Charismatic, Team-oriented, Humane-oriented, Autonomous
	3. Based on the hypothesis stated above, what would the null hypothesis be?
		1. The null hypothesis is that there is no significant difference between the two divisions in terms of the attributes they look for in their leaders.
	4. Based on the data output below, can the null hypothesis be rejected? Explain.
		1. We can reject the null hypothesis for the "Self-protective" and "Participative" attributes. The p-values for these attributes are less than 0.05, this means the observed differences between the two divisions are statistically significant.
	5. Based on these data, what might be your next steps in researching/evaluating similarities and/or differences among the divisions pertaining to the attributes they look for in leaders?
		1. Exploring more specific aspects of the significant attributes: Self-protective and Participative, in addition to surveys or interviews to better inform understanding.
	6. How might you use these data points to discuss with senior leaders in your organization on where to focus leadership development & training efforts? 
		1. Prioritize leadership development programs that enhance Self-protective and Participative behaviors, particularly in the underperforming division. Focus on specific needs and preferences of each division.
	7. What data are missing to make a compelling case?
		1. Other performance metrics, employee satisfaction, and workspace culture
10. You are working as a Manager at Exelon Energy at the Three-Mile Island facility on energy conservation. A sampling of data from 20 households has come in and you notice that households that have moved to energy conserving devices have saved Exelon 29,089 kilowatt hours. This is great news. However, you’d also like to determine if the size of the household is positively correlated to kilowatt hours usage and the strength of the correlation. Perform a correlation test on the data presented in the spreadsheet. 
	1. The correlation coefficient for family size “without energy conserving device”
		1. Correlation Coefficient: 0.3236
	2. The correlation coefficient for family size “with energy conserving device”
		1. Correlation Coefficient: 0.1979
	3. Explain the results and what information can be drawn from this calculation. 
		1. Without Energy-Conserving Devices: The correlation coefficient of 0.3236 suggests a moderate positive correlation between family size and energy consumption. Larger families tend to consume more energy, but the relationship is not very strong.
		2. With Energy-Conserving Devices: The correlation coefficient of 0.1979 indicates a weak positive correlation. The relationship between family size and energy consumption is less pronounced when energy-conserving devices are used.
	4. Discuss limitations of your calculations and its ability to be generalized to the broader energy conservation program.
		1. A sample size of 20 is quite small, the energy-conserving devices can be varied in used and could impact the numbers, and other variable factors like lifestyle and income could effect energy-consumption. 