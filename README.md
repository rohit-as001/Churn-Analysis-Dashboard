# Churn-Analysis-Dashboard (Music Streaming Churn Analysis Dashboard)
### This Repository has Churn Analysis Dashboard projects.


"Know Who's Leaving Before They Go — Turn Churn Data Into Customer Loyalty"


# Project Overview

This project focuses on analyzing customer churn behavior to identify patterns, risk factors, and opportunities for improving user retention.
The interactive dashboard provides insights into user demographics, device usage, network performance, buffering experience, and content preferences, helping businesses understand why customers leave.
It allows dynamic filtering based on Payment Method and Auto-Renewal status, enabling deeper behavioral analysis.
Music Streaming Churn Analysis Dashboard is a comprehensive customer retention analytics project built in Microsoft Excel and Power Bi, analyzing subscriber churn behavior for a music streaming platform. The dataset covers 4,600 total users with a 31% churn rate — examining churn patterns across demographics, device types, network quality, buffering experience, music genre preferences, subscription plans, and payment methods.
The project delivers a fully interactive Excel Dashboard with filter slicers for Payment Method, Auto Renewal, enabling dynamic drill-down into churn behavior across multiple user segments simultaneously.
This type of analysis is directly applicable to real-world business challenges in subscription retention strategy, product experience optimization, customer segmentation, targeted re-engagement campaigns, and telecom/infrastructure investment planning for digital streaming platforms.



## Business Objectives
- Track total users, active users, and churned users
- Measure overall churn rate
- Identify key drivers of churn
- Analyze churn across demographics, devices, and networks
- Understand the impact of user experience (buffering, performance)
- Support strategies to reduce churn and improve retention


## Key KPIs
- Total Users: 4,600
- Active Users: 3,188 (69%)
- Churned Users: 1,412 (31%)
- Overall Churn Rate: 31%
- Device Types: Android, iOS, Web
- Network Types: 4G, 5G, WiFi
- Subscription Plans: Free, Family, Premium
- Payment Methods: Auto-Debit, Card, UPI, Wallet
- Music Genres Tracked: Rock, HipHop, Pop, Jazz, EDM, Classical




# Key Insights

1) Overall Churn Performance (31% Overall Churn Rate — A Critical Business Risk)

  - A 31% churn rate is relatively high and indicates significant user drop-off.
  - Nearly 1 in 3 users leaves the platform, highlighting retention challenges.
  - With 1,412 out of 4,600 users churned (31%), the platform is losing nearly one-third of its subscribers. For a subscription business, this is a significant and urgent retention problem. Industry benchmarks for streaming services typically target churn rates below 5–10% per year. A 31% churn rate signals systemic issues in product experience, value perception, or competitive positioning that need immediate attention.


2) Device-Based Churn

  - Android users (~36%) have the highest churn rate.
  - Followed by iOS (~34%) and Web (~30%).


3) Network Type Analysis

  - Churn is highest among 4G users (~34%), followed by 5G (~34%) and WiFi (~32%).
  - Web platform users churn at 36.19% — the highest of all device types — followed by Android (33.92%) and iOS (29.89%). iOS users are the most loyal, churning at nearly 6 percentage points less than web users. This suggests the web streaming experience is significantly underperforming relative to mobile apps — possibly due to inferior UI/UX, slower performance, or a lack of web-exclusive features.


4) Buffering Time Impact

  - Churn increases significantly with higher buffering times (3–4 seconds).
  - Lower buffering times (1–2 seconds) have reduced churn.
  - Churn rate by buffering time shows a non-obvious pattern: churn peaks at 0–1 second (20.47%), dips in the middle, rises again at 3–4 seconds (21.53%), and drops sharply at 4+ seconds (18.20%). This counterintuitive result suggests that users experiencing near-zero buffering still churn — indicating that buffering alone is not the primary driver of churn, and other factors (content quality, pricing, competition) play a dominant role.

    
5️) Demographic Insights

  - Male users show higher churn compared to females.
  - Age group 18–25 and 46+ have higher churn counts.
  - The demographic bar chart shows Male users have approximately 2,000 active and 900 churned users, while Female users have ~1,200 active and ~500 churned. The proportional churn rates are similar (~31% for both genders), but male users represent a higher absolute churn count — making them the priority target for retention campaigns given their larger volume contribution.


