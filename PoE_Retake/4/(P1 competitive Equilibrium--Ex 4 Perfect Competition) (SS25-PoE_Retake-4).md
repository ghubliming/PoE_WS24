[[Guidelines Equilibrium (SS25-PoE_Retake-4)]]

Let’s dive into this problem about competitive equilibrium in a perfectly competitive market. The image provides both the problem statement and its solution, and I’ll break it down systematically, explaining each part of the question, analyzing the solution step by step, and ensuring clarity in reasoning, methods, assumptions, and definitions. Let’s get started.

---

### Understanding the Problem

The problem involves a perfectly competitive market in the long run, where we need to analyze equilibrium conditions for profit-maximizing firms. Here’s a breakdown of the key components:

- **Market Setup:**
  - Market demand is given by $Q^D(p) = a - p$, where $p \geq 0$ is the price and $a > 0$ is a constant.
  - The market is served by $n \in \mathbb{N}$ identical profit-maximizing firms.
  - Each firm has a cost function $C(q) = c^f + q^2$ for $q > 0$, and $C(q) = 0$ for $q = 0$, where $c^f > 0$ is a quasi-fixed cost, and $q \geq 0$ is the firm’s output.

- **Part (a):** Determine the equilibrium number of firms $n^*$ as a function of $a$ and $c^f$.

- **Part (b):** Calculate the equilibrium number of firms and profit per firm for three cases:
  - (i) $a = 120$, $c^f = 100$
  - (ii) $a = 120$, $c^f = 64$
  - (iii) $a = 126$, $c^f = 100$

- **Part (c):** Now, a tax $t \geq 0$ per unit of output is levied on producers. Determine the equilibrium number of firms $n^*$ as a function of $a$, $c^f$, and $t$.

- **Part (d):** For $a = 126$, $c^f = 100$, and $t = 6$, calculate:
  - The equilibrium number of firms $n^*$,
  - Profit per firm $\pi^*$,
  - Tax revenue $T$,
  - Welfare loss of taxation $WL$.

==The problem assumes a long-run competitive equilibrium, where firms produce only if they earn non-negative profits, and the number of firms adjusts until profits are zero (a standard condition in perfect competition).==

---

### Step-by-Step Explanation of the Solution

The provided solution follows a logical sequence to address each part. I’ll go through each step, explaining the reasoning, methods, concepts, assumptions, and definitions, ensuring clarity at every stage.

#### Part (a): Equilibrium Number of Firms as a Function of $a$ and $c^f$
[[condition for max Profit (SS25-PoE_Retake-4)]]

