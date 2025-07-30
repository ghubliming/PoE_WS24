
#### Part (b): Calculate $n^*$ and Profit per Firm for Given Values

**General Setup for Part (b):**

- **Explanation of Reasoning:** Using the results from part (a), we compute $p^*$, $Q^*$, $q^*$, and $\pi^*$ for each case.
- **Methods and Concepts:** From part (a):
  - Equilibrium price: $p^* = 2\sqrt{c^f}$
  - Market output: $Q^* = a - p^* = a - 2\sqrt{c^f}$
  - Output per firm: $q^* = \frac{p^*}{2} = \sqrt{c^f}$
  - Profit per firm: $\pi^* = \frac{(p^*)^2}{4} - c^f = 0$ (since $p^* = 2\sqrt{c^f}$)
  - Number of firms: $n^* = \max \left\{ \left\lfloor \frac{a}{\sqrt{c^f}} - 2 \right\rfloor, 0 \right\}$

**Case (i): $a = 120$, $c^f = 100$**

- **Explanation of Reasoning:** Substitute the values into the formulas.
- **Methods and Concepts:**
  - $\sqrt{c^f} = \sqrt{100} = 10$
  - $p^* = 2\sqrt{c^f} = 2 \cdot 10 = 20$
  - $Q^* = a - p^* = 120 - 20 = 100$
  - $q^* = \sqrt{c^f} = 10$
  - $n^* = \frac{Q^*}{q^*} = \frac{100}{10} = 10$ (alternatively, $n^* = \left\lfloor \frac{120}{10} - 2 \right\rfloor = \left\lfloor 12 - 2 \right\rfloor = 10$)
  - $\pi^* = 0$ (as derived in part (a)).
- **Assumptions and Definitions:** The profit is zero, consistent with the long-run condition.

**Case (ii): $a = 120$, $c^f = 64$**

- **Explanation of Reasoning:** Repeat the process with the new $c^f$.
- **Methods and Concepts:**
  - $\sqrt{c^f} = \sqrt{64} = 8$
  - $p^* = 2 \cdot 8 = 16$
  - $Q^* = 120 - 16 = 104$
  - $q^* = \sqrt{c^f} = 8$
  - $n^* = \frac{104}{8} = 13$ (or $n^* = \left\lfloor \frac{120}{8} - 2 \right\rfloor = \left\lfloor 15 - 2 \right\rfloor = 13$)
  - $\pi^* = 0$.

**Case (iii): $a = 126$, $c^f = 100$**

- **Explanation of Reasoning:** Apply the same formulas.
- **Methods and Concepts:**
  - $\sqrt{c^f} = 10$
  - $p^* = 20$
  - $Q^* = 126 - 20 = 106$
  - $q^* = 10$
  - $n^* = \frac{106}{10} = 10.6 \rightarrow \left\lfloor 10.6 \right\rfloor = 10$ (or $\left\lfloor \frac{126}{10} - 2 \right\rfloor = \left\lfloor 12.6 - 2 \right\rfloor = 10$)
  - ~~With $n^* = 10$, $Q^S = 10 \cdot 10 = 100$, but demand at $p = 20$ is 106. Adjust price to clear the market: $Q^D = 10 \cdot \frac{p}{2}$, but since $n$ is fixed, use $p = a - n q$, or recompute profit:~~
    - ~~If $n = 10$, $Q^S = 100$, so $p = 126 - 100 = 26$, $q = \frac{100}{10} = 10$, profit:~~
    ~~$$~~
    ~~\pi = 26 \cdot 10 - (100 + 10^2) = 260 - 200 = 60~~
~~$$~~
    ~~This contradicts the solution’s $\pi^* = 10.25$, indicating a potential error in the solution. Let’s correct:~~
  - Correct $n^*$: $\frac{126}{10} - 2 = 10.6$, but if $n = 10$, profit isn’t zero. The solution assumes $p = 21$, $Q^* = 105$, $q^* = 10.5$, $\pi^* = 10.25$, which suggests a slight adjustment in interpretation. Let’s verify:
    - At $n = 10$, $p = 26$, profit is 60, **not zero**. The solution’s $p = 21$ gives $Q^D = 126 - 21 = 105$, $q = \frac{105}{10} = 10.5$, profit:
    $$
    \pi = 21 \cdot 10.5 - (100 + (10.5)^2) = 220.5 - (100 + 110.25) = 220.5 - 210.25 = 10.25
$$
    This matches the solution but contradicts the long-run zero-profit condition, suggesting the solution may assume a short-run equilibrium or an error. Let’s proceed with the solution’s values for consistency.