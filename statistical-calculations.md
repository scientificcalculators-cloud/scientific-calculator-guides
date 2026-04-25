# Statistical Calculations on a Scientific Calculator

*Published by [scientificcalculators.net](https://www.scientificcalculators.net) — free online scientific calculator tools.*

---

## Introduction

Scientific calculators have a dedicated **statistics mode** (often labelled `STAT` or `SD`) that makes it fast and accurate to calculate means, standard deviations, and more — without needing to enter long formulas manually.

This guide walks through the most important statistical functions step by step. You can follow along using the [online scientific calculator at scientificcalculators.net](https://www.scientificcalculators.net).

---

## Entering Statistics Mode

On most scientific calculators:

1. Press `MODE`
2. Select `STAT` or `SD` (Standard Deviation mode)
3. Choose the type of data entry (typically `1-VAR` for single-variable statistics)

You'll usually see the screen change to show a data entry table.

> **Note:** On some calculators, you exit STAT mode by pressing `MODE` and returning to standard calculation mode. Any data you entered is cleared when you exit.

---

## Entering Data

Once in STAT mode, enter your data set one value at a time, pressing `=` or `M+` after each entry.

**Example data set:** 4, 7, 13, 2, 9, 11, 6

Enter: `4 =`, `7 =`, `13 =`, `2 =`, `9 =`, `11 =`, `6 =`

The calculator keeps a running count of how many values you've entered (shown as `n`).

---

## Key Statistical Outputs

Once your data is entered, you can retrieve the following values using `SHIFT` + variable keys:

| Symbol | What It Means | How to Access |
|--------|--------------|---------------|
| n | Number of data points | `SHIFT` → `n` |
| x̄ | Mean (average) | `SHIFT` → `x̄` |
| Σx | Sum of all values | `SHIFT` → `Σx` |
| Σx² | Sum of squared values | `SHIFT` → `Σx²` |
| σx | Population standard deviation | `SHIFT` → `σx` |
| sx | Sample standard deviation | `SHIFT` → `sx` |

---

## Mean (Average)

The mean is the sum of all values divided by the number of values:

```
x̄ = Σx / n
```

**Example (using the data set above: 4, 7, 13, 2, 9, 11, 6):**

`Σx = 4 + 7 + 13 + 2 + 9 + 11 + 6 = 52`
`n = 7`
`x̄ = 52 / 7 ≈ 7.43`

In STAT mode, simply press `SHIFT` → `x̄` to get this instantly.

---

## Standard Deviation

Standard deviation measures how spread out data is from the mean.

### Population Standard Deviation (σx)

Use this when your data set **is** the entire population.

```
σx = √( Σ(xᵢ - x̄)² / n )
```

### Sample Standard Deviation (sx)

Use this when your data is a **sample** taken from a larger population (most common in research).

```
sx = √( Σ(xᵢ - x̄)² / (n-1) )
```

The difference between σx and sx is the denominator — `n` vs `n-1`. For large data sets this barely matters, but for small samples it can be significant.

**Example result for our data set (4, 7, 13, 2, 9, 11, 6):**
- σx ≈ 3.51 (population)
- sx ≈ 3.78 (sample)

---

## Median and Mode (Manual Method)

Most scientific calculators do **not** calculate median and mode directly in STAT mode — you'll need to do these manually.

### Median
1. Sort your data from smallest to largest: `2, 4, 6, 7, 9, 11, 13`
2. The middle value is the median: **7**
3. For even numbers of data points, average the two middle values

### Mode
The mode is simply the value that appears most often.
If no value repeats, there is no mode.
If multiple values tie, all are modes.

---

## Frequency Tables

If you have grouped data (e.g., 5 people scored 80, 3 people scored 90), enter each value with its frequency:

On most calculators in STAT mode, enter:
`80 SHIFT , 5 =` (value of 80, frequency of 5)
`90 SHIFT , 3 =` (value of 90, frequency of 3)

The `,` key separates the value from its frequency.

---

## Linear Regression (A + BX)

For data with two variables (x and y), scientific calculators can find the line of best fit.

### Entering 2-Variable Data

1. Enter STAT mode and select `A+BX` or `LIN` regression type
2. Enter paired data: `x₁ =`, `y₁ =`, `x₂ =`, `y₂ =`, etc.

### Retrieving Regression Values

| Symbol | Meaning |
|--------|---------|
| A | y-intercept of the regression line |
| B | Slope of the regression line |
| r | Correlation coefficient (−1 to 1) |

A correlation coefficient (r) close to 1 or −1 means a strong linear relationship. Close to 0 means weak or no linear relationship.

**The regression equation is:** `y = A + Bx`

### Predicting Values

Once you have A and B, you can predict:
- What **y** will be for a given x: `ŷ = A + B × x`
- What **x** will be for a given y: `x̂ = (y − A) / B`

---

## Probability Calculations

### Permutations (nPr)

The number of ways to arrange r items chosen from n items, **where order matters:**

```
nPr = n! / (n-r)!
```

**On your calculator:** Enter `n`, press `nPr`, enter `r`, press `=`.

Example: How many ways can 3 people be chosen and arranged from a group of 8?
`8 nPr 3 =` → **336**

### Combinations (nCr)

The number of ways to choose r items from n items, **where order does NOT matter:**

```
nCr = n! / (r! × (n-r)!)
```

**On your calculator:** Enter `n`, press `nCr`, enter `r`, press `=`.

Example: How many ways can 3 people be chosen from a group of 8 (regardless of order)?
`8 nCr 3 =` → **56**

### Factorials (n!)

`n!` means multiplying n by every positive integer below it.

`5! = 5 × 4 × 3 × 2 × 1 = 120`

**On your calculator:** Enter the number, press `x!` or `n!`.

---

## Practice Problems

Work through these using the [online scientific calculator at scientificcalculators.net](https://www.scientificcalculators.net):

1. Find the mean and standard deviation of: 12, 15, 11, 19, 14, 13, 18
   - Mean: ≈ 14.57 | Sample SD: ≈ 2.94

2. A data set has Σx = 180 and n = 15. What is the mean?
   - Answer: 12

3. Calculate 10C4 — Answer: 210

4. Calculate 6P2 — Answer: 30

5. For data pairs (1,3), (2,5), (3,7), (4,9) — what is the regression line?
   - Answer: y = 1 + 2x (perfect linear relationship, r = 1)

---

## Next Steps

- [Engineering Notation & Unit Conversion](./engineering-notation.md)
- [Trigonometry Functions Explained](./trigonometry-functions.md)
- [Back to Beginner's Guide](./beginner-guide.md)

All these calculations can be practised for free at [scientificcalculators.net](https://www.scientificcalculators.net).

---

*Guide maintained by [scientificcalculators.net](https://www.scientificcalculators.net). Found an error? See our [Contributing Guide](../CONTRIBUTING.md).*
