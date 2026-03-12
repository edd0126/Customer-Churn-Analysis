# Marketing Investment Analysis & Cohort-Based LTV/ROMI Study

## Overview
End-to-end business analysis of a ticket sales platform (Showz) using 18 months 
of server logs, order data, and marketing spend across multiple acquisition sources. 
The goal was to evaluate how marketing budget was being allocated and whether 
investments were generating measurable returns.

**Tools:** Python (Pandas, Matplotlib) | **Type:** Exploratory Data Analysis, 
Cohort Analysis, Marketing Analytics

## Key Questions Answered
- How do users behave on the platform? (sessions, frequency, retention)
- When do users convert to paying customers?
- What is the LTV per acquisition cohort?
- Which marketing sources have the lowest CAC and best ROMI?

## Key Findings

**User Behavior**
- Platform traffic peaked during the Oct–Nov holiday season, aligning with 
  event-buying trends
- Average session duration: ~10 minutes
- Average time from registration to first purchase: ~16 days

**Purchase Patterns**
- 88.2% of users placed only 1 order per month — suggesting limited repeat 
  purchase behavior in the analyzed period

**Marketing Spend & Efficiency**
- Source 3 received the largest share of investment ($141,321.63 total), 
  representing 131% more spend than the second-highest source (Source 4)
- Despite high spend, Source 3 had one of the highest customer acquisition costs 
  (CAC), while Sources 9 and 10 showed significantly lower CAC
- No cohort achieved positive ROMI during the full analysis period, though 
  cumulative LTV showed an upward trend over time

## Conclusions & Recommendations
The data revealed a misalignment between marketing budget allocation and 
acquisition efficiency. Source 3's dominance in spend was not justified by 
proportionally better results. A recommended course of action is to redistribute 
budget more evenly across sources using controlled baseline parameters, enabling 
a more reliable comparison of channel performance and faster path to positive ROI.
