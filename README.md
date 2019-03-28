**Analyze A/B Test Results**

**Summary**

A/B tests are very commonly performed by data analysts and data scientists. It is important that I get some practice working with the difficulties of these.

For this project, I was working to understand the results of an A/B test run by an e-commerce website. The company has developed a new web page in order to try and increase the number of users who &quot;convert,&quot; meaning the number of users who decide to pay for the company&#39;s product. My goal was to work through this notebook to help the company understand if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision.

**Conclusions**

Through studying the 3 steps below of this project we can summarize our conclusion as follows:

**Part I - Probability:**

If the statistical results is not interpreted accurately it will mislead us and lead us to wrong analysis and decisions for example (Simpson&#39;s Paradox).

**Part II - A/B Test**

In the hypothesis test we fail to reject the null hypothesis where statistically old page conversion rate is better than or equal to the new page conversion rate.

**Part III - A regression appr**** oach**

Logistic regression is used because the response variable &#39;converted&#39; has (0 or 1) or (True/False) values and the regression results agrees with A/B test results. Adding extra variable like &#39;country&#39; doesn&#39;t influence or add something useful to the regression model as shown in the results.

**Final conclusion and decisions**

According to the previous 3 stages analysis we did not found clear statistical significance between the old page and the new page but if we take practical significance into considerations the duration of the test which is 22 days is too short to find a statistical significance therefore the test of significance should take enough period of time for example (6 months) to find clear statistical or practical significance to take decision to run the new page or to stop it.
