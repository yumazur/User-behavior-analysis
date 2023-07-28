# User-behavior-analysis
Project «User behavior analysis». Built a sales funnel, explored the path of users to purchase. Analyzed the results of the A / A test and the A / B test. Checked the hypotheses about the equality of shares for the stages of the funnel.
### Objective: 
* Explore the results of an A/A/B test to change fonts throughout the application. Find out if the font affects the behavior of visitors;
* Analyze the sales funnel.
### Skills and tools:
Python, Pandas, Seaborn, Plotly, Matplotlyb, A/B testing, event analytics, product metrics, testing of statistical hypotheses
### Examples of visualizing data from a project:
![UserBehavior](https://github.com/yumazur/User-behavior-analysis/assets/140715941/35fd24db-5d0f-48d6-aaf2-3712fc698d58)

### Analysis results:
1. Changes (new font) made to the test group did not have a significant impact on user behavior compared to the control group;

2. Based on the conducted A/B test and the obtained p-values, we conclude that there were no statistically significant differences in the steps of the funnel between the control and test groups;

3. Testing was carried out on data received within one week. Such a period of time may be sufficient to conduct an AB test if it is necessary to quickly see and evaluate significant changes in user behavior. However, if there is a need to increase the accuracy of the results, then it is recommended to increase the time for data collection. This can help increase the sample size and reduce the influence of random factors on test results. In addition, a longer testing period can help to see the longer term effects of the changes that are made to the test population. Font is a parameter whose influence can only be assessed over a long period of time. However, increasing the testing period may take more time and resources, which should also be taken into account. If the changed font is not intended to increase conversion and the assessment is needed only to understand whether it will have a negative impact, then the result of the A / B test indicates that the font does not have any negative impact at this stage.

4. To test the statistical hypotheses, a significance level of 0.05 and the Bonferoni correction were used, since the test would be multiple and the ratios of the shares were checked. In total, we conducted 15 tests between groups to compare proportions.

`Sales funnel` (calculations of previous). The biggest losses at the stage of transition from the main screen to the offer:

- `100%` MainScreen
- `60%` Offers Screen
- `80%` CartScreen
- `94%` Payment

### Recommendations to improve the conversion
- Analyze and improve the attractiveness of the main screen of the site in order to increase the number of users who go to the offer page.
- Optimize the offer page to increase the likelihood of users adding items to their cart. Perhaps this can be done by improving product descriptions, adding photos, etc.
- Optimize the checkout process to increase the number of users completing a payment successfully.
- Carrying out test changes at each stage of the funnel with subsequent analysis of the results will determine the most effective measures to increase conversion and improve user experience on the site.  
  
