# (Full step by step is in wiki)

## Title: Cyclistic Member Analysis

## Date: January 13th 2026

## Prepared for: Cyclistic Marketing & Executive Team

## Prepared by: Luke Sherwin

### Executive Summary:

To convert casual riders into annual members and drive future growth, our analysis of 12 months of trip data reveals key behavioral differences: casual riders take longer trips (20 vs. 12 minutes), prefer electric bikes (53%) and afternoon rides (61%), while members use classic bikes more often. We recommend a three-part strategy: 1) A "Loyalty Minutes" program rewarding morning and classic bike use with membership credits, 2) A premium "Afternoon Electric Advantage" tier guaranteeing peak-hour e-bike access, and 3) A "Duration based" campaign incentivizing efficient, member-like ride durations by showing the savings that would be gained by membership. These targeted initiatives will nudge casual riders toward member behaviors, address their preferences, and systematically increase conversion rates.

### Business Task & Objective:

The marketing team believes the company’s future success depends on maximizing the number of annual memberships. Therefore, our team wants to understand how casual riders and annual members use Cyclistic bikes differently. From these insights, our team will design a new marketing strategy to convert casual riders into annual members.

### Data Source:

The last 12 months of Cyclistic trip data.

### Data Cleaning:

Merge data into one table, check for duplicates, delete incomplete records, delete inaccurate records, export cleaned table.

### Analysis:

Create pivot tables of necessary information in order to obtain insights:
The percentage of members and casual riders
The average length of rides of each rider type
The percentage of the type of bike used by each member type
The percentage of rides before and after noon by each member type

### Visualizations:

<img width="443" height="371" alt="Percent of Member Type (1)" src="https://github.com/user-attachments/assets/e8905f9d-6bd4-4347-90ae-c83526d7bfeb" />

<img width="532" height="371" alt="Average Duration (1)" src="https://github.com/user-attachments/assets/3acb04cc-6ec5-4305-ab87-2148acf641c8" />

<img width="537" height="335" alt="Classic Vs Electric Bike (4)" src="https://github.com/user-attachments/assets/c63bed74-bd94-45ab-a04b-c8ea228e9f64" />

<img width="600" height="371" alt="Before vs After Noon" src="https://github.com/user-attachments/assets/2a1f8c88-388c-4433-aaf2-c5433ba5c792" />

The following data was found:

Members make up 64% and casual riders make up 36% of total rentals.

Members' average trip duration is 12 minutes and casual riders are 20 minutes.

Members use classic bikes 55% of the time and electric bike 45% of the time,
Casual riders use classic bikes 47% of the time and electric bikes 53% of the time.

Members use bikes after noon 55% of the time and before noon 45% of the time,
Casual riders use bikes after noon 61% of the time and before noon 39% of the time.

### Recommendations:

1. Implement "Loyalty Minutes" Conversion Program
Recommendation: Create a program where casual riders accumulate "minutes credits" toward membership. Every ride counts toward a discount, with bonus credits for rides before noon and on classic bikes.
Rationale: The data reveals a strategic opportunity: casual riders use bikes 39% before noon vs. members' 45%, indicating a smaller but still significant morning user base. Additionally, casual riders prefer electric bikes (53%) while members prefer classic bikes (55%). By offering extra credits for less-congested morning hours and classic bike usage (which members prefer anyway), we can:
Incentivize behavior that aligns with member patterns
Reduce strain on electric bike inventory during peak hours
Create a clear path to membership through accumulated value

Expected Impact: A graduated conversion approach lowers the psychological barrier to membership while teaching casual riders to adopt member-like behaviors.

Implementation:
Launch in-app "Membership Meter" showing progress toward discounted membership
Offer 2x credits for rides before noon
Offer 1.5x credits for classic bike usage
Send push notifications: "Your 5 morning rides this month earned you 10% off an annual membership!"

2. Create "Afternoon Electric Advantage" Membership Tier
Recommendation: Introduce a premium membership tier guaranteeing electric bike access during peak afternoon hours (12-6 PM) when casual riders use bikes 61% of the time.
Rationale: Casual riders show the strongest preference for electric bikes (53%) and afternoon usage (61%), suggesting they value convenience and assistance during their preferred riding times. Members currently use bikes 55% after noon but prefer classic bikes (55%), indicating they may be settling for what's available. By creating a tier that solves the electric bike availability problem during peak hours, we address casual riders' primary preferences directly.

Expected Impact: Capture higher-value casual riders who are currently frustrated by afternoon electric bike scarcity while segmenting the market effectively.

Implementation:
Price the "Electric Advantage" tier 25-30% above standard membership
Guarantee electric bike reservation availability for members 2+ hours in advance
Market with messaging: "Skip the afternoon hunt. Your e-bike is waiting."
Target casual riders with 3+ afternoon electric bike rentals monthly

3. Implement "Duration-Based" Pricing Psychology
Recommendation: Redesign the pricing display to show casual riders how much they're overspending compared to members, based on their actual usage patterns.
Rationale: The 20-minute average trip duration for casual riders represents a specific usage pattern we can target with comparative pricing. Create personalized communications showing: "Your last 5 trips averaged 22 minutes. As a member, you would have saved $X." This makes the membership value concrete and personalized rather than abstract.

Expected Impact: Higher conversion rates through behavioral economics principles (loss aversion and concrete comparison). Riders who see exactly how much money they're leaving on the table are more likely to convert.

Implementation:
Develop in-app calculator showing membership savings based on user's historical data
Send monthly "Savings Opportunity" emails to casual riders
Create dynamic pricing displays showing member vs. casual costs for common trip durations
Offer "Duration Discount" - prorated membership based on recent casual spending

### Impact:
Rolling out all three campaigns over four months would realistically create a layered impact: 
Initial short-term conversion lifts from the Duration-Based Pricing, 
followed by increased premium revenue and improved bike rebalancing from the Afternoon Electric Advantage tier, 
culminating in sustained behavior change and higher long-term loyalty through the Loyalty Minutes program.

Link to report:

[Cyclistic Report](https://docs.google.com/document/d/1VIBVF57c1CQ3iA1-R2bEAseQhZDLWW-XmqY7wnAWb6Q/edit?usp=sharing)

Link to presentation:

[Cyclistic Presentation](https://docs.google.com/presentation/d/1I8duFguO9XIB3JbE_bP3LERQi1GsgAJlILHtDisNCLA/edit?usp=sharing)
