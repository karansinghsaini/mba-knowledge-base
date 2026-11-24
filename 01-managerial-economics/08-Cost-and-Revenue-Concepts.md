# Cost and Revenue Concepts

## 8.1 Cost Concepts

* **What are Costs?** Costs are the total expenses a business pays to produce goods or services. Understanding how costs behave helps managers set prices, plan budgets, and maximize profits.

### 1. Types of Short-Run Costs

| Cost Type | Simple Meaning | Formula | Real-World Examples |
| :--- | :--- | :--- | :--- |
| **Fixed Cost ($FC$)** | Expenses that **do not change** regardless of how much you produce (paid even if output is zero). | $FC = \text{Constant}$ | Factory rent, permanent staff salaries, insurance, loan interest. |
| **Variable Cost ($VC$)** | Expenses that **change directly** with production—rising when output grows and falling when output drops. | $VC = f(Q)$ | Raw materials (flour, steel), hourly worker wages, factory electricity. |
| **Total Cost ($TC$)** | The combined total of fixed and variable costs at any production level. | $TC = FC + VC$ | Total monthly spending on rent + materials + wages. |
| **Average Cost ($AC$ or $ATC$)** | The cost of producing **one single unit** on average (per-unit cost). | $AC = \frac{TC}{Q} = AFC + AVC$ | If making $100$ shirts costs $₹20,000$, then $AC = ₹200$ per shirt. |
| **Marginal Cost ($MC$)** | The **extra cost** of producing **one additional unit** of output. | $MC = \frac{\Delta TC}{\Delta Q}$ | If making $100$ shirts costs $₹20,000$ and $101$ shirts costs $₹20,150$, $MC = ₹150$. |

### 2. Short-Run Cost Curves & How They Behave

In the short run, at least one input (like factory size) is fixed, which shapes how cost curves look:

```
Cost per Unit
  │ \          /  MC (Marginal Cost)
  │  \        /   /  ATC (Average Total Cost)
  │   \      /   /   /  AVC (Average Variable Cost)
  │    \    ●───●───'  <-- MC cuts AVC & ATC at their lowest points!
  │     \  /   /
  │      `●───'
  │       \
  │        `────────── AFC (Average Fixed Cost - falls continuously)
  └───────────────────── Output (Q)
```

* **Average Fixed Cost ($AFC$):** Falls continuously as output increases because the fixed rent/overhead is spread over more units ("spreading effect").
* **Average Variable Cost ($AVC$) & Average Total Cost ($ATC$):** Both are **U-shaped**—they fall at first due to better teamwork and efficiency, then rise later due to overcrowding and diminishing returns.
* **Marginal Cost ($MC$) vs. Average Cost ($AC$) Rule:**
  * When **$MC < AC$**, Average Cost is **falling** (the extra unit is cheaper than the current average, pulling the average down).
  * When **$MC > AC$**, Average Cost is **rising** (the extra unit is more expensive than the current average, pulling the average up).
  * When **$MC = AC$**, Average Cost is at its **lowest (minimum) point**.

### 3. Long-Run Cost Curves ($LRAC$)

* **No Fixed Costs in the Long Run:** Over a long period, a business can build bigger factories, buy new machines, or downsize—so **all costs become variable**.
* **The "Envelope" Curve:** The **Long-Run Average Cost ($LRAC$)** curve is a smooth U-shaped curve that wraps around (is tangent to) multiple Short-Run Average Cost ($SRAC$) curves representing different factory sizes.

```
Average Cost
  │ \   SRAC1 (Small Plant)         SRAC3 (Large Plant) /
  │  \   /   \                     /   \               /
  │   `─●─────\   SRAC2 (Optimal) /     `─────────────'
  │      \     \   /   \         /
  │       `─────`─●─────`───────'  <-- LRAC ("Envelope Curve")
  │           Optimal Scale
  └─────────────────────────────────── Output (Q)
   Economies of Scale   │   Diseconomies of Scale
