>[!tip]
>Get the Function Graph in Solution PDF


Let’s analyze the problem and solution for each of the questions (Problems 5–8) in the provided image. I’ll break down each question, explain what it’s asking, and then provide a step-by-step explanation of the solution, including reasoning, methods, concepts, assumptions, and definitions. Finally, I’ll summarize each problem’s solution and confirm the final answer.

---

### **Problem 5: Individual Profit Maximization and Market Equilibrium**

#### **What the Question is Asking**
Problem 5 asks for the profit per firm in a market equilibrium where two profit-maximizing firms (A and B) operate in the short run, taking prices as given ([[price-taker behavior (SS25-PoE_Retake-5)]]). The firms have identical cost functions, and there is an externality: each firm’s output increases the other firm’s costs. The market demand is provided, and we need to find the equilibrium where firms maximize their profits individually, then calculate each firm’s profit. The options are 0, 15, 30, or 45.

**Key Components:**
- **Cost Function:** $C(q_i) = 15 + \frac{1}{100} q_i^2 + \frac{1}{5} q_j$, where $q_i$ is firm $i$’s output, and $q_j$ is the other firm’s output ($i \neq j$).
- **Market Demand:** $Q^D(p) = 200 - 100p$.
- **Price-Taker Assumption:** Firms take the market price $p$ as given.
- **Externality:** The term $\frac{1}{5} q_j$ in the cost function indicates that firm $j$’s output increases firm $i$’s costs.
- **Goal:** Find the profit per firm in equilibrium.

#### **Step-by-Step Solution**

**Step 1: Set Up the Profit Maximization Problem**
- **Explanation of Reasoning:** Each firm maximizes its profit individually, ignoring the externality it imposes on the other. Profit for firm $i$ is revenue minus cost: $\pi_i(q_i) = p \cdot q_i - C(q_i)$.
- **Methods and Concepts:** Substitute the cost function into the profit equation:
  $$
  \pi_i(q_i) = p \cdot q_i - \left( 15 + \frac{1}{100} q_i^2 + \frac{1}{5} q_j \right) = p \cdot q_i - 15 - \frac{1}{100} q_i^2 - \frac{1}{5} q_j.
$$
  Since firms are price-takers, $p$ is given, and firm $i$ chooses $q_i$ to maximize profit, treating $q_j$ (the other firm’s output) as fixed.
- **Assumptions and Definitions:** Assume $q_i, q_j \geq 0$. The term $\frac{1}{5} q_j$ is treated as a constant by firm $i$ because it depends on the other firm’s output. Marginal cost (MC) is the derivative of the cost function with respect to $q_i$.

**Step 2: Derive the Necessary Condition for Profit Maximization**
- **Explanation of Reasoning:** To maximize profit, take the derivative of $\pi_i(q_i)$ with respect to $q_i$ and set it to zero (first-order condition).
- **Methods and Concepts:** -

>[!tip]
>Still MC but only to i not j

- Compute the derivative:
  $$
  \frac{d\pi_i(q_i)}{dq_i} = p - \frac{d}{dq_i} \left( 15 + \frac{1}{100} q_i^2 + \frac{1}{5} q_j \right) = p - \frac{2}{100} q_i = p - \frac{1}{50} q_i.
$$
  Set the derivative to zero:
  $$
  p - \frac{1}{50} q_i = 0 \implies p = \frac{1}{50} q_i \implies q_i = 50p.
$$
  This is firm $i$’s supply function $q_i(p) = 50p$. The term $\frac{1}{50} q_i$ is the marginal cost $MC(q_i)$, since $\frac{d}{dq_i} \left( \frac{1}{100} q_i^2 \right) = \frac{1}{50} q_i$.
- **Assumptions and Definitions:** The derivative ignores $\frac{1}{5} q_j$ because it’s constant with respect to $q_i$. The marginal cost does not include the externality term $\frac{1}{5} q_j$, reflecting that firms do not internalize the external cost.

**Step 3: Compute Market Supply**
- **Explanation of Reasoning:** Since the firms are identical, both have the same supply function. Market supply is the sum of individual supplies.
- **Methods and Concepts:** For two firms:
  $$
  Q^S(p) = q_A(p) + q_B(p) = 50p + 50p = 100p.
$$
- **Assumptions and Definitions:** Symmetry is assumed (firms A and B are identical), so $q_A = q_B = 50p$.

**Step 4: Find Market Equilibrium**
- **Explanation of Reasoning:** Equilibrium occurs where market supply equals market demand: $Q^S(p) = Q^D(p)$.
- **Methods and Concepts:** ==Set the supply and demand equal:==
  $$
  Q^D(p) = 200 - 100p, \quad Q^S(p) = 100p.
