
Let’s dive into this problem about a profit-maximizing firm with a monopoly on selling sparkling wine at the Bavarian State Opera. The problem has two parts: (a) finding the firm’s maximum willingness to pay for the exclusive right to sell during one opera season, and (b) determining how this willingness changes if the city of Munich imposes a tax on the seller. Let’s break it down and solve it step by step, following the solution provided in the image while explaining the reasoning, methods, concepts, assumptions, and definitions along the way.

---

### Step 1: Understand What the Question is Asking

#### Part (a): Determine the Firm’s Maximum Willingness to Pay
The firm has a monopoly on selling sparkling wine at the opera, meaning it’s the only seller and can set the price to maximize profit. The variable cost of selling $Q$ servings of sparkling wine is given as $c(Q) = 2Q$, and the market demand per opera season is $Q^D(p) = 10,000 - 1,000p$, where $p$ is the price per serving and $Q \geq 0$. The firm also faces a quasi-fixed cost $c^f$, which is the payment for the exclusive right to sell. If the firm is awarded the contract, its total cost is $C(Q) = c^f + 2Q$. The firm wants to maximize its profit, and we need to find the maximum amount $c^f$ it is willing to pay for this right, assuming it must at least break even (i.e., profit is non-negative).

#### Part (b): Impact of a Tax on the Maximum Willingness to Pay
The city of Munich levies a tax on the seller of sparkling wine, and we need to see how this affects the firm’s maximum willingness to pay for the exclusive right. The tax is applied in two scenarios:
- (i) A tax of $t = 2$ per unit sold.
- (ii) A tax of $t = 0.25$ on the firm’s profit.

For each scenario, we need to recalculate the maximum $c^f$ the firm is willing to pay.

---

### Step 2: Solve Part (a) – Maximum Willingness to Pay Without Tax

#### Step 2.1: Derive the Revenue Function
The demand function is given as $Q^D(p) = 10,000 - 1,000p$. To work with quantities, we need the inverse demand function, which expresses price as a function of quantity:
$$
p(Q) = 10 - \frac{1}{1,000}Q
$$
- **Reasoning:** The inverse demand function is needed because the firm, as a monopolist, chooses the quantity $Q$ to maximize profit, and the price $p$ will adjust according to the demand curve.
- **Methods and Concepts:** This is a standard linear demand function. Solving $Q = 10,000 - 1,000p$ for $p$, we divide through by 1,000 and rearrange: $p = 10 - \frac{Q}{1,000}$.
- **Assumptions and Definitions:** We assume $Q \geq 0$, as negative quantities don’t make sense in this context. The demand function implies that at $p = 0$, $Q = 10,000$, and at $p = 10$, $Q = 0$.

Now, the firm’s revenue $R(Q) = p(Q) \cdot Q$:
$$
R(Q) = \left(10 - \frac{1}{1,000}Q\right)Q = 10Q - \frac{1}{1,000}Q^2
$$
- **Reasoning:** Revenue is price times quantity. Substituting the inverse demand function into the revenue formula gives us a quadratic function of $Q$.
- **Methods and Concepts:** Basic revenue calculation for a monopolist, using the price function derived from demand.

#### Step 2.2: Set Up the Profit Maximization Problem
The firm’s total cost is $C(Q) = c^f + 2Q$. The profit function $\pi(Q)$ is revenue minus total cost:
$$
\pi(Q) = R(Q) - C(Q) = \left(10Q - \frac{1}{1,000}Q^2\right) - (c^f + 2Q) = 10Q - \frac{1}{1,000}Q^2 - c^f - 2Q
$$
Simplify:
$$
\pi(Q) = 8Q - \frac{1}{1,000}Q^2 - c^f
$$
- **Reasoning:** Profit is revenue minus all costs. The variable cost $2Q$ is subtracted from the revenue, and $c^f$ is a fixed cost that doesn’t affect the quantity choice but impacts the overall profit.
- **Methods and Concepts:** Standard profit function setup for a monopolist.
- **Assumptions and Definitions:** $c^f$ is a quasi-fixed cost, meaning it’s incurred only if the firm operates (i.e., if $Q > 0$). If the firm doesn’t sell anything ($Q = 0$), it avoids $c^f$.

