>[!tip]
>### Economic Interpretation
> 
> This result shows that at q = 10 and p = 25:
> 
> - The firm is earning exactly zero economic profit
> - The price equals both the marginal cost and the average total cost
> - This is consistent with the long-run equilibrium in perfect competition
> 
> ## Conclusion
> 
> No, the merchant does not earn any economic profit in the free market equilibrium. They are exactly breaking even, covering all their costs including the opportunity cost of their resources (which is included in economic cost). This zero-profit condition is characteristic of the long-run equilibrium in perfectly competitive markets.



---

### Problem Overview

The setup describes a perfectly competitive market in the long run, where market demand is given by:

$$Q^D(p) = 125 - p$$

and each firm’s total cost function is:

$$C(q) = \begin{cases} 
25 + 20q + \frac{1}{4}q^2, & q > 0 \\
0, & q = 0 
\end{cases}$$

Here, $p \geq 0$ is the price, $q \geq 0$ is the output of an individual firm, and there are $n \in \mathbb{N}$ identical firms. In a perfectly competitive market in the long run, firms produce where price equals marginal cost ($p = MC(q)$), and they only produce if they can earn non-negative profits; otherwise, they produce $q = 0$. The break-even quantity occurs where marginal cost equals average total cost ($MC(q) = AC(q)$), and at this point, firms earn zero profit.

The problems ask us to:
- **Problem 2:** Find the number of firms $n$ in equilibrium.
- **Problem 3:** Calculate consumer surplus and producer surplus in equilibrium.
- **Problem 4:** Determine the welfare loss from introducing a price ceiling at $p' = 20$.
- **Problem 5:** Assess the welfare loss from a price floor at $p'' = 20$.
- **Problem 6:** Recalculate the number of firms with a lump-sum subsidy $S = 24$.

Let’s solve each problem systematically.

---

### Problem 2: Number of Firms in Equilibrium

#### Question Breakdown
We need to determine the number of firms $n$ in long-run equilibrium. In a perfectly competitive market, equilibrium occurs where:
1. Price equals marginal cost for each firm ($p = MC(q)$).
2. Firms earn zero profit (price equals average total cost, $p = AC(q)$), as firms enter or exit until profits are zero.
3. Market demand equals market supply ($Q^D(p) = Q^S(p)$).

#### Step-by-Step Solution

**Step 1: Derive Marginal Cost (MC) and Average Total Cost (AC)**  
- **Reasoning:** To find the profit-maximizing output, we need the marginal cost, as firms set $p = MC(q)$. We also need the average total cost to determine the break-even point where firms earn zero profit.
- **Methods and Concepts:** Marginal cost is the derivative of the total cost function with respect to quantity $q$. Average total cost is total cost divided by quantity.
- **Calculation:**  
  The cost function for $q > 0$ is $C(q) = 25 + 20q + \frac{1}{4}q^2$.  
  - Marginal cost:  
    $$MC(q) = \frac{dC}{dq} = \frac{d}{dq} \left( 25 + 20q + \frac{1}{4}q^2 \right) = 20 + \frac{1}{2}q$$
  - Average total cost:  
    $$AC(q) = \frac{C(q)}{q} = \frac{25 + 20q + \frac{1}{4}q^2}{q} = \frac{25}{q} + 20 + \frac{1}{4}q$$
- **Assumptions:** The cost function is differentiable for $q > 0$, and $C(0) = 0$ implies no fixed costs if the firm doesn’t produce.

**Step 2: Find the Break-Even Quantity (where $MC = AC$)**  
- **Reasoning:** In the long run, firms produce where $p = MC = AC$, earning zero profit. This is the minimum point of the AC curve.
- **Methods and Concepts:** Set $MC(q) = AC(q)$ and solve for $q$.
- **Calculation:**  
  $$20 + \frac{1}{2}q = \frac{25}{q} + 20 + \frac{1}{4}q$$  
  Subtract 20 from both sides:  
  $$\frac{1}{2}q = \frac{25}{q} + \frac{1}{4}q$$  
  Subtract $\frac{1}{4}q$ from both sides:  
  $$\frac{1}{2}q - \frac{1}{4}q = \frac{25}{q}$$  
  $$\frac{1}{4}q = \frac{25}{q}$$  
  Multiply through by $q$:  
  $$\frac{1}{4}q^2 = 25$$  
  $$q^2 = 100$$  
  $$q = 10$$ (since $q \geq 0$).
- **Verification:**  
  - At $q = 10$, $MC = 20 + \frac{1}{2} \cdot 10 = 25$.  
  - $AC = \frac{25}{10} + 20 + \frac{1}{4} \cdot 10 = 2.5 + 20 + 2.5 = 25$.  
  So, $MC = AC = 25$, and the break-even quantity is $q = 10$.

**Step 3: Determine the Equilibrium Price**  
- **Reasoning:** At the break-even quantity, the price is set where $p = MC = AC$.  
- From Step 2, when $q = 10$, $p = MC = 25$. So, the equilibrium price is $p = 25$.