$$
  $$
  200 - 100p = 100p \implies 200 = 200p \implies p = 1.
$$
  Substitute $p = 1$ into the demand (or supply) to find equilibrium quantity:
  $$
  Q^* = 100p = 100 \cdot 1 = 100.
$$
  Each firm produces:
  $$
  q^* = 50p = 50 \cdot 1 = 50.
$$
- **Assumptions and Definitions:** The market clears at $p^* = 1$, and $Q^* = 100$, with each firm producing $q^* = 50$.

**Step 5: Calculate Profit per Firm**
- **Explanation of Reasoning:** Use the equilibrium values to compute profit: $\pi_i = p \cdot q_i - C(q_i)$.
- **Methods and Concepts:** Substitute $p = 1$, $q_i = 50$, $q_j = 50$ into the cost function:
  $$
  C(50) = 15 + \frac{1}{100} (50)^2 + \frac{1}{5} (50) = 15 + \frac{1}{100} \cdot 2500 + \frac{1}{5} \cdot 50 = 15 + 25 + 10 = 50.
$$
  Profit:
  $$
  \pi^* = p \cdot q_i - C(q_i) = 1 \cdot 50 - 50 = 50 - 50 = 0.
$$
- **Assumptions and Definitions:** The externality term $\frac{1}{5} q_j = \frac{1}{5} \cdot 50 = 10$ increases costs, reducing profit to zero.

**Overall Summary for Problem 5:**
The firms maximize profit by setting marginal cost equal to price, leading to a supply function $q_i(p) = 50p$. Market equilibrium occurs at $p = 1$, with each firm producing 50 units, for a total of 100 units. The externality increases costs, and profit per firm is zero. The correct answer is **(A) 0**.

---

### **Problem 6: Welfare-Maximizing Total Output**

#### **What the Question is Asking**
Problem 6 asks for the welfare-maximizing total output, where [[welfare maximization]] means the firms internalize the externality (aligning social marginal benefit with social marginal cost). The options are 30, 60, 90, or 120.

**Key Components:**
- Same cost function and market demand as Problem 5.
- **Welfare Maximization:** Firms collectively maximize total profit, internalizing the externality.
- **Goal:** Find the total output $Q_{\text{opt}}$.

#### **Step-by-Step Solution**

**Step 1: Set Up the Collective Maximization Problem**
- **Explanation of Reasoning:** ==Welfare maximization requires the firms to maximize their combined profit, internalizing the externality.==
- **Methods and Concepts:** Total profit for firms A and B:
  $$
  \Pi(q_A, q_B) = p \cdot q_A + p \cdot q_B - C(q_A) - C(q_B) = p \cdot (q_A + q_B) - \left( 15 + \frac{1}{100} q_A^2 + \frac{1}{5} q_B \right) - \left( 15 + \frac{1}{100} q_B^2 + \frac{1}{5} q_A \right).
$$
  Simplify:
  $$
  \Pi(q_A, q_B) = p \cdot (q_A + q_B) - 15 - 15 - \frac{1}{100} q_A^2 - \frac{1}{100} q_B^2 - \frac{1}{5} q_B - \frac{1}{5} q_A.
$$
  Since $q_A + q_B = Q$, and firms are identical, assume $q_A = q_B$, so $q_A = q_B = \frac{Q}{2}$. Substitute:
  $$
  q_A = q_B = \frac{Q}{2}, \quad Q = q_A + q_B.
$$
  Rewrite the profit in terms of $Q$, but first maximize with respect to $q_A$ and $q_B$.
- **Assumptions and Definitions:** Symmetry is assumed ($q_A = q_B$). Welfare maximization aligns social marginal benefit (price) with social marginal cost (including the externality).

**Step 2: Derive the Necessary Conditions**
- **Explanation of Reasoning:** Take partial derivatives of $\Pi$ with respect to $q_A$ and $q_B$, set to zero.
- **Methods and Concepts:** Partial derivative with respect to $q_A$:
  $$
  \frac{\partial \Pi}{\partial q_A} = p - \frac{1}{50} q_A - \frac{1}{5} = 0 \implies p = \frac{1}{50} q_A + \frac{1}{5}.
$$
  Partial derivative with respect to $q_B$:
  $$
  \frac{\partial \Pi}{\partial q_B} = p - \frac{1}{50} q_B - \frac{1}{5} = 0 \implies p = \frac{1}{50} q_B + \frac{1}{5}.
$$
  Since firms are identical, $q_A = q_B$, so:
  $$
  p = \frac{1}{50} q_A + \frac{1}{5}.
$$
  The term $\frac{1}{50} q_A$ is $MC(q_A)$, and $\frac{1}{5}$ is the marginal external cost $MC_{Ex}(q_A)$, because firm A’s output increases firm B’s cost by $\frac{1}{5}$.