#### Step 2.3: Maximize Profit with Respect to Quantity
To find the profit-maximizing quantity, take the derivative of $\pi(Q)$ with respect to $Q$ and set it to zero:
$$
\frac{d\pi(Q)}{dQ} = 8 - \frac{2}{1,000}Q = 8 - \frac{1}{500}Q
$$
Set the derivative equal to zero:
$$
8 - \frac{1}{500}Q = 0 \implies \frac{1}{500}Q = 8 \implies Q = 8 \cdot 500 = 4,000
$$
So, the monopoly quantity is $Q^M = 4,000$.
- **Reasoning:** The monopolist maximizes profit where marginal revenue equals marginal cost. The derivative of profit with respect to $Q$ gives the marginal profit, and setting it to zero finds the optimal quantity.
- **Methods and Concepts:** Marginal analysis. The derivative of revenue $R(Q) = 10Q - \frac{1}{1,000}Q^2$ is $MR = 10 - \frac{2}{1,000}Q$, and the marginal cost $MC = \frac{d}{dQ}(2Q) = 2$. Equating $MR = MC$ would give the same result, but here we directly maximize profit.
- **Assumptions and Definitions:** We assume the second derivative is negative to confirm a maximum: $\frac{d^2\pi}{dQ^2} = -\frac{1}{500} < 0$, which it is, so $Q = 4,000$ is indeed a maximum.

#### Step 2.4: Calculate the Monopoly Price and Profit
Substitute $Q^M = 4,000$ into the inverse demand function to find the price:
$$
p^M = 10 - \frac{1}{1,000}(4,000) = 10 - 4 = 6
$$
Now, calculate the profit at this quantity:
$$
\pi^M = 8(4,000) - \frac{1}{1,000}(4,000)^2 - c^f = 32,000 - \frac{1}{1,000}(16,000,000) - c^f = 32,000 - 16,000 - c^f = 16,000 - c^f
$$
- **Reasoning:** The price is determined by the demand curve at the optimal quantity. Profit is then computed by plugging $Q^M$ into the profit function.
- **Methods and Concepts:** Substitution into the inverse demand and profit functions.

#### Step 2.5: Determine the Maximum Willingness to Pay
The firm is willing to pay for the exclusive right as long as its profit is non-negative ($\pi^M \geq 0$):
$$
16,000 - c^f \geq 0 \implies c^f \leq 16,000
$$
Thus, the maximum willingness to pay is $c^f = 16,000$.
- **Reasoning:** The maximum willingness to pay is the value of $c^f$ that makes profit exactly zero, as the firm will not pay more than what allows it to break even.
- **Methods and Concepts:** Break-even analysis for a monopolist.
- **Assumptions and Definitions:** We assume the firm will participate if profit is at least zero. “Willingness to pay” here means the highest $c^f$ the firm can afford while still breaking even.

---

### Step 3: Solve Part (b) – Impact of Taxes on Maximum Willingness to Pay

#### Part (b)(i): Tax of $t = 2$ Per Unit Sold
A tax of $t = 2$ per unit sold adds to the variable cost. The new variable cost becomes $2Q + tQ = 2Q + 2Q = 4Q$. The total cost is now:
$$
C(Q) = c^f + 4Q
$$
The profit function becomes:
$$
\pi(Q) = 10Q - \frac{1}{1,000}Q^2 - c^f - 4Q = 6Q - \frac{1}{1,000}Q^2 - c^f
$$
- **Reasoning:** The tax increases the cost per unit, which affects the profit function by increasing the variable cost coefficient.
- **Methods and Concepts:** Adjusting the cost function to include a per-unit tax.

Maximize the new profit function:
$$
\frac{d\pi(Q)}{dQ} = 6 - \frac{1}{500}Q = 0 \implies \frac{1}{500}Q = 6 \implies Q = 6 \cdot 500 = 3,000
$$
So, $Q^M = 3,000$.
- **Reasoning:** The tax increases the marginal cost, so the firm produces less to maximize profit.
- **Methods and Concepts:** Same marginal analysis as before, but with a higher marginal cost ($MC = 4$).

