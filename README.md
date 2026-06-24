# AI Route Optimization Statistical Analysis

## Project Overview

This project evaluates whether AI Route Optimization improves delivery performance using statistical analysis techniques. The study applies probability, hypothesis testing, confidence intervals, normality testing, and association analysis to validate a business claim.

### Business Problem

Management claims that AI Route Optimization reduces delivery time.

As a Data Analyst, the objective is to determine whether deliveries using AI Route Optimization are significantly faster than deliveries without AI assistance and provide a data-driven recommendation.

---

## Dataset Information

### Dataset Size

* 500 Delivery Records
* 8 Features

### Features

| Feature                 | Description                            |
| ----------------------- | -------------------------------------- |
| Order_ID                | Unique order identifier                |
| Delivery_Time_Min       | Delivery time in minutes               |
| Distance_KM             | Distance covered for delivery          |
| Order_Value_INR         | Order value in INR                     |
| Delivery_Partner_Rating | Delivery partner rating                |
| Customer_Rating         | Customer rating                        |
| Traffic_Level           | Traffic condition (Low, Medium, High)  |
| AI_Route                | Whether AI Route Optimization was used |

---

## Statistical Techniques Used

### 1. Variable Classification

* Continuous Variables
* Discrete Variables
* Categorical Variables

### 2. Probability Analysis

* Probability of AI Route usage
* Probability of delivery time exceeding a threshold

### 3. Chi-Square Test of Independence

Used to determine whether Traffic Level and AI Route usage are associated.

### 4. Normality Testing

* KDE Plot
* Q-Q Plot
* Skewness
* Kurtosis
* Shapiro-Wilk Test

### 5. Standard Deviation & Z-Score Analysis

* ±1 Standard Deviation Range
* Z-Score Calculation

### 6. Confidence Interval Estimation

Estimated the population mean delivery time using a 95% Confidence Interval.

### 7. One-Sample T-Test

Tested whether the average delivery time differs from the company's claimed benchmark of 30 minutes.

### 8. Independent Two-Sample T-Test

Compared delivery times between:

* AI Route Deliveries
* Non-AI Route Deliveries

---

## Key Findings

### AI Route Usage

* 54.4% of deliveries used AI Route Optimization.

### Traffic Level vs AI Route

* Chi-Square Test p-value = 0.9607
* No significant association found between Traffic Level and AI Route usage.

### Delivery Time Distribution

* Delivery times approximately follow a normal distribution.
* Shapiro-Wilk p-value > 0.05.

### Probability Analysis

* Probability of delivery time exceeding 40 minutes = 15.2%.

### Delivery Time Statistics

* Mean Delivery Time = 31.24 minutes
* Standard Deviation = 8.74 minutes

### Confidence Interval

* 95% Confidence Interval:

  * Lower Bound = 29.42 minutes
  * Upper Bound = 32.75 minutes

### One-Sample T-Test

* Tested company claim that average delivery time is 30 minutes.
* p-value = 0.199
* Insufficient evidence to conclude that the average delivery time differs from 30 minutes.

### AI Route Optimization Impact

| Group        | Mean Delivery Time |
| ------------ | ------------------ |
| AI Route     | 29.81 min          |
| Non-AI Route | 32.58 min          |

* AI Route deliveries were approximately 2.77 minutes faster on average.
* Two-Sample T-Test p-value = 0.0967

### Statistical Conclusion

Although AI Route deliveries show lower average delivery times, the difference is not statistically significant at the 95% confidence level.

---

## Business Recommendation

Based on the statistical analysis:

* AI Route Optimization shows promising performance improvements.
* Current evidence is insufficient to conclusively prove a significant reduction in delivery time.
* Additional data collection and further testing are recommended before making large-scale investment decisions.

### Final Verdict

AI Route Optimization appears to reduce delivery time, but the current analysis does not provide strong enough statistical evidence to confirm the improvement with 95% confidence.

---

## Learning Outcomes

This project demonstrates practical application of:

* Probability Theory
* Descriptive Statistics
* Inferential Statistics
* Confidence Intervals
* Hypothesis Testing
* Chi-Square Test
* One-Sample T-Test
* Independent Two-Sample T-Test
* Business Decision-Making using Statistics
