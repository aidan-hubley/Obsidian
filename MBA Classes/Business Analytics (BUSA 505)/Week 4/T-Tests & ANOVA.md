	The first four questions are meant to validate our understanding of statistical concepts and do not require use of the dataset.

1. When would you use a t-test to analyze data?
	1. A t-test is used to compare means between two groups of data, it's helpful when the sample size is small or the standard deviation is unknown.
2. Describe the difference between a single-tailed and two-tailed t-test.
	1. A one-tailed t-test is used when you have specific direction for the difference between the means.
	2. A two-tailed t-test is used when you don't have a direction but still want the difference.
3. What is the difference between a t-test and ANOVA?
	1. A t-test compares the means of two groups.
	2. ANOVA compares the means of three or more groups, it determines if there is an overall difference between the groups.
4. Explain the difference between an independent t-test and a paired t-test.
	1. An independent t-test compares the means of two independent groups.
	2. A paired t-test compares the means of two related groups.

---

	The next set of questions will enable us to assess the Treatment Group Results vs Placebo Group Results aspect of the study.

5. Is there a significant difference between the average ages of patients that received the treatment drug versus the placebo?
	1. No. running a two-tailed test on the ages of the patients provides a result of 0.954, meaning that there is no significant difference between the ages of the patients that received the treatment drug verses the placebo.
6. Is there a significant difference between the Treatment Group Results (week 2/4)?
	1. Yes, p-value: 0.005129912. There is a significant difference.
7. Is there a significant difference between the Treatment Group Results (week 4/6)?
	1. Yes, p-value: 0.019920866. There is a significant difference.
8. Is there a significant difference between the Treatment Group Results (week 6/8)?
	1. Yes, p-value: 0.289285514. There is not a significant difference.
9. Considering the results of Q6-8 now run a test that allows us to compare all weeks at the same time for the Treatment Group Results.  When describing what the result of this test means be sure to state it in a way that compares/contrasts the Q9 result vs the Q6-Q8 results where it makes sense to do so.  Let’s also see what this test shows us for the Placebo Group Results.
	1. To compare the treatment group results across all weeks simultaneously, an **ANOVA** was performed. The ANOVA test provided a p-value of: 0.114908, this indicates a significant difference in treatment results across the different weeks. This confirms the findings from the pairwise t-tests in Q6-Q8, which identified specific differences between certain weeks. However, the ANOVA provides a more comprehensive overview by indicating that at least one week's results differ significantly from the others.
	2. To compare the placebo group results across all weeks simultaneously, an ANOVA was performed. The ANOVA results indicate no significant difference in placebo results across the different weeks (p = 0.272966). This suggests that any observed differences in the treatment group are likely due to the treatment itself, rather than other factors like natural progression of the disease or placebo effects.
10. Let’s try one final approach with these Treatment Group & Placebo Group Results. Please add an additional column to the tab within the spreadsheet that houses this data.  In that column, add up the results from weeks 2 through 8 for all of the respondents in both groups.  Now, compare the added up results for the Treatment Group and the Placebo Group.  Is there a significant difference between those who received the Placebo vs those who received the experimental drug treatment?
	1. When running a two-sample t-test on the summed data, comparing all weeks of data from the placebo group to the drug group, p-value: 0.829952. There is no significant difference between the summed results from the two groups.

---

	The next set of questions will allow us to examine the Pain Level & Side effect data.
	
11. Looking at Group A and Group B separately, consider the fact that each person experiences (to a certain degree) a level of pain and a side effect of some sort.  For each group run a test that can tell us if there are differences between the patients themselves and then, separately the pain levels and side effects.  Do results vary by patient to such a degree that we may need to learn more about the specific patients and classify them based on unique characteristics not presented in this data before re-running results?  Do higher pain levels imply higher degrees of side effects?
	1. One-way ANOVA was used to compare pain levels and side effects among individual patients within each group (A and B).
		1. For both groups, the ANOVA results indicate **no significant differences** between individual patients in terms of mean pain levels and side effects. (Group A p-value: 0.592319, Group B p-value: 0.862482)
	2. Correlation Analysis was used to assess the relationship between pain level and side effects within each group.
		1. Group A: A weak negative correlation (-0.175652) was found, suggesting a slight tendency for higher pain levels to be associated with lower side effects.
		2. Group B: A moderate positive correlation (0.721691) was found, indicating that higher pain levels tend to be associated with higher side effects.
	3. There are no significant differences between individual patients within each group, the relationship between pain and side effects varies between the groups.
12. Now let’s think about how we proceeded for Q11 and ask what would happen if we combined Groups A & B into a single “supergroup”.  We want to perform another test that will tell us if there are not only differences between patients and pain levels vs side effects but this test should also tell us if anything about the how if at all the patients interact with the pain levels and side effects.  Please run that test and share your observations.
	1. Based on the two-way ANOVA, there is no evidence to suggest significant differences between groups or individual patients in terms of pain levels and side effects
		1. There is no significant difference in mean pain levels or side effects between Group A and Group B.
		2. There is no significant difference in mean pain levels or side effects between individual patients, regardless of group.
		3. There is no significant interaction effect between Group and Patient that depends on the individual patient.

---

	After answering the above questions it is time to summarize your results for the Board.
	
13. The last question for this assignment will enable you to provide your recommendations to the Board of Directors. Be sure to communicate in terminology that the Board members can understand while, in doing so, ensure that the key reasons for your recommendation around spending more money on research is backed by the results of your own research on the data provided.  The letter should not exceed one page in length.
	1. Here are the key findings:
		1. Treatment Group:
			1. Significant improvements were observed in the treatment group from week 2 to week 6.
			2. However, there was no significant improvement from week 6 to week 8.
		2. Placebo Group:
			1. No significant differences were found in the placebo group across the different weeks.
		3. Patient Variability:
			1. Within both the treatment and placebo groups, there were no significant differences between individual patients in terms of pain levels and side effects.
			2. The relationship between pain and side effects varied between the groups.
	2. Based on the data analysis, we recommend further investment and research in the experimental drug. The significant improvements observed in the treatment group from the weeks of 2 to 6 demonstrate the potential efficacy of the drug. Unfortunately, the lack of significant improvement from the weeks of 6 to week 8 raises concerns about the long-term efficacy and potential plateauing of the treatment's effects. Additional research is necessary to investigate the optimal treatment duration and potential strategies ensure sustainable benefits. By investing in further research, we would be able to gain valuable insights into the long-term efficacy and safety of this experimental drug, ultimately leading to improved patient outcomes.