- **Assumptions and Definitions:** The social marginal cost is $MC(q_A) + MC_{Ex}(q_A)$.

**Step 3: Solve for Supply**
- **Explanation of Reasoning:** Solve for $q_A$:
  $$
  p = \frac{1}{50} q_A + \frac{1}{5} \implies p - \frac{1}{5} = \frac{1}{50} q_A \implies q_A = 50 \left( p - \frac{1}{5} \right) = 50p - 10.
$$
  Similarly, $q_B = 50p - 10$. Market supply:
  $$
  Q^S(p) = q_A + q_B = (50p - 10) + (50p - 10) = 100p - 20.
$$
- **Assumptions and Definitions:** Symmetry ensures equal outputs.

**Step 4: Find Market Equilibrium**
- **Explanation of Reasoning:** Set supply equal to demand:
  $$
  200 - 100p = 100p - 20 \implies 200 + 20 = 100p + 100p \implies 220 = 200p \implies p = 1.1.
$$
  Total quantity:
  $$
  Q^* = 100p - 20 = 100 \cdot 1.1 - 20 = 110 - 20 = 90.
$$
  Each firm produces:
  $$
  q^* = 50p - 10 = 50 \cdot 1.1 - 10 = 55 - 10 = 45.
$$
- **Assumptions and Definitions:** Market clears at $p = 1.1$, $Q = 90$.

**Step 5: Verify Welfare-Maximizing Output**
- **Explanation of Reasoning:** The total output $Q_{\text{opt}} = 90$ is the welfare-maximizing quantity because firms internalize the externality.
- **Methods and Concepts:** Compare with options: 30, 60, 90, 120.
- **Assumptions and Definitions:** Welfare maximization equates social marginal benefit (demand) with social marginal cost.

**Overall Summary for Problem 6:**
By internalizing the externality, the firms’ supply shifts to $Q^S(p) = 100p - 20$. Equilibrium occurs at $p = 1.1$, with total output $Q = 90$, which is the welfare-maximizing quantity. The correct answer is **(C) 90**.


[[Explore Deep reason Problem 6 Welfare-Maximizing Total Output--(P5-8 External Effects--Ex 5 Market Failure)) (SS25-PoE_Retake-5)]]


---

### **Problem 7: Welfare Loss from Individual Profit Maximization**

#### **What the Question is Asking**
Problem 7 asks for the welfare loss (deadweight loss) resulting from individual profit maximization (Problem 5) compared to the welfare-maximizing output (Problem 6). Options are 0, 1, 19, or 20.

**Key Components:**
- Equilibrium quantity from individual profit maximization: $Q^* = 100$ (from Problem 5).
- Welfare-maximizing quantity: $Q_{\text{opt}} = 90$ (from Problem 6).
- **Goal:** Calculate the welfare loss due to overproduction.

#### **Step-by-Step Solution**

**Step 1: Understand Welfare Loss**
- **Explanation of Reasoning:** Welfare loss occurs because individual profit maximization leads to overproduction ($Q^* = 100$) compared to the welfare-maximizing output ($Q_{\text{opt}} = 90$). For the excess output (from 90 to 100), social marginal cost exceeds social marginal benefit.
- **Methods and Concepts:** ==Welfare loss is the area of the triangle where $MC_{Ex}$ (external cost) exceeds the demand curve between $Q_{\text{opt}}$ and $Q^*$:==
  $$
  WL = \frac{1}{2} \cdot (Q^* - Q_{\text{opt}}) \cdot MC_{Ex}(Q^*).
$$
[[WL loss formula in externel effects (SS25-PoE_Retake-5)]] 

- **Assumptions and Definitions:** $MC_{Ex} = \frac{1}{5}$ (constant, from the cost function term $\frac{1}{5} q_j$).

**Step 2: Compute the Welfare Loss**
- **Explanation of Reasoning:** Use the formula:
  $$
  Q^* = 100, \quad Q_{\text{opt}} = 90, \quad MC_{Ex} = \frac{1}{5}.
$$
- **Methods and Concepts:** Substitute:
  $$
  WL = \frac{1}{2} \cdot (100 - 90) \cdot \frac{1}{5} = \frac{1}{2} \cdot 10 \cdot \frac{1}{5} = 5 \cdot \frac{1}{5} = 1.
$$
- **Assumptions and Definitions:** The external cost is constant at $\frac{1}{5}$. The welfare loss triangle’s height is $MC_{Ex}$, and the base is the difference in quantities.

**Overall Summary for Problem 7:**
Individual profit maximization leads to overproduction (100 vs. 90), causing a welfare loss because the social marginal cost exceeds the social marginal benefit for the excess output. The welfare loss is 1, so the correct answer is **(B) 1**.

