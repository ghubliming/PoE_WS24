Let’s dive into the concept of **corner solutions** in the context of utility maximization, specifically addressing **Step 5: Check for Corner Solutions** from the previous problem. I’ll explain what a corner solution is, why we check for it, how to check for it, and what it means in this economic context.

---

### What is a Corner Solution?

In utility maximization problems, like the one we’re solving, a **corner solution** occurs when the optimal consumption bundle lies at the boundary of the feasible set, meaning the consumer spends all their income on just one good (or none of another). This is in contrast to an **interior solution**, where the consumer buys positive quantities of all goods (e.g., $q_1 > 0$ and $q_2 > 0$).

In our problem:
- We have two goods, $q_1$ and $q_2$, with prices $p_1$ and $p_2$, and a budget constraint $p_1 q_1 + p_2 q_2 = y$.
- An **interior solution** would mean $q_1 > 0$ and $q_2 > 0$, which we found in the previous steps using the condition that the marginal rate of substitution (MRS) equals the price ratio ($MRS_{1,2} = \frac{p_1}{p_2}$).
- A **corner solution** would occur if:
  - The consumer spends all their income on good 1: $q_1 = \frac{y}{p_1}$, $q_2 = 0$.
  - Or, the consumer spends all their income on good 2: $q_1 = 0$, $q_2 = \frac{y}{p_2}$.

A corner solution typically happens when the indifference curve (representing the consumer’s preferences) does not intersect the budget line at a point of tangency (where MRS equals the price ratio) but instead reaches the highest utility at one of the axes (i.e., consuming only one good).

---

### Why Check for Corner Solutions?

We check for corner solutions because the interior solution assumes that the consumer always buys some of both goods, which may not hold under certain preferences or prices. For example:
- If one good becomes extremely expensive relative to the other, the consumer might prefer to buy only the cheaper good.
- If the utility function has a form that heavily favors one good over the other (e.g., perfect substitutes), the consumer might choose a corner solution.

Failing to check for corner solutions could lead to an incomplete or incorrect answer. The interior solution we derived ($q_1 = \frac{y p_2}{p_1 (p_1 + p_2)}$, $q_2 = \frac{y p_1}{p_2 (p_1 + p_2)}$) assumes $q_1 > 0$ and $q_2 > 0$, but we need to verify if this is always the case or if a corner solution might yield higher utility under certain conditions.

---

### How to Check for Corner Solutions?

To check for corner solutions, we evaluate the utility at the boundary points of the budget constraint and compare it with the utility at the interior solution. Here’s the step-by-step process:

#### 1. Identify the Corner Points
The budget constraint is:
$$
p_1 q_1 + p_2 q_2 = y.
$$
- **Corner 1**: Spend all income on good 1 ($q_2 = 0$):
  $$
  p_1 q_1 = y \implies q_1 = \frac{y}{p_1}, \quad q_2 = 0.
$$
- **Corner 2**: Spend all income on good 2 ($q_1 = 0$):
  $$
  p_2 q_2 = y \implies q_1 = 0, \quad q_2 = \frac{y}{p_2}.
$$

#### 2. Compute Utility at Each Corner
The utility function is:
$$
U(q_1, q_2) = q_1^{\frac{1}{2}} + q_2^{\frac{1}{2}}.
$$
- At $(q_1, q_2) = \left( \frac{y}{p_1}, 0 \right)$:
  $$
  U\left( \frac{y}{p_1}, 0 \right) = \left( \frac{y}{p_1} \right)^{\frac{1}{2}} + 0^{\frac{1}{2}} = \left( \frac{y}{p_1} \right)^{\frac{1}{2}}.
$$
- At $(q_1, q_2) = \left( 0, \frac{y}{p_2} \right)$:
  $$
  U\left( 0, \frac{y}{p_2} \right) = 0^{\frac{1}{2}} + \left( \frac{y}{p_2} \right)^{\frac{1}{2}} = \left( \frac{y}{p_2} \right)^{\frac{1}{2}}.
$$

