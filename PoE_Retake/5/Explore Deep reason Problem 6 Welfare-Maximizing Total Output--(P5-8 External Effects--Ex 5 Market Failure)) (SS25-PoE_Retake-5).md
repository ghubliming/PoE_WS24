
# Deep Reason for Difference Between Individual and Collective Outcomes (Problem 6)

The fundamental cause of the difference between individual profit maximization (Problem 5) and collective welfare maximization (Problem 6) is the presence of an **externality** - a cost imposed on one party by another's actions without being reflected in market prices.

## Mathematical Explanation

When firms maximize individually, each firm i maximizes:

```
πᵢ = p·qᵢ - (15 + qᵢ²/100 + qⱼ/5)
```

Taking the derivative and setting equal to zero:

```
∂πᵢ/∂qᵢ = p - qᵢ/50 = 0
```

So each firm produces where `p = MC = qᵢ/50`

When firms maximize collectively, they maximize:

```
Π = p(qₐ+qᵦ) - (15 + qₐ²/100 + qᵦ/5) - (15 + qᵦ²/100 + qₐ/5)
```

Taking the partial derivatives:

```
∂Π/∂qₐ = p - qₐ/50 - 1/5 = 0
∂Π/∂qᵦ = p - qᵦ/50 - 1/5 = 0
```

So the collective solution produces where `p = MC + MEC = qᵢ/50 + 1/5`

## Economic Explanation

1. **Externalities create a wedge between private and social costs**: When firms decide individually, they only consider their private marginal cost (qᵢ/50), ignoring the external cost (1/5) they impose on others.

2. **Individual rationality leads to market failure**: Each firm rationally ignores costs it imposes on others, leading to overproduction (100 vs. 90 units) relative to the social optimum.
    
3. **The tragedy of the commons effect**: Each firm has an incentive to produce more because it bears only a fraction of the social cost of its actions but captures all private benefits.
    
4. **Internalization of externalities**: The collective solution forces firms to "internalize" the external effect, meaning they account for all costs their production imposes, both internal and external.

1。**外部性在私人和社会成本之间产生楔形**：当公司单独决定时，他们只考虑其私人边际成本（qᵢ/50），而忽略了他们对他人强加的外部成本（1/5）。

2。**个人合理性导致市场失败**：每个公司从理性上忽略其对他人的成本，从而导致相对于社会最佳效果而导致生产过量（100 vs. 90单位）。
    
3。**公地效应的悲剧**：每个公司都有生产更多的动机，因为它仅承担其行动的社会成本的一小部分，但可以捕获所有私人利益。
    
4。**外部性的内在化**：集体解决方案迫使公司“内部化”外部效应，这意味着它们是所有成本所施加的，无论是内部还是外部的。
    

This difference between private optimization (which ignores externalities) and social optimization (which accounts for them) is the fundamental cause of market failures and explains why individual profit maximization doesn't always lead to socially optimal outcomes.

## Why This Connection Exists

What you're observing is not coincidental. The mathematical formalism captures something fundamental about economic interactions:

1. **Mathematical representation of incentives**: The profit functions mathematically encode the incentives that each economic agent faces. The derivatives represent how these agents respond to these incentives at the margin.
    
2. **Optimization reveals behavior**: When we solve these optimization problems, we're not just manipulating symbols—we're uncovering the logical consequences of rational decision-making under specific constraints and incentives.
    
3. ==**Externalities as missing terms**: The external cost (qⱼ/5) appears in one firm's cost function but doesn't factor into their decision-making about their own production level. Mathematically, this term "disappears" in the individual's first-order condition but remains in the collective optimization.==
3。**作为缺少术语的外部性**：外部成本（qⱼ/5）出现在一家公司的成本功能中，但并没有考虑到他们对自己的生产水平的决策。从数学上讲，该术语在个人的一阶条件下“消失”，但仍在集体优化中。
    

## The Power of Formalization

What makes this particularly powerful is that once formalized mathematically:

- We can precisely quantify the gap between individual and social outcomes (10 units per firm)
- We can identify exactly what correction is needed (a tax or subsidy of 1/5)
- We can prove these results are general, not just specific to particular examples

The mathematician Alfred North Whitehead once said, "The aim of science is to seek the simplest explanations of complex facts." Economic mathematics does exactly this—it distills complex social phenomena into elegant equations that reveal the essential structure of the problem.

This is why economic theory is so powerful: the math isn't just a tool for calculation; it's a language that reveals deep truths about human interaction and coordination problems that might otherwise remain hidden or intuitive rather than precise.