Find the new monopoly price:
$$
p^M = 10 - \frac{1}{1,000}(3,000) = 10 - 3 = 7
$$
Calculate the profit:
$$
\pi^M = 6(3,000) - \frac{1}{1,000}(3,000)^2 - c^f = 18,000 - 9,000 - c^f = 9,000 - c^f
$$
Set profit to zero to find the maximum $c^f$:
$$
9,000 - c^f \geq 0 \implies c^f \leq 9,000
$$
Thus, the maximum willingness to pay is $c^f = 9,000$.
- **Reasoning:** The tax reduces the firm’s profit, so it’s willing to pay less for the exclusive right.
- **Methods and Concepts:** Same break-even analysis as in part (a).

#### Part (b)(ii): Tax of $t = 0.25$ on Profit
A tax of 25% on profit means the firm keeps $1 - t = 0.75$ of its profit after tax. The profit before tax is the same as in part (a):
$$
\pi(Q) = 8Q - \frac{1}{1,000}Q^2 - c^f
$$
The after-tax profit is:
$$
\pi_{\text{after tax}}(Q) = (1 - 0.25) \left( 8Q - \frac{1}{1,000}Q^2 - c^f \right) = 0.75 \left( 8Q - \frac{1}{1,000}Q^2 - c^f \right)
$$
Maximize this with respect to $Q$:
$$
\frac{d}{dQ} \left[ 0.75 \left( 8Q - \frac{1}{1,000}Q^2 - c^f \right) \right] = 0.75 \left( 8 - \frac{1}{500}Q \right) = 0
$$
$$
8 - \frac{1}{500}Q = 0 \implies Q = 4,000
$$
The quantity $Q^M = 4,000$, which is the same as in part (a).
- **Reasoning:** A profit tax doesn’t affect the quantity decision because it scales the profit function by a constant (0.75), which doesn’t change the point where the derivative is zero.
- **Methods and Concepts:** Profit taxes don’t affect marginal decisions in this context, a standard result in microeconomics.

The price is the same as in part (a): $p^M = 6$. The profit before tax is:
$$
\pi^M = 16,000 - c^f
$$
After-tax profit:
$$
\pi_{\text{after tax}}^M = 0.75 (16,000 - c^f)
$$
Set after-tax profit to zero:
$$
0.75 (16,000 - c^f) \geq 0 \implies 16,000 - c^f \geq 0 \implies c^f \leq 16,000
$$
So, the maximum willingness to pay is $c^f = 16,000$, the same as in part (a).
- **Reasoning:** The profit tax reduces the firm’s after-tax profit, but the willingness to pay is defined by the break-even point, which remains the same because $Q$ doesn’t change.
- **Methods and Concepts:** Break-even analysis with a profit tax.
- **Assumptions and Definitions:** The problem’s wording suggests that “profit” for the tax means profit after accounting for $c^f$, which is consistent with the solution provided.

---

### Step 4: Overall Summary

- **Part (a):** The firm maximizes profit by selling $Q^M = 4,000$ servings at a price of $p^M = 6$, earning a profit of $16,000 - c^f$. The maximum willingness to pay for the exclusive right is $c^f = 16,000$, where profit is zero.
- **Part (b)(i):** With a per-unit tax of $t = 2$, the firm reduces output to $Q^M = 3,000$, sets $p^M = 7$, and earns a profit of $9,000 - c^f$. The maximum willingness to pay drops to $c^f = 9,000$.
- **Part (b)(ii):** With a 25% profit tax, the firm’s quantity and price remain $Q^M = 4,000$ and $p^M = 6$, and the maximum willingness to pay remains $c^f = 16,000$, as the profit tax doesn’t affect the quantity decision or break-even point in this context.

The solution leverages monopoly profit maximization, marginal analysis, and tax incidence principles, confirming the final answers: $c^f = 16,000$ in part (a), $c^f = 9,000$ in part (b)(i), and $c^f = 16,000$ in part (b)(ii).
