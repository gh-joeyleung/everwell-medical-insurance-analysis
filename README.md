# Everwell Medical Insurance Analysis 

# Background and Overview
Everwell Medical Insurance is a leading U.S.-based provider of comprehensive health insurance solutions, committed to delivering high-quality, accessible, and affordable healthcare coverage to individuals, families, and businesses. Since its inception, Everwell has focused on leveraging innovative solutions and customer-centric approaches to simplify the health insurance experience and ensure that members receive the care and support they need.

With a strong emphasis on transparency, reliability, and exceptional customer service, Everwell aims to empower Americans to make informed healthcare decisions while fostering long-term relationships built on trust and satisfaction. Through strategic partnerships with healthcare providers and investment in digital tools, Everwell strives to create a seamless and personalized insurance experience that meets the evolving needs of its members.

# Business Objectives
1) to increase the number of customer signups,
2) to raise awareness of Everwell’s brand across the country.

# North Star Metrics
To evaluate campaign performance, the insights focused on the following key metrics:
- **Impressions:** The number of people who saw a marketing campaign.
- **Cost per Click (CPC):** the amount an advertiser pays each time a user clicks on their advertisement
- **Signup Rate:** The percentage of people who see a campaign and subsequently sign up for a MedCare plan.
- **Cost per Signup:** The average dollars spent in order to acquire a signup from each campaign.
- **Click through Rate (CTR):** The percentage of people who see a campaign and click on the associated link.

> - ERD of Dataset can be found [here]

# Insights Summary

**Signup Rate**
- Across campaign categories, Health for All campaigns had the best-performing signup rate (2%) and the second-highest number of signups (3.5K).
- This high signup rate is due to the Health Awareness campaign type, which had by far the highest signup rate across all campaign types (2.8%).
- Interestingly, the category with the highest number of signups - #HealthyLiving - had a comparably low signup rate at 0.3%.

**Click through Rate**
- Across categories, Health for All and Benefit Updates performed nearly 3x better than the average CTR at 25% and 22%, respectively.
- Within the two categories with high CTR, phealth awareness-based campaigns were the sole contributor CTR (37% and 31%).
- Family Coverage Plan had high impressions but no clicks - this needs to be investigated and could be due to missing data or issues with the campaign.

**Cost per Signup**
- Across campaign categories, Golden Years Security had by far the highest cost per signup ($178), as well as the lowest number of signups (23), compared to an average of $3.7.
- Within the two campaign categories with highest cost per signup, info-based campaign types (like offers and policy info) drove high costs per signup.
- Health Awareness campaign of Summer Wellness Tips had a cost per signup of $939 with only 2 signups.

# Recommendations
- **Budget Reallocation:** Reallocate budget from Golden Years Security, which has high cost per acquisition, to Health for All campaigns. The second category outperforms across all key metrics, yet we have invested a relatively low amount ($20K) on them.
- **Campaign Type:** For Summer Wellness Tips, focus more on policy information and less on health awareness-type marketing, which had low signup rate and high cost per signup. Consider removing these campaigns.
- **Marketing Channels:** Although social and referral had the highest number of impressions (7M), email had the highest CTR (15%) and the lowest CPC ($0.03). Consider increasing the campaigns sent via email.
- **#HealthyLiving:** Decrease investment in this campaign category, which has the highest spend ($46K) but mediocre signup rates compared to Health for All campaigns.

# Dashboard
The dashboard can be found in Tableau Public here. This dashboard enables users to filter by plan, campaign type, and state, and focuses on trends and values in marketing metrics, signup metrics, and claim metrics.

<img width="1509" height="525" alt="Screenshot 2025-10-18 at 23 38 48" src="https://github.com/user-attachments/assets/1ec02374-8d71-4ba9-8ec1-b823b5e733d2" />
<img width="1500" height="795" alt="Screenshot 2025-10-18 at 23 39 41" src="https://github.com/user-attachments/assets/b201d356-7c34-4af7-a5fa-fcb685c60a18" />

# Presentation Sample
The presentation created for the marketing team walks through the insights and recommendations above and can be requested. Some extracts are presented below for easy viewing.

<img width="1192" height="676" alt="image" src="https://github.com/user-attachments/assets/836bd3be-a49e-47f2-bf02-b2a8b1dc3fd3" />

<img width="1198" height="688" alt="image" src="https://github.com/user-attachments/assets/c2658f62-1310-4369-a41b-1bcb6a98445f" />

<img width="1190" height="672" alt="image" src="https://github.com/user-attachments/assets/d1aec0ae-65fe-4b62-82d7-cab0199db8b4" />