**Step 4: Derive the Individual Firm’s Supply Function**  
- **Reasoning:** The firm’s supply function $q(p)$ comes from setting $p = MC(q)$, but firms only produce if $p \geq AC_{\text{min}}$, otherwise they produce $q = 0$.  
- **Calculation:**  
  From $p = MC(q)$, we have:  
  $$p = 20 + \frac{1}{2}q$$  
  $$\frac{1}{2}q = p - 20$$  
  $$q = 2(p - 20)$$  
  The minimum AC occurs at $q = 10$, where $AC = 25$. Thus, the firm produces $q = 2(p - 20)$ if $p \geq 25$; otherwise, $q = 0$.  
  The supply function is:  
  $$q(p) = \begin{cases} 
  2(p - 20), & p \geq 25 \\
  0, & p < 25 
  \end{cases}$$

**Step 5: Derive Market Supply**  
- **Reasoning:** Market supply is the sum of individual supplies over $n$ firms: $Q^S(p) = n \cdot q(p)$.  
- **Calculation:**  
  $$Q^S(p) = \begin{cases} 
  n \cdot 2(p - 20), & p \geq 25 \\
  0, & p < 25 
  \end{cases}$$

**Step 6: Find Equilibrium by Equating Market Demand and Supply**  
- **Reasoning:** In equilibrium, $Q^D(p) = Q^S(p)$, and we know $p = 25$ from the break-even condition.  
- **Calculation:**  
  - Market demand: $Q^D(p) = 125 - p$. At $p = 25$:  
    $$Q^D(25) = 125 - 25 = 100$$  
  - Market supply at $p = 25$:  
    $$q(25) = 2(25 - 20) = 2 \cdot 5 = 10$$  
    $$Q^S(25) = n \cdot 10$$  
  - Set $Q^D = Q^S$:  
    $$100 = n \cdot 10$$  
    $$n = 10$$  
- **Assumptions:** We assume $n$ is an integer, as specified ($n \in \mathbb{N}$).

**Summary for Problem 2:**  
We derived the marginal and average costs, found the break-even quantity $q = 10$ where $p = 25$, and used market demand and supply to find $n = 10$. The answer is **(B) 10**.

---

### Problem 3: Consumer Surplus and Producer Surplus in Equilibrium

#### Question Breakdown
Given $n = 10$, $p = 25$, and equilibrium quantity $Q = 100$, compute consumer surplus (CS) and producer surplus (PS).
给定$ n = 10 $，$ p = 25 $，以及平衡数量$ q = 100 $，计算消费者盈余（CS）和生产者剩余（PS）。
#### Step-by-Step Solution

**Step 1: Calculate Consumer Surplus**  
- **Reasoning:** Consumer surplus is the area under the demand curve above the price, from $Q = 0$ to the equilibrium quantity.
- **Methods and Concepts:** For a linear demand curve $Q^D = 125 - p$, CS is the area of a triangle. The demand curve intersects the price axis at $Q = 0$, so $p = 125$. At $p = 25$, $Q = 100$.  
- **Calculation:**  
  $$\text{CS} = \frac{1}{2} \cdot (\text{base}) \cdot (\text{height}) = \frac{1}{2} \cdot (125 - 25) \cdot 100 = \frac{1}{2} \cdot 100 \cdot 100 = 5,000$$
>![](./_P2-6%20--Ex%204%20Perfect%20Competition_%20_SS25-PoE_Retake-4_-1745503129654.png)
>**The way I drew it** (traditional economics textbook style):
> - Price (P) on the vertical axis
> - Quantity (Q) on the horizontal axis
> - Demand curve slopes downward from left to right


**Step 2: Calculate Producer Surplus**  

>![](./_P2-6%20--Ex%204%20Perfect%20Competition_%20_SS25-PoE_Retake-4_-1745505747099.png)


- **Reasoning:** Producer surplus is the area above the supply curve but below the price. In long-run equilibrium, $p = AC_{\text{min}}$, so firms earn zero profit, and PS is typically zero. However, let’s compute using the supply curve.  
- **Methods and Concepts:** The market supply curve starts at $p = 25$, but we use the marginal cost curve from $p = 20$ (where $q = 0$) to $p = 25$.  
- Individual supply: $q = 2(p - 20)$, so $p = 20 + \frac{q}{2}$. Market supply: $Q = n \cdot q = 10 \cdot 2(p - 20) = 20(p - 20)$. At $p = 25$, $Q = 100$.  
  The supply curve starts at $p = 20$ (where $Q = 0$).  
  $$\text{PS} = \frac{1}{2} \cdot (\text{base}) \cdot (\text{height}) = \frac{1}{2} \cdot (25 - 20) \cdot 100 = \frac{1}{2} \cdot 5 \cdot 100 = 250$$

**Summary for Problem 3:**  
Consumer surplus is 5,000, and producer surplus is 250, so **(B)** is correct. Note that in the long run, PS is often zero due to zero profits, but the problem’s calculation aligns with the given options.

---