>[!tip] Connection to other notes
>[[SS25/PoE_Retake/3/(P6-8 Profit Maximization--Ex3 Production and Supply) (SS25-PoE_Retake-3)#^g0ok73]]


**Step 1: Determine the Firm’s Profit-Maximizing Output**

- **Explanation of Reasoning:** In a perfectly competitive market, each firm takes the market price $p$ as given and maximizes profit by *setting marginal cost equal to price, provided profit is non-negative*. If profit is negative, the firm produces $q = 0$.
- **Methods and Concepts:** Profit is defined as $\pi = pq - C(q)$. For $q > 0$, $C(q) = c^f + q^2$, so profit is $\pi = pq - (c^f + q^2)$. To maximize profit, take the derivative with respect to $q$, set it to zero, and solve for $q$:
  $$
  \frac{\partial \pi}{\partial q} = p - \frac{\partial C}{\partial q} = 0 \quad \Rightarrow \quad p = MC(q)
$$
  The marginal cost $MC(q) = \frac{\partial C}{\partial q} = \frac{\partial}{\partial q}(c^f + q^2) = 2q$. Thus:
  $$
  p = 2q \quad \Rightarrow \quad q = \frac{p}{2}
$$
  This gives the profit-maximizing output for a firm, assuming $q > 0$.
- **Assumptions and Definitions:** We assume the firm produces $q > 0$ for now and will check the profit condition later. Marginal cost $MC(q)$ is the derivative of the cost function with respect to output.

[[Alternative Solution Step 2+ (SS25-PoE_Retake-4)]]
**Step 2: Calculate Profit and *Break-Even* Condition**

- **Explanation of Reasoning:** In the long run, firms in a perfectly competitive market enter or exit until profit is zero (the break-even condition). We need to find the profit at $q = \frac{p}{2}$ and set it to zero.
- **Methods and Concepts:** Substitute $q = \frac{p}{2}$ into the profit function:
  $$
  \pi = pq - C(q) = p \left( \frac{p}{2} \right) - \left( c^f + \left( \frac{p}{2} \right)^2 \right) = \frac{p^2}{2} - c^f - \frac{p^2}{4} = \frac{p^2}{4} - c^f
$$
  In the long run, profit must be zero:
  $$
  \frac{p^2}{4} - c^f = 0 \quad \Rightarrow \quad p^2 = 4c^f \quad \Rightarrow \quad p = 2\sqrt{c^f}
$$
  (We take the positive root since price must be non-negative.) This $p$ is the break-even price.
- **Assumptions and Definitions:** We assume $c^f > 0$, so $\sqrt{c^f}$ is real and positive. The break-even condition ensures firms neither make profits nor losses in the long run.

**Step 3: Determine Individual and Market Supply**

- **Explanation of Reasoning:** Using the break-even price, we find the firm’s output and the market supply. Firms produce only if the price is at least the break-even price (otherwise, profit would be negative, and they’d produce $q = 0$).
- **Methods and Concepts:** At $p = 2\sqrt{c^f}$, the firm’s output is:
  $$
  q = \frac{p}{2} = \frac{2\sqrt{c^f}}{2} = \sqrt{c^f}
$$
  The individual supply function $q(p)$ is:
  $$
  q(p) = \begin{cases} 
  \frac{p}{2}, & p \geq 2\sqrt{c^f} \\
  0, & p < 2\sqrt{c^f}
  \end{cases}
$$
  With $n$ firms, market supply $Q^S(p) = n \cdot q(p)$:
  $$
  Q^S(p) = \begin{cases} 
  n \cdot \frac{p}{2}, & p \geq 2\sqrt{c^f} \\
  0, & p < 2\sqrt{c^f}
  \end{cases}
$$
- **Assumptions and Definitions:** We assume all $n$ firms are active at $p \geq 2\sqrt{c^f}$. Individual supply reflects the firm’s decision to produce based on price.

**Step 4: Market Equilibrium and Number of Firms**

- **Explanation of Reasoning:** In equilibrium, market demand equals market supply at the break-even price. We solve for $n$.
- **Methods and Concepts:** At $p = 2\sqrt{c^f}$, market demand is:
  $$
  Q^D(p) = a - p = a - 2\sqrt{c^f}
$$
  Market supply is:
  $$
  Q^S(p) = n \cdot \frac{p}{2} = n \cdot \frac{2\sqrt{c^f}}{2} = n \sqrt{c^f}
$$
  Equate demand and supply:
  $$
  a - 2\sqrt{c^f} = n \sqrt{c^f}
$$
  Solve for $n$:
  $$
  n \sqrt{c^f} + 2\sqrt{c^f} = a \quad \Rightarrow \quad (n + 2)\sqrt{c^f} = a \quad \Rightarrow \quad n + 2 = \frac{a}{\sqrt{c^f}} \quad \Rightarrow \quad n = \frac{a}{\sqrt{c^f}} - 2
$$
  Since $n$ must be a non-negative integer, the equilibrium number of firms is:
  $$
  n^* = \max \left\{ \left\lfloor \frac{a}{\sqrt{c^f}} - 2 \right\rfloor, 0 \right\}
$$
- **Assumptions and Definitions:** We assume $a - 2\sqrt{c^f} \geq 0$ for positive demand; otherwise, the market may not exist. The floor function $\lfloor x \rfloor$ ensures $n$ is an integer.

#### Part (b) Equilibrium Number of Firms and Profit Calculations (SS25-PoE_Retake-4)
[[Part (b) Equilibrium Number of Firms and Profit Calculations (SS25-PoE_Retake-4)]]

- under note maybe also correct but is not the standard solution
[[Dropped Problem b Archive(P1 competitive Equilibrium--Ex 4 Perfect Competition) (SS25-PoE_Retake-4)]]
#### Part (c): Equilibrium Number of Firms with Tax $t$

**Step 1: Adjust Costs for Tax**

- **Explanation of Reasoning:** A per-unit tax $t$ increases the firm’s cost by $tq$, so we need to re-derive the **profit**-maximizing condition.
- **Methods and Concepts:** New cost function: $C(q) + tq = c^f + q^2 + tq$. Profit:
  $$
  \pi = pq - (c^f + q^2 + tq)
$$
  Maximize by taking the derivative:
  $$
  \frac{\partial \pi}{\partial q} = p - (2q + t) = 0 \quad \Rightarrow \quad p = 2q + t \quad \Rightarrow \quad q = \frac{p - t}{2}
$$

>[!tip]
>Without tax is price p = MC
>with tax now is p - t = MC




**Step 2: Break-Even Condition with Tax**

- **Explanation of Reasoning:** Set profit to zero in the long run.
- **Methods and Concepts:** Substitute $q = \frac{p - t}{2}$:
  $$
  \pi = pq - (c^f + q^2 + tq) = p \left( \frac{p - t}{2} \right) - \left( c^f + \left( \frac{p - t}{2} \right)^2 + t \left( \frac{p - t}{2} \right) \right)
$$
  $$
  = \frac{p(p - t)}{2} - c^f - \frac{(p - t)^2}{4} - \frac{t(p - t)}{2}
$$
  Simplify:
  $$
  \pi = \frac{(p - t)^2}{4} - c^f
$$
  Set $\pi = 0$:
  $$
  \frac{(p - t)^2}{4} - c^f = 0 \quad \Rightarrow \quad (p - t)^2 = 4c^f \quad \Rightarrow \quad p - t = 2\sqrt{c^f} \quad \Rightarrow \quad p = 2\sqrt{c^f} + t
$$
>[!tip]
>without Tax is MC = AC
>now with the tax is still MC = AC, but profit p = $p_{no tax}$ + t = MC + t




**Step 3: Market Equilibrium with Tax**

- **Explanation of Reasoning:** Use the new price to find $q$, $Q^S$, and equate to demand.
- **Methods and Concepts:**
  - $q = \frac{p - t}{2} = \frac{(2\sqrt{c^f} + t) - t}{2} = \sqrt{c^f}$
  - Market supply: $Q^S = n \sqrt{c^f}$
  - Demand: $Q^D = a - p = a - (2\sqrt{c^f} + t)$
  - Equate: $a - 2\sqrt{c^f} - t = n \sqrt{c^f}$
  - Solve for $n$:
    $$
    n = \frac{a - t}{\sqrt{c^f}} - 2, \quad n^* = \max \left\{ \left\lfloor \frac{a - t}{\sqrt{c^f}} - 2 \right\rfloor, 0 \right\}
$$

#### Part (d): Specific Values with Tax

- **Explanation of Reasoning:** For $a = 126$, $c^f = 100$, $t = 6$, compute all required values.
- **Methods and Concepts:**
  - $\sqrt{c^f} = 10$
  - $n^* = \left\lfloor \frac{126 - 6}{10} - 2 \right\rfloor = \left\lfloor 12 - 2 \right\rfloor = 10$
  - $p^* = 2\sqrt{c^f} + t = 20 + 6 = 26$
  - $Q^* = a - p^* = 126 - 26 = 100$
  - $q^* = \sqrt{c^f} = 10$
  - $\pi^* = pq - (c^f + q^2 + tq) = 26 \cdot 10 - (100 + 100 + 6 \cdot 10) = 260 - 260 = 0$
  - Tax revenue $T = t \cdot Q^* = 6 \cdot 100 = 600$
  - *Welfare loss*: Without tax ($t = 0$, from part (b)(iii)), $p = 20$, $Q = 105$. With tax, $p = 26$, $Q = 100$. Welfare loss (deadweight loss) is the area of the triangle:
    $$
    WL = \frac{1}{2} \cdot (26 - 20) \cdot (105 - 100) = \frac{1}{2} \cdot 6 \cdot 5 = 15
$$

#### Further for WL

Based on the solution sheet, the welfare loss calculation is:

**Without tax (t = 0):** Q* = 105
**With tax (t = 6):** Q* = 100
**Output reduction:** 105 - 100 = 5 units

**Welfare Loss Formula:**
$$WL = \frac{1}{2} \times \text{tax rate} \times \text{output reduction}$$
$$WL = \frac{1}{2} \times 6 \times 5 = 15$$


**Economic Interpretation:**
The welfare loss of 15 represents the deadweight loss triangle where:
- Base = tax rate (6)
- Height = quantity reduction (5)
- Area = ½ × 6 × 5 = 15

This measures the lost consumer and producer surplus from the 5 units of output that are no longer produced due to the tax distortion.