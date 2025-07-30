# Solve Routine For Perfect Competition Problems

This document outlines a systematic approach to solving long-run equilibrium problems in a perfectly competitive market, based on the common structure of Exercise 4 questions.

---

### **Knowns & Unknowns**

*   **Typically Known:**
    *   **Market Demand Function:** e.g., $Q^D(p) = a - p$
    *   **Individual Firm's Cost Function:** e.g., $C(q) = c^f + q^2$ or $C(q) = \text{fixed-cost} + \text{variable-costs}$

*   **Typically Unknown (What you need to find):**
    *   $n^*$: Equilibrium number of firms
    *   $p^*$: Equilibrium market price
    *   $q^*$: Equilibrium quantity produced by a single firm
    *   $Q^*$: Total equilibrium quantity in the market
    *   $\pi^*$: Profit per firm in equilibrium
    *   Consumer Surplus (CS), Producer Surplus (PS), Welfare Loss (WL)

---

### **The Step-by-Step Solution Routine**

#### **Part 1: Find the Firm's Break-Even Point (The core of the solution)**

This determines the price and quantity at which a firm earns zero economic profit, the key condition for long-run equilibrium.

1.  **Derive Marginal Cost (MC):**
    *   Take the first derivative of the cost function $C(q)$ with respect to quantity $q$.
    *   $MC(q) = \frac{dC(q)}{dq}$

2.  **Derive Average Total Cost (AC):**
    *   Divide the total cost function $C(q)$ by the quantity $q$.
    *   $AC(q) = \frac{C(q)}{q}$

3.  **Find the Break-Even Quantity ($q^*$):**
    *   Set Marginal Cost equal to Average Total Cost: **$MC(q) = AC(q)$**.
    *   Solve this equation for $q$. This gives you the optimal quantity $q^*$ that each firm will produce in the long-run equilibrium.

4.  **Find the Break-Even Price ($p^*$):**
    *   Substitute the break-even quantity $q^*$ back into the Marginal Cost function (or the Average Cost function, they will be equal).
    *   $p^* = MC(q^*)$. This is the equilibrium market price.

#### **Part 2: Determine the Market Outcome**

Now that you know the equilibrium price and the quantity per firm, you can determine the overall market structure.

5.  **Calculate Total Market Quantity ($Q^*$):**
    *   Substitute the equilibrium price $p^*$ into the given Market Demand function.
    *   $Q^* = Q^D(p^*)$

6.  **Calculate the Number of Firms ($n^*$):**
    *   Divide the total market quantity by the quantity per firm.
    *   $n^* = \frac{Q^*}{q^*}$

#### **Part 3: Handle Special Conditions & Calculations**

*   **Integer Constraint for Firms:**
    *   If the calculated $n^*$ is not a whole number (e.g., 10.6), the actual number of firms in the market must be the integer part, so $n_{actual}^* = \lfloor n^* \rfloor$ (e.g., 10).
    *   In this case, firms will make a small positive profit. To calculate it, you must re-calculate the equilibrium values using the integer $n_{actual}^*$. The key is to find the new price by setting $Q^D(p) = n_{actual}^* \cdot q(p)$, where $q(p)$ is the individual supply curve from $p=MC(q)$.

*   **Calculating Profit ($\pi^*$):**
    *   Profit is Total Revenue minus Total Cost: $\pi^* = (p^* \cdot q^*) - C(q^*)$.
    *   In a perfect long-run equilibrium (where $n^*$ is an integer), profit $\pi^*$ will be **zero**. If the integer constraint binds, it will be slightly positive.

*   **Effect of a Per-Unit Tax ($t$):**
    1.  The tax adds to the cost: $C_{new}(q) = C(q) + t \cdot q$.
    2.  This increases the marginal cost: $MC_{new}(q) = MC(q) + t$.
    3.  The average cost also changes: $AC_{new}(q) = AC(q) + t$.
    4.  **Repeat the entire routine** with these new cost functions to find the new equilibrium.

*   **Calculating Surpluses and Welfare Loss:**
    *   **Consumer Surplus (CS):** The area of the triangle below the demand curve and above the equilibrium price $p^*$. For a linear demand curve, find the "choke price" (where $Q^D=0$) and calculate: $CS = \frac{1}{2} \cdot Q^* \cdot (\text{choke\quad price} - p^*)$.
    *   **Producer Surplus (PS):** The area of the triangle above the supply curve and below the equilibrium price $p^*$.
    *   **Welfare Loss (WL):** The loss of total surplus (CS + PS) due to a market distortion (like a tax or price ceiling). It is typically the area of the deadweight loss triangle, calculated as $\frac{1}{2} \cdot \Delta Q \cdot (\text{price \quad wedge})$.