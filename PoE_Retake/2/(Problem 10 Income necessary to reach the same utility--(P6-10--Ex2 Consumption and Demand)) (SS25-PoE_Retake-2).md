Let’s dive into Problem 10 with a clear and detailed explanation, focusing on why we arrive at $q_1 = 4$ and $q_2 = 12 - 2 = 10$, and how this leads to the final answer.

**Problem 10:** We need to find the income $y$ necessary after the price decrease of good 2 (from $p_2 = 8$ to $p_2 = 4$) so that the individual can reach the same level of utility as before the price decrease. The utility function is $U(q_1, q_2) = q_1^{\frac{1}{2}} + q_2$, income is originally $y = 80$, and prices are $p_1 = 1$, with $p_2 = 4$ after the decrease.

### Step 1: Determine the original utility level (before the price decrease)
Before the price decrease, $p_1 = 1$, $p_2 = 8$, and $y = 80$. From Problem 6, we found the optimal bundle:
- $q_1 = 16$, $q_2 = 8$

Calculate the utility at this bundle:
$$
U = q_1^{\frac{1}{2}} + q_2 = 16^{\frac{1}{2}} + 8 = 4 + 8 = 12
$$
So, the target utility level to maintain is $U = 12$.

### Step 2: Set up the problem after the price decrease
After the price decrease, $p_2 = 4$, and we need to find the new income $y$ that allows the individual to achieve $U = 12$ at the new prices $(p_1, p_2) = (1, 4)$. This is essentially a cost-minimization problem: we want the cheapest bundle that yields $U = 12$.

The utility constraint is:
$$
q_1^{\frac{1}{2}} + q_2 = 12
$$

The cost of the bundle at the new prices is:
$$
\text{Cost} = p_1 q_1 + p_2 q_2 = 1 \cdot q_1 + 4 \cdot q_2
$$
We need to minimize this cost subject to the utility constraint.

### Step 3: Solve the cost-minimization problem
From the utility constraint, express $q_2$ in terms of $q_1$:
$$
q_2 = 12 - q_1^{\frac{1}{2}}
$$

Substitute $q_2$ into the cost function:
$$
\text{Cost} = q_1 + 4 q_2 = q_1 + 4 (12 - q_1^{\frac{1}{2}}) = q_1 + 48 - 4 q_1^{\frac{1}{2}}
$$

To minimize this, take the derivative with respect to $q_1$ and set it to zero:
$$
\frac{d(\text{Cost})}{dq_1} = 1 - 4 \cdot \frac{1}{2} q_1^{-\frac{1}{2}} = 1 - \frac{2}{\sqrt{q_1}} = 0
$$
$$
1 = \frac{2}{\sqrt{q_1}} \implies \sqrt{q_1} = 2 \implies q_1 = 4
$$

Now, substitute $q_1 = 4$ back into the utility constraint to find $q_2$:
$$
q_1^{\frac{1}{2}} + q_2 = 12 \implies 4^{\frac{1}{2}} + q_2 = 12 \implies 2 + q_2 = 12 \implies q_2 = 12 - 2 = 10
$$

This is where the expression $q_2 = 12 - 2 = 10$ comes from: $4^{\frac{1}{2}} = 2$, so $q_2 = 12 - 2 = 10$.

### Step 4: Alternative approach (using tangency condition)
The cost-minimization problem can also be solved using the tangency condition (MRS = price ratio), which should give the same result. The MRS is:
$$
MRS = \frac{MU_1}{MU_2} = \frac{\frac{1}{2} q_1^{-\frac{1}{2}}}{1} = \frac{1}{2 \sqrt{q_1}}
$$

The price ratio at the new prices is:
$$
\frac{p_1}{p_2} = \frac{1}{4}
$$

Set MRS equal to the price ratio:
$$
\frac{1}{2 \sqrt{q_1}} = \frac{1}{4} \implies 2 \sqrt{q_1} = 4 \implies \sqrt{q_1} = 2 \implies q_1 = 4
$$

Then, use the utility constraint to find $q_2$:
$$
q_2 = 12 - 4^{\frac{1}{2}} = 12 - 2 = 10
$$

This confirms our earlier result: the bundle that achieves $U = 12$ at the new prices is $(q_1, q_2) = (4, 10)$.

### Step 5: Calculate the required income
The cost of this bundle at the new prices is the income required:
$$
y = p_1 q_1 + p_2 q_2 = 1 \cdot 4 + 4 \cdot 10 = 4 + 40 = 44
$$

### Step 6: Compare with the options
The options for Problem 10 are:
- (A) $y = 36$
- (B) $y = 40$
- (C) $y = 44$
- (D) $y = 48$

Our calculated income is $y = 44$, which matches option (C).

### Why $q_1 = 4$, $q_2 = 12 - 2 = 10$?
The values come from the optimization process:
- $q_1 = 4$ arises because the tangency condition (or cost minimization) at the new prices forces the MRS to equal the price ratio, leading to $\sqrt{q_1} = 2$.
- $q_2 = 12 - 2 = 10$ comes from plugging $q_1 = 4$ into the utility constraint $q_1^{\frac{1}{2}} + q_2 = 12$. Since $4^{\frac{1}{2}} = 2$, we get $q_2 = 12 - 2 = 10$.

**Answer for Problem 10: (C)**

This approach ensures the individual achieves the same utility ($U = 12$) at the new prices with the minimum income possible.