```

* **Why $LRAC$ is U-Shaped:**
  * **Falling Part (Economies of Scale):** Growing larger lowers per-unit costs through bulk buying discounts, specialized managers, and better machinery.
  * **Rising Part (Diseconomies of Scale):** Growing *too* large raises per-unit costs due to slow communication, management delays, and coordination issues.

---

## 8.2 Revenue Concepts

* **What is Revenue?** Revenue is the total money a company brings in from selling its products or services before subtracting any costs.

### 1. Total, Average, and Marginal Revenue

1. **Total Revenue ($TR$):** Total cash earned from sales ($TR = P \times Q$).
   * *Example:* Selling $100$ units at $₹10$ each gives $TR = ₹10 \times 100 = ₹1,000$.
2. **Average Revenue ($AR$):** Revenue earned **per unit sold**. Because $AR = \frac{TR}{Q} = \frac{P \times Q}{Q}$, **Average Revenue is always equal to Price ($AR = P$)**, making the $AR$ curve identical to the firm's demand curve.
   * *Example:* If $TR = ₹2,000$ from selling $200$ units, $AR = \frac{₹2,000}{200} = ₹10$.
3. **Marginal Revenue ($MR$):** The **extra revenue** gained from selling **one additional unit** ($MR = \frac{\Delta TR}{\Delta Q}$).
   * *Example:* If selling $5$ units earns $₹500$ and selling $6$ units earns $₹570$, then $MR = ₹570 - ₹500 = ₹70$.

### 2. Revenue Curves in Different Markets

```
Revenue (Perfect Competition)      Revenue (Monopoly / Imperfect Competition)
  │         / TR (Straight line)     │      .─ TR (Inverted U-Shape)
  │       /                          │    /   \
  │     /                            │   /     \
  │   /                              │  /       \
  ├──●────────── AR = MR = P         │ /  \  AR (Demand Curve)
  │ /                                │/    \
  └───────────── Output (Q)          └──────●────\──── Output (Q)
                                             \    \
                                              MR   (MR lies below AR)
```

* **Perfect Competition (Price Taker):** The firm can sell as much as it wants at the fixed market price. Therefore, **$P = AR = MR$** (a flat horizontal line), and **$TR$ rises in a straight line**.
* **Monopoly / Imperfect Competition (Price Maker):** To sell more units, the firm must lower its price on *all* units sold. Therefore, both **$AR$ and $MR$ slope downward**, **$MR$ lies below $AR$** (falling twice as fast), and **$TR$ forms an inverted U-shape** (rising, peaking when $MR = 0$, and then falling).

---

## 8.3 Revenue and Price Elasticity of Demand

* **The Core Formula:** Marginal Revenue ($MR$) is directly linked to Price ($P$) and Price Elasticity of Demand ($E$):
  $$MR = P \left(1 - \frac{1}{E}\right)$$

### How Elasticity Controls $TR$ and $MR$

```
Revenue
  │           .─ TR Peaks (Maximum Revenue)
  │         /   \
  │       /       \
  │     /  E > 1   │  E < 1
  │   /  (Elastic) │ (Inelastic)
  └────────────────●────────── Output (Q)
      \            │
       \  MR > 0   │  MR < 0
        `──────────●──────────
                 MR = 0 (Unitary Elastic: E = 1)
```

| Demand Elasticity Zone | Value of $MR$ | What Happens to $TR$ When Price Drops ($P \downarrow$) | Best Pricing Strategy for Managers |
| :--- | :--- | :--- | :--- |
| **1. Elastic Demand ($E > 1$)** | **Positive ($MR > 0$)** | **$TR$ Increases ($\uparrow$):** Buyers respond strongly to lower prices, boosting total sales cash. | **Lower prices** or offer discounts to grow sales volume and revenue. |
| **2. Unitary Elastic ($E = 1$)** | **Zero ($MR = 0$)** | **$TR$ is at Maximum (Unchanged):** Price drop and volume gain balance out exactly. | **Revenue Maximization Point:** Hold price steady if the goal is peak total revenue. |
| **3. Inelastic Demand ($E < 1$)** | **Negative ($MR < 0$)** | **$TR$ Decreases ($\downarrow$):** Lowering price brings very few new buyers, hurting total earnings. | **Raise prices** to increase total revenue without losing many customers. |

### Key Managerial Rules
* **For Revenue Maximization:** Produce and price at the exact point where **$MR = 0$** (unitary elasticity, $E = 1$).
* **For Profit Maximization:** Produce at the exact output level where **Marginal Revenue equals Marginal Cost ($MR = MC$)**. If $MR > MC$, producing more adds to profit; if $MR < MC$, cutting output saves more cost than lost revenue.