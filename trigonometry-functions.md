# Trigonometry Functions on a Scientific Calculator

*Published by [scientificcalculators.net](https://www.scientificcalculators.net) — free online scientific calculator tools.*

---

## Introduction

Trigonometry is one of the core reasons students and professionals reach for a scientific calculator. The trig functions — sine, cosine, and tangent — are used in everything from geometry and physics to engineering and navigation.

This guide explains exactly how to use trig functions on a scientific calculator, covering degrees vs radians, inverse functions, and common mistakes to avoid. Follow along using the free calculator at [scientificcalculators.net](https://www.scientificcalculators.net).

---

## The Three Core Functions

### Sine (sin)

The sine of an angle in a right-angled triangle is:

```
sin(θ) = Opposite / Hypotenuse
```

**On your calculator:** Press `sin`, then enter the angle, then `=`.

Example: `sin(30°)` = 0.5

### Cosine (cos)

The cosine of an angle is:

```
cos(θ) = Adjacent / Hypotenuse
```

**On your calculator:** Press `cos`, then enter the angle, then `=`.

Example: `cos(60°)` = 0.5

### Tangent (tan)

The tangent of an angle is:

```
tan(θ) = Opposite / Adjacent = sin(θ) / cos(θ)
```

**On your calculator:** Press `tan`, then enter the angle, then `=`.

Example: `tan(45°)` = 1

---

## Degrees vs Radians — The Most Important Setting

This is the single most common source of errors when using trig functions on a calculator.

**Always check your angle mode before using sin, cos, or tan.**

| Mode | Full Circle | Quarter Circle | Common Use |
|------|------------|----------------|-----------|
| Degrees (DEG) | 360° | 90° | School maths, everyday use |
| Radians (RAD) | 2π ≈ 6.283 | π/2 ≈ 1.571 | University, physics, calculus |

### Key Values to Memorise

| Angle (DEG) | Angle (RAD) | sin | cos | tan |
|------------|------------|-----|-----|-----|
| 0° | 0 | 0 | 1 | 0 |
| 30° | π/6 | 0.5 | √3/2 ≈ 0.866 | 1/√3 ≈ 0.577 |
| 45° | π/4 | √2/2 ≈ 0.707 | √2/2 ≈ 0.707 | 1 |
| 60° | π/3 | √3/2 ≈ 0.866 | 0.5 | √3 ≈ 1.732 |
| 90° | π/2 | 1 | 0 | undefined |

### Converting Between Degrees and Radians

```
Radians = Degrees × (π / 180)
Degrees = Radians × (180 / π)
```

**Example:** Convert 45° to radians:
`45 × (π ÷ 180) = 0.7854 radians`

---

## Inverse Trig Functions (sin⁻¹, cos⁻¹, tan⁻¹)

Inverse functions go the other way — they take a ratio and give you the angle.

| Function | Also Written As | Finds |
|----------|----------------|-------|
| sin⁻¹ | arcsin | The angle whose sine is x |
| cos⁻¹ | arccos | The angle whose cosine is x |
| tan⁻¹ | arctan | The angle whose tangent is x |

**On your calculator:** Press `SHIFT` or `2nd`, then press `sin` (which now shows `sin⁻¹`), then enter your value.

### Example

A right-angled triangle has an opposite side of 5 and a hypotenuse of 10. What is the angle?

```
sin(θ) = 5/10 = 0.5
θ = sin⁻¹(0.5) = 30°
```

On your calculator (in DEG mode):
→ `SHIFT` → `sin` → `0.5` → `=` → **30°**

---

## The Pythagorean Identity

One of the most important trig identities to verify on your calculator:

```
sin²(θ) + cos²(θ) = 1
```

This holds true for **any** angle. You can verify this easily:

Try `sin(37)² + cos(37)² =` → Result should be exactly **1**.

If you get something other than 1, you've made a mistake in your calculation.

---

## Reciprocal Functions

Your calculator may not have dedicated keys for these, but you can calculate them easily:

| Function | Definition | Calculator Method |
|----------|-----------|------------------|
| cosecant (csc) | 1 / sin(θ) | `1 ÷ sin(θ)` |
| secant (sec) | 1 / cos(θ) | `1 ÷ cos(θ)` |
| cotangent (cot) | 1 / tan(θ) | `1 ÷ tan(θ)` |

**Example:** Calculate csc(30°):
`1 ÷ sin(30) =` → **2**

---

## Solving Right-Angled Triangles

### Finding a Side Length

**Problem:** A ladder leans against a wall. The ladder is 5m long and makes a 70° angle with the ground. How high up the wall does it reach?

We need the opposite side (height), given the hypotenuse (5m) and the angle (70°).

```
sin(70°) = height / 5
height = 5 × sin(70°)
```

Calculator: `5 × sin(70) =` → **4.698m**

### Finding an Angle

**Problem:** A ramp rises 2m over a horizontal distance of 8m. What is the angle of the ramp?

```
tan(θ) = 2 / 8 = 0.25
θ = tan⁻¹(0.25)
```

Calculator: `SHIFT tan(0.25) =` → **14.04°**

---

## Trig Functions with Complex Expressions

When using trig functions inside larger calculations, use parentheses carefully.

**Wrong:** `sin 45 + cos 45 × 2`
Calculator might interpret this as `sin(45) + (cos(45) × 2)`

**Right:** `(sin(45) + cos(45)) × 2` — if that's what you intend

Always be explicit with your brackets to avoid ambiguity.

---

## Practice Problems

Work through these using the [online scientific calculator at scientificcalculators.net](https://www.scientificcalculators.net):

1. Calculate `cos(120°)` — Answer: −0.5
2. Calculate `tan⁻¹(1)` in degrees — Answer: 45°
3. Find the hypotenuse of a right triangle with opposite = 7, angle = 35° — Answer: ≈ 12.2
4. Verify: `sin²(55°) + cos²(55°)` — Answer: 1
5. Convert 3π/4 radians to degrees — Answer: 135°

---

## Common Mistakes

| Mistake | Fix |
|---------|-----|
| Wrong angle mode (DEG vs RAD) | Always check mode before starting |
| Using − instead of ⁻¹ for inverse | Use SHIFT + sin/cos/tan |
| Missing parentheses | Be explicit with every bracket |
| tan(90°) giving an error | tan(90°) is mathematically undefined |

---

## Next Steps

- [Statistical Calculations](./statistical-calculations.md)
- [Engineering Notation & Unit Conversion](./engineering-notation.md)
- [Back to Beginner's Guide](./beginner-guide.md)

Practise all these functions for free at [scientificcalculators.net](https://www.scientificcalculators.net).

---

*Guide maintained by [scientificcalculators.net](https://www.scientificcalculators.net). Found an error? See our [Contributing Guide](../CONTRIBUTING.md).*
