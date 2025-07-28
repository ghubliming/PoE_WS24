Let’s dive into why the welfare loss (WL) in a monopoly is calculated using the formula $WL = \frac{1}{2} \cdot (Q^* - Q^M) \cdot (p(Q^M) - MC(Q^M))$, and specifically address why we use $MC(Q^M)$ instead of the price where $p = MC$, which corresponds to $p(Q^*)$.

---

### **Understanding Welfare Loss in a Monopoly**

Welfare loss, or deadweight loss (DWL), represents the inefficiency caused by a monopoly compared to a perfectly competitive market. ==In a competitive market, output is produced where price equals marginal cost ($p = MC$), maximizing total surplus (consumer surplus + producer surplus)==. A monopolist, however, restricts output to maximize profit, producing where marginal revenue equals marginal cost ($MR = MC$), which results in a higher price and lower quantity than the competitive outcome. The welfare loss is the "lost" surplus from the units not produced (from $Q^M$ to $Q^*$).

---

### **Breaking Down the Formula**

The formula for welfare loss is:

$$
WL = \frac{1}{2} \cdot (Q^* - Q^M) \cdot (p(Q^M) - MC(Q^M)).
$$

- $Q^*$: The competitive output where $p = MC$.
- $Q^M$: The monopoly output where $MR = MC$.
- $p(Q^M)$: The price the monopolist charges at $Q^M$, determined by the demand curve.
- $MC(Q^M)$: The marginal cost at the monopoly output $Q^M$.

This formula calculates the area of the "deadweight loss triangle" on a supply-demand graph:
- The base of the triangle is the difference in quantity: $Q^* - Q^M$.
- The height of the triangle is the difference between the price consumers are willing to pay at $Q^M$ (i.e., $p(Q^M)$) and the marginal cost of producing that quantity (i.e., $MC(Q^M)$).

---

### **Why $MC(Q^M)$ Instead of $p(Q^*)$?**

The question asks why we use $MC(Q^M)$—the marginal cost at the monopoly output—instead of the price at the competitive output $p(Q^*)$, which is where $p = MC$.

#### **Step 1: Visualize the Deadweight Loss Triangle**
On a graph with quantity on the x-axis and price on the y-axis:
- The demand curve is downward sloping: $p = 75 - Q$.
- The marginal cost curve is upward sloping: $MC = \frac{1}{2} Q$ (from the cost function $C(Q) = c^f + \frac{1}{4} Q^2$).
- The marginal revenue curve for a linear demand $p = 75 - Q$ is $MR = 75 - 2Q$.
- ==The monopolist produces at $Q^M = 30$, where $MR = MC$, and charges $p(Q^M) = 45$.==
- The competitive output is at $Q^* = 50$, where $p = MC$, and the price is $p(Q^*) = 25$.

The deadweight loss is the triangle formed by:
- The demand curve from $Q^M$ to $Q^*$.
- The marginal cost curve from $Q^M$ to $Q^*$.
- The vertical line at $Q^M$.

#### **Step 2: Identify the Height of the Triangle**
==The welfare loss triangle represents the lost surplus for the units not produced (from $Q^M = 30$ to $Q^* = 50$):==
- At $Q^M = 30$, the price consumers are willing to pay is $p(Q^M) = 45$, but the cost to produce that 30th unit is only $MC(Q^M) = \frac{1}{2} \cdot 30 = 15$.
- ==For each additional unit beyond $Q^M$ up to $Q^*$, the value to consumers (given by the demand curve) exceeds the cost of production (given by the marginal cost curve). This difference represents the surplus that could have been gained but is lost due to the monopoly’s restricted output.==

The height of the triangle at $Q^M$ is the vertical distance between the demand curve and the marginal cost curve at that quantity:
- Demand at $Q^M$: $p(Q^M) = 45$.
- Marginal cost at $Q^M$: $MC(Q^M) = 15$.
- Height: $p(Q^M) - MC(Q^M) = 45 - 15 = 30$.

#### **Step 3: Why Not Use $p(Q^*)$?**
Now, let’s consider using $p(Q^*)$, the price at the competitive output:
- At $Q^* = 50$, $p(Q^*) = 75 - 50 = 25$, which equals $MC(Q^*) = \frac{1}{2} \cdot 50 = 25$.

