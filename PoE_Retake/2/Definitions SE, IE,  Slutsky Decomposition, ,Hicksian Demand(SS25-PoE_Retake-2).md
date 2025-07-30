
Let’s break down the key economic concepts involved in this exercise—Substitution Effect (SE), Income Effect (IE), Slutsky Decomposition, and Hicksian Demand—while tying them directly to the problems (6–10). These concepts are central to understanding consumer behavior in response to price changes, especially in the context of utility maximization and cost minimization. I’ll explain each term in detail and show how they’re applied in the problems.

---

### Key Setup for All Problems
- **Utility Function:** $U(q_1, q_2) = q_1^{\frac{1}{2}} + q_2$
- **Income:** $y = 80$
- **Original Prices:** $p_1 = 1$, $p_2 = 8$
- **New Prices (after decrease):** $p_1 = 1$, $p_2 = 4$
- The price of good 2 decreases from 8 to 4, and we analyze the effects on consumption and utility.

---

### Definitions of Key Concepts

#### 1. Hicksian Demand (Compensated Demand)
- **Definition:** Hicksian demand represents the quantities of goods a consumer would buy to achieve a specific utility level at given prices, minimizing expenditure. It’s called "compensated" because income is adjusted to keep utility constant, isolating the effect of price changes on consumption due to substitution between goods.
- **Mathematically:** For utility $U(q_1, q_2)$, prices $p_1, p_2$, and target utility $\bar{U}$, the Hicksian demands $q_1^h(p_1, p_2, \bar{U})$, $q_2^h(p_1, p_2, \bar{U})$ solve:
  $$
  \text{Minimize } p_1 q_1 + p_2 q_2 \text{ subject to } U(q_1, q_2) = \bar{U}
$$
- **In This Exercise:** Hicksian demands are used in Problems 8, 9, and 10 to compute substitution effects and the income needed to maintain utility. For example, in Problem 10, we find the Hicksian bundle at the new prices $(p_1, p_2) = (1, 4)$ to achieve the original utility $U = 12$. We calculated $q_1 = 4$, $q_2 = 10$, because this bundle minimizes cost while keeping utility at 12.

#### 2. Marshallian Demand (Uncompensated Demand)
- **Definition:** Marshallian demand represents the quantities of goods a consumer chooses to maximize utility given their income and prices. It’s "uncompensated" because it reflects both substitution and income effects of a price change.
- **Mathematically:** For utility $U(q_1, q_2)$, prices $p_1, p_2$, and income $y$, the Marshallian demands $q_1^m(p_1, p_2, y)$, $q_2^m(p_1, p_2, y)$ solve:
  $$
  \text{Maximize } U(q_1, q_2) \text{ subject to } p_1 q_1 + p_2 q_2 = y
$$
- **In This Exercise:** Marshallian demands are calculated in Problems 6 and 7. In Problem 6 (before the price decrease), the bundle is $(q_1, q_2) = (16, 8)$, and in Problem 7 (after the price decrease), it’s $(q_1, q_2) = (4, 19)$. These bundles maximize utility given the budget constraint.

#### 3. Substitution Effect (SE)
- **Definition:** The substitution effect measures the change in consumption of a good due to a price change, holding utility constant (i.e., along the same indifference curve). It captures how the consumer substitutes between goods as relative prices change, assuming their real purchasing power is adjusted to maintain the same utility.
- **In This Exercise:** The SE is calculated in Problems 8 and 9.
  - For good 1 (Problem 8): We compare the original Marshallian bundle $(16, 8)$ with the Hicksian bundle at the new prices $(4, 10)$, keeping utility at $U = 12$. The SE for good 1 is:
    $$
    SE_1 = q_1^{\text{Hicksian}} - q_1^{\text{original}} = 4 - 16 = -12
$$
  - For good 2 (Problem 9): The SE is:
    $$
    SE_2 = q_2^{\text{Hicksian}} - q_2^{\text{original}} = 10 - 8 = 2
$$

#### 4. Income Effect (IE)
- **Definition:** The income effect measures the change in consumption of a good due to the change in real purchasing power caused by a price change, holding prices constant at the new level. It captures how the consumer adjusts consumption when their effective income (ability to achieve utility) changes.
- **In This Exercise:** The IE is calculated in Problem 8 for good 1.
  - Total change in $q_1$: From the original bundle $(16, 8)$ to the new Marshallian bundle $(4, 19)$, $q_1$ changes from 16 to 4, so:
    $$
    \Delta q_1 = 4 - 16 = -12
$$
  - The SE for good 1 is $-12$. The IE is the difference between the total change and the SE:
    $$
    IE_1 = \Delta q_1 - SE_1 = -12 - (-12) = 0
$$
  - This makes sense because the utility function $U = q_1^{\frac{1}{2}} + q_2$ implies good 1 has a specific substitution behavior, and the linear term in $q_2$ can lead to a zero income effect for good 1 in this case.

