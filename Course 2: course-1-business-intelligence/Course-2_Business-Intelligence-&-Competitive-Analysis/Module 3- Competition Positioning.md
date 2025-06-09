# 📊 Module 3: Competition Positioning

This module explores how to assess a company’s position in the competitive landscape using data-driven analysis. It focuses on ranking firms relative to peers and identifying performance patterns through KPI benchmarking.

---

## 🎯 Learning Objectives

- Position a company within its industry to evaluate its competitive standing  
- Rank companies against their peers to identify strengths, weaknesses, and improvement areas  
- Examine KPIs to detect abnormal performance signals  

---

## 🔍 Key Concepts and Examples

### 🧩 1. Competitive Landscape Mapping

Understanding the size and profitability of firms helps reveal their market position. For example, in the airline industry:

- **Delta Air Lines (DAL)**, **United Airlines (UAL)**, and **American Airlines (AAL)** were similar in size based on revenue.  
- However, **Delta** and **United** showed higher operating income than **American**, indicating they were more profitable.  
- **Southwest Airlines (LUV)**, though smaller in size, had better profitability due to efficient asset utilization.

This shows that size and profitability do not always align, and a smaller company can outperform a larger one operationally.

---

### 📈 2. Profit Frontier

The **profit frontier** represents the best achievable profitability level for a given revenue class. It acts like a boundary that defines optimal performance.

- **Delta Airlines** was positioned on the profit frontier, showing it achieved the best possible margin for its revenue level.  
- **American Airlines**, on the other hand, was far below the frontier, making it the worst performer in its revenue group.

**Think of it like a running race**. The profit frontier is the track record, and companies on or near it are top performers. Those far behind signal underperformance and room for improvement.

---

### 📊 3. Return vs. Risk Matrix

This analysis plots **Return on Assets (ROA)** against the **Liability to Asset ratio**, helping assess how well a company converts its resources into profit while managing financial risk.

- **Southwest Airlines** had the **highest ROA** and **lowest liability ratio**, reflecting strong performance and financial stability.  
- **American Airlines** had a **liability-asset ratio greater than 1**, meaning it had more liabilities than assets. It also had the **lowest ROA**, showing weak returns and high financial stress.

**In simple terms**, if you are borrowing too much (high liabilities) but not making enough return (low ROA), your business is operating under financial strain.

---

### 🥇 4. Enterprise Ranking

Enterprise ranking uses KPIs such as **total revenue**, **operating income**, and **ROA** to classify companies within an industry. These rankings help detect which firms lead and which lag behind.

- **Delta** ranked highest in both **total revenue** and **operating income** among US airlines.  
- **Southwest**, despite lower revenue, ranked highest in **ROA**, reflecting better profitability per dollar of asset.  
- A mistake often made is assuming that bigger companies are always better. For example, **JD.com** had higher revenue but was less profitable than **Alibaba**.

**The key lesson is**: ranking by multiple KPIs gives a more complete picture than just looking at revenue alone.

---

### 🩺 5. KPI Examination (Health Check Approach)

**KPI examination** is similar to a **physical health check-up**. Just as doctors assess your health using vital signs and reference ranges, business analysts evaluate a company using financial metrics and industry percentiles.

- In medicine, a **red blood cell (RBC)** count between the **5th and 95th percentile** is considered normal.  
- In business, a company’s KPI (such as net income margin or current ratio) is considered healthy if it falls between the **25th and 75th percentile** compared to peers.

#### Example: American Airlines KPI Health Check

- **Profitability**: Lowest operating margin, net margin, and ROA in the industry (almost 0 percentile rank).  
- **Financial Health**: Current ratio at 45 percent and liability-asset ratio above one, suggesting inability to meet short-term debts.  
- **Growth**: Normal total revenue growth, but operating and net income were below the 25th percentile.  
- **Efficiency**: Acceptable operating cost over total revenue, but high inventory days indicated mixed operational efficiency.

This examination process identifies specific problems and helps guide targeted improvements.

---

## ✅ Final Takeaway

Competitive positioning is not just about being big. It is about being **efficient**, **profitable**, and **financially healthy** compared to others in the same industry. Methods like **profit frontier mapping**, **risk-return analysis**, **ranking**, and **KPI benchmarking** give a clear, multi-dimensional view of how a company is really performing.

---
## Quiz: 


