An end-to-end analysis of a supply chain dataset: exploratory data analysis (EDA) in a SQL database and a four-page interactive dashboard in Power BI. The goal is to find where the business is exposed on quality, cost and stock, and to turn the findings into clear recommendations.

Business questions
Which product categories, locations and suppliers drive revenue?
Which suppliers deliver the best quality, and which cost more without a quality benefit?
How much revenue sits on products that have failed or not yet passed inspection?
Are we paying for transport speed we do not actually get?
Which high-selling SKUs are at risk of running out of stock?

<img width="908" height="495" alt="Screenshot 2026-10-03 114022" src="https://github.com/user-attachments/assets/eba4e8e1-815d-44b7-a834-3addc6f6d23b" />
<img width="910" height="500" alt="Screenshot 2026-10-03 114040" src="https://github.com/user-attachments/assets/742968cf-9e42-4971-bb9b-4193ba411b5b" />
<img width="891" height="492" alt="Screenshot 2026-10-03 114058" src="https://github.com/user-attachments/assets/c6b7a670-0330-41cd-b1e6-ea13071d9a94" />
<img width="872" height="490" alt="Screenshot 2026-10-03 114117" src="https://github.com/user-attachments/assets/bd838834-20f5-4b98-8343-1ae9ed18dda1" />

Key insights
Revenue mix: skincare is about 42% of revenue; the top 5 SKUs are only 8.4%, so concentration risk is low.
Quality: only 23 of 100 SKUs passed inspection. About 77% of revenue sits on products that failed or are still pending, and 15 SKUs failed with defect rates above 3%.
Suppliers: one supplier combines the highest revenue with the lowest defect rate; another costs about 40% more to manufacture with no quality benefit. Longer supplier lead times tend to go with higher defect rates (correlation about 0.30, a modest link).
Logistics: sea is about 25% cheaper but slowest; air costs the most and is not faster than road.
Inventory: 54 of 100 SKUs hold less stock than their order quantity, and 13 critical SKUs (stock under 20, sales of 500+) carry about 14% of revenue.
Recommended actions
Clear pending inspections and fix or pause the 15 high-risk SKUs.
Review the highest-cost supplier and set a defect-reduction plan for the supplier with the highest defect rate.
Review air freight usage and move non-urgent shipments to sea.
Replenish the 13 critical SKUs first and base reorder levels on sales velocity.