#### 5. Slutsky Decomposition
- **Definition:** The Slutsky decomposition breaks down the total effect of a price change on consumption into the substitution effect (SE) and the income effect (IE). It’s a way to separate the two forces at play when a price changes:
  $$
  \text{Total Effect} = \text{Substitution Effect} + \text{Income Effect}
$$
  - The total effect is the change in Marshallian demand from the old to the new prices.
  - The substitution effect uses Hicksian demand to isolate the effect of relative price changes.
  - The income effect captures the effect of the change in real income.
- **In This Exercise:** Slutsky decomposition is used in Problems 8 and 9 to find the SE and IE.
  - **Problem 8 (for good 1):** Total effect on $q_1$ is $-12$, SE is $-12$, so IE is 0.
  - **Problem 9 (for good 2):** Total effect on $q_2$ is $19 - 8 = 11$. SE is 2, so IE is:
    $$
    IE_2 = \Delta q_2 - SE_2 = 11 - 2 = 9
$$
  - The decomposition helps us understand how much of the change in consumption is due to substitution (price ratio change) versus income (purchasing power change).

---

### Application in Each Problem

#### Problem 6: Original Marshallian Demand (Before Price Decrease)
- **Goal:** Find the optimal consumption bundle at $p_1 = 1$, $p_2 = 8$, $y = 80$.
- **Method:** Maximize utility subject to the budget constraint $q_1 + 8 q_2 = 80$. Using the tangency condition (MRS = price ratio), we get $q_1 = 16$, $q_2 = 8$.
- **Concept:** This is the Marshallian demand, as it’s the utility-maximizing bundle given income and prices.

#### Problem 7: New Marshallian Demand (After Price Decrease)
- **Goal:** Find the new bundle and expenditure after $p_2$ drops to 4.
- **Method:** New budget constraint: $q_1 + 4 q_2 = 80$. Tangency gives $q_1 = 4$, $q_2 = 19$. Expenditure on good 2 is $4 \cdot 19 = 76$.
- **Concept:** This is again Marshallian demand at the new prices, reflecting both substitution and income effects of the price decrease.

#### Problem 8: Income Effect for Good 1
- **Goal:** Find the IE for good 1.
- **Method:** Use Slutsky decomposition:
  - **Total Effect:** $q_1$ changes from 16 to 4 ($-12$).
  - **Substitution Effect:** Compare the original bundle $(16, 8)$ to the Hicksian bundle at new prices $(4, 10)$, so $SE_1 = 4 - 16 = -12$.
  - **Income Effect:** $IE_1 = -12 - (-12) = 0$.
- **Concepts:** Hicksian demand (to compute SE), Slutsky decomposition (to separate SE and IE).

#### Problem 9: Substitution Effect for Good 2
- **Goal:** Find the SE for good 2.
- **Method:** From Slutsky decomposition:
  - Hicksian $q_2 = 10$, original $q_2 = 8$.
  - $SE_2 = 10 - 8 = 2$.
- **Concept:** The SE isolates the change in $q_2$ due to the price ratio change, using Hicksian demand to keep utility constant.

#### Problem 10: Income to Maintain Utility (Hicksian Demand)
- **Goal:** Find the income needed to achieve the original utility $U = 12$ at new prices.
- **Method:** Solve for the Hicksian bundle at $(p_1, p_2) = (1, 4)$, $U = 12$. We get $q_1 = 4$, $q_2 = 10$. Cost = $1 \cdot 4 + 4 \cdot 10 = 44$.
- **Concept:** This is purely Hicksian demand, as we minimize expenditure to achieve a fixed utility level.

---

### How These Concepts Interconnect
- **Marshallian vs. Hicksian:** Marshallian demands (Problems 6 and 7) reflect the consumer’s actual choices given income. Hicksian demands (Problems 8–10) are theoretical—they show what the consumer would buy if income were adjusted to maintain utility, used for analyzing price effects.
- **Slutsky Decomposition:** Bridges the two by breaking down the total change in Marshallian demand into:
  - Substitution effect (using Hicksian demand to hold utility constant).
  - Income effect (the remaining change due to purchasing power).
- **Economic Insight:** The price decrease of good 2 makes it relatively cheaper, so the SE leads the consumer to buy more of good 2 ($SE_2 = 2$) and less of good 1 ($SE_1 = -12$). The IE reflects how the consumer’s increased purchasing power affects consumption—in this case, $IE_1 = 0$, but $IE_2 = 9$, showing good 2 consumption increases further due to higher real income.

---

### Final Answers (Recap)
- Problem 6: $(q_1, q_2) = (16, 8)$, (B)
- Problem 7: Expenditure on good 2 = 76, (D)
- Problem 8: $IE_1 = 0$, (B)
- Problem 9: $SE_2 = 2$, (C)
- Problem 10: Income = 44, (C)

These concepts are foundational in microeconomics for understanding how consumers respond to price changes, and this exercise illustrates their practical application.

