<p align= 'center'> <img width="200" height="120" alt="image" src="https://github.com/user-attachments/assets/353458ce-0ac8-4daa-9aa9-112ab5cc13d0" />

# <p align= 'center'> Store Performance Report

<br>

# <p align= 'center'> Client Background

<br>

OfficeSupplies is a US-based company that sells popular consumer office supplies and electronics to US clientele. Established in 2019, the company has grown and expanded in the last few years. It has encountered increasing competition from peer companies as well as unique challenges and opportunities brought on by COVID-19 pandemic.

OfficeSupplies book of business is approaching **800** unique customers and possesses over 5900 transactions, generating sales revenue exceeding $1.6 million. The available data spans various dimensions and metrics, including sales, products, sales by regions, and company’s profit trend in year 2019 vs 2020.  

Reporting to the Head of Operations, an in-depth analysis was conducted to evaluate OfficeSupplies store’s performance over the past several years (2019-2020). This comprehensive review provides valuable insights that internal cross-functional teams will utilize to streamline processes and enhance store’s commercial performance. The key insights and recommendations focus on the following areas:

<br>

### Store performance Key Metrics:
**- Sales trends – Focusing on key metrics of sales revenue, number of orders placed, and average order value (AOV).**
**- Product performance – Analyzing different product lines, market impact, and product returns to inform strategic product decisions.**
**-	Regional results – Evaluating regional demand and product performance within regions to identify areas for improvement.** 

<br>

## <p align= 'center'> Executive Summary
<br>
### <p align= 'center'> Sales Revenue Analysis (2019-2020)

 <img width="800" height="400" alt="image" src="https://github.com/user-attachments/assets/cdfd425d-9f96-40c6-bead-d6e35d8b325b" />

<br>

**1.	Revenue Growth and Peak Performance:**
- [Q4 2020 was the strongest quarter, with sales consistently growing each month as a result of the COVID-19 pandemic]
- 	Q4 2020 saw the highest revenue month ($126.2K in December 2020), making it the best – performing period 
-  Difference between first’s (January 2019) and last month’s revenue (December 2020) is +88.1K in sales which shows positive business growth 

**2.	Quarterly insights & Seasonal Trends:** 
- Q4 of each year typically shows strong performance, likely due to seasonal shopping trends and marketing efforts.
- Q1 of 2020 ended very well (89K in sales), but revenue quickly dropped to 50.8K signaling an overall weak performance in April. 

