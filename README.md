# Maven-Market-Quest
### Situation:
Maven Market, a multi-national grocery chain, operates in Canada, Mexico, and the United States. The aim was to analyze the topline performance across various regions and products.

### Task:
Leverage Power BI to connect and shape data, build a relational model, create calculated fields and measures, and design an interactive report to derive actionable insights.

### Action:
#### 1. Data Integration and Shaping
Connected and transformed data from tables: Calendar, Customers, Products, Regions, Returns, Stores, Transactions.
#### 2. Relational Modeling 
Established relationships among tables to ensure seamless data flow and analysis.
#### 3. DAX Measures
-Utilized CALCULATE to modify context filters.<br>
-Employed DATESINPERIOD, DATEADD, and DATESYTD for time intelligence.<br>
-Used MAX to determine peak values.<br>
-Calculated ratios with DIVIDE to avoid division errors.<br>
-Applied ALL to remove filters for total calculations.<br>
-Summed data with SUM and SUMX for aggregated insights.<br>
-Incorporated RELATED to fetch related table data.<br>
-Counted rows with COUNTROWS and distinct values with DISTINCTCOUNT.

### Result:
1. Portland achieved 1,000 sales in December.
2. High Top product returns in Mexico doubled from 4 to 8, with a return rate of 1.2%.
3. Plato products led with the highest profit margin of 63.55% in 1998.
