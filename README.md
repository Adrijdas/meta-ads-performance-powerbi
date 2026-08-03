# Meta Ad Performance Analysis Dashboard

## Project Overview

This project presents an interactive **Power BI dashboard** for analysing paid advertising campaign performance across **Facebook and Instagram**.

The dashboard evaluates campaign reach, engagement, conversions, audience behaviour, ad formats, geographic performance, time-based trends, and budget utilisation.

The main objective is to help marketing teams identify high-performing platforms, audiences, locations, time periods, and advertisement formats for better campaign and budget decisions.

---

## Dashboard Preview

![Meta Ad Performance Dashboard](images/meta-ad-performance-dashboard.png)

---

## Tools Used

* Power BI
* Power Query
* DAX
* Data Modelling
* Star Schema

---

## Dataset

The project contains four tables:

| Table       | Description                                                  |
| ----------- | ------------------------------------------------------------ |
| `ad_events` | Stores impressions, clicks, shares, comments, and purchases  |
| `ads`       | Contains platform, ad type, target gender, age, and interest |
| `campaigns` | Contains campaign information and budget                     |
| `users`     | Contains user demographic and location information           |

The `ad_events` table works as the main fact table, while the other tables support campaign, audience, and geographic analysis.

---

## Key Performance Indicators

| KPI             | Result |
| --------------- | -----: |
| Impressions     |   216K |
| Clicks          |  25.4K |
| Engagements     |  29.3K |
| Purchases       |   1.3K |
| CTR             | 11.76% |
| Engagement Rate | 13.56% |
| Conversion Rate |  5.21% |
| Purchase Rate   |  0.61% |
| Total Budget    |  $2.5M |

---

## Dashboard Features

The dashboard includes:

* Dynamic KPI selector
* Facebook and Instagram comparison
* Gender and age analysis
* Country-level performance map
* Weekly and hourly engagement trends
* Calendar activity analysis
* Ad-format performance comparison
* Interactive campaign, platform, and audience filters

---

## Key Insights

* Facebook generated higher impressions, clicks, engagements, and purchases than Instagram.
* Instagram achieved slightly higher CTR and engagement rate.
* Strong CTR and engagement show that the advertisements successfully attracted audience interest.
* The low purchase rate of **0.61%** indicates a major drop-off in the lower conversion funnel.
* Female audiences generated the highest engagement.
* The strongest-performing age group was approximately **18–30 years**.
* The United States, India, Brazil, Germany, and the United Kingdom were major engagement markets.
* Engagement was highest during the afternoon and evening, around **15:00–20:00**.
* Video advertisements delivered the highest CTR and engagement rate.
* Stories generated the highest impression volume and purchase rate.

---

## Business Recommendations

* Improve landing pages, offers, and checkout processes to increase purchases.
* Focus more on female audiences aged 18–30.
* Allocate more budget to Video and Stories advertisements.
* Schedule advertisements mainly during afternoon and evening hours.
* Increase investment in high-performing geographic markets.
* Use retargeting campaigns for users who clicked but did not purchase.

---

## Skills Demonstrated

* Data modelling and relationship creation
* DAX measure development
* KPI analysis
* Dashboard design
* Audience segmentation
* Campaign performance analysis
* Business insight generation

---

## Conclusion

This project demonstrates an end-to-end Power BI workflow, from data preparation and modelling to dashboard creation and business recommendations.

The main finding is that the campaigns generated strong reach and engagement, but purchase conversion remained weak. Improving the conversion funnel and reallocating budget toward stronger audiences, locations, and ad formats could significantly improve campaign performance.

---

## Author

**Adrij Das**

Aspiring Data Analyst skilled in Power BI, SQL, Excel, Power Query, DAX, data visualisation, and business analysis.