6️) Genre-Based Engagement (Genre-Wise Churn Varies — High-User Genres Don't Always Mean Low Churn)

  - Some content genres show higher user count but also higher churn.
  - Indicates mismatch between content expectations and delivery.
  - The combo chart shows that genres with the highest user counts (such as certain top genres approaching 1,000 users) don't always have the lowest churn rates. The churn rate line fluctuates between approximately 16–17% across genres, with some higher-volume genres showing elevated churn. This means content investment in popular genres should be paired with targeted retention tactics, not assumed to naturally retain users.


7) Payment & Auto-Renewal Behavior (Payment Method Reveals Behavioral Churn Patterns)

  - Users without auto-renewal are more likely to churn.
  - Payment method also influences retention patterns.
  - With four payment methods — Auto-Debit, Card, UPI, and Wallet — users on passive payment methods (Auto-Debit) are likely to churn less than those on active methods (UPI, Wallet) that require manual renewal intent. The slicer allows management to isolate churn rates by payment method and design specific nudge strategies for each payment segment.


8) Active-to-Churn Ratio Is Healthiest in the 36–45 Segment

  - The 36–45 age group has the best retention ratio with only 315 churns out of 1,041 users (~30.3%) — the lowest churn rate across all age groups. This middle-aged professional segment is likely more financially stable, less likely to switch platforms impulsively, and more invested in curated music preferences — making them the most valuable long-term subscriber cohort.




## Business Recommendations

1. Improve User Experience (Critical)
  - Reduce buffering time through:
      - Better CDN optimization
      - Adaptive streaming
  - Ensure smooth performance, especially for Android users.


2. Strengthen Retention Strategy
  - Introduce loyalty programs and personalized offers.
  - Send targeted notifications before subscription expiry.


3. Optimize Subscription Model
  - Promote auto-renewal plans with discounts or benefits.
  - Simplify payment processes for better user retention.


4. Content Personalization
  - Use user behavior data to recommend relevant content.
  - Improve underperforming genres or invest in high-demand ones.

    
5. Segment-Based Marketing
  - Target high-churn groups:
      - 18–25 users → offer engaging content & offers
      - 46+ users → improve usability and accessibility


6. Monitor Churn Drivers Continuously
  - Build alerts for:
      - Increased buffering time
      - Drop in active users
  - Use predictive models to identify users at risk of churn.


7. Design Targeted Retention Campaigns for the 18–25 Cohort
  - Young adults (18–25) represent the highest absolute churn volume. Management should develop age-specific retention programs — including student discount pricing, social sharing features, playlist collaboration, and exclusive genre drops for EDM/HipHop (genres popular in this age group) — to improve stickiness for this volatile but high-potential segment.


8. Create a VIP Retention Program for the 36–45 Segment
  - The 36–45 age group is the platform's most loyal demographic. Management should reward this retention with a premium loyalty program featuring exclusive features (offline downloads, higher audio quality, family plan perks) to deepen engagement, increase lifetime value, and turn loyal users into brand advocates.


9. Segment Churn Analysis by Payment Method and Run Experiments
  - Users on passive payment methods (Auto-Debit) likely churn less. Management should A/B test payment-specific retention strategies: for UPI and Wallet users, test SMS reminders 7 days before expiry; for Card users, test annual plan discounts; for Auto-Debit users, focus on content engagement rather than payment friction.



## Tools & Technologies
- Visualization Tool: Power BI/Excel Dashboard
- Dataset: Churn Data
- **Skills Applied:**
  - Data Cleaning & Transformation
  - Customer Behavior Analysis
  - KPI Monitoring
  - Retention & Churn Analysis
  - Slicers & Filter Panel — Interactive filters for Payment Method (Auto-Debit, Card, UPI, Wallet) and Auto Renewal (Yes/No)


Conclusion

This dashboard provides a deep understanding of customer churn behavior, enabling businesses to identify key risk factors and take proactive actions.
By focusing on user experience, personalization, and subscription optimization, organizations can significantly improve customer retention and lifetime value.


        _"Retention is not about keeping customers — it's about understanding why they leave and removing every reason to go."_
