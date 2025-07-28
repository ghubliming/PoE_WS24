
Let’s break down the problem and its solution step by step. The problem involves a utility-maximizing individual with a Cobb-Douglas utility function, and we need to solve for demand functions, optimal consumption bundles, substitution and income effects, and the compensating income after a price change.

---

### Given Information:
- Utility function: $U(q_1, q_2) = q_1^\alpha q_2^\beta$, where $\alpha > 0$, $\beta > 0$.
- Budget constraint: $y = p_1 q_1 + p_2 q_2$, where $y$ is income, $p_1$ and $p_2$ are prices of goods 1 and 2, and $q_1$, $q_2$ are quantities.
- Specific values: $\alpha = \beta = \frac{1}{2}$, $y = 600$, $p_1 = 25$.
- Price of good 2 changes from $p_2 = 25$ to $p_2' = 100$.

The utility function simplifies to $U(q_1, q_2) = q_1^{1/2} q_2^{1/2}$, which is a Cobb-Douglas form. The solution provides key properties:
1. Demand for each good is independent of the other good’s price.
2. The individual spends a constant fraction of income on each good: $\frac{\alpha}{\alpha + \beta}$ on good 1 and $\frac{\beta}{\alpha + \beta}$ on good 2.

Since $\alpha = \beta = \frac{1}{2}$, we have $\alpha + \beta = 1$, so the fractions are:
- Fraction on good 1: $\frac{\alpha}{\alpha + \beta} = \frac{1/2}{1} = \frac{1}{2}$.
- Fraction on good 2: $\frac{\beta}{\alpha + \beta} = \frac{1/2}{1} = \frac{1}{2}$.

---

### Part (a): Determine the individual demand function for each good
For a Cobb-Douglas utility function $U(q_1, q_2) = q_1^\alpha q_2^\beta$, the demand functions are derived by maximizing utility subject to the budget constraint. The solution provides the general form of the demand functions by solving the optimization problem:

1. **Budget constraint**: $y = p_1 q_1 + p_2 q_2$.
2. **Tangency condition (MRS = price ratio)**: The marginal rate of substitution (MRS) is the ratio of the marginal utilities:
   $$
   MRS_{1,2} = \frac{\partial U / \partial q_1}{\partial U / \partial q_2} = \frac{\alpha q_1^{\alpha-1} q_2^\beta}{\beta q_1^\alpha q_2^{\beta-1}} = \frac{\alpha q_2}{\beta q_1}.
$$
   Set MRS equal to the price ratio $\frac{p_1}{p_2}$:
   $$
   \frac{\alpha q_2}{\beta q_1} = \frac{p_1}{p_2} \implies q_2 = \frac{\beta}{\alpha} \cdot \frac{p_1}{p_2} q_1.
$$
3. Substitute $q_2$ into the budget constraint:
   $$
   y = p_1 q_1 + p_2 \left( \frac{\beta}{\alpha} \cdot \frac{p_1}{p_2} q_1 \right) = p_1 q_1 + \frac{\beta}{\alpha} p_1 q_1 = p_1 q_1 \left( 1 + \frac{\beta}{\alpha} \right) = p_1 q_1 \frac{\alpha + \beta}{\alpha}.
$$
   Solve for $q_1$:
   $$
   q_1 = \frac{y}{p_1} \cdot \frac{\alpha}{\alpha + \beta}.
$$
   Similarly, solve for $q_2$:
   $$
   q_2 = \frac{y}{p_2} \cdot \frac{\beta}{\alpha + \beta}.
$$

With $\alpha = \beta = \frac{1}{2}$, the demand functions are:
$$
q_1 = \frac{y}{p_1} \cdot \frac{1/2}{1} = \frac{y}{2 p_1}, \quad q_2 = \frac{y}{p_2} \cdot \frac{1/2}{1} = \frac{y}{2 p_2}.
$$

---

### Part (b): Determine the optimal consumption bundles before and after the price increase
- **Before the price increase ($p_2 = 25$)**:  


  Given $y = 600$, $p_1 = 25$, $p_2 = 25$:
  $$
  q_1 = \frac{y}{2 p_1} = \frac{600}{2 \cdot 25} = 12, \quad q_2 = \frac{y}{2 p_2} = \frac{600}{2 \cdot 25} = 12.
$$
  So, the optimal bundle $C$ is $(q_1, q_2) = (12, 12)$.