#### 3. Compute Utility at the Interior Solution
From the previous solution, the interior solution is:
$$
q_1 = \frac{y p_2}{p_1 (p_1 + p_2)}, \quad q_2 = \frac{y p_1}{p_2 (p_1 + p_2)}.
$$
Substitute into the utility function:
$$
U(q_1, q_2) = \left( \frac{y p_2}{p_1 (p_1 + p_2)} \right)^{\frac{1}{2}} + \left( \frac{y p_1}{p_2 (p_1 + p_2)} \right)^{\frac{1}{2}}.
$$
Factor out common terms:
$$
U = \left( \frac{y}{p_1 + p_2} \right)^{\frac{1}{2}} \left( \left( \frac{p_2}{p_1} \right)^{\frac{1}{2}} + \left( \frac{p_1}{p_2} \right)^{\frac{1}{2}} \right).
$$
Simplify the second part:
$$
\left( \frac{p_2}{p_1} \right)^{\frac{1}{2}} + \left( \frac{p_1}{p_2} \right)^{\frac{1}{2}} = \frac{p_2^{\frac{1}{2}}}{p_1^{\frac{1}{2}}} + \frac{p_1^{\frac{1}{2}}}{p_2^{\frac{1}{2}}} = \frac{p_2^{\frac{1}{2}} p_2^{\frac{1}{2}} + p_1^{\frac{1}{2}} p_1^{\frac{1}{2}}}{p_1^{\frac{1}{2}} p_2^{\frac{1}{2}}} = \frac{p_1 + p_2}{(p_1 p_2)^{\frac{1}{2}}}.
$$
So the utility at the interior solution is:
$$
U = \left( \frac{y}{p_1 + p_2} \right)^{\frac{1}{2}} \cdot \frac{p_1 + p_2}{(p_1 p_2)^{\frac{1}{2}}} = y^{\frac{1}{2}} \left( \frac{p_1 + p_2}{p_1 + p_2} \right)^{\frac{1}{2}} \cdot \frac{p_1 + p_2}{(p_1 p_2)^{\frac{1}{2}}} = y^{\frac{1}{2}} \frac{p_1 + p_2}{(p_1 p_2)^{\frac{1}{2}}}.
$$

#### 4. Compare Utilities
We need to determine if the utility at the interior solution is higher than at the corners. However, in this specific problem, we can take a shortcut by examining the demand functions directly:
$$
q_1 = \frac{y p_2}{p_1 (p_1 + p_2)}, \quad q_2 = \frac{y p_1}{p_2 (p_1 + p_2)}.
$$
Notice that for all $p_1 > 0$, $p_2 > 0$, and $y > 0$, both $q_1$ and $q_2$ are strictly positive:
- $q_1 > 0$ because $y p_2 > 0$ and $p_1 (p_1 + p_2) > 0$.
- $q_2 > 0$ because $y p_1 > 0$ and $p_2 (p_1 + p_2) > 0$.

This suggests the interior solution always holds under the given conditions. But to be rigorous, let’s consider the utility comparison or the MRS at the boundaries.

#### 5. Alternative Check Using MRS at the Boundary
At a corner solution, the MRS does not equal the price ratio; instead, the consumer chooses a corner if the MRS condition suggests they’d be better off consuming only one good. At $q_2 = 0$:
$$
MRS_{1,2} = \left( \frac{q_2}{q_1} \right)^{\frac{1}{2}} = \left( \frac{0}{q_1} \right)^{\frac{1}{2}} = 0.
$$
Compare to the price ratio:
$$
\frac{p_1}{p_2} > 0.
$$
Since $MRS = 0 < \frac{p_1}{p_2}$, the consumer would want to give up good 1 to get more of good 2 (because the market values good 1 more than the consumer does at this point), suggesting this corner ($q_2 = 0$) is not optimal. Similarly, at $q_1 = 0$:
$$
MRS_{1,2} = \left( \frac{q_2}{0} \right)^{\frac{1}{2}} \to \infty.
$$
Since $MRS \to \infty > \frac{p_1}{p_2}$, the consumer would want to give up good 2 to get more of good 1, so this corner ($q_1 = 0$) is also not optimal.

The MRS condition confirms that the tangency condition ($MRS = \frac{p_1}{p_2}$) holds at the interior solution, and the corners do not yield higher utility.

---

### What Does This Mean?

In this problem, **Step 5: Check for Corner Solutions** concludes that there are no corner solutions because $q_1 > 0$ and $q_2 > 0$ for all positive prices and income. This means:
- The consumer always prefers to consume a mix of both goods rather than spending all their income on just one good.
- The utility function $U = q_1^{\frac{1}{2}} + q_2^{\frac{1}{2}}$ (a form of CES utility with substitutability) and the positive prices ensure that the indifference curves are always tangent to the budget line at an interior point.

This result aligns with the nature of the utility function, which exhibits diminishing marginal utility for each good but still values both goods positively, leading to a balanced consumption bundle.

---

### What Does Checking for Corner Solutions Do?

Checking for corner solutions ensures our solution is complete:
1. **Accuracy**: It confirms that the interior solution is indeed the global maximum, not just a local one.
2. **Robustness**: It accounts for edge cases where preferences or prices might lead to extreme consumption choices (e.g., if the utility function were for perfect substitutes like $U = q_1 + q_2$, we’d likely get a corner solution).
3. **Economic Insight**: It tells us about consumer behavior—here, the absence of corner solutions indicates that the goods are substitutes but not perfect substitutes, and the consumer always benefits from consuming both.

In summary, Step 5 ensures we haven’t missed a scenario where the consumer might optimally choose to consume only one good, and in this case, it confirms that the interior solution is the correct one.
