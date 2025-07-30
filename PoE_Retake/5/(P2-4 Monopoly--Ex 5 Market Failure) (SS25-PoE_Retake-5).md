>![](./_P2-4%20Monopoly--Ex%205%20Market%20Failure_%20_SS25-PoE_Retake-5_-1745576412307.png)
>[[Graph Expl((P2-4 Monopoly--Ex 5 Market Failure)) (SS25-PoE_Retake-5)]]


Let’s analyze the attached image, which contains economics problems related to monopoly behavior, along with their solutions. The image includes a general setup for a monopoly problem, followed by specific multiple-choice questions (Problems 2, 3, and 4). I’ll focus on breaking down the questions, explaining the solutions step by step, and ensuring clarity in reasoning, methods, concepts, assumptions, and definitions. Since the solutions are provided, I’ll verify them and elaborate on the process.

---

### **Understanding the General Setup (Problem 2-4: Monopoly)**

The general setup describes a profit-maximizing monopolist with the following:

- **Inverse Market Demand:** $Q^D(p) = 75 - p$, which can be rewritten as $p = 75 - Q$.
- **Total Costs:** $C(Q) = c^f + \frac{1}{4} Q^2$, where $Q \geq 0$, $c^f \geq 0$ (quasi-fixed costs), and $Q \geq 0$.
- **Profit Function:** The monopolist maximizes profit, given by:
  $$
  \pi(Q) = p(Q) \cdot Q - C(Q) = (75 - Q) \cdot Q - \left( c^f + \frac{1}{4} Q^2 \right) = 75Q - Q^2 - \frac{1}{4} Q^2 - c^f = 75Q - \frac{5}{4} Q^2 - c^f.
$$

The solution derives the profit-maximizing quantity by taking the derivative of the profit function with respect to $Q$:

$$
\frac{d\pi(Q)}{dQ} = 75 - 2 \cdot \frac{5}{4} Q = 75 - \frac{5}{2} Q.
$$

Set the derivative to zero to find the **critical point**:
>*Q^M*
$$
75 - \frac{5}{2} Q = 0 \implies Q = 30.
$$

Thus, the monopoly output is $Q^M = 30$. The corresponding price is:

$$
p^M = 75 - Q^M = 75 - 30 = 45.
$$

The monopoly profit is:

$$
\pi^M = (75 - 30) \cdot 30 - \left( c^f + \frac{1}{4} (30)^2 \right) = 45 \cdot 30 - \left( c^f + \frac{1}{4} \cdot 900 \right) = 1,350 - 225 - c^f = 1,125 - c^f.
$$

For comparison, the welfare-maximizing (competitive) output occurs where price equals marginal cost ($p = MC$). Marginal cost is:

$$
MC(Q) = \frac{dC(Q)}{dQ} = \frac{d}{dQ} \left( c^f + \frac{1}{4} Q^2 \right) = \frac{1}{2} Q.
$$

==Set $p = MC$:==

$$
75 - Q = \frac{1}{2} Q \implies 75 = \frac{3}{2} Q \implies Q = 50.
$$

So, the ==competitive output== is $Q^* = 50$, and the corresponding price is:

$$
p^* = 75 - 50 = 25.
$$

---

### **Problem 2: Threshold for Quasi-Fixed Costs**

**Question:** The monopolist’s profit must be non-negative in the long run. Given $\pi^M = 1,125 - c^f$, find the threshold for quasi-fixed costs $c^f$ below which the monopolist’s output is $Q > 0$. Options: (A) 0, (B) 375, (C) 1,125, (D) 1,875.

**Step-by-Step Solution:**

1. **Determine the Profit Condition for Production:**
   - A monopolist produces $Q > 0$ in the long run if profit is non-negative ($\pi \geq 0$).
   - From the setup, the monopoly profit at $Q^M = 30$ is:
     $$
     \pi^M = 1,125 - c^f.
$$
   - For the monopolist to produce, profit must be at least zero:
     $$
     1,125 - c^f \geq 0 \implies c^f \leq 1,125.
$$

2. **Interpret the Threshold:**
   - If $c^f > 1,125$, the profit becomes negative ($\pi^M < 0$), and the monopolist would choose not to produce ($Q = 0$).
   - The question asks for the threshold below which the monopolist produces $Q > 0$, so $c^f \leq 1,125$.

3. **Compare with Options:**
   - (A) 0: Too low; the monopolist can still produce with higher $c^f$.
   - (B) 375: Still too low; profit would be $1,125 - 375 = 750 > 0$.
   - (C) 1,125: Matches the threshold exactly; profit is zero, but the monopolist is indifferent (typically produces in economics problems unless specified otherwise).
   - (D) 1,875: Exceeds the threshold; profit is $1,125 - 1,875 = -750 < 0$, so the monopolist shuts down.

**Methods and Concepts:**
- **Profit Maximization:** Monopolists maximize profit where marginal revenue (MR) equals marginal cost (MC). Here, MR is derived from the demand function $p = 75 - Q$, so $MR = 75 - 2Q$. Equating $MR = MC$ gave $Q^M = 30$.
- **Long-Run Decision:** In the long run, firms produce only if profit is non-negative due to the ability to exit the market.

**Assumptions and Definitions:**
- Assume the monopolist produces if $\pi \geq 0$ (standard in economics unless shutdown is explicitly modeled).
- Quasi-fixed costs ($c^f$) are costs incurred if production occurs ($Q > 0$), but not if $Q = 0$.

**Conclusion for Problem 2:**
The threshold for $c^f$ is 1,125, so the answer is (C), as provided.

---