---

### **Problem 8: Tax and Subsidy for Zero Profit**

#### **What the Question is Asking**
Problem 8 introduces a tax $t = \frac{1}{5}$ per unit of output on producers, combined with a lump-sum subsidy $S > 0$ per firm, such that firms make zero profit in equilibrium. We need to find the subsidy $S$. Options are 3.75, 7.5, 11.25, or 15.

**Key Components:**
- Tax $t = \frac{1}{5}$ equals the external cost, so firms internalize the externality (same as welfare maximization in Problem 6).
- Lump-sum subsidy $S$ ensures zero profit.
- **Goal:** Find $S$.

#### **Step-by-Step Solution**
- Not Collective

**Step 1: Adjust the Profit Maximization with Tax**
- **Explanation of Reasoning:** The tax $t = \frac{1}{5}$ is equivalent to the external cost, so firms effectively internalize the externality, leading to the same supply as in Problem 6.
- **Methods and Concepts:** Profit with tax:
  $$
  \pi_i(q_i) = p \cdot q_i - C(q_i) - t \cdot q_i + S.
$$
  Substitute $C(q_i)$ and $t = \frac{1}{5}$:
  $$
  \pi_i(q_i) = p \cdot q_i - \left( 15 + \frac{1}{100} q_i^2 + \frac{1}{5} q_j \right) - \frac{1}{5} q_i + S.
$$
  Simplify:
  $$
  \pi_i(q_i) = \left( p - \frac{1}{5} \right) q_i - 15 - \frac{1}{100} q_i^2 - \frac{1}{5} q_j + S.
$$
  Maximize with respect to $q_i$:
  $$
  \frac{d\pi_i}{dq_i} = \left( p - \frac{1}{5} \right) - \frac{1}{50} q_i = 0 \implies p - \frac{1}{5} = \frac{1}{50} q_i \implies q_i = 50 \left( p - \frac{1}{5} \right) = 50p - 10.
$$
  This matches the supply from Problem 6, confirming the tax internalizes the externality.
- **Assumptions and Definitions:** The tax shifts the effective price to $p - t$.

**Step 2: Find Equilibrium**
- **Explanation of Reasoning:** The supply is the same as Problem 6: $Q^S(p) = 100p - 20$. Equilibrium:
  $$
  200 - 100p = 100p - 20 \implies p = 1.1, \quad Q^* = 90, \quad q^* = 45.
$$
- **Assumptions and Definitions:** Same as Problem 6.

**Step 3: Compute Profit Before Subsidy**
- **Explanation of Reasoning:** Calculate profit without the subsidy, then set $S$ to make total profit zero.
- **Methods and Concepts:** Profit without $S$:
  $$
  \pi_i = p \cdot q_i - C(q_i) - t \cdot q_i.
$$
  Substitute $p = 1.1$, $q_i = 45$, $q_j = 45$, $t = \frac{1}{5}$:
  $$
  C(45) = 15 + \frac{1}{100} (45)^2 + \frac{1}{5} (45) = 15 + \frac{2025}{100} + 9 = 15 + 20.25 + 9 = 44.25.
$$
  Tax payment:
  $$
  t \cdot q_i = \frac{1}{5} \cdot 45 = 9.
$$
  Revenue:
  $$
  p \cdot q_i = 1.1 \cdot 45 = 49.5.
$$
  Profit:
  $$
  \pi_i = 49.5 - 44.25 - 9 = 49.5 - 53.25 = -3.75.
$$
- **Assumptions and Definitions:** Profit is negative without the subsidy.

**Step 4: Determine the Subsidy**
- **Explanation of Reasoning:** Set total profit to zero:
  $$
  \pi_i + S = 0 \implies -3.75 + S = 0 \implies S = 3.75.
$$
- **Methods and Concepts:** The lump-sum subsidy offsets the negative profit.
- **Assumptions and Definitions:** Firms make zero profit in equilibrium.

**Overall Summary for Problem 8:**
The tax $t = \frac{1}{5}$ internalizes the externality, leading to the welfare-maximizing output (as in Problem 6). In equilibrium, each firm produces 45 units at $p = 1.1$, but incurs a loss of 3.75 due to the tax and costs. A subsidy $S = 3.75$ ensures zero profit. The correct answer is **(A) 3.75**.

---

### **Final Confirmation**
- **Problem 5:** (A) 0 – Confirmed.
- **Problem 6:** (C) 90 – Confirmed.
- **Problem 7:** (B) 1 – Confirmed.
- **Problem 8:** (A) 3.75 – Confirmed.

All solutions align with the provided answers, and the reasoning is consistent with economic principles of profit maximization, externalities, and welfare analysis.
