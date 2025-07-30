>[!tip]
>Graph is in the solution PDF
>![](./(P9-10%20Public%20Goods--Ex%205%20Market%20Failure)%20(SS25-PoE_Retake-5)-1753822516280.png)

Let’s dive into Problems 9 and 10 about public goods, as presented in the image. These are classic economics problems involving the provision of a public good by multiple individuals, considering costs, benefits, and welfare implications. I’ll break down each problem, explain the key components, and then provide a step-by-step solution for both, following the requested structure.

---

### Problem 9: Welfare-Maximizing Quantity of the Public Good

#### What the Question is Asking
Problem 9 asks for the welfare-maximizing quantity of a public good ($Q_{opt}$) provided collectively by five identical individuals. We are given:
- The total cost function for providing the public good: $C(Q) = 10Q + \frac{1}{4}Q^2$.
- Each individual’s marginal benefit from the public good: $MB(Q) = 4 - \frac{1}{10}Q$.
- The goal is to find the quantity $Q$ that maximizes total welfare (or total surplus), defined as the total benefit minus the total cost.

Key components:
- **Public Good:** A good that is non-excludable and non-rivalrous, meaning one person’s consumption doesn’t reduce the amount available for others, and no one can be excluded from using it (e.g., a lighthouse).
- **Five Individuals:** All individuals are identical, so their marginal benefits are the same.
- **Welfare Maximization:** We need to maximize total surplus, which requires balancing the total benefits to all individuals against the total cost of provision.
- **Options:** We need to choose between $Q_{opt} = 0$, $-10$, $20$, or $40$.

#### Step-by-Step Solution

**Step 1: Understand the Samuelson Condition for Public Goods**
- **Explanation of Reasoning:** For public goods, the welfare-maximizing quantity occurs where the sum of all individuals’ marginal benefits equals the marginal cost of provision. This is known as the Samuelson condition, which accounts for the non-rivalrous nature of public goods—everyone benefits from the same quantity $Q$.
- **Methods and Concepts:** The Samuelson condition is:
  $$
  \sum MB(Q) = MC(Q)
$$
  Here, there are 5 individuals, each with the same marginal benefit $MB(Q) = 4 - \frac{1}{10}Q$. Thus, the total marginal benefit is:
  $$
  \sum MB(Q) = 5 \cdot MB(Q) = 5 \left(4 - \frac{1}{10}Q\right) = 20 - \frac{1}{2}Q
$$
- **Assumptions and Definitions:** We assume all individuals are identical and that the marginal benefit decreases linearly as $Q$ increases, reflecting diminishing returns. $MB(Q)$ is the additional benefit each individual gets from an extra unit of $Q$, and $MC(Q)$ is the marginal cost of producing one more unit of the public good.

**Step 2: Compute the Marginal Cost**
- **Explanation of Reasoning:** To apply the Samuelson condition, we need the marginal cost $MC(Q)$, which is the derivative of the total cost function $C(Q) = 10Q + \frac{1}{4}Q^2$.
- **Methods and Concepts:** Differentiate $C(Q)$ with respect to $Q$:
  $$
  MC(Q) = \frac{d}{dQ} \left(10Q + \frac{1}{4}Q^2\right) = 10 + \frac{1}{4} \cdot 2Q = 10 + \frac{1}{2}Q
$$
- **Assumptions and Definitions:** The cost function is quadratic, implying increasing marginal costs, which is typical for production processes where costs rise as output increases.

**Step 3: Apply the Samuelson Condition**
- **Explanation of Reasoning:** ==Set the sum of marginal benefits equal to the marginal cost to find the welfare-maximizing quantity:==
  $$
  5 \cdot MB(Q) = MC(Q) \implies 20 - \frac{1}{2}Q = 10 + \frac{1}{2}Q
$$
- **Methods and Concepts:** Solve for $Q$:
  $$
  20 - \frac{1}{2}Q = 10 + \frac{1}{2}Q
$$
  Add $\frac{1}{2}Q$ to both sides:
  $$
  20 = 10 + \frac{1}{2}Q + \frac{1}{2}Q = 10 + Q
$$
  Subtract 10 from both sides:
  $$
  20 - 10 = Q \implies Q = 10
$$
- **Assumptions and Definitions:** We assume $Q \geq 0$, as negative quantities are not meaningful for public goods provision. The solution $Q = 10$ is the candidate for $Q_{opt}$.

~~**Step 4: Verify the Solution and Check Options**~~
- **Explanation of Reasoning:** The calculated $Q = 10$ should be compared to the given options: 0, $-10$, 20, or 40. We also verify by checking the second-order condition for a maximum (i.e., the second derivative of the net benefit function should be negative).
- **Methods and Concepts:** The net benefit is ==total benefit== minus total cost. ==Total benefit for 5 individuals is the integral of the sum of marginal benefits from 0 to $Q$:==
  $$
  TB(Q) = \int_0^Q (20 - \frac{1}{2}x) \, dx = 20x - \frac{1}{4}x^2 \Big|_0^Q = 20Q - \frac{1}{4}Q^2
$$
  Net benefit = $TB(Q) - C(Q) = (20Q - \frac{1}{4}Q^2) - (10Q + \frac{1}{4}Q^2) = 10Q - \frac{1}{2}Q^2$. The first derivative is $10 - Q$, and the second derivative is $-1 < 0$, confirming a maximum at $Q = 10$.
- **Assumptions and Definitions:** Option $-10$ is not feasible (negative quantity). Among the feasible options (0, 20, 40), $Q = 10$ (option B) aligns with our calculation.

#### Overall Summary for Problem 9
The welfare-maximizing quantity $Q_{opt}$ is found using the Samuelson condition, balancing the sum of marginal benefits for five individuals ($20 - \frac{1}{2}Q$) against the marginal cost ($10 + \frac{1}{2}Q$). Solving gives $Q = 10$, which matches option (B). The steps confirm that this quantity maximizes total surplus by ensuring the additional benefit of the last unit equals its additional cost.

---

### Problem 10: Welfare Loss from Individual Provision

#### What the Question is Asking
Problem 10 examines the welfare loss when individuals provide the public good based on their own maximization, rather than collectively. We need to:
- Determine the quantity provided under individual provision.
- Calculate the welfare loss, defined as the difference between the maximum possible surplus (at $Q_{opt}$) and the surplus achieved under individual provision.
- Options for welfare loss: 0, 25, 50, or 100.

Key components:
- **Individual Provision:** Each individual decides how much to contribute to the public good, maximizing their own surplus, leading to underprovision due to the free-rider problem.
- **Welfare Loss:** The loss in surplus due to providing less than the optimal quantity.

#### Step-by-Step Solution

**Step 1: Determine Quantity Under Individual Provision**
- **Explanation of Reasoning:** In individual provision, each person maximizes their own surplus, treating others’ contributions as fixed. However, since all individuals are identical and act simultaneously, we look for a symmetric Nash equilibrium where each contributes the same amount. The condition for an individual’s contribution is that their marginal benefit equals their marginal cost (assuming they bear the full cost of their contribution).
- **Methods and Concepts:** For an individual, the marginal benefit is $MB(Q) = 4 - \frac{1}{10}Q$, and the marginal cost of providing $Q$ units alone is $MC(Q) = 10 + \frac{1}{2}Q$. Set $MB(Q) = MC(Q)$:
  $$
  4 - \frac{1}{10}Q = 10 + \frac{1}{2}Q
$$
  Solve:
  $$
  4 - 10 = \frac{1}{2}Q + \frac{1}{10}Q \implies -6 = \frac{5}{10}Q + \frac{1}{10}Q = \frac{6}{10}Q \implies -6 = \frac{3}{5}Q \implies Q = -10
$$
  ==Since $Q \geq 0$, this implies $Q = 0$ (a corner solution)—no individual contributes, as the marginal cost exceeds the marginal benefit for all $Q > 0$.==
- **Assumptions and Definitions:** We assume individuals act non-cooperatively, leading to the free-rider problem where each hopes others will provide the good. The total quantity $Q = 0$ under individual provision.

**Step 2: Calculate Surplus at $Q = 0$ and $Q_{opt} = 10$**
- **Explanation of Reasoning:** Welfare loss is the difference in surplus between the optimal quantity ($Q_{opt} = 10$) and the individually provided quantity ($Q = 0$). Surplus is total benefit minus total cost.
- **Methods and Concepts:** 
  - At $Q = 0$:
    $$
    TB(0) = 0, \quad C(0) = 0 \implies \text{Surplus} = 0