### **Problem 3: Welfare Loss with Fixed Costs**

**Question:** If quasi-fixed costs are $c^f = 625$, and the monopoly output is $Q^M = 30$, compute the welfare loss. Options: (A) Consumer surplus ($CS$) = 600, (B) Producer surplus ($PS$) = 900, (C) Total surplus ($TS$) = 1,500, (D) Welfare loss ($WL$) = 300.

**Step-by-Step Solution:**

1. **[[Compute Welfare Loss Formula (SS25-PoE_Retake-5)]]**

>[!tip]
>For each additional unit beyond $Q^M$ up to $Q^*$, the value to consumers (given by the demand curve) exceeds the cost of production (given by the marginal cost curve). This difference represents the surplus that could have been gained but is lost due to the monopoly’s restricted output.

   - Welfare loss (deadweight loss) in a monopoly is the loss of total surplus compared to the competitive outcome:
     $$
     WL = \frac{1}{2} \cdot (Q^* - Q^M) \cdot (p(Q^M) - MC(Q^M)).
$$ ^kyzp7d
   - Given: $Q^* = 50$, $Q^M = 30$, $p(Q^M) = 45$, $MC(Q^M) = \frac{1}{2} \cdot 30 = 15$.

2. **Calculate Welfare Loss:**
   - Substitute the values:
     $$
     WL = \frac{1}{2} \cdot (50 - 30) \cdot (45 - 15) = \frac{1}{2} \cdot 20 \cdot 30 = 300.
$$

3. **Verify Against Options:**
   - (A) $CS = 600$: This is consumer surplus, not welfare loss. $CS = \frac{1}{2} \cdot (75 - 45) \cdot 30 = 450$, so this is incorrect.
	   - $Q^M = 30$ $p(Q^M) = 45$
   - (B) $PS = 900$: ==Producer surplus is $PS = \pi^M = 1,125 - 625 = 500$==, incorrect. ^ns1mwo
   - (C) $TS = 1,500$: Total surplus under monopoly is $CS + PS = 450 + 500 = 950$, incorrect.
   - (D) $WL = 300$: Matches our calculation.

[[CS PS in (Problem 3 Welfare Loss with Fixed Costs--(P2-4 Monopoly--Ex 5 Market Failure)) (SS25-PoE_Retake-5)]]

**Methods and Concepts:**
- **Welfare Loss:** The triangle between the demand curve and marginal cost curve from $Q^M$ to $Q^*$, representing lost gains from trade.
- **Consumer and Producer Surplus:** $CS$ is the area above price and below demand; $PS$ is profit in this context.

**Assumptions and Definitions:**
- Assume $c^f$ does not affect marginal cost (it’s quasi-fixed), so $MC = \frac{1}{2} Q$.
- Welfare loss is the difference between competitive and monopoly total surplus.

**Conclusion for Problem 3:**
The welfare loss is 300, so the answer is (D), as provided.

---

### **Problem 4: Effect of a Price Ceiling**

**Question:** If $c^f = 0$, the monopoly output is $Q^M = 30$, price is $p^M = 45$. A price ceiling at $p' = 40$ induces the monopolist to increase output to $Q^D(p') = 35$. What is the effect? Options: (A) Increase in consumer surplus, (B) Decrease in consumer surplus, (C) Increase in monopoly profit, (D) Neither affects consumer surplus nor monopoly profit.

**Step-by-Step Solution:**

1. **Determine Output with Price Ceiling:**
   - The price ceiling is $p' = 40$. The monopolist cannot charge above this, so output is determined by demand:
     $$
     Q^D(p') = 75 - 40 = 35.
$$

2. **Compare Consumer Surplus:**
   - **Without Price Ceiling:** $p^M = 45$, $Q^M = 30$, $CS = \frac{1}{2} \cdot (75 - 45) \cdot 30 = 450$.
   - **With Price Ceiling:** $p' = 40$, $Q = 35$, $CS = \frac{1}{2} \cdot (75 - 40) \cdot 35 = \frac{1}{2} \cdot 35 \cdot 35 = 612.5$.
   - Consumer surplus increases from 450 to 612.5.

3. **Check Other Effects (Optional for Verification):**
   - **Monopoly Profit:** Without ceiling: $\pi = 1,125$ (since $c^f = 0$). With ceiling: $\pi = 40 \cdot 35 - \frac{1}{4} \cdot 35^2 = 1,400 - 306.25 = 1,093.75$. Profit decreases, so (C) is incorrect.
   - Since consumer surplus increases, (B) and (D) are incorrect.

**Methods and Concepts:**
- **Price Ceiling:** Forces the monopolist to charge a lower price, increasing output along the demand curve.
- **Consumer Surplus:** Area under the demand curve and above the price, increases with lower price and higher quantity.

**Assumptions and Definitions:**
- Assume the monopolist produces at the price ceiling level (standard in such problems).
- Consumer surplus is the benefit to consumers from paying less than their willingness to pay.

**Conclusion for Problem 4:**
The price ceiling increases consumer surplus, so the answer is (A), as provided.

---

### **Overall Summary**

- **Problem 2:** The threshold for quasi-fixed costs is $c^f = 1,125$, ensuring non-negative profit for the monopolist to produce. Answer: (C).
- **Problem 3:** Welfare loss is calculated as 300, representing the deadweight loss due to monopoly output being less than the competitive output. Answer: (D).
- **Problem 4:** A price ceiling at $p' = 40$ increases output to 35, raising consumer surplus. Answer: (A).

Each solution leverages core economic principles like profit maximization, welfare analysis, and the impact of price controls, with calculations confirming the provided answers.