### Problem 4: Welfare Loss from a Price Ceiling at $p' = 20$

#### Question Breakdown
A price ceiling at $p' = 20$ is introduced. We need to find the welfare loss (deadweight loss).

#### Step-by-Step Solution

**Step 1: Analyze the Effect of the Price Ceiling**  
- **Reasoning:** The equilibrium price is $p = 25$. A price ceiling at $p = 20 < 25$ forces the price below equilibrium. Firms produce where $p = MC$, but at $p = 20$, $p < AC_{\text{min}} = 25$, so firms produce $q = 0$.  
- **Calculation:**  
  At $p = 20$, individual supply:  
  $$q(20) = 0 \text{ (since } p < 25\text{)}$$  
  Market supply: $Q^S = n \cdot 0 = 0$.  
  Market demand:  
  $$Q^D(20) = 125 - 20 = 105$$  
  But since supply is 0, quantity traded is 0.

**Step 2: Calculate Welfare Loss**  
- **Reasoning:** Without the price ceiling, total surplus (TS) is $\text{CS} + \text{PS} = 5,000 + 250 = 5,250$. With the price ceiling, $Q = 0$, so $\text{CS} = 0$, $\text{PS} = 0$, and total surplus is 0. Welfare loss is the loss in total surplus.  
- **Calculation:**  
  $$\text{Welfare Loss} = 5,250 - 0 = 5,250$$

**Summary for Problem 4:**  
The price ceiling reduces quantity to 0, eliminating all surplus. Welfare loss is 5,250, so **(D)** is correct.

---

### Problem 5: Welfare Loss from a Price Floor at $p'' = 20$

#### Question Breakdown
A price floor at $p'' = 20$ is introduced. We need to find the welfare loss.

#### Step-by-Step Solution

**Step 1: Analyze the Effect of the Price Floor**  
- **Reasoning:** The equilibrium price is $p = 25$. A price floor at $p = 20 < 25$ is below the equilibrium price, so it has no effect—firms can still sell at $p = 25$.  
- **Calculation:** The market remains at $p = 25$, $Q = 100$, with no change in surplus.

**Step 2: Calculate Welfare Loss**  
- **Reasoning:** Since the price floor doesn’t affect the equilibrium, there is no welfare loss.  
- $$\text{Welfare Loss} = 0$$

**Summary for Problem 5:**  
The price floor is non-binding, so welfare loss is 0, and **(A)** is correct.

---

### Problem 6: Number of Firms with a Lump-Sum Subsidy $S = 24$

#### Question Breakdown
A subsidy $S = 24$ per firm reduces costs to $C(q) - S$. We need to find the new number of firms.

#### Step-by-Step Solution

**Step 1: Adjust the Cost Function**  
- **Reasoning:** The subsidy lowers fixed costs. New cost:  
  $$C(q) - S = \begin{cases} 
  25 + 20q + \frac{1}{4}q^2 - 24 = 1 + 20q + \frac{1}{4}q^2, & q > 0 \\
  0, & q = 0 
  \end{cases}$$

**Step 2: Recalculate MC and AC**  
- **Calculation:**  
  - $MC$ is unchanged: $MC = 20 + \frac{1}{2}q$.  
  - New $AC$:  
    $$AC(q) = \frac{1 + 20q + \frac{1}{4}q^2}{q} = \frac{1}{q} + 20 + \frac{1}{4}q$$

**Step 3: Find New Break-Even Quantity**  
- Set $MC = AC$:  
  $$20 + \frac{1}{2}q = \frac{1}{q} + 20 + \frac{1}{4}q$$  
  $$\frac{1}{2}q - \frac{1}{4}q = \frac{1}{q}$$  
  $$\frac{1}{4}q = \frac{1}{q}$$  
  $$q^2 = 4$$  
  $$q = 2$$  
- At $q = 2$:  
  $$p = MC = 20 + \frac{1}{2} \cdot 2 = 21$$

**Step 4: Find New Number of Firms**  
- Individual supply at $p = 21$:  
  $$q = 2(21 - 20) = 2$$  
- Market demand:  
  $$Q^D(21) = 125 - 21 = 104$$  
- Market supply: $Q^S = n \cdot 2$.  
- Equate:  
  $$104 = n \cdot 2$$  
  $$n = 52$$

**Summary for Problem 6:**  
The subsidy lowers the break-even price to 21, increasing the number of firms to 52, so **(D)** is correct.

---

### Overall Summary
- **Problem 2:** Equilibrium number of firms is 10, as market demand and supply balance at $p = 25$, $q = 10$.
- **Problem 3:** Consumer surplus is 5,000, producer surplus is 250.
- **Problem 4:** A price ceiling at 20 causes a welfare loss of 5,250 by reducing quantity to 0.
- **Problem 5:** A price floor at 20 has no effect, so welfare loss is 0.
- **Problem 6:** A subsidy of 24 lowers the break-even price to 21, increasing the number of firms to 52.

All answers match the provided solutions: **2(B), 3(B), 4(D), 5(A), 6(D)**.
