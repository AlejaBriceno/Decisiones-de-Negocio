# Data-driven business decisions
I prioritized hypotheses using Reach, Impact, Confidence, and Effort (RICE) provided by the Marketing department, conducted an A/B test, and concluded that users in group B purchase more than those in group A

## 🛠️ Technologies used:
Python, NumPy, SciPy, Matplotlib, Datetime, Statsmodels, Seaborn

## ✅ Objectives:
-Apply the ICE framework to prioritize hypotheses.

-Apply the RICE framework to prioritize hypotheses.

-Show how the prioritization of hypotheses changes when using RICE instead of ICE.

## 🔍 Procedure
1. Read the data
2. Data preparation: check for duplicates, missing values, data types, rename columns
3. Data analysis:
     -Graph the relative difference in the cumulative average order size for Group B compared to Group A.

     -Calculate the conversion rate of each group as the ratio between orders and the number of daily visits.

     -Calculate the 95th and 99th percentiles of the number of orders per user.

     -Determine the statistical significance of the difference in conversion between the groups using the raw data.

## 📊 Results:
Both for the raw and the filtered data, the proportion test indicates that the conversion rate of Group B is higher than that of Group A. This suggests that users in Group B make more purchases than those in Group A.
