
# A/B Test on Website Text Reduction
This project aims to determine whether reducing the amount of text on a company's website, which sells a digital product, and presenting users with a simplified version will result in an increase in sign-up demos. <br> 
<br>
We will use A/B testing to measure the performance of the changes on the website for the control and experimental groups and to identify whether there is a statistically significant difference between these two.

<br>

![App Screenshot](https://i.imgur.com/avkviYm.png)

## 💾 Data & Tools
The data presented in this readme file is purely fictional. The purpose is to practice the general process and steps involved in running an A/B test. 

For conducting the analysis of results, **Python** was used along with several popular libraries such as: <br>
✅ NumPy = for numerical computing. <br>
✅ Pandas =  data manipulation. <br>
✅ Matplotlib = data visualization.<br>
✅ Scipy = to perform statistical tests on the data. <br>

## 🔎 Experiment Design
### Variants
There are two variants:<br>

**Control Group (Variant A)**: Current website with extensive text.<br>
**Test Group (Variant B)**: Light version of the website.<br>

## 📍 Hypothesis
We will consider Variant B superior only if it proves to be better at a Type I error rate of 5%. The hypotheses are defined as follows:

**H0: PB - PA = 0 (Null Hypothesis)**<br>
**H1: PB - PA > 0 (Alternative Hypothesis)**<br>

The null hypothesis (H0) states that there is no significant difference in conversion probability between the two variants, indicating that the amount of text on the website does not affect the chances of conversion. The alternative hypothesis (H1) states that there is a significant difference in conversion probability between the two variants, implying that the amount of text on the website may impact the likelihood of conversion.

## 🎯 Metric
The primary metric for this A/B test is the conversion rate, defined as the proportion of sessions ending up with a transaction, in this case users signing up for a demo. We will use the conversion rate to determine the success of the A/B experiment.

## 📏 Sample Size
The probability of being exposed to either variant is equal, but the probability of conversion is approximately 19% for the new variant, compared to around 16% for the old variant.

## 📊 Results
The experimental group (B) converted more users than the control group (A), and the difference in conversion rates between the two groups is slightly bigger than the target we set. However, we need to evaluate how confident we're in the result by looking at the distribution of the two groups.

We plotted the distribution of the control group and calculated the probability of obtaining the result observed in the experimental group. The probability of getting the result from the test group (B) was close to zero.

## ✍ Conclusion
Based on the results, we can conclude that reducing the amount of text on the website increases the likelihood of conversion. Therefore, we should proceed with the simplified version of the website.


