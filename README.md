# Convenience-store-analyst-pbi
Retail BI Dashboard (Power BI Case Study)

<img width="743" height="498" alt="image" src="https://github.com/user-attachments/assets/0de89432-bcc5-422c-b5c3-066c3a93fd84" />

1. Business Context

Convenience store chains such as GS25 operate with high SKU variety, frequent replenishment cycles, and high transaction volume.

To support operational decisions, this project simulates a retail analytics dashboard designed to help business stakeholders monitor:

* Sales performance

* Product category contribution

* Store operations efficiency

* Inventory health

* Customer membership behavior

The dashboard aims to answer:

* Which categories drive the most revenue?

* Which store formats perform best?

* When are stores most operationally stressed?

* Are stockouts affecting sales?

* Do membership programs drive revenue?

  <img width="1220" height="671" alt="image" src="https://github.com/user-attachments/assets/38fe0514-6fcc-40a9-89ef-36c4da2d2fd2" />

Problem

Retail performance must be monitored continuously to detect seasonal trends and store format performance differences.

Detection

The dashboard shows:

* Total Net Sales: 15B

* Gross Profit: 5B

* GM%: 35%

* Transactions: 60K

* AOV: 253K

* Items per Basket: 5.91

From the revenue trend:

* Sales peaked in Q3

* Sales declined sharply in Q4
  
  <img width="592" height="224" alt="image" src="https://github.com/user-attachments/assets/d5ee4fb3-5848-49fd-989a-0b04c282ee21" />

Root Cause Hypothesis

Street stores likely benefit from:

* Higher daily foot traffic

* Longer operating hours

* Higher impulse purchases

The Q4 drop may be associated with:

* Seasonality

* Reduced footfall

* Inventory issues

  <img width="1214" height="670" alt="image" src="https://github.com/user-attachments/assets/e833e31a-3904-4680-9390-a780905af99b" />

Problem

Retailers must understand which product categories drive revenue and profitability.

Detection

Category revenue distribution shows:

Top categories:

1️⃣ Beverage
2️⃣ Food
3️⃣ Personal Care

Lower contribution:

* Tobacco

* Household

However, profitability differs.
Root Cause Hypothesis

Possible drivers:

* Beverage products have high purchase frequency

* Personal care items have higher margins

* Food products may suffer from higher cost of goods

This suggests sales leaders are not always profit leaders.
<img width="1217" height="694" alt="image" src="https://github.com/user-attachments/assets/69a99621-4557-4e3b-9809-6961091ff068" />
Problem

Convenience stores must manage staffing and operations across different shifts.

Detection

<img width="566" height="226" alt="image" src="https://github.com/user-attachments/assets/557cad3f-2f28-4fb9-ae00-e62652358bc7" />

Operational heatmap shows peak activity around:

* 7AM – 10AM

* 11AM – 2PM

Wait time distribution indicates:

Most transactions complete within 40–70 seconds.

Root Cause Hypothesis

Morning peak may be driven by:

* commuters

* breakfast purchases

* coffee

Afternoon activity may be lunch-related.

Night shift demand is lower but still significant for convenience retail.
<img width="1226" height="653" alt="image" src="https://github.com/user-attachments/assets/86671bf4-dbf8-4176-b6c3-7ae6e1b2da25" />
Problem

Regional store performance can vary significantly due to location characteristics.

Detection

Regional revenue distribution:

Region	Revenue Share
North	37%
South	31%
Central	30%

However, store-level analysis reveals variation in:

* sales per m²

* OOS rate

* store productivity

Root Cause Hypothesis

Performance differences may stem from:
<img width="1214" height="657" alt="image" src="https://github.com/user-attachments/assets/600e8b07-866c-4506-9621-6727932a9e4e" />

* urban density

* store placement

* customer demographics

<img width="1224" height="685" alt="image" src="https://github.com/user-attachments/assets/5f3d6dbe-bf05-4104-b604-d55f39264c20" />
Problem

Stockouts are critical for convenience stores where customers expect immediate availability.

Detection

<img width="585" height="227" alt="image" src="https://github.com/user-attachments/assets/9ab75b64-52f0-44ba-a481-9679ed4bf461" />


Inventory turnover analysis shows:

High turnover:

* Personal Care

* Household

Lower turnover:

* Tobacco

* Snack

Root Cause Hypothesis

High OOS rate in fast-moving categories suggests:

* demand underestimation

* reorder thresholds set too low

* supply chain delay

Stockouts in high-frequency categories may directly reduce revenue.

**Key Insights
**

1️⃣ Beverage is the largest revenue contributor

2️⃣ Street-format stores dominate revenue performance

3️⃣ Morning shift generates the highest sales

4️⃣ Personal care category suffers from high stockout rate

**Business Recommendations
**

Improve revenue and operational efficiency by:

Inventory

* Increase safety stock for high OOS categories

* Improve demand forecasting

Store Operations

* Allocate more staff during morning peak

* Product Strategy

* Promote high-margin categories

Customer Strategy

* Expand membership programs

* Offer targeted promotions to non-members