| Question | Topic                                | Correct Answer(s)                                                                                                        |
| -------- | ------------------------------------ | ------------------------------------------------------------------------------------------------------------------------ |
| Q1       | Revenue vs. Cost Analysis            | How much more revenue per unit cost increase; Total revenue over total cost ratio                                       |
| Q2       | Profit Frontier                      | Profit margin calculated as ratio (denominator = revenue); Harder to maintain margin as revenue increases               |
| Q3       | Return vs. Risk in Competitiveness   | Different from financial investment; Higher liability-asset ratio can lead to lower ROA in capital-intensive industries |
| Q4       | Combining Enterprise Rankings        | Revenue shows size but not profit; Big ≠ Strong; Profitability/ROA matters more than size                               |
| Q5       | KPI Examination                      | Shows percentile rank; Identifies normal/high/low KPI range; Provides reference intervals                               |
| Q6       | KPI Interpretation                   | Helps find alarming KPIs; Shows outperforming/underperforming areas vs. competitors 

## 📌 Project Summary

This project focuses on the **competitive positioning** and **KPI examination** of **DoorDash**, with a contextual link to **Wolt** (a Finnish company now owned by DoorDash) and the broader food delivery industry. While my original focus was on Finland and Wolt, due to data availability, I pivoted to analyzing DoorDash through U.S. market data on SCData.

Key findings include:
- Strong revenue and gross profit performance
- Persistently negative net income due to high operational costs
- High growth rate in free cash flow and revenue
- Mixed financial health, with solid liquidity but higher liabilities

This helped understand DoorDash's position among its peers and the trade-offs between growth and profitability in capital-intensive sectors.

🔗 **View the full interactive dashboard here**: [https://www.scdata.ai/project/58041](https://www.scdata.ai/project/58041)

# To understand KPI chart:  

## 📊 KPI Examination – DoorDash, Inc.

In this section, I conduct a **KPI examination** for DoorDash using available US market data via SCData.ai. Although my original focus was on Wolt and Finland, this pivot helps maintain industry relevance and allows for deeper analysis, thanks to richer data availability for DoorDash.

### 🔍 Objective:
To understand where DoorDash stands among its peers in the **food delivery & logistics sector** across four key areas:
- Profitability
- Financial Health
- Growth
- Operational Efficiency

---

## 🧮 Summary Table

| KPI Category         | KPI                                         | DoorDash Value | Percentile Rank | Status   | Key Insight                                                                 |
|---------------------|----------------------------------------------|----------------|------------------|----------|------------------------------------------------------------------------------|
| **Profitability**   | Gross Margin                                 | 0.468          | 68th             | Normal   | Healthy gross margin, above industry median (0.36)                          |
|                     | Operating Margin                             | -0.067         | 27th             | Normal   | Struggles with operational profit; slightly better than lowest quartile     |
|                     | Net Margin                                   | -0.066         | 33rd             | Normal   | Net profitability is weak but within the typical industry range             |
|                     | Return on Assets                             | -0.053         | 35th             | Normal   | ROA is negative, reflecting efficiency challenges                           |
|                     | Return on Invested Capital                   | -0.077         | 27th             | Normal   | Returns are low, showing room for strategic investment improvements         |
| **Financial Health**| Free Cash Flow / Total Cost                  | 0.146          | 86th             | **High** | Strong cash flow efficiency; among the top 15% of peers                     |
|                     | Current Ratio                                | 1.641          | 56th             | Normal   | Good liquidity to cover short-term obligations                              |
|                     | Liability Asset Ratio                        | 0.371          | 18th             | **Low**  | Conservative debt structure; lower financial risk                           |
| **Growth**          | Total Revenue Growth Rate                    | 31.1%          | 90th             | **High** | Outstanding revenue growth – industry-leading performance                   |
|                     | Free Cash Flow Growth Rate                   | 63.2%          | 100th            | **High** | Exceptional FCF growth – highest among peers                                |
| **Operational Eff.**| SG&A / Total Revenue                         | 36%            | 60th             | Normal   | SG&A cost structure is fairly efficient compared to peers                   |
|                     | Cash Conversion Cycle                        | 5.35 days      | 32nd             | Normal   | Efficient cycle; quicker than industry median (43 days)                     |

---

## 🧠 Interpretation & Examples

To make KPI Examination more relatable:

- Just like **a doctor compares your lab test results (e.g., RBC count)** against a reference range (say 5th–95th percentile), here we compare DoorDash's metrics against industry benchmarks.
  
- Example: DoorDash’s **Gross Margin (46.8%)** is better than the median (36%) and falls between the **75th and 90th percentiles**, meaning it’s performing better than most competitors in this area.

- On the flip side, a KPI like **Operating Margin (-6.7%)** falls below the 50th percentile — suggesting operational inefficiencies or high fixed costs.

---

## ✅ Key Takeaways

- **Strengths**: DoorDash is a top performer in **revenue growth** and **cash flow generation**, with a solid **gross margin** and **low debt levels**.
- **Weaknesses**: It still struggles with **profitability ratios** such as operating and net margin, and has **moderate efficiency issues** in return-based KPIs.
- **Opportunity**: Leveraging strong growth and cash flow to streamline operations and improve long-term profitability.

---