**3.	Key Takeaways & Recommendations:**
- {Investigate the causes of the Q2 2020 Decline (e.g., market changes, competition, internal factors, pricing.)
- Leverage high performance periods (e.g., Q3 and Q4 of strong years) to refine marketing and sales strategies. 
- Reassess business strategy for 2021, focusing on pricing, promotions, and customer engagement to regain momentum at the start of the Q1.


<br>

## <p align= 'center'> Dataset Structure and ERD (Entity relationship diagram)

The database structure as seen below consists of four tables: orders, order_status, location and customers with a total row count of 5901 records. 

 <img width="800" height="400" alt="image" src="https://github.com/user-attachments/assets/18a09943-0822-48ef-a7a4-5539c3608e91" />



<br>


## <p align= 'center'> Insights Deep-Dive

<img width="800" height="400" alt="image" src="https://github.com/user-attachments/assets/ca2080f5-b49b-4e70-acc5-6f356abbaa56" />
<br>
 
## <p align= 'center'> Sales Revenue
1.	Minimum and Maximum Sales revenue 
o	Minimum value of Sales Revenue was reached during February 2019 (25.5K) which represents sales revenue slowdown most likely caused by the end of a holiday season. 
o	Maximum value of Sales revenue was reached in December 2020 (126.2k), which is more than double compared to sales revenue a year ago. 
2.	Sharp Revenue Growth in Q4 – A Major Sales Increase
o	Historically, Q4 (Oct-Dec) has been the strongest quarter due to holiday shopping (Black Friday, Cyber Monday, Christmas sales). 
o	In November 2019, company was able to reach 66k sales for the first time during that year and in December 2020, company recorded 126k sales. The pandemic led to a significant boost in eCommerce sales, with Q4 seeing a rapid increase in sales revenue for both years.
3.	Declining growth months – February and April – indication of a weak consumer demand
o	February and April are declining months for both 2019 and 2020 when it comes to sales revenue growth. 
o	Q1 2020 finished strong (89K in March) but decreased significantly to 50.8K in April. This represents a sharp decline in sales revenue of 42.9%.  
o	Sales revenue lows in February 2019 and April 2020 suggests customer retention, pricing, or product – market fit issues. OfficeSupplies company may need to re-strategize through marketing, promotions, or change in pricing.  

<br>

<img width="800" height="400" alt="image" src="https://github.com/user-attachments/assets/6efa2eec-1631-4b72-abde-13a42fa5b7c5" />




<br>
 
Average Order Value (AOV) and Order Count

1.	Sharp AOV Surge in 2020 
o	2020 saw the highest AOV growth from $224 (Dec 2019) to $390 (Dec 2020) which is 74% increase. This aligns with pandemic – driven eCommerce boom. 
o	AOV growth indicates growing business and reflects higher customer satisfaction and loyalty. 
o	From March 2019 to September 2019 there was a constant decline in AOV (from $257 to $177). This decline might indicate a potential customer behavior shift or economic factors change and should be investigated 
further. 

<br>

<img width="800" height="400" alt="image" src="https://github.com/user-attachments/assets/9fcfe74b-1280-4cf3-a41e-fcc033fb5181" />

<br>

2.	Order Count
o	Order counts closely following sales revenue, for example, minimum value of number of orders (Feb 2019, 126) is correlated with minimum value of sales revenue 25.5K for the same month. 
o	Total orders increased by 28% from 2019 to 2020. 
o	A high number of orders doesn’t necessarily result in a high amount of sales revenue. September 2020 had record breaking 385 sales, but sales revenue did not match Q4 2020 heights. 
o	High AOV can lead to high sales revenue even when number of orders is average (for example, August 2020). It indicates effective upselling and increased customer loyalty.  

 <br>


## <p align= 'center'> Product Performance
<br>
<img width="800" height="400" alt="image" src="https://github.com/user-attachments/assets/1680b516-2b32-40a5-83d9-8bebe17d3364" />
<br>

<p align= 'center'> Sales Heatmap
o	Phones had the most consistent sales for two consecutive years totaling 196.5K and it’s the highest revenue generating product overall. 
o	The second and third best performing products in terms of sales are Chairs (181.9K total) and Binders (174.9K total). 
o	Binders made the biggest improvement in sales year wise. From 2019 to 2020 there was a huge shift in demand for binders (+314% in sales revenue).
o	Fasteners (15.2K total), Envelopes (16.5K) and Labels (19.3K) had a low number of sales compared to other products, although their demand increased from 2019 to 2020. 

<br>
<p align= 'center'> Profit Heatmap
o	Copiers were the most profitable items by a big margin with total profit reaching +42.7K over two years.
o	Accessories (+25.3K total), Phones (+22.3K total) and Paper (+21K total) also generated high profit margins from sales. 
o	The least profitable item – Tables. It generated a loss of -11K over two-years period and this item should be monitored closely. Company might want to replace tables with other items or remove them from the market to avoid future loss. 
o	Other items that generate loss are supplies (-1.6K) and bookcases (-343).  



<img width="800" height="400" alt="image" src="https://github.com/user-attachments/assets/17b91308-e848-438b-8412-210f4a48f4b6" />

<br>
 
Returns by each Sub-Category
o	Binders (46), Paper (35) and Furnishings (32) are the items that customers returned the most. These items require more attention because it might be an indicator of poor quality/unreliable products and an urgent need for quality control. 
o	Copiers (2), Machines (3) and Supplies (5) were the least returned items, indicating a high quality of products and high customer satisfaction with an item. 


<br>


## <p align= 'center'> Regional Results
 <br>
<img width="800" height="400" alt="image" src="https://github.com/user-attachments/assets/bdd9cc0d-a411-47ad-bf45-f6c8e41618cd" />

o	In 2019, West region generated the most sales revenue (185K), while South region generated the least sales revenue from all four regions with 89K.
o	In 2020, sales distribution across all four regions remained similar. West region lead sales department with 337K sales revenue while South region generated the least sales revenue with 164K. 
o	 All four regions improved their sales revenue significantly from 2019 to 2020.  South region increased their sales revenue by 84%, West region by 82%, Central region by 81% and East region by 64%.

 <img width="811" height="802" alt="image" src="https://github.com/user-attachments/assets/bd876a53-3be6-4c7b-aa79-cf4e5a403540" />
<br>

o	In 2019, West region generated the most profit from sales (+24K), while South region generated the least amount of profit from all regions with 18K.
o	In 2020, there was a big shift in profit for all four regions. West region increased their profit margin by 83%, while East region improved by 65%.  
o	 Central and South regions had a difficult year profit wise, and their profit margins decreased from 2019 to 2020 by 60% and 50% respectively.

<br>

### <p align= 'center'> Recommendations
<br>
Based on the uncovered insights, here are actionable items that OfficeSupplies can take away from our analysis.
<br>
<p align= 'center'> Sales
- Remedy sales lows due to seasonal fluctuations in Q2 2020 by increasing marketing campaigns during these low – sales periods. 
o	In Q2 2020 Sales declined by -27.3% compared to Q1.
o	While Average Sales Growth for each quarter is +15.1%
- Company should prioritize maintaining AOV above the average during all year by setting a free shipping threshold by encouraging larger shopping carts, creating loyalty programs and implementing customer reviews.
o	In 2020 April, AOV decreased to 222, which is 14.6% below the average.
<br>
<p align= 'center'> Products
- Optimize inventory for high – performing products year – round to increase yearly profit margins
o	Copiers are the strongest items in terms of profit, reaching +42.7K over two years.
o	Accessories, Phones and Paper also generated high profit from sales with +68.6K combined profit over two years. 
- Deprioritize inventory for low – performing products.
o	Tables and Supplies together generated 156K in Sales Revenue over two years but profit-wise, resulted in a loss of 12.6K.
- Develop a quality assurance and quality control plan for the most returned items. 
o	Binders (46), Paper (35), Furnishings (32) and Phones (29) were the most returned items resulting in 49% of total returns. 
<br>
<p align= 'center'> Regions 
- Maximize market share in West region, as this region dominates sales across all OfficeSupplies products. 
o	33% of all product sales happened in West region.
o	38% of all profit comes from the West region.
- Diversify the portfolio in the South market by potential expansion to Latin America by offering localized products, sales channels and market reach to increase sales revenue, purchase orders and potential profit. 
o	South region generated only 16% of all sales revenue and only 15% of all profit from all regions leaving a potential room for business development and growth. 
