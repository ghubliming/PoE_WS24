# Part (b): Equilibrium Number of Firms and Profit Calculations

## Economic Logic and Formula Selection

**The Fundamental Question**: How many firms can the market support in long-run equilibrium?

**Core Economic Principle**: In perfect competition's long run, firms earn exactly zero economic profit. If firms make positive profits, new competitors enter (increasing supply, lowering prices). If firms lose money, some exit (reducing supply, raising prices). The market gravitates toward zero-profit equilibrium.

**Why the Floor Function Formula**: $n^* = \max\left\{\left\lfloor\frac{a}{\sqrt{c^f}} - 2\right\rfloor, 0\right\}$

This captures a critical real-world constraint: **you cannot have fractional firms**. If the "perfect" number were 10.6 firms, we can only have 10 actual firms. The market settles at 10 firms with slightly positive profits rather than perfect zero profits.

**[[Alternative Equilibrium Formulas and Economic (SS25-PoE_Retake-4)]] Meaning**:

- **Price**: $p^* = \frac{2a}{n^* + 2}$ - Price depends on market size ($a$) and competition intensity. More firms → lower prices.
- **Market quantity**: $Q^* = \frac{an^*}{n^* + 2}$ - Total market output
- **Output per firm**: $q^* = \frac{a}{n^* + 2}$ - Each firm's market share shrinks as competitors enter
- **Profit per firm**: $\pi^* = \frac{a^2}{(n^* + 2)^2} - c^f$ - Shows why integer constraints matter for profits

## Case (i): $a = 120$, $c^f = 100$

**Step 1**: Find $n^*$
$$n^* = \left\lfloor\frac{120}{\sqrt{100}} - 2\right\rfloor = \left\lfloor\frac{120}{10} - 2\right\rfloor = \lfloor 12 - 2 \rfloor = 10$$

**Step 2**: Calculate equilibrium values with $n^* = 10$
- $p^* = \frac{2 \times 120}{10 + 2} = \frac{240}{12} = 20$
- $Q^* = \frac{120 \times 10}{12} = \frac{1200}{12} = 100$
- $q^* = \frac{120}{12} = 10$
- $\pi^* = \frac{120^2}{12^2} - 100 = \frac{14400}{144} - 100 = 100 - 100 = 0$

**Answer**: $n^* = 10$ firms, $\pi^* = 0$ per firm *(Perfect competitive equilibrium - integer constraint doesn't bind)*

## Case (ii): $a = 120$, $c^f = 64$

**Step 1**: Find $n^*$
$n^* = \left\lfloor\frac{120}{\sqrt{64}} - 2\right\rfloor = \left\lfloor\frac{120}{8} - 2\right\rfloor = \lfloor 15 - 2 \rfloor = 13$

**Step 2**: Calculate equilibrium values with $n^* = 13$
- $p^* = \frac{2 \times 120}{13 + 2} = \frac{240}{15} = 16$
- $Q^* = \frac{120 \times 13}{15} = \frac{1560}{15} = 104$
- $q^* = \frac{120}{15} = 8$
- $\pi^* = \frac{120^2}{15^2} - 64 = \frac{14400}{225} - 64 = 64 - 64 = 0$

**Answer**: $n^* = 13$ firms, $\pi^* = 0$ per firm *(Perfect competitive equilibrium - integer constraint doesn't bind)*

## Case (iii): $a = 126$, $c^f = 100$

**Step 1**: Find $n^*$
$n^* = \left\lfloor\frac{126}{\sqrt{100}} - 2\right\rfloor = \left\lfloor\frac{126}{10} - 2\right\rfloor = \lfloor 12.6 - 2 \rfloor = \lfloor 10.6 \rfloor = 10$

**Step 2**: Calculate equilibrium values with $n^* = 10$
- $p^* = \frac{2 \times 126}{10 + 2} = \frac{252}{12} = 21$
- $Q^* = \frac{126 \times 10}{12} = \frac{1260}{12} = 105$
- $q^* = \frac{126}{12} = 10.5$
- $\pi^* = \frac{126^2}{12^2} - 100 = \frac{15876}{144} - 100 = 110.25 - 100 = 10.25$

**Answer**: $n^* = 10$ firms, $\pi^* = 10.25$ per firm *(Market imperfection due to integer constraint - the "missing 0.6 firm" leaves remaining firms with small positive profits)*

## Economic Interpretation

**Cases (i) & (ii)**: Perfect competitive outcomes where integer constraint doesn't bind. Market achieves exact zero-profit equilibrium.
整数约束不具有约束力的完美竞争结果。市场实现了确切的零企业平衡。

**Case (iii)**: Shows real-world market limitation. Market wants 10.6 firms but can only support 10. The small profit (10.25) represents economic rent from the missing fractional firm that cannot enter. This explains why some competitive industries have persistent small profits despite no barriers to entry.
显示现实世界中的市场限制。市场需要10.6家公司，但只能支持10。少量利润（10.25）代表了无法进入的缺失分数公司的经济租金。这就解释了为什么一些竞争行业尽管没有进入障碍，但仍有持续的少量利润。