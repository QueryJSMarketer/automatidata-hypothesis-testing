# automatidata-hypothesis-testing
Statistical analysis and hypothesis testing regarding NYC taxi fares (PACE Project)
# 🚕 NYC Taxi Trip Fare Analysis: Hypothesis Testing (Automatidata)

## 📌 Executive Summary & Project Overview
This project evaluates whether there is a statistically significant difference in taxi fare amounts (`fare_amount`) between customers paying with **credit cards** versus **cash** using data from the New York City Taxi and Limousine Commission (TLC).

The project follows the **PACE Framework** (Plan, Analyze, Construct, Execute).

---

## 📊 Key Findings & Statistical Results
* **Credit Card Average Fare:** $13.43
* **Cash Average Fare:** $12.21
* **Observed Difference:** +$1.22 per trip (+10% for digital payments)
* **Statistical Test:** Welch's Two-Sample t-test (One-sided)
* **Test Results:** $t$-statistic = $6.8668$, $p$-value = $0.0000$ ($\alpha = 0.05$)
* **Conclusion:** Reject the null hypothesis ($H_0$). Customers paying with credit cards pay significantly higher fares on average.

---

## 💡 Strategic Business Recommendations
1. **Promote Credit Card Adoption:** Implement in-app incentives and loyalty rewards to encourage cash users to register credit cards.
2. **Fleet Allocation:** Optimize driver coverage in long-distance trip corridors and airport routes where credit card transactions dominate.
3. **Further Causal Analysis:** Conduct follow-up multivariate regression analyses to control for trip distance (miles) and pickup time.

---

## 🛠️ Tools & Technologies
* **Python 3.x**
* **Pandas & NumPy** (Data Manipulation)
* **SciPy (`scipy.stats`)** (Inferential Statistics & Hypothesis Testing)
* **Matplotlib & Seaborn** (Data Visualization)

---

## 📂 Repository Structure
* `automatidata_hypothesis_testing.ipynb` - Complete Jupyter Notebook with Data Cleaning, EDA, and Welch's t-test.
* `2017_Yellow_Taxi_Trip_Data.csv` - TLC Taxi Trip Dataset.
* `Executive_Summary.pdf` - High-level Executive Summary Presentation Slides.
