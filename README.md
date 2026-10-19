# customer-credit-and-loan-analytics
This project features a data-driven model that helps financial teams analyze consumer borrowing patterns, track repayment behaviors, and launch automated, personalized loan campaigns. By processing structural datasets across active portoflios, the system provides clarity on portfolio asset quality, client segment action, and cross-selling potential



## Business Problem
The goal of this analysis is to evaluate customer credit profiles, loan distribution patterns, and financial behaviors across different age demographics. By understanding how key credit metrics—such as annual income, monthly balance, payment delays, credit limit changes, and investment patterns—vary by age and credit mix, the business can optimize risk management, tailor credit products, and implement highly targeted marketing and promotional strategies.

---

## 1. Key General Metrics Baseline
Based on the executive summary dashboard, the overall macro baseline metrics for the customer population are:
* **Average Annual Income:** $170.60K
* **Average Monthly Income / Balance:** $405.24
* **Average Number of Delays in Payment:** 20.75 days from the due date
* **Average Credit Change % / Utilization:** 32.27%

---

## 2. Demographic Adjustments & Behavioral Insights

### Age vs. Changed Credit Limit Relationship
The analysis reveals an inverse correlation between age and adjustments to credit limits:
* **Younger Demographics (Ages 14–25):** Experience the highest average positive adjustments in credit limits, peaking at around **13.7%** to **14.0%**. This indicates a high-growth phase where credit lines are aggressively extended as income profiles establish.
* **Middle Demographics (Ages 25–45):** Stabilize with moderate limit increases fluctuating around **10%** to **11.5%**.
* **Older Demographics (Ages 45+):** Show a steep decline in credit line adjustments, dropping sharply to **6.6%** and below near age 60, signaling stable or freezing credit capacities as financial footprints mature.

### Payment Behavior Across Credit Mix Categories
Customer repayment behavior shifts drastically depending on their credit type diversity (*Good*, *Standard*, *Standard*, *Bad*):
* **Good Credit Mix:** Dominates high-value spend with strong consistency. It shows a stable distribution of low-to-high spent value payments and negligible defaults.
* **Standard Credit Mix:** Accounts for the highest frequency of standard volume transactions, representing the predictable majority of mid-tier consumers.
* **Bad Credit Mix:** Shows a significant spike in payment delays and an over-indexing of low-spent, irregular payment patterns, pointing to severe credit constraint and risk indicators.

---

## 3. Age Demographic Distribution Profile
The population age structure exhibits a clear bimodal frequency distribution with distinct consumer peaks:
* **Primary Peak:** Occurs around **Ages 23–26**, with a maximum single-year count of **956 customers** at age 25. This highlights a dominant young adult segment actively utilizing entry-to-mid level credit lines.
* **Secondary Peak:** Occurs around **Ages 38–44**, stabilizing near **523 customers** per year bracket, representing a mature credit segment.
* **Tails:** Drops off significantly for dependents under 18 (e.g., 134 at age 15) and seniors over 55.

---

## 4. Credit Score Cross-Tabulation by Age Groups
Categorizing the population into the defined structural age rules reveals how credit status shifts over a consumer lifecycle:
* **Teen (14–19):** Higher volume of Standard/Bad scores due to thin credit files.
* **Young Adult (19–25):** The highest volume segment across Good and Standard tiers.
* **Old Adult (25–35):** Highest representation in **Standard (2.1K)** and **Good (1.2K)** brackets.
* **Old1 (35–45):** Stable performance with **1.9K Standard** and **1.0K Good** profiles.
* **Old2 (>45):** Low baseline volume but highly consolidated counts in standard tiers.

---

## 5. Payment Behavior vs. Credit Mix Frequency Matrix
An evaluation of payment behavior highlights that:
* Customers with **Standard** credit mixes show the highest volume of general activity across all payment types.
* Customers with **Good** credit mixes prioritize regular, high-value investments and low-spent large-value transfers.
* Customers with **Bad** credit mixes are heavily constrained, with transaction volumes concentrated in low-value, high-frequency emergency transactions.

---

## 6 & 7. Potential Target Customer Segments for Loans
To maximize loan dispersal efficiency, the dataset isolates specific high-intent target ages based on **Average Credit Inquiries exceeding a 7.5 threshold**.

### Identified Target Demographics:
* **Teens/Young Starters (Ages 14–18):** Inquiries peak dramatically between **8.24 and 10.73**, driven by student loans, first vehicles, or credit line applications.
* **Mid-Career Resters (Ages 26–29 & 38–39):** Exhibit an average inquiry frequency of **7.52 to 7.87**, showing active market shopping for mortgages and lifestyle restructuring.

---

## 8. Lifetime Value (LTV) Scores & Targeted Promotions
Using the multi-factor business baseline equation for Customer Lifetime Value:
$$\\text{LTV} = (0.3 \\times \\text{Annual Income}) - (0.15 \\times \\text{Payment Delay days}) + 0.4 \\times \\text{Score Weight} + 0.075 \\times (\\text{Invested Amount} + \\text{Monthly Balance})$$

The following customized strategic promotions are automated for deployment:

| LTV Range | Promotional Campaign Strategy | Target Demographics Identified |
| :--- | :--- | :--- |
| **LTV > 80,000** | **30% off on online purchases + Home Loan at 4% interest rate** | Premium high-income earners (Ages 14, 27, 29, 31) |
| **LTV 60,000 – 80,000** | **15% off on online purchases + $10,000 worth of Gift Hampers** | Up-and-coming mid-tier earners (Ages 15, 22) |
| **LTV 50,000 – 60,000** | **Any loan option customized at 5% interest rate** | Stable core retail base (Age 30) |

---

## 9. Loan and Credit Card Ownership Cycles
Credit line utility shows direct age-based expansion patterns:
* **Ages 14–22:** Ownership climbs sharply as customers transition into independence. Average number of loans climbs to **5.27**, and credit cards peak at **7.09**.
* **Ages 23–45:** Ownership plateaus into a steady state, balancing an average of **3.50 to 3.96 loans** and maintaining **5.30 to 5.60 credit cards**.
* **Ages 45+:** Sharp consolidation phase where active loans drop below **1.58** and card accounts reduce, indicating long-term debt elimination.

---

## 10. Loan Dispersal Popularity Metrics
Total active dispersed loans across the corporate portfolio (**Total Dispersed: 3,305 loans**):
1. **Credit-Builder Loan:** 1,200 (Most Popular - High engagement for building credit files)
2. **Payday Loan:** 1,198 (High frequency, short-term liquidity requirement)
3. **Home Equity Loan:** 1,166 (Significant long-term asset collateral usage)
4. **Debt Consolidation Loan:** 1,153 (Refinancing preference among mid-tier groups)
5. **Auto Loan:** 1,105 (Steady baseline asset vehicle financing)
6. **Mortgage Loan:** 1,149 (Core real estate financing footprint)

---
**Dashboard Preview**

![Dashboard Snapshot](https://github.com/the-sejal/customer-credit-and-loan-analytics/blob/main/report%20page%201.png)
![Dashboard Snapshot](https://github.com/the-sejal/customer-credit-and-loan-analytics/blob/main/report%20page%201.png)