If we used $p(Q^*)$ instead of $MC(Q^M)$, the height would be:
$$
p(Q^M) - p(Q^*) = 45 - 25 = 20.
$$

This would give a welfare loss of:
$$
WL = \frac{1}{2} \cdot (Q^* - Q^M) \cdot (p(Q^M) - p(Q^*)) = \frac{1}{2} \cdot (50 - 30) \cdot (45 - 25) = \frac{1}{2} \cdot 20 \cdot 20 = 200.
$$

This is incorrect because it doesn’t represent the true deadweight loss triangle:
- $p(Q^*) = 25$ is the price at $Q^*$, but the welfare loss triangle’s height at $Q^M$ depends on the marginal cost at $Q^M$, not the price or marginal cost at $Q^*$.
- Using $p(Q^*)$ would imply we’re measuring the height at the wrong point. The triangle’s height at $Q^M$ must reflect the difference between what consumers are willing to pay ($p(Q^M)$) and the cost of producing that unit ($MC(Q^M)$), because that’s the starting point of the lost surplus.

#### **Step 4: Why $MC(Q^M)$ Makes Sense**
- The marginal cost at $Q^M$ ($MC(Q^M)$) represents the cost of producing the last unit the monopolist makes.
- For the units between $Q^M$ and $Q^*$, the surplus per unit is the difference between the demand curve (consumer willingness to pay) and the marginal cost (cost to produce). At $Q = Q^M$, this difference is $p(Q^M) - MC(Q^M)$, and at $Q = Q^*$, the difference is zero (since $p(Q^*) = MC(Q^*)$).
- The welfare loss is the area of the triangle, which averages this difference over the range from $Q^M$ to $Q^*$. Using $MC(Q^M)$ as the lower bound of the height correctly captures the starting point of the lost surplus.

#### **Step 5: Geometric Intuition**
The welfare loss triangle has:
- Base: $Q^* - Q^M = 50 - 30 = 20$.
- Height at $Q^M$: $p(Q^M) - MC(Q^M) = 45 - 15 = 30$.
- Height at $Q^*$: $p(Q^*) - MC(Q^*) = 25 - 25 = 0$.

Since the demand and marginal cost curves are linear, the area of the triangle is:
$$
WL = \frac{1}{2} \cdot \text{base} \cdot \text{height at } Q^M = \frac{1}{2} \cdot (Q^* - Q^M) \cdot (p(Q^M) - MC(Q^M)) = \frac{1}{2} \cdot 20 \cdot 30 = 300.
$$

Using $p(Q^*)$ would underestimate the height at $Q^M$, leading to an incorrect area.

---

### **Methods and Concepts**

- **Deadweight Loss:** The loss of economic efficiency when the equilibrium quantity is not at the competitive level. It’s the surplus that could have been gained from additional units but isn’t due to market distortions like a monopoly.
- **Triangle Area:** The formula $\frac{1}{2} \cdot \text{base} \cdot \text{height}$ applies because the welfare loss region is a triangle (due to linear demand and marginal cost curves).
- **Marginal Cost:** $MC = \frac{dC}{dQ}$, which determines the cost of producing additional units and is crucial for identifying the competitive output and the cost side of the welfare loss.

---

### **Assumptions and Definitions**

- **Linear Curves:** The demand and marginal cost curves are linear, making the welfare loss a perfect triangle. If they were non-linear, we’d need to integrate the difference between demand and marginal cost from $Q^M$ to $Q^*$.
- **No Externalities:** We assume the only inefficiency is due to the monopoly’s output restriction, with no other market failures.
- **Marginal Cost at $Q^M$:** This is the cost of producing the 30th unit, not the cost at $Q^*$, because we’re evaluating the surplus lost starting at the monopoly’s output level.

---

### **Summary**

The welfare loss formula uses $MC(Q^M)$ because it correctly captures the height of the deadweight loss triangle at the monopoly output $Q^M$. This height ($p(Q^M) - MC(Q^M)$) reflects the surplus lost on the first unit not produced by the monopolist. Using $p(Q^*)$ (where $p = MC$) would measure the height at the wrong point, underestimating the welfare loss. The correct calculation, as shown, yields $WL = 300$, matching the solution provided in the image.
