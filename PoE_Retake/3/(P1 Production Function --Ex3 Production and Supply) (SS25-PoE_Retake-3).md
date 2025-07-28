Let’s solve this step by step for the production function $q = F(L, K) = L^a K^b$, where $a \in (0,1)$, $b \in (0,1)$, $L > 0$, and $K > 0$.

---

### (a) Show that the production function exhibits positive and decreasing marginal products of both inputs.

The marginal product of an input measures the additional output from an additional unit of that input, holding the other input constant.

- **Marginal Product of Labor (MPL):**
  $$
  MPL = \frac{\partial q}{\partial L} = \frac{\partial}{\partial L} (L^a K^b) = a L^{a-1} K^b
$$
  - **Positive:** Since $a > 0$, $L > 0$, $K > 0$, and $K^b > 0$, $MPL = a L^{a-1} K^b > 0$.
  - **Decreasing:** Compute the second derivative with respect to $L$:
    $$
    \frac{\partial MPL}{\partial L} = \frac{\partial}{\partial L} (a L^{a-1} K^b) = a (a-1) L^{a-2} K^b
$$
    Since $a \in (0,1)$, $a-1 < 0$, so $a (a-1) < 0$. Also, $L^{a-2} > 0$, $K^b > 0$, so $\frac{\partial MPL}{\partial L} < 0$, meaning MPL is decreasing.

- **Marginal Product of Capital (MPK):**
  $$
  MPK = \frac{\partial q}{\partial K} = \frac{\partial}{\partial K} (L^a K^b) = L^a b K^{b-1}
$$
  - **Positive:** Since $b > 0$, $L > 0$, $K > 0$, and $L^a > 0$, $MPK = L^a b K^{b-1} > 0$.
  - **Decreasing:** Compute the second derivative with respect to $K$:
    $$
    \frac{\partial MPK}{\partial K} = \frac{\partial}{\partial K} (L^a b K^{b-1}) = L^a b (b-1) K^{b-2}
$$
    Since $b \in (0,1)$, $b-1 < 0$, so $b (b-1) < 0$. Also, $L^a > 0$, $K^{b-2} > 0$, so $\frac{\partial MPK}{\partial K} < 0$, meaning MPK is decreasing.

Thus, the production function exhibits **positive and decreasing marginal products** for both inputs.

---

### (b) Determine the conditions under which the production function exhibits constant, increasing, and decreasing returns to scale, respectively.

Returns to scale are determined by scaling both inputs by a factor $t > 0$ and observing the effect on output.

Scale inputs $L$ and $K$ by $t$:
$$
F(tL, tK) = (tL)^a (tK)^b = t^a L^a t^b K^b = t^{a+b} L^a K^b = t^{a+b} q
$$
- If $a + b = 1$, then $t^{a+b} = t^1 = t$, so $F(tL, tK) = t q$, which means **constant returns to scale**.
- If $a + b > 1$, then $t^{a+b} > t$ (for $t > 1$), so $F(tL, tK) > t q$, which means **increasing returns to scale**.
- If $a + b < 1$, then $t^{a+b} < t$ (for $t > 1$), so $F(tL, tK) < t q$, which means **decreasing returns to scale**.

Thus:
- **Constant returns to scale:** $a + b = 1$
- **Increasing returns to scale:** $a + b > 1$
- **Decreasing returns to scale:** $a + b < 1$

---

### (c) Show that the isoquants associated with the production function are strictly convex.
[[Isoquant (SS25-PoE_Retake-3)]]
An isoquant represents combinations of $L$ and $K$ that produce the same output level $q$. For $q = L^a K^b$, fix output at $\bar{q}$:
$$
L^a K^b = \bar{q}
$$
Solve for $K$ as a function of $L$:
$$
K^b = \frac{\bar{q}}{L^a} \quad \Rightarrow \quad K = \left( \frac{\bar{q}}{L^a} \right)^{1/b} = \bar{q}^{1/b} L^{-a/b}
$$
To determine convexity, compute the second derivative of $K$ with respect to $L$. First, the slope of the isoquant (marginal rate of technical substitution, MRTS):
$$
\frac{dK}{dL} = \frac{d}{dL} \left( \bar{q}^{1/b} L^{-a/b} \right) = \bar{q}^{1/b} \left( -\frac{a}{b} \right) L^{-a/b - 1}
$$
Now, the second derivative:
$$
\frac{d^2 K}{dL^2} = \frac{d}{dL} \left( \bar{q}^{1/b} \left( -\frac{a}{b} \right) L^{-a/b - 1} \right) = \bar{q}^{1/b} \left( -\frac{a}{b} \right) \left( -\frac{a}{b} - 1 \right) L^{-a/b - 2}
$$
- Since $\bar{q}^{1/b} > 0$, $-\frac{a}{b} < 0$, and $-\frac{a}{b} - 1 < 0$ (because $a/b > 0$), the term $\left( -\frac{a}{b} - 1 \right) > 0$.
- Also, $\left( -\frac{a}{b} \right) \left( -\frac{a}{b} - 1 \right) > 0$, and $L^{-a/b - 2} > 0$.

Thus, $\frac{d^2 K}{dL^2} > 0$, meaning the isoquant is **strictly convex** (it curves upward when $K$ is expressed as a function of $L$).

---

### Summary:
- (a) The production function has positive and decreasing marginal products for both $L$ and $K$.
- (b) Returns to scale: constant if $a + b = 1$, increasing if $a + b > 1$, decreasing if $a + b < 1$.
- (c) The isoquants are strictly convex.