$$
  - At $Q_{opt} = 10$:
    $$
    TB(10) = 20 \cdot 10 - \frac{1}{4} \cdot 10^2 = 200 - 25 = 175
$$
    $$
    C(10) = 10 \cdot 10 + \frac{1}{4} \cdot 10^2 = 100 + 25 = 125
$$
    $$
    \text{Surplus at } Q_{opt} = 175 - 125 = 50
$$
- **Assumptions and Definitions:** The total benefit is the sum of benefits across all 5 individuals, integrated over the marginal benefit function.

**Step 3: Compute Welfare Loss**
- **Explanation of Reasoning:** Welfare loss is the surplus at $Q_{opt}$ minus the surplus at the individually provided quantity:
  $$
  WL = \text{Surplus}(Q_{opt}) - \text{Surplus}(Q=0) = 50 - 0 = 50
$$
  ==Alternatively, the problem provides a [[formula for welfare loss (SS25-PoE_Retake-5)]]:==

  $$
  WL = \frac{1}{2} \cdot Q_{opt} \cdot [5 \cdot MB(0) - MC(0)]
$$
  This formula calculates the deadweight loss (or welfare loss) when a public good is not provided at all (the corner solution where Q = 0) when it should optimally be provided at some positive quantity.
	
	Breaking it down:
	
	1. **Why the space between MC and sum MB?**
	    
	    - The welfare loss represents the unrealized net benefits to society
	    - ==At any quantity, the vertical distance between the social marginal benefit curve (5·MB) and the marginal cost curve (MC) represents the net benefit from producing one more unit==
	    - The total welfare loss is the sum of all these foregone net benefits between Q=0 and Q=Q_opt
	2. **Why multiplication by ½?**
	    
	    - This formula is calculating the area of a triangle
	    - The base of the triangle is Q_opt
	    - The height is [5·MB(0) - MC(0)], which is the vertical gap between curves at Q=0
	    - Area of triangle = ½ × base × height
	3. **What it means:**
	    
	    - ==It quantifies society's lost welfare from not producing the public good==
	    - It's using the starting point (Q=0) values because in this problem, the market provides nothing
	    - The 5·MB represents the vertical sum of all individual marginal benefits (for 5 identical individuals)
	    - The formula assumes linear MB and MC curves (which allows the simple triangle calculation)
	
	This calculation reveals how much total welfare society loses when a public good that should be provided is not provided at all.
  
  At $Q = 0$, $5 \cdot MB(0) = 5 \cdot 4 = 20$, $MC(0) = 10$, so:
  $$
  WL = \frac{1}{2} \cdot 10 \cdot (20 - 10) = \frac{1}{2} \cdot 10 \cdot 10 = 50
$$
- **Methods and Concepts:** The formula reflects the deadweight loss triangle, where the base is $Q_{opt}$ and the height is the difference between total marginal benefit and marginal cost at $Q = 0$.
- **Assumptions and Definitions:** The welfare loss arises because individual provision leads to $Q = 0$, far below the optimal $Q = 10$, due to the free-rider problem.

**Step 4: Match with Options**
- **Explanation of Reasoning:** The calculated welfare loss of 50 matches option (C).
- **Methods and Concepts:** No further computation needed; the result aligns with the provided solution.
- **Assumptions and Definitions:** The free-rider problem is a key concept in public goods, leading to underprovision and welfare loss.

#### Overall Summary for Problem 10
Individual provision results in $Q = 0$ because each person’s marginal cost exceeds their marginal benefit, leading to a corner solution (no provision). The welfare-maximizing quantity is $Q_{opt} = 10$, with a surplus of 50. The welfare loss, due to underprovision, is 50, matching option (C). The free-rider problem causes this inefficiency, as individuals do not account for the benefits others receive from their contribution.

---

### Final Confirmation
- **Problem 9:** The welfare-maximizing quantity is $Q_{opt} = 10$, so the answer is (B).
- **Problem 10:** The welfare loss from individual provision is 50, so the answer is (C).

Both solutions align with the provided answers in the image, confirming the correctness of the approach.
