# Sales_Finance_Report

## About Company :
- AtliQ Hardware is a multinational company that sells products such as printers, mice, PCs, etc., to two customer types: e-commerce platforms (e.g., Amazon, Flipkart) and brick-and-mortar stores (e.g., Croma, Best Buy). The company uses three sales channels:

    - Retailer: Croma, Amazon
    - Distributor: Neptune
    - Direct Channel: AtliQ e Store, AtliQ Exclusive
 
      
## Project Objective :
- The primary goal of this project is to analyze AtliQ Hardware's sales and financial performance from 2019 to 2021. This analysis will support the company in making informed decisions for growth, identifying sales trends, and evaluating market performance. The fiscal year for AtliQ Hardware runs from September to August.

-------------------------

### Techniques used :-

#### ETL Process with Power Query : 
- Extracted data from multiple sources, cleaned inconsistent values, fixed headers, and transformed negative quantities into absolute values.

#### Date Table Creation : 
- Built a dedicated Date Table in Power Query to ensure unique dates for accurate time-based analysis.

#### Fiscal Calendar Setup : 
- Derived fiscal months and quarters in Power Pivot to align reporting with AtliQ Hardware’s fiscal year.

#### Data Modeling : 
- Created relationships between fact and dimension tables using Power Pivot for structured and reliable data analysis.

#### Supplementary Data Integration : 
- Added additional datasets into the model through Power Pivot to enhance overall insights.

#### DAX Calculations : 
- Used DAX to build dynamic calculated columns and measures for deeper analytical flexibility.

#### Pivot Table Reporting : 
- Designed Pivot Tables to summarize sales and financial performance effectively.

#### Conditional Formatting : 
- Applied conditional formatting to highlight key trends, variances, and important metrics

-------------------------

### 1.P&L Insights (2019–2021) - Based on Net Sales, COGS, Gross Margin & GM%

#### 1️⃣ Overall Growth Performance

- Massive revenue growth from 2019 → 2021, rising from 87.5M → 598.9M.

- 2021 vs 2020 net sales increased by +204.5%, indicating extremely strong demand recovery or major expansion.

#### 2️⃣ Cost of Goods Sold (COGS) Trend

- COGS increased from 51.2M (2019) → 380.7M (2021).

- 2021 vs 2020 COGS showed a significant +308.6% jump, which is higher than the sales growth rate → indicating rising production costs or inefficiencies.

#### 3️⃣ Gross Margin Growth

- Gross Margin rose steadily from 36.2M (2019) → 218.2M (2021).

- 2021 vs 2020 GM increased by +297.6%, reflecting strong profitability expansion.

#### 4️⃣ Gross Margin % Decline

- GM% dropped from:

    - 41.4% (2019)

    - 37.3% (2020)

    - 36.4% (2021)

- Despite higher sales & margins, profitability % is decreasing, meaning:

- Costs are rising faster than revenue

- Possible pricing pressure or inflation in raw materials

![p&l report by fiscal years](https://github.com/parthpatoliya97/Sales_Finance_Report/blob/main/Images/P&L%20Report%20by%20fiscal%20years.png?raw=true)

---------------

### 2. Bottom 10 Products by Quantity

- The bottom-performing products collectively sold 545K units, with AQ HOME Allin1 Gen 2 being the least demanded at just 8,854 units. These low-performing items highlight potential candidates for discontinuation or re-evaluation.

![bottom 10 product based on quantity](https://github.com/parthpatoliya97/Sales_Finance_Report/blob/main/Images/bottom%2010%20products%20based%20on%20quantity.png?raw=true)

-------------------

### 3. Customer Net Sales Performance (2019–2021)

- Customer sales surged from $39.4M in 2020 to $169.2M in 2021, reflecting strong recovery and demand growth. Neptune ranked as the top customer in 2021, while Nova posted extraordinary growth due to minimal prior-year sales. High growth from established customers like Integration Stores and Chiptec indicates strong momentum in recently acquired or expanded partnerships.

![customer net sales](https://github.com/parthpatoliya97/Sales_Finance_Report/blob/main/Images/customer%20net%20sales%20performance.png?raw=true)

------------------

### 4. Division Sales Report

- Sales expanded sharply from $196.7M (2020) to $598.9M (2021), a growth of 304%. The PC division grew the fastest, while the P&A division remained the largest contributor at $338.4M. This strong multi-division growth reflects broad recovery and rising demand across categories.

![division sales report](https://github.com/parthpatoliya97/Sales_Finance_Report/blob/main/Images/division%20sales%20report.png?raw=true)

----------------

### 5. India Customer Net Sales Performance

- India generated $161.3M in 2021, driven largely by Amazon, which contributed $23M in sales. Customers such as Electricalsocity saw over 415% growth, indicating expansion into new sales channels and stronger retail penetration. The top 15 customers together represented the entirety of India’s market revenue.

![india net sales](https://github.com/parthpatoliya97/Sales_Finance_Report/blob/main/Images/india%20net%20sales.png?raw=true)

----------------

### 6. Market Performance vs Target

- AtliQ Hardwares missed its overall FY 2021 sales target by 9.2%, representing a shortfall of $54.9M. The USA recorded the largest absolute miss, while Spain and Canada saw the highest percentage shortfalls. Despite the overall decline, several markets—including France, the UK, South Korea, and Italy—exceeded their sales targets, demonstrating strong regional performance in these areas.

![market performance vs target](https://github.com/parthpatoliya97/Sales_Finance_Report/blob/main/Images/market%20performance%20vs%20target.png?raw=true)

---------------

### 7. GM% by Sub-Zone (P&L by Subzone)

- Gross Margin performance declined across all sub-zones from FY 2019 to FY 2021. ANZ and ROA recorded the sharpest drops, while India consistently remained the least profitable market. ROA and SE were the strongest profit contributors in earlier years, but by FY 2021, NE and ROA/SE emerged as the most profitable regions. Quarterly performance remained stable within each year, showing no major seasonal fluctuations.

![p&l by subzone](https://github.com/parthpatoliya97/Sales_Finance_Report/blob/main/Images/p&l%20by%20subzone.png?raw=true)

---------------

### 8. Market P&L Report (FY 2021)

- India emerged as the largest revenue-generating market, contributing $161.3M, nearly twice that of the USA. However, it also recorded the lowest Gross Margin %, confirming weaker profitability. In contrast, New Zealand, Japan, and the UK delivered the highest margins, making them the most profitable markets despite their smaller size.

![p&l report by market](https://github.com/parthpatoliya97/Sales_Finance_Report/blob/main/Images/p&l%20report%20by%20market.png?raw=true)

-----------------

### 9. Global P&L by Quarter

- Revenue grew consistently year-over-year, reaching $598.9M in 2021, though profitability weakened as GM% declined from 41.4% (2019) to 36.4% (2021). Sales peaked in Q1 2021 and gradually slowed through Q4, while gross margins remained stable across quarters, indicating consistent cost control despite rising sales volume.

![p&l repprt by quarters](https://github.com/parthpatoliya97/Sales_Finance_Report/blob/main/Images/p&l%20report%20by%20quarters%201.png?raw=true)

-------------------

### 10. Top 10 Products by Quantity

- The highest-selling products delivered 34.3M units, with AQ Master wired x1 Ms alone contributing 4.2M units. The dominance of the "AQ Master" and "AQ Gamers" product lines underscores their importance as the company’s core volume drivers.

![top 10 products by quantity](https://github.com/parthpatoliya97/Sales_Finance_Report/blob/main/Images/top%2010%20products%20on%20quantity.png?raw=true)
