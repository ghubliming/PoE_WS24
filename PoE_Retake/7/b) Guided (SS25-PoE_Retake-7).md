# General Guidelines for Solving Steady-State Consumption Problems in Economic Growth Models

I understand that part (b) of the economic growth problem seems abstract and unclear. Let me provide a clear, step-by-step guideline for approaching these types of problems with detailed explanations of the economic meaning behind each step.

## The Problem Structure (Part b)
Calculate steady-state consumption per worker c* as a function of the saving rate s, given:
- A production function Y = L^(1/2) K^(1/2)
- Population growth rate n = 1/20
- Depreciation rate δ = 1/10

## Step-by-Step Guidelines with Deep Explanations

### Step 1: Identify the Steady-State Condition
**Formula:** sf(k*) = (δ + n)k*

**Economic Meaning:** 
- ==This is the fundamental equilibrium condition in the Solow growth model==
- Left side: Investment per worker (sf(k*))
- Right side: "Break-even investment" needed to maintain constant capital per worker
  - δk* replaces depreciated capital
  - nk* provides new workers with the same capital as existing workers
为新工人提供与现有工人相同的资本
- This condition means the economy has reached a long-run equilibrium ==where capital per worker== is neither increasing nor decreasing

### Step 2: Substitute the Production Function
**Formula:** Using f(k) = k^(1/2) from part (a), we get:
s(k*)^(1/2) = (δ + n)k*

**Economic Meaning:**
- ==We're using our specific production technology (Cobb-Douglas) to determine how output relates to capital==
- The exponent 1/2 indicates diminishing returns to capital accumulation - a key feature of neoclassical growth models
- Each additional unit of capital generates less additional output than the previous unit

### Step 3: Solve for Steady-State Capital per Worker (k*)
**Process:**
1. Substitute δ + n = 3/20 (or 1/20 as used in the solution)
2. Rearrange to isolate k*:
   - s(k*)^(1/2) = (1/20)k*
   - Dividing both sides by (k*)^(1/2): s = (1/20)(k*)^(1/2)
   - Rearranging: (k*)^(1/2) = 20s
   - Therefore: k* = 400s²

**Economic Meaning:**
- This equation reveals how capital accumulation depends on saving behavior
- Higher saving rates lead to higher steady-state capital levels
- The quadratic relationship (k* = 400s²) shows that capital increases at an increasing rate with the saving rate
- This relationship is determined by the specific production technology and depreciation parameters

### Step 4: Calculate Steady-State Output per Worker (y*)
**Formula:** y* = f(k*) = (k*)^(1/2) = (400s²)^(1/2) = 20s

**Economic Meaning:**
- This shows how the economy's productive capacity depends on saving behavior
- The linear relationship (y* = 20s) indicates that output grows proportionally with saving rate
- The coefficient 20 depends on technology and demographic parameters
- This relationship captures the positive impact of capital accumulation on economic output

### Step 5: Determine Steady-State Consumption per Worker (c*)
**Formula:** c* = (1-s)y* = (1-s)(20s) = 20s - 20s²

**Economic Meaning:**
- ==This equation represents the fundamental consumption-saving tradeoff==
- The first term (20s) shows how saving increases consumption by building productive capacity
- The second term (-20s²) reflects the immediate consumption sacrifice from saving
- The quadratic form reveals that excessive saving can reduce consumption (diminishing returns)
- This relationship captures the essence of intertemporal consumption choices

## Why This Approach Works

1. **Balanced Growth Path Analysis:** We're identifying long-run equilibrium where per-worker variables remain constant.

2. **Saving-Investment Dynamics:** The approach captures how saving translates into capital formation and ultimately affects consumption.

3. **Economic Trade-offs:** The final formula c* = 20s - 20s² elegantly shows the fundamental trade-off between current sacrifice (saving) and future benefit (higher productive capacity).

4. **Parameter Sensitivity:** The method reveals how demographic factors (n) and technological factors (depreciation, production function) influence economic outcomes.

5. **Mathematical Foundation for Policy:** This approach provides a rigorous basis for finding optimal policies, as you'll do in part (c) when identifying the golden-rule saving rate.

This methodology forms the core of growth theory analysis and allows economists to understand how different saving behaviors affect long-run economic well-being and living standards.
