In the cost-minimization process, we take the derivative with respect to $L$ because we substituted $K = \frac{10000}{L}$ (from the production constraint $L \cdot K = 10000$) into the cost function, making it a function of $L$ only: $C = wL + r \left(\frac{10000}{L}\right)$. This allows us to minimize $C$ by finding the optimal $L$, then back-solving for $K$.

You can also take the derivative with respect to $K$ if you rewrite the constraint as $L = \frac{10000}{K}$ and substitute into the cost function: $C = w \left(\frac{10000}{K}\right) + rK$. Then, differentiate with respect to $K$:

For the original case ($w = 2.5$, $r = 2.5$):
$$
C = 2.5 \left(\frac{10000}{K}\right) + 2.5K
$$
$$
\frac{dC}{dK} = 2.5 \left(-\frac{10000}{K^2}\right) + 2.5 = 0
$$
$$
-\frac{10000}{K^2} + 1 = 0 \implies K^2 = 10000 \implies K = 100
$$
Then, $L = \frac{10000}{K} = 100$, which matches the earlier result.

The two approaches are equivalent because the production function and cost constraint are symmetric in $L$ and $K$, and the prices $w$ and $r$ are initially equal. Both methods exploit the constraint to reduce the problem to one variable, leading to the same solution. However, if $w \neq r$, the numerical results will adjust, but the methods remain equivalent in structure.