- **After the price increase ($p_2' = 100$)**:  
  Now $p_2 = 100$, while $y = 600$, $p_1 = 25$:
  $$
  q_1' = \frac{y}{2 p_1} = \frac{600}{2 \cdot 25} = 12, \quad q_2' = \frac{y}{2 p_2} = \frac{600}{2 \cdot 100} = 3.
$$
  So, the new optimal bundle $C'$ is $(q_1', q_2') = (12, 3)$.

---

### Part (c): Decompose the total effect into substitution and income effects
The price of good 2 increases from 25 to 100, causing the bundle to change from $C = (12, 12)$ to $C' = (12, 3)$. The total effect on $q_2$ is:
$$
\Delta q_2 = q_2' - q_2 = 3 - 12 = -9.
$$
We decompose this into the **substitution effect** (movement along the same indifference curve) and the **income effect** (movement due to the change in purchasing power).

#### Step 1: Find the hypothetical bundle $\tilde{C}$
The hypothetical bundle $\tilde{C} = (\tilde{q}_1, \tilde{q}_2)$ is where the consumer would be at the new price ratio $\frac{p_1}{p_2} = \frac{25}{100} = \frac{1}{4}$, but on the same indifference curve as the initial bundle $C$.

- **Same indifference curve as $C$**: At $C = (12, 12)$, the utility is:
  $$
  U(12, 12) = (12)^{1/2} (12)^{1/2} = \sqrt{12} \cdot \sqrt{12} = 12.
$$
  So, $\tilde{C}$ must satisfy:
  $$
  U(\tilde{q}_1, \tilde{q}_2) = \tilde{q}_1^{1/2} \tilde{q}_2^{1/2} = 12 \implies \tilde{q}_1 \tilde{q}_2 = 144.
$$

- **Tangency to the new price ratio**: The MRS at $\tilde{C}$ must equal the new price ratio:
$$
  MRS = \frac{\partial U / \partial q_1}{\partial U / \partial q_2} = \frac{(1/2) q_1^{-1/2} q_2^{1/2}}{(1/2) q_1^{1/2} q_2^{-1/2}} = \frac{q_2}{q_1} = \frac{p_1}{p_2} = \frac{1}{4} \implies \tilde{q}_2 = \frac{1}{4} \tilde{q}_1.
$$

Substitute $\tilde{q}_2 = \frac{1}{4} \tilde{q}_1$ into the utility equation:
$$
\tilde{q}_1 \cdot \frac{1}{4} \tilde{q}_1 = 144 \implies \frac{1}{4} \tilde{q}_1^2 = 144 \implies \tilde{q}_1^2 = 576 \implies \tilde{q}_1 = 24.
$$
Then:
$$
\tilde{q}_2 = \frac{1}{4} \cdot 24 = 6.
$$
So, $\tilde{C} = (24, 6)$.

#### Step 2: Substitution and Income Effects
- **Substitution effect**: Movement from $C = (12, 12)$ to $\tilde{C} = (24, 6)$:
  $$
  \text{Substitution effect on } q_2 = \tilde{q}_2 - q_2 = 6 - 12 = -6.
$$
- **Income effect**: Movement from $\tilde{C} = (24, 6)$ to $C' = (12, 3)$:
  $$
  \text{Income effect on } q_2 = q_2' - \tilde{q}_2 = 3 - 6 = -3.
$$
- **Total effect**: Matches the sum:
  $$
  \text{Total effect} = -6 + (-3) = -9.
$$

---

### Part (d): Income necessary to reach the same utility as before the price increase
We need the income $\tilde{y}$ that allows the consumer to afford $\tilde{C} = (24, 6)$ at the new prices $p_1 = 25$, $p_2 = 100$:
$$
\tilde{y} = p_1 \tilde{q}_1 + p_2 \tilde{q}_2 = 25 \cdot 24 + 100 \cdot 6 = 600 + 600 = 1,200.
$$
So, the new income must be 1,200 to achieve the same utility as before.

---

### Summary of Results:
- **(a)** Demand functions: $q_1 = \frac{y}{2 p_1}$, $q_2 = \frac{y}{2 p_2}$.
- **(b)** Before: $(12, 12)$; After: $(12, 3)$.
- **(c)** Substitution effect on $q_2$: -6; Income effect on $q_2$: -3; Total effect: -9.
- **(d)** New income: 1,200.