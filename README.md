# NovaStream Churn Analysis

## Project Overview

NovaStream is a fictional subscription-based streaming company experiencing customer churn.

This project analyzes customer behavior, satisfaction, support interactions, subscription plans, tenure, and marketing channels to identify who is most likely to churn and where the business is at risk of losing recurring revenue.

The goal is to turn customer data into actionable insights that can help NovaStream improve retention and protect recurring revenue.

---

## Business Problem

NovaStream has a 27.1% churn rate, creating a significant risk to recurring revenue.

The analysis investigates:

- Which customer segments are most exposed to churn?
- Is customer satisfaction associated with churn?
- Does customer tenure affect churn risk?
- Is there a relationship between support tickets and churn?
- Which marketing channels have the highest churn risk?
- Which subscription segments have the most MRR at risk?

---

## Key Metrics

| Metric | Result |
|---|---:|
| Churn Rate | 27.1% |
| MRR at Risk | $30,434 |
| Average Satisfaction | 7.0 / 13 |
| At-Risk Customers | 3 |

---

## Key Insights

### 1. Low satisfaction customers face the highest churn risk

Customers with low satisfaction scores show substantially higher churn rates, particularly as their tenure increases.

For customers with 121–208 days of tenure, the churn rate reaches 88% among the low-satisfaction segment.

This suggests that declining customer satisfaction may be an important warning signal for retention.

### 2. Longer tenure does not necessarily mean lower churn

The churn risk heatmap shows that churn increases considerably among customers with longer tenure when satisfaction is low or medium.

This indicates that NovaStream should not focus retention efforts only on new customers. Long-tenured customers can also become high-value churn risks when their experience deteriorates.

### 3. Support activity is strongly associated with churn

The dashboard shows a clear increase in churn rate as support ticket volume rises.

Customers with higher numbers of support tickets have substantially higher churn rates than customers with fewer tickets.

This suggests that repeated unresolved customer issues may be an important retention risk.

### 4. Family and Individual plans have the highest MRR at risk

The Family and Individual subscription segments represent the largest portions of MRR at risk.

These segments could therefore be prioritized when designing retention campaigns because reducing churn within them could have a meaningful impact on recurring revenue.

### 5. Marketing channel performance changes with customer tenure

Churn risk varies significantly across marketing channels and tenure groups.

Several channels show particularly high churn among customers with 121–208 days of tenure, suggesting that acquisition source alone may not explain customer quality — the customer's experience after acquisition also matters.

---

## Recommendations

### 1. Introduce proactive retention campaigns

Identify customers showing a combination of:

- Low satisfaction
- Increasing support tickets
- Longer tenure
- High-value subscription plans

These customers should receive proactive engagement before they churn.

### 2. Investigate recurring support issues

Customers generating multiple support tickets should be flagged for review.

NovaStream should identify the most common reasons for repeated support interactions and address the underlying problems rather than treating each ticket individually.

### 3. Prioritize high-value segments

Retention efforts should prioritize the Family and Individual plans because they currently account for the highest MRR at risk.

### 4. Review marketing channel quality

NovaStream should evaluate customers acquired through channels with consistently high long-term churn.

The objective should not simply be to acquire more customers, but to acquire customers who are likely to remain subscribed.

---

## Dashboard

The Tableau dashboard brings the analysis together through:

- Churn Rate KPI
- MRR at Risk KPI
- Average Satisfaction KPI
- At-Risk Customer Count
- MRR at Risk by Customer Segment
- Support Tickets vs Churn Rate
- Satisfaction Score vs Churn Rate
- Churn Risk Heatmap
- Churn Heatmap by Marketing Channel

---

## Tools Used

- Tableau — Data visualization and dashboard development
- Data Analysis — Customer churn, satisfaction, tenure, support activity, subscription plans and marketing channels

---

## Project Outcome

The analysis shows that customer churn is not driven by a single factor.

Satisfaction, support activity, tenure, subscription segment, and acquisition channel all provide useful signals for identifying customers at risk of leaving.

The biggest opportunity for NovaStream is to move from reactive churn management to proactive retention, using these signals to identify high-risk customers before they cancel.

---

## Dashboard Preview
![Novastream Churn Analysis Dashboard](Capture.png)

NovaStream Churn Analysis Dashboard
