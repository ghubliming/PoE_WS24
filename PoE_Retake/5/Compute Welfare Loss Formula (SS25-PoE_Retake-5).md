
>[!warning] Caution
>old notes may exist logic problem

[[Archive (Compute Welfare Loss Formula) (SS25-PoE_Retake-5)]]

---

# Understanding the Welfare Loss Formula in Monopoly

Let's examine why the welfare loss (deadweight loss) in a monopoly is calculated using the formula $WL = \frac{1}{2} \cdot (Q^* - Q^M) \cdot (p(Q^M) - MC(Q^M))$ and clarify the geometric and economic reasoning behind this calculation.

---

## **Welfare Loss Fundamentals**

Welfare loss (deadweight loss) represents the economic inefficiency caused by monopoly pricing compared to perfect competition. In a competitive market, output occurs where price equals marginal cost ($p = MC$), maximizing total economic surplus. A monopolist restricts output to where marginal revenue equals marginal cost ($MR = MC$), creating a welfare loss from the units that could have been profitably produced but weren't.

---

## **The Economic Setup**

Using the given example:
- **Demand curve**: $p = 75 - Q$
- **Marginal cost**: $MC = \frac{1}{2}Q$ (derived from $C(Q) = c^f + \frac{1}{4}Q^2$)
- **Marginal revenue**: $MR = 75 - 2Q$ (for linear demand)

**Equilibrium Points:**
- **Monopoly**: $MR = MC \Rightarrow 75 - 2Q = \frac{1}{2}Q \Rightarrow Q^M = 30$, $p(Q^M) = 45$
- **Competition**: $p = MC \Rightarrow 75 - Q = \frac{1}{2}Q \Rightarrow Q^* = 50$, $p(Q^*) = MC(Q^*) = 25$

---

## **The Deadweight Loss Triangle**

The deadweight loss is the triangular area between:
- The demand curve from $Q^M$ to $Q^*$
- The marginal cost curve from $Q^M$ to $Q^*$
- The vertical line at $Q^M$

**Triangle vertices:**
- Point A: $(Q^M, p(Q^M)) = (30, 45)$ - on the demand curve
- Point B: $(Q^M, MC(Q^M)) = (30, 15)$ - on the MC curve  
- Point C: $(Q^*, p(Q^*)) = (50, 25)$ - where demand meets MC

---

## **Why the Formula Works**

The formula $WL = \frac{1}{2} \cdot (Q^* - Q^M) \cdot (p(Q^M) - MC(Q^M))$ calculates the area of this triangle because:

### **For Linear Curves, This Gives the Exact Area**

When both demand and marginal cost curves are linear, the deadweight loss region is a perfect triangle. The area can be calculated as:

$$\text{Area} = \frac{1}{2} \times \text{base} \times \text{height}$$

Where:
- **Base**: $Q^* - Q^M = 50 - 30 = 20$
- **Height**: The vertical distance at $Q^M$ between demand and MC curves = $p(Q^M) - MC(Q^M) = 45 - 15 = 30$

Therefore: $WL = \frac{1}{2} \times 20 \times 30 = 300$

### **Why This Height Measurement is Correct**

The height $p(Q^M) - MC(Q^M)$ represents:
- **$p(Q^M) = 45$**: What consumers are willing to pay for the 30th unit
- **$MC(Q^M) = 15$**: The cost of producing the 30th unit
- **Difference = 30**: The surplus that could be created from the 30th unit but is lost due to monopoly restriction

---

## **Alternative Calculation Methods**

### **Integration Approach**
The welfare loss can also be calculated by integrating the difference between willingness to pay and marginal cost:

$$WL = \int_{Q^M}^{Q^*} [p(Q) - MC(Q)] \, dQ = \int_{30}^{50} [(75-Q) - \frac{1}{2}Q] \, dQ$$

$$= \int_{30}^{50} (75 - \frac{3}{2}Q) \, dQ = [75Q - \frac{3}{4}Q^2]_{30}^{50} = 300$$

This confirms our geometric calculation.

### **Why Not Use $p(Q^*)$?**

Some might ask why we don't use $p(Q^*) = MC(Q^*) = 25$ in the calculation. If we tried:

$$WL_{incorrect} = \frac{1}{2} \times (Q^* - Q^M) \times (p(Q^M) - p(Q^*)) = \frac{1}{2} \times 20 \times (45-25) = 200$$

This is wrong because:
1. **$p(Q^*) = MC(Q^*)$** by definition at competitive equilibrium
2. **The height should be measured vertically** at a single quantity point, not between different quantity points
3. **$p(Q^M) - p(Q^*)$** represents the price difference between two different quantities, not the surplus per unit at any specific quantity

> **Yes, we can substitute** $p(Q^*) = MC(Q^*)$ because they're identical at competitive equilibrium.
> 
> **But we don't substitute in the welfare loss formula** because the formula specifically needs $MC(Q^M)$, not $MC(Q^*)$.
> 
> The welfare loss formula is:
> $$WL = \frac{1}{2} \times (Q^* - Q^M) \times (p(Q^M) - MC(Q^M))$$
> 
> We need $MC(Q^M) = MC(30) = 15$, not $MC(Q^*) = MC(50) = 25$.
> 
> The substitution $p(Q^*) = MC(Q^*)$ is valid, but it doesn't help us because we need the marginal cost at the monopoly quantity ($Q^M$), not at the competitive quantity ($Q^*$).
> 
> So the issue isn't that $p(Q^*) \neq MC(Q^*)$ - they are equal. The issue is that we need $MC$ evaluated at $Q^M$, not at $Q^*$.


---

## **Economic Interpretation**

The welfare loss of 300 represents:
- **Lost consumer surplus**: Consumers who would have bought units 31-50 at prices between 45 and 25, but can't because the monopolist restricts output
- **Lost producer surplus**: The monopolist could profitably produce units 31-50 (since price exceeds marginal cost for these units) but chooses not to maximize short-term profits
- **Pure inefficiency**: This surplus is lost to society entirely, not transferred between groups

---

## **Key Assumptions**

- **Linear demand and marginal cost curves**: Ensures the welfare loss region is triangular
- **No externalities**: The only market failure is monopoly pricing
- **Single-price monopoly**: The monopolist charges the same price to all consumers
- **No fixed costs in welfare calculation**: Fixed costs don't affect the marginal analysis of welfare loss

---

## **Summary**

The formula $WL = \frac{1}{2} \cdot (Q^* - Q^M) \cdot (p(Q^M) - MC(Q^M))$ correctly calculates deadweight loss because:

1. **It measures the right triangle**: The area between demand and marginal cost curves from $Q^M$ to $Q^*$
2. **It uses the correct height**: $p(Q^M) - MC(Q^M)$ is the vertical distance between curves at the monopoly quantity
3. **It reflects economic reality**: Each unit between $Q^M$ and $Q^*$ has value exceeding its production cost, representing genuine welfare loss

The calculation yields $WL = 300$, representing the total surplus lost due to monopoly output restriction.