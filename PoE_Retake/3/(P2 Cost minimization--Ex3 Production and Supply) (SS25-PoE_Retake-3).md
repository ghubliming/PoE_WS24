Let’s solve this cost-minimization problem step by step.

---

### Given:
- Production function: $q = F(L, K) = (L \cdot K)^{\frac{1}{2}}$
- Output constraint: $q = 100$
- Initial wage rate for labor: $w = 2.5$
- Rental rate for capital: $r = 2.5$

#### Part (a): Determine the cost-minimizing input bundle and depict it in a diagram.

1. **Set up the production constraint:**
   $$
   q = (L \cdot K)^{\frac{1}{2}} = 100
$$
   Square both sides:
   $$
   L \cdot K = 100^2 = 10000
$$
   So, $K = \frac{10000}{L}$.

2. **Cost function:**
   The total cost is:
   $$
   C = wL + rK = 2.5L + 2.5K
$$

3. **Substitute $K$:**
   $$
   K = \frac{10000}{L}
$$
   So the cost function becomes:
   $$
   C = 2.5L + 2.5 \left(\frac{10000}{L}\right) = 2.5L + \frac{25000}{L}
$$

4. **Minimize the cost:**
   *Take the derivative of $C$ with respect to $L$ and set it to zero:*
[[here why choose L (Part (a) Determine the cost-minimizing input bundle and depict it in a diagram.(P2 Cost minimization--Ex3 Production and Supply)) (SS25-PoE_Retake-3)]]
   $$
   \frac{dC}{dL} = 2.5 - \frac{25000}{L^2} = 0
$$
   $$
   2.5 = \frac{25000}{L^2}
$$
   $$
   L^2 = \frac{25000}{2.5} = 10000
$$
   $$
   L = \sqrt{10000} = 100
$$

5. **Find $K$:**
   $$
   K = \frac{10000}{L} = \frac{10000}{100} = 100
$$

6. **Cost-minimizing bundle:**
   The cost-minimizing input bundle is $(L, K) = (100, 100)$.

7. **Total cost:**
   $$
   C = 2.5 \times 100 + 2.5 \times 100 = 250 + 250 = 500
$$

8. **Depict in a diagram:**
   - Plot $L$ on the x-axis and $K$ on the y-axis.
   - The isoquant is $L \cdot K = 10000$, a hyperbola.
   - The isocost line is $2.5L + 2.5K = 500$, or $K = 200 - L$.
   - The tangency point is at $(L, K) = (100, 100)$.

   Since I cannot generate images directly, the diagram would show the isoquant $L \cdot K = 10000$ and the isocost line tangent at $(100, 100)$. If you'd like a visual, I can confirm if you'd like me to generate one!

---

#### Part (b): Wage rate rises to $w = 10$, while $r = 2.5$.

##### (i) Effect on input costs if the same input bundle $(L, K) = (100, 100)$ is employed:
- Original cost with $w = 2.5$, $r = 2.5$:
  $$
  C = 2.5 \times 100 + 2.5 \times 100 = 500
$$
- New cost with $w = 10$, $r = 2.5$:
  $$
  C_{\text{new}} = 10 \times 100 + 2.5 \times 100 = 1000 + 250 = 1250
$$
- **Increase in cost:**
  $$
  1250 - 500 = 750
$$

So, the cost increases by 750 if the same bundle is used.

##### (ii) Effect on the cost-minimizing input bundle:
1. **New cost function with $w = 10$, $r = 2.5$:**
   $$
   C = 10L + 2.5K
$$
   Substitute $K = \frac{10000}{L}$:
   $$
   C = 10L + 2.5 \left(\frac{10000}{L}\right) = 10L + \frac{25000}{L}
$$

2. **Minimize the new cost:**
   Take the derivative with respect to $L$:
   $$
   \frac{dC}{dL} = 10 - \frac{25000}{L^2} = 0
$$
   $$
   10 = \frac{25000}{L^2}
$$
   $$
   L^2 = \frac{25000}{10} = 2500
$$
   $$
   L = \sqrt{2500} = 50
$$

3. **Find $K$:**
   $$
   K = \frac{10000}{L} = \frac{10000}{50} = 200
$$

4. **New cost-minimizing bundle:**
   $(L, K) = (50, 200)$.

5. **New total cost:**
   $$
   C = 10 \times 50 + 2.5 \times 200 = 500 + 500 = 1000
$$

6. **Cost increase compared to original cost:**
   Original cost was 500, new cost is 1000:
   $$
   1000 - 500 = 500
$$

So, with the new cost-minimizing bundle, the cost increases by 500.

---

### Summary:
- **(a)** Cost-minimizing bundle: $(L, K) = (100, 100)$, total cost = 500. Diagram shows isoquant and isocost tangent at this point.
- **(b)(i)** If the same bundle is used, cost increases by 750 (from 500 to 1250).
- **(b)(ii)** New cost-minimizing bundle: $(L, K) = (50, 200)$, cost increases by 500 (from 500 to 1000).