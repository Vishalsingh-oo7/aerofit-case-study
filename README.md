# Aerofit — Descriptive Statistics & Probability


---

## Project snapshot

**Goal:** Use descriptive statistics and probability to profile Aerofit customers, compare three treadmill products (KP281, KP481, KP781), and provide actionable business recommendations for product positioning and marketing.


---

## Business problem

The Aerofit market research team wants to:

* Identify customer segments most likely to buy each treadmill model.
* Summarize numeric and categorical statistics to support product decisions.
* Compute event and conditional probabilities (e.g., purchase probability by age/income) and convert insights into business actions.

---

## Data

### Inferred data dictionary

The notebook used these columns (please ensure your CSV has matching names):

* `Product` — treadmill model (KP281, KP481, KP781)
* `Revenue` — order/revenue value
* `Age` — numeric age
* `Gender` — Male / Female
* `Income` — numeric annual income
* `Education` — years of education
* `MaritalStatus` — Partnered / Single
* `Fitness` — fitness level (numeric scale)
* `Usage` — weekly usage frequency (times/week)
* `Miles` — miles run per week
* `Age group` — derived bucket (Young / Middle-aged / Old)
* `Income group` — derived bucket (Low / Medium / High)

**Income buckets used in notebook:**

* `Low` : 29,000 – 50,000
* `Medium` : 51,000 – 75,000
* `High` : 76,000 – 105,000

---

## Product portfolio (notebook notes)

* **KP281** — entry-level — **\$1,500** — most preferred
* **KP481** — mid-level — **\$1,750**
* **KP781** — premium — **\$2,500** — least preferred

---

## Analysis performed 

1. Data loading
2. Data preprocessing (missing values, type fixes, new buckets)
3. Outlier detection & handling
4. Univariate analysis (counts, proportions)
5. Descriptive statistics (mean, median, std, IQR)
6. Bivariate analysis (cross-tabs, group comparisons)
7. Probability & conditional probability analyses (P(product | age/income/education))
8. Business insights & recommendations

---

## Key findings & insights (extracted from the notebook)

* **Product preference:** KP281 ≈ **44.44%**, KP481 ≈ **33.3%**, KP781 ≈ **22.22%**. KP281’s affordability likely drives adoption.
* **Gender:** ≈ **57.78%** male customers.
* **Marital status:** ≈ **59.4%** married.
* **Age:** mean age ≈ **28.8 years** — concentrated in the young segment (18–39).
* **Income groups:** \~**88%** of customers are Low + Medium (29k–75k), \~**11.67%** High.
* **Education:** majority at \~14–16 years of education; very high education (>18 yrs) correlates with lower purchase likelihood.
* **Behavioral pattern (KP481 buyer):** Age 18–39, Income 29k–75k, Education 14–16 yrs, Usage \~3×/week, Runs \~80–120 miles/week.
* **Notable:** Very high income (>80k) customers showed lower purchase probability (likely opt for other premium brands).

---

## Business recommendations

* **Promote KP281** to young, low-to-mid income segments as the value model.
* **Target KP481** to mid-runners (18–39 yrs) emphasizing value-for-money and mid-level performance.
* **Re-evaluate KP781** — adjust positioning, pricing, or target premium channels.
* **Use education & fitness signals** to sharpen ad targeting.



---
