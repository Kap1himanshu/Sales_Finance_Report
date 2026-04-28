# Sales_Finance_Report

## About Company :

* AtliQ Hardware is a multinational company that sells products such as printers, mice, PCs, etc., to two customer types: e-commerce platforms (e.g., Amazon, Flipkart) and brick-and-mortar stores (e.g., Croma, Best Buy). The company uses three sales channels:

  + Retailer: Croma, Amazon
  + Distributor: Neptune
  + Direct Channel: AtliQ e Store, AtliQ Exclusive

## Project Objective :

* The primary goal of this project is to analyze AtliQ Hardware's sales and financial performance from 2019 to 2021. This analysis will support the company in making informed decisions for growth, identifying sales trends, and evaluating market performance. The fiscal year for AtliQ Hardware runs from September to August.

---

### Techniques used :-

#### ETL Process with Power Query :

* Extracted data from multiple sources, cleaned inconsistent values, fixed headers, and transformed negative quantities into absolute values.

#### Date Table Creation :

* Built a dedicated Date Table in Power Query to ensure unique dates for accurate time-based analysis.

#### Fiscal Calendar Setup :

* Derived fiscal months and quarters in Power Pivot to align reporting with AtliQ Hardware's fiscal year.

#### Data Modeling :

* Created relationships between fact and dimension tables using Power Pivot for structured and reliable data analysis.

#### Supplementary Data Integration :

* Added additional datasets into the model through Power Pivot to enhance overall insights.

#### DAX Calculations :

* Used DAX to build dynamic calculated columns and measures for deeper analytical flexibility.

#### Pivot Table Reporting :

* Designed Pivot Tables to summarize sales and financial performance effectively.

#### Conditional Formatting :

* Applied conditional formatting to highlight key trends, variances, and important metrics.

---

### 1. P&L Insights (2019–2021) - Based on Net Sales, COGS, Gross Margin & GM%

#### 1️⃣ Overall Growth Performance

* Massive revenue growth from 2019 → 2021, rising from 87.5M → 598.9M.
* 2021 vs 2020 net sales increased by +204.5%, indicating extremely strong demand recovery or major expansion.

#### 2️⃣ Cost of Goods Sold (COGS) Trend

* COGS increased from 51.2M (2019) → 380.7M (2021).
* 2021 vs 2020 COGS showed a significant +308.6% jump, which is higher than the sales growth rate → indicating rising production costs or inefficiencies.

#### 3️⃣ Gross Margin Growth

* Gross Margin rose steadily from 36.2M (2019) → 218.2M (2021).
* 2021 vs 2020 GM increased by +297.6%, reflecting strong profitability expansion.

#### 4️⃣ Gross Margin % Decline

* GM% dropped from:

  + 41.4% (2019)
  + 37.3% (2020)
  + 36.4% (2021)

* Despite higher sales & margins, profitability % is decreasing, meaning:
  + Costs are rising faster than revenue
  + Possible pricing pressure or inflation in raw materials

<img width="698" height="355" alt="image" src="https://github.com/user-attachments/assets/1b849ff6-34b0-4373-9206-f4b91de03445" />


---

### 2. Bottom 10 Products by Quantity

* The bottom-performing products collectively sold 545K units, with AQ HOME Allin1 Gen 2 being the least demanded at just 8,854 units. These low-performing items highlight potential candidates for discontinuation or re-evaluation.

<img width="651" height="512" alt="image" src="https://github.com/user-attachments/assets/73fb5078-a71b-4680-9310-94beb6febe0d" />

---

### 3. Customer Net Sales Performance (2019–2021)

* Customer sales surged from $39.4M in 2020 to $169.2M in 2021, reflecting strong recovery and demand growth. Neptune ranked as the top customer in 2021, while Nova posted extraordinary growth due to minimal prior-year sales. High growth from established customers like Integration Stores and Chiptec indicates strong momentum in recently acquired or expanded partnerships.

<img width="424" height="702" alt="image" src="https://github.com/user-attachments/assets/3b6cc050-8855-40c1-9347-ac480ce51920" />


---

### 4. Division Sales Report

* Sales expanded sharply from $196.7M (2020) to $598.9M (2021), a growth of 304%. The PC division grew the fastest, while the P&A division remained the largest contributor at $338.4M. This strong multi-division growth reflects broad recovery and rising demand across categories.

<img width="483" height="338" alt="image" src="https://github.com/user-attachments/assets/3d90d734-43f5-4868-a417-bae16068a124" />


---

### 5. India Customer Net Sales Performance

* India generated $161.3M in 2021, driven largely by Amazon, which contributed $23M in sales. Customers such as Electricalsocity saw over 415% growth, indicating expansion into new sales channels and stronger retail penetration. The top 15 customers together represented the entirety of India's market revenue.

<img width="552" height="656" alt="image" src="https://github.com/user-attachments/assets/b28b0486-eb80-45e6-915b-211fd9cd2372" />


---

### 6. Market Performance vs Target

* AtliQ Hardwares missed its overall FY 2021 sales target by 9.2%, representing a shortfall of $54.9M. The USA recorded the largest absolute miss, while Spain and Canada saw the highest percentage shortfalls. Despite the overall decline, several markets—including France, the UK, South Korea, and Italy—exceeded their sales targets, demonstrating strong regional performance in these areas.

<img width="662" height="703" alt="image" src="https://github.com/user-attachments/assets/a7f884ec-a862-4c72-9d21-bf5f5ca01840" />


---

### 7. GM% by Sub-Zone (P&L by Subzone)

* Gross Margin performance declined across all sub-zones from FY 2019 to FY 2021. ANZ and ROA recorded the sharpest drops, while India consistently remained the least profitable market. ROA and SE were the strongest profit contributors in earlier years, but by FY 2021, NE and ROA/SE emerged as the most profitable regions. Quarterly performance remained stable within each year, showing no major seasonal fluctuations.

<img width="439" height="711" alt="image" src="https://github.com/user-attachments/assets/96100d20-0f51-42c9-9d08-db248b7a18b8" />


---

### 8. Market P&L Report (FY 2021)

* India emerged as the largest revenue-generating market, contributing $161.3M, nearly twice that of the USA. However, it also recorded the lowest Gross Margin %, confirming weaker profitability. In contrast, New Zealand, Japan, and the UK delivered the highest margins, making them the most profitable markets despite their smaller size.

<img width="581" height="710" alt="image" src="https://github.com/user-attachments/assets/d1327a62-dc06-44a4-8270-20850e0d7270" />


---

### 9. Global P&L by Quarter

* Revenue grew consistently year-over-year, reaching $598.9M in 2021, though profitability weakened as GM% declined from 41.4% (2019) to 36.4% (2021). Sales peaked in Q1 2021 and gradually slowed through Q4, while gross margins remained stable across quarters, indicating consistent cost control despite rising sales volume.

<img width="423" height="707" alt="image" src="https://github.com/user-attachments/assets/28d6671f-1379-4b14-982d-de996e18cb2e" />


---

### 10. Top 10 Products by Quantity

* The highest-selling products delivered 34.3M units, with AQ Master wired x1 Ms alone contributing 4.2M units. The dominance of the "AQ Master" and "AQ Gamers" product lines underscores their importance as the company's core volume drivers.

<img width="801" height="627" alt="image" src="https://github.com/user-attachments/assets/ebbadef8-3279-4ff1-888a-7fd38f42e7c5" />

