RFM-Customer-Segmentation-Python
RFM Segmentation Analysis
🎯 What Is This Project About?
Every business has customers who buy regularly, customers who are about to leave, and customers who have already gone quiet. This project uses a technique called RFM Analysis to automatically sort 1,000 customers into behaviour-based groups — so a business knows exactly who to focus on, who to win back, and who is at risk of churning.
RFM stands for: Recency (how recently did they buy?), Frequency (how often do they buy?), Monetary (how much do they spend?)
________________________________________
🛠️ Tools & Techniques Used
•	Python — for all data processing and analysis
•	Pandas — to clean, merge, and calculate RFM scores
•	Matplotlib & Seaborn — to visualise the customer segments
•	Google Colab / Jupyter Notebook — development environment
________________________________________
📊 The Dataset
File	What It Contains
Customer_Master_Data.csv	1,000 customers — name, age, city, gender, join date
Customer_Transactions.csv	23,050 transactions with dates and amounts
________________________________________
🔢 Key Results
Customer Segment	What It Means (Plain English)	Count	% of Base
🏆 Champions	Buy often, spend a lot, bought recently — your best customers	127	12.7%
💛 Loyal Customers	Buy regularly and spend well — strong relationship	114	11.4%
🌱 Potential Loyalists	Recently active but not yet frequent — nurture them	252	25.2%
⚠️ At Risk	Used to buy often but haven't recently — about to leave	207	20.7%
💤 Hibernating	Low activity across all three metrics — largely inactive	273	27.3%
➖ Others	Mixed signals — need further monitoring	27	2.7%
Total Revenue Analysed: ₹2.3 Crore across 23,050 transactions At-Risk Revenue (money that could be lost): ₹53.5 Lakh
________________________________________
📈 Visuals
Customer Distribution by Segment
 
Revenue Contribution by Segment
 
Recency vs Monetary — Coloured by Segment
 
________________________________________
💡 What Does This Tell a Business?
1. The top 24% of customers (Champions + Loyal) are holding the business together. Only about 1 in 4 customers is truly engaged. This is a risky concentration — if these customers leave, revenue drops sharply.
2. ₹53.5 Lakh is sitting in the "At Risk" group right now. These 207 customers spent well in the past but have gone quiet. They have not left yet — but they will if no action is taken. A targeted win-back campaign could recover a significant portion of this revenue.
3. Hibernating customers (273 people) are the biggest re-engagement opportunity. This is the largest single group. A simple discount or loyalty offer could reactivate a meaningful percentage of them.
________________________________________
🎯 Recommendations
1.	Protect your Champions first — Create a VIP or loyalty reward program for the 127 Champions before they drift into the At Risk category.
2.	Launch a win-back campaign for At Risk customers — Personalised offers or reminders sent to the 207 At Risk customers could recover up to ₹16L+ if even 30% respond.
3.	Re-engage Hibernating customers with a low-cost campaign — A simple email with a discount code costs almost nothing but could reactivate hundreds of inactive buyers.
4.	Invest in Potential Loyalists — The 252 Potential Loyalists are the future Champions. Targeted engagement now will move them up the segment ladder.
________________________________________
📂 Project Structure
📁 RFM-Customer-Segmentation-Python/
│
├── 📁 Data/
│   ├── Customer_Master_Data.csv
│   └── Customer_Transactions.csv
│
├── 📁 Pictures/
│   ├── segment_distribution.png
│   ├── revenue_per_segment.png
│   └── rfm_scatter.png
│
├── 📁 Notebook/
│   └── python_mini_project.ipynb
│
└── README.md
