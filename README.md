Overview

This project analyzes customer purchase behavior at California Mall using the RFM (Recency, Frequency, Monetary) model to identify customer segments and support marketing strategies.

Dataset

Key columns: invoice_no, customer_id, category, quantity, invoice_date, price, shopping_mall, sales.

Process

RFM Calculation:

Recency = days since last transaction (end of 2023)

Frequency = total transactions per customer

Monetary = total spending per customer

Scoring (1–5) using percentiles.

Segmentation:

Champions (511–555)

Loyal (451–510)

Potential (351–450)

At Risk (151–350)

Age Range: <20, 20–30, 31–40, 41–50, 51–60, 60+, Unknown.

Dashboard Pages

RFM Overview

Customer Insights

Sales Insights

Output

RFM_FINAL.csv – includes RFM metrics, segments, and age ranges, ready for visualization in Power BI or Tableau.
