# The Complete Mathematics Book
## From Counting to Graduate Mathematics — One Continuous Path

> *"Mathematics is not about numbers, equations, computations, or algorithms: it is about understanding."* — William Paul Thurston

---

## How to Use This Book

This book takes you from the very beginning (what a number is) to the doorstep of research mathematics. It is written as **one continuous staircase**: every chapter uses only what came before it.

**The rules of the road**

1. **Do not skip the exercises.** Mathematics is learned with a pencil, not with the eyes. Each chapter ends with practice problems; answers are given at the end of that chapter so you can check yourself.
2. **Go slowly in the early parts, even if they feel easy.** Many adult learners get stuck in calculus because of weak fractions or algebra. Fixing the foundation is the fastest way up.
3. **Explain each idea out loud** in your own words. If you can't explain it simply, re-read it.
4. **Use the "Checkpoint" boxes.** If you can't do a checkpoint, go back before moving on.
5. **From Part V onward, proofs matter more than answers.** You will move from *computing* to *proving*.

**Notation:** Mathematics is written in LaTeX style here, e.g. $x^2$, $\frac{a}{b}$, $\sqrt{2}$, $\int_0^1 f(x)\,dx$. Most Markdown viewers (GitHub, Obsidian, Typora, VS Code with a math extension) render these properly.

**Suggested pace (studying 1–2 hours a day)**

| Part | Level | Approx. time |
|---|---|---|
| I | Primary (Classes 1–5) | 2–4 weeks |
| II | Middle school (Classes 6–8) | 1–2 months |
| III | High school (Classes 9–12) | 4–6 months |
| IV | Calculus | 3–5 months |
| V | Undergraduate core | 1.5–2 years |
| VI | Graduate | 2+ years |
| VII | Appendices & reference | ongoing |

---

## Table of Contents

**Part I — Primary Foundations**
1. Numbers and Place Value
2. Addition and Subtraction
3. Multiplication and Division
4. Factors, Multiples, Primes
5. Fractions
6. Decimals and Percentages
7. Measurement and Basic Geometry

**Part II — Middle School Mathematics**
8. Integers (Negative Numbers)
9. Rational Numbers and Exponents
10. Ratio, Proportion and Rates
11. Introduction to Algebra
12. Linear Equations and Inequalities
13. Geometry: Angles, Triangles, Pythagoras
14. Area, Volume and Surface Area
15. Data and Basic Statistics

**Part III — High School Mathematics**
16. Real Numbers and Logic of Proof
17. Polynomials and Factorisation
18. Quadratic Equations
19. Functions and Graphs
20. Exponentials and Logarithms
21. Trigonometry
22. Coordinate Geometry and Conic Sections
23. Sequences and Series
24. Counting: Permutations, Combinations, Binomial Theorem
25. Probability
26. Complex Numbers
27. Vectors and 3D Geometry
28. Matrices and Determinants

**Part IV — Calculus**
29. Limits and Continuity
30. Differentiation
31. Applications of Derivatives
32. Integration
33. Applications of Integration
34. Infinite Series and Taylor Series
35. Multivariable Calculus
36. Ordinary Differential Equations

**Part V — Undergraduate Mathematics**
37. Logic, Sets and Proof Techniques
38. Linear Algebra
39. Real Analysis
40. Abstract Algebra
41. Discrete Mathematics and Graph Theory
42. Number Theory
43. Probability Theory and Statistics
44. Complex Analysis
45. Point-Set Topology
46. Numerical Methods

**Part VI — Graduate Mathematics**
47. Measure Theory and Lebesgue Integration
48. Functional Analysis
49. Advanced Algebra: Rings, Modules, Fields, Galois Theory
50. Differential Geometry and Manifolds
51. Algebraic Topology
52. Partial Differential Equations
53. Advanced Probability (Measure-Theoretic)
54. Gateways to Research: Algebraic Geometry, Category Theory, Representation Theory

**Part VII — Appendices**
- A. Symbols and Notation
- B. Master Formula Sheet
- C. The Greek Alphabet
- D. Recommended Books per Level
- E. A Study Plan and Self-Assessment Checklists

---

# PART I — PRIMARY FOUNDATIONS

---

## Chapter 1: Numbers and Place Value

### 1.1 What is a number?
A **number** tells us "how many" (cardinality) or "which position" (order). The **natural numbers** are the counting numbers:
$$\mathbb{N} = \{1, 2, 3, 4, \dots\}$$
Adding zero gives the **whole numbers** $\{0, 1, 2, 3, \dots\}$.

### 1.2 Place value (base 10)
We write numbers using ten digits: 0–9. The **position** of a digit gives its value.

| Ten-thousands | Thousands | Hundreds | Tens | Ones |
|---|---|---|---|---|
| 4 | 7 | 0 | 3 | 5 |

$$47{,}035 = 4\times10000 + 7\times1000 + 0\times100 + 3\times10 + 5\times1$$

This is called **expanded form**. The 0 is a *placeholder*: without it, 4735 would be a different number.

**Indian vs International system**
- Indian: 1,00,00,000 = one crore; 1,00,000 = one lakh.
- International: 10,000,000 = ten million; 100,000 = one hundred thousand.

### 1.3 Comparing and ordering
- More digits ⇒ bigger (for whole numbers): 1000 > 999.
- Same number of digits ⇒ compare from the left: 5 **8**21 > 5 **3**99.
- Symbols: $<$ (less than), $>$ (greater than), $=$ (equal).

### 1.4 Rounding
To round to the nearest 10/100/1000, look at the digit just to the right:
- 0–4 → round down; 5–9 → round up.
- 3,467 to nearest hundred → 3,500 (the tens digit is 6).

### 1.5 The number line
```
<---|----|----|----|----|----|----|--->
    0    1    2    3    4    5    6
```
Numbers increase to the right. This picture will later hold negatives, fractions, and every real number.

### Practice 1
1. Write 30,508 in expanded form.
2. Which is larger: 70,099 or 70,909?
3. Round 8,451 to the nearest thousand and to the nearest ten.
4. Write "two lakh five thousand and six" in digits.

**Answers:** 1) $3\times10000 + 0\times1000 + 5\times100 + 0\times10 + 8$ 2) 70,909 3) 8,000; 8,450 4) 2,05,006 (205,006)

---

## Chapter 2: Addition and Subtraction

### 2.1 Addition
Addition combines quantities. Key properties:
- **Commutative:** $a + b = b + a$
- **Associative:** $(a+b)+c = a+(b+c)$
- **Identity:** $a + 0 = a$

**Column addition with carrying**
```
   1 1        (carries)
   4 5 8
 + 3 7 6
 -------
   8 3 4
```
8+6 = 14 → write 4, carry 1. 5+7+1 = 13 → write 3, carry 1. 4+3+1 = 8.

### 2.2 Subtraction
Subtraction is *taking away* or *finding the difference*. It is **not** commutative: $7-3 \ne 3-7$.

**Borrowing (regrouping)**
```
   7 0 2
 - 3 4 8
 -------
   3 5 4
```
2 < 8, so borrow: the 0 cannot lend, so borrow from 7 → 6, the 0 becomes 10, then lend 1 → 9, and 2 becomes 12. 12−8=4, 9−4=5, 6−3=3.

**Check:** subtraction is the inverse of addition: $354 + 348 = 702$ ✓.

### 2.3 Mental math tricks
- **Compensation:** $398 + 245 = 400 + 245 - 2 = 643$.
- **Counting up:** $1000 - 637$: from 637 to 640 is 3, to 700 is 60, to 1000 is 300 → 363.

### Practice 2
1. 5,678 + 2,945  2. 9,001 − 4,567  3. 999 + 999 (mentally)  4. A shop had 1,250 pens, sold 487. How many remain?

**Answers:** 1) 8,623 2) 4,434 3) 1,998 4) 763

---

## Chapter 3: Multiplication and Division

### 3.1 Multiplication as repeated addition
$4 \times 3 = 3 + 3 + 3 + 3 = 12$. It is also an **array**: 4 rows of 3 dots.

Properties:
- Commutative $ab = ba$; Associative $(ab)c = a(bc)$; Identity $a\times1=a$; Zero $a\times 0 = 0$.
- **Distributive:** $a(b + c) = ab + ac$. This is the single most important law in arithmetic and algebra.

Example: $7 \times 23 = 7 \times 20 + 7\times 3 = 140 + 21 = 161$.

**Memorise tables up to 12 × 12** (and ideally squares up to 20² = 400).

### 3.2 Long multiplication
```
      3 4 7
    ×   2 6
   -------
    2 0 8 2    (347 × 6)
    6 9 4 0    (347 × 20)
   -------
    9 0 2 2
```

### 3.3 Division
Division is sharing equally or repeated subtraction. $\text{dividend} = \text{divisor} \times \text{quotient} + \text{remainder}$, with $0 \le \text{remainder} < \text{divisor}$.

$47 \div 5 = 9$ remainder $2$, because $47 = 5\times 9 + 2$.

**Division by zero is undefined.** (If $6 \div 0 = q$, then $0 \times q = 6$, impossible.)

### 3.4 Long division
$\;864 \div 4$: 8÷4=2; 6÷4=1 r2; bring down 4 → 24÷4=6. Answer 216.

### 3.5 Order of operations (BODMAS / PEMDAS)
**B**rackets → **O**rders (powers, roots) → **D**ivision & **M**ultiplication (left to right) → **A**ddition & **S**ubtraction (left to right).

$8 + 2 \times (9 - 4)^2 \div 10 = 8 + 2 \times 25 \div 10 = 8 + 50 \div 10 = 8 + 5 = 13$

### Practice 3
1. 248 × 37  2. 1,764 ÷ 12  3. $20 - 12 \div 4 \times 2$  4. 125 × 8 mentally  5. 100 ÷ 7 (quotient and remainder)

**Answers:** 1) 9,176 2) 147 3) 14 4) 1,000 5) 14 r 2

---

## Chapter 4: Factors, Multiples, Primes

### 4.1 Definitions
- $a$ is a **factor** (divisor) of $b$ if $b = a \times k$ for a whole number $k$. Factors of 12: 1, 2, 3, 4, 6, 12.
- $b$ is a **multiple** of $a$ in that case. Multiples of 4: 4, 8, 12, 16, …
- A **prime** has exactly two factors: 1 and itself. 2, 3, 5, 7, 11, 13, 17, 19, 23, 29, …
- A **composite** number has more than two factors. **1 is neither prime nor composite.**

### 4.2 Divisibility rules
| Divisor | Rule |
|---|---|
| 2 | last digit even |
| 3 | digit sum divisible by 3 |
| 4 | last two digits divisible by 4 |
| 5 | last digit 0 or 5 |
| 6 | divisible by 2 and 3 |
| 8 | last three digits divisible by 8 |
| 9 | digit sum divisible by 9 |
| 10 | last digit 0 |
| 11 | alternating digit sum divisible by 11 |

### 4.3 Prime factorisation
**Fundamental Theorem of Arithmetic:** every whole number > 1 is a product of primes in exactly one way (ignoring order).

$360 = 2^3 \times 3^2 \times 5$ (factor tree: 360 → 36 × 10 → (4×9)×(2×5) → …)

### 4.4 HCF (GCD) and LCM
- **HCF**: take common primes with the *smallest* powers.
- **LCM**: take all primes with the *largest* powers.

$12 = 2^2\cdot 3$, $18 = 2\cdot 3^2$: HCF $= 2\cdot3 = 6$, LCM $= 2^2\cdot3^2 = 36$.

**Useful fact:** $\text{HCF}(a,b)\times\text{LCM}(a,b) = a\times b$. Check: $6 \times 36 = 216 = 12 \times 18$ ✓.

**Euclid's algorithm** (fast HCF): $\gcd(a,b) = \gcd(b, a \bmod b)$.
$\gcd(84, 36) = \gcd(36, 12) = \gcd(12, 0) = 12$.

### Practice 4
1. List all primes below 50. 2. Prime-factorise 1,260. 3. HCF and LCM of 48 and 180. 4. Is 7,425 divisible by 9? by 11?

**Answers:** 1) 2,3,5,7,11,13,17,19,23,29,31,37,41,43,47 (15 primes) 2) $2^2\cdot3^2\cdot5\cdot7$ 3) HCF 12, LCM 720 4) digit sum 18 → yes by 9; alternating sum 7−4+2−5=0 → yes by 11.

---

## Chapter 5: Fractions

### 5.1 Meaning
$\frac{a}{b}$ means: split a whole into $b$ equal parts and take $a$ of them. $a$ = **numerator**, $b$ = **denominator** ($b\ne0$).
- **Proper:** $a<b$ (e.g. $\frac34$). **Improper:** $a \ge b$ (e.g. $\frac{7}{4}$). **Mixed:** $1\frac34 = \frac74$.

### 5.2 Equivalent fractions and simplest form
Multiply or divide top and bottom by the same non-zero number: $\frac{2}{3} = \frac{4}{6} = \frac{10}{15}$.
Simplest form: divide by the HCF. $\frac{18}{24} = \frac{3}{4}$ (HCF 6).

### 5.3 Comparing
Use a common denominator or cross-multiply: $\frac{5}{8}$ vs $\frac{3}{5}$: $5\times5 = 25 > 24 = 3\times8$, so $\frac58 > \frac35$.

### 5.4 Operations
- **Add/Subtract:** common denominator (use LCM).
$$\frac{2}{3} + \frac{3}{4} = \frac{8}{12} + \frac{9}{12} = \frac{17}{12} = 1\tfrac{5}{12}$$
- **Multiply:** top × top, bottom × bottom. $\frac{2}{3}\times\frac{9}{10} = \frac{18}{30} = \frac{3}{5}$. (Cancel first to save work.)
- **Divide:** multiply by the reciprocal ("keep, change, flip").
$$\frac{3}{4} \div \frac{2}{5} = \frac{3}{4}\times\frac{5}{2} = \frac{15}{8}$$

**Why flip?** Dividing by $\frac25$ asks "how many $\frac25$'s fit?" Since five fifths make 1, there are $\frac52$ copies of $\frac25$ in every 1.

**"Of" means multiply:** $\frac{3}{5}$ of 40 $= \frac35 \times 40 = 24$.

### Practice 5
1. Simplify $\frac{42}{56}$. 2. $\frac{5}{6} - \frac{4}{9}$ 3. $2\frac{1}{3} \times 1\frac{1}{2}$ 4. $\frac{7}{8} \div 1\frac{3}{4}$ 5. Order: $\frac23, \frac58, \frac{7}{12}$

**Answers:** 1) $\frac34$ 2) $\frac{7}{18}$ 3) $\frac72 = 3\frac12$ 4) $\frac12$ 5) $\frac{7}{12} < \frac58 < \frac23$

---

## Chapter 6: Decimals and Percentages

### 6.1 Decimals
Decimals extend place value to the right: tenths, hundredths, thousandths.
$$3.472 = 3 + \frac{4}{10} + \frac{7}{100} + \frac{2}{1000}$$

- **Add/Subtract:** line up the decimal points.
- **Multiply:** multiply as whole numbers, then count decimal places: $0.3 \times 0.12 = 0.036$ (1+2 = 3 places).
- **Divide:** shift both numbers to make the divisor whole: $4.5 \div 0.15 = 450 \div 15 = 30$.

**Fraction ↔ decimal:** $\frac{3}{8} = 3\div 8 = 0.375$. $\frac13 = 0.333\ldots = 0.\overline{3}$ (repeating).

### 6.2 Percentages
"Percent" = per hundred. $x\% = \frac{x}{100}$.
- $35\% = 0.35 = \frac{7}{20}$
- $x\%$ of $N$ = $\frac{x}{100}\times N$. 15% of 240 = 36.
- **Percentage change** $= \dfrac{\text{new} - \text{old}}{\text{old}} \times 100\%$.
- Increase by $r\%$: multiply by $(1 + \frac{r}{100})$. Decrease: multiply by $(1 - \frac{r}{100})$.

**Trap:** +20% then −20% is **not** back to start: $1.2 \times 0.8 = 0.96$ → a 4% loss.

### 6.3 Money applications
- **Profit% = (SP − CP)/CP × 100.**
- **Simple interest:** $SI = \dfrac{P \times R \times T}{100}$.
- **Compound interest:** $A = P\left(1 + \dfrac{R}{100}\right)^T$.

Example: ₹10,000 at 10% p.a. for 2 years. SI = ₹2,000. CI: $10000 \times 1.21 = 12100$ → interest ₹2,100.

### Practice 6
1. $2.5 \times 0.04$ 2. $7.2 \div 0.09$ 3. Write $\frac{5}{16}$ as a decimal and percentage. 4. A price rises from ₹800 to ₹920. Percent increase? 5. CI on ₹5,000 at 8% for 2 years.

**Answers:** 1) 0.1 2) 80 3) 0.3125 = 31.25% 4) 15% 5) $5000 \times 1.1664 = 5832$ → ₹832

---

## Chapter 7: Measurement and Basic Geometry

### 7.1 Units (metric)
- Length: 10 mm = 1 cm; 100 cm = 1 m; 1000 m = 1 km
- Mass: 1000 g = 1 kg
- Capacity: 1000 mL = 1 L; 1 L = 1000 cm³
- Time: 60 s = 1 min; 60 min = 1 h

### 7.2 Basic shapes
- **Point, line, line segment, ray.**
- **Angle:** measured in degrees. Acute (< 90°), right (= 90°), obtuse (90°–180°), straight (180°), reflex (> 180°).
- **Polygons:** triangle (3), quadrilateral (4), pentagon (5), hexagon (6)…
- **Circle:** centre, radius $r$, diameter $d = 2r$.

### 7.3 Perimeter and area
| Shape | Perimeter | Area |
|---|---|---|
| Rectangle $l \times b$ | $2(l+b)$ | $lb$ |
| Square side $s$ | $4s$ | $s^2$ |
| Triangle | sum of sides | $\frac12 \times \text{base} \times \text{height}$ |
| Circle | $2\pi r$ | $\pi r^2$ |

$\pi \approx 3.14159\ldots \approx \frac{22}{7}$.

**Why is a triangle half a rectangle?** Draw a rectangle around it; the triangle's height splits it into two rectangles, each cut exactly in half by a side of the triangle.

### 7.4 Volume
Cuboid: $V = l \times b \times h$. Cube: $V = s^3$.

### Practice 7
1. Convert 3.75 km to metres. 2. Perimeter and area of a 12 m × 7 m garden. 3. Area of a circle of radius 7 cm ($\pi = 22/7$). 4. How many 1-litre bottles fill a 50 cm × 40 cm × 30 cm tank?

**Answers:** 1) 3,750 m 2) 38 m; 84 m² 3) 154 cm² 4) 60,000 cm³ = 60 bottles

> **Checkpoint I:** Can you add $\frac{3}{8} + \frac{5}{12}$, find 17.5% of 640, and find the LCM of 14 and 21 without a calculator? (Answers: $\frac{19}{24}$, 112, 42.) If yes, move on.

---

# PART II — MIDDLE SCHOOL MATHEMATICS

---

## Chapter 8: Integers (Negative Numbers)

### 8.1 Why negatives?
Temperatures below zero, debts, floors below ground. The **integers** are
$$\mathbb{Z} = \{\dots, -3, -2, -1, 0, 1, 2, 3, \dots\}$$
The **absolute value** $|x|$ is the distance from 0: $|-5| = 5$, $|5| = 5$.

### 8.2 Rules
- **Adding a negative = subtracting:** $7 + (-3) = 4$.
- **Subtracting a negative = adding:** $7 - (-3) = 10$.
- **Signs in multiplication/division:**

| × | + | − |
|---|---|---|
| **+** | + | − |
| **−** | − | + |

$(-4)\times(-6) = 24$; $(-20) \div 5 = -4$.

**Why is negative × negative positive?** Using the distributive law: $0 = (-1)\times 0 = (-1)\times(1 + (-1)) = -1 + (-1)(-1)$, so $(-1)(-1)$ must equal $1$. The rule is *forced* by keeping arithmetic consistent.

### Practice 8
1. $-8 + 15 - (-4)$ 2. $(-3)^3$ 3. $(-2)^4$ 4. $\frac{(-12)(-5)}{-6}$

**Answers:** 1) 11 2) −27 3) 16 4) −10

---

## Chapter 9: Rational Numbers and Exponents

### 9.1 Rational numbers
$\mathbb{Q}$ = all numbers of the form $\frac{p}{q}$ with integers $p, q$, $q \neq 0$. Every rational number has a decimal that **terminates or repeats**.

Converting a repeating decimal: let $x = 0.\overline{36}$. Then $100x = 36.\overline{36}$, so $99x = 36$, $x = \frac{36}{99} = \frac{4}{11}$.

### 9.2 Laws of exponents
For $a, b \neq 0$ and integers $m, n$:
1. $a^m \cdot a^n = a^{m+n}$
2. $\dfrac{a^m}{a^n} = a^{m-n}$
3. $(a^m)^n = a^{mn}$
4. $(ab)^n = a^n b^n$
5. $a^0 = 1$
6. $a^{-n} = \dfrac{1}{a^n}$
7. $a^{1/n} = \sqrt[n]{a}$, and $a^{m/n} = (\sqrt[n]{a})^m$

Example: $\dfrac{2^5 \cdot 2^{-2}}{2^{4}} = 2^{5-2-4} = 2^{-1} = \frac12$. And $27^{2/3} = (\sqrt[3]{27})^2 = 9$.

### 9.3 Scientific notation
$a \times 10^n$ with $1 \le a < 10$. Speed of light ≈ $3 \times 10^8$ m/s; mass of an electron ≈ $9.11\times10^{-31}$ kg.

### 9.4 Squares and roots
$\sqrt{x}$ is the non-negative number whose square is $x$. $\sqrt{144} = 12$. Simplify: $\sqrt{72} = \sqrt{36\cdot2} = 6\sqrt2$.

### Practice 9
1. Write $0.\overline{7}$ and $0.1\overline{6}$ as fractions. 2. $(3^2)^3 \div 3^4$ 3. $16^{-3/4}$ 4. $(4\times10^5)(3\times10^{-2})$ 5. $\sqrt{50} + \sqrt{18}$

**Answers:** 1) $\frac79$; $\frac16$ 2) 9 3) $\frac18$ 4) $1.2 \times 10^4$ 5) $8\sqrt2$

---

## Chapter 10: Ratio, Proportion and Rates

### 10.1 Ratio
$a : b$ compares two quantities of the same kind. Simplify like fractions: $15:25 = 3:5$.

**Dividing in a ratio:** split ₹1,200 in ratio 2:3:5 → total parts 10 → ₹240, ₹360, ₹600.

### 10.2 Proportion
$a:b = c:d \iff ad = bc$ (cross-multiplication).
- **Direct proportion:** $y = kx$ (double one, double the other). Example: cost vs quantity.
- **Inverse proportion:** $y = \frac{k}{x}$ (double one, halve the other). Example: workers vs days.

Example: 6 workers build a wall in 10 days. 15 workers? Work = 60 worker-days → 4 days.

### 10.3 Rates and speed
$$\text{speed} = \frac{\text{distance}}{\text{time}}$$
**Average speed** = total distance / total time (not the average of speeds!). Going 60 km at 30 km/h and returning at 60 km/h: total 120 km in 2 + 1 = 3 h → 40 km/h.

### 10.4 Unitary method
If 7 kg costs ₹350, then 1 kg costs ₹50, so 12 kg costs ₹600.

### Practice 10
1. Divide 84 in the ratio 3:4. 2. If $x:12 = 5:8$, find $x$. 3. A car travels 150 km in 2.5 h. Speed? 4. 8 taps fill a tank in 27 min. How long for 6 taps?

**Answers:** 1) 36, 48 2) 7.5 3) 60 km/h 4) 36 min

---

## Chapter 11: Introduction to Algebra

### 11.1 Variables
A **variable** is a letter standing for an unknown or changing number. Algebra lets us state facts that are true for *every* number: $a + b = b + a$.

- **Expression:** $3x + 5$ (no equals sign).
- **Equation:** $3x + 5 = 20$ (a statement that may be true or false).
- **Term**, **coefficient** (the 3 in $3x$), **constant** (the 5).
- **Like terms** have the same variable part: $4x^2$ and $-7x^2$.

### 11.2 Simplifying
Collect like terms: $5x + 3y - 2x + 7y = 3x + 10y$.
Expand brackets with the distributive law: $3(2x - 5) = 6x - 15$; $-(x - 4) = -x + 4$.

### 11.3 Key identities (memorise!)
$$(a+b)^2 = a^2 + 2ab + b^2$$
$$(a-b)^2 = a^2 - 2ab + b^2$$
$$(a+b)(a-b) = a^2 - b^2$$
$$(x+a)(x+b) = x^2 + (a+b)x + ab$$

**Proof of the first:** $(a+b)(a+b) = a(a+b) + b(a+b) = a^2 + ab + ba + b^2 = a^2 + 2ab + b^2$.

**Mental math with identities:** $103^2 = (100+3)^2 = 10000 + 600 + 9 = 10609$. $47 \times 53 = (50-3)(50+3) = 2500 - 9 = 2491$.

### 11.4 Substitution
If $x = -2$, $y = 3$: $2x^2 - xy + y = 2(4) - (-6) + 3 = 17$.

### Practice 11
1. Simplify $4(a - 2b) - 3(2a - b)$. 2. Expand $(2x + 3)^2$. 3. Expand $(3x - 4)(3x + 4)$. 4. Compute $98^2$ mentally.

**Answers:** 1) $-2a - 5b$ 2) $4x^2 + 12x + 9$ 3) $9x^2 - 16$ 4) 9604

---

## Chapter 12: Linear Equations and Inequalities

### 12.1 Solving linear equations
**Golden rule:** do the same thing to both sides.
$$5x - 7 = 2x + 8 \implies 3x = 15 \implies x = 5$$
**Check** by substitution: $25 - 7 = 18 = 10 + 8$ ✓.

With fractions, multiply by the LCM of denominators:
$$\frac{x}{3} + \frac{x}{4} = 7 \implies 4x + 3x = 84 \implies x = 12$$

### 12.2 Word problems — the method
1. Name the unknown ("let $x$ = …").
2. Translate sentences into an equation.
3. Solve. 4. Check that the answer makes sense.

*Example:* A father is 3 times as old as his son. In 12 years he will be twice as old. Ages? Let son = $x$: $3x + 12 = 2(x + 12) \Rightarrow x = 12$. Son 12, father 36.

### 12.3 Simultaneous equations (two unknowns)
$$\begin{cases} 2x + 3y = 13 \\ x - y = -1\end{cases}$$
**Substitution:** $x = y - 1$ → $2(y-1) + 3y = 13$ → $5y = 15$ → $y = 3$, $x = 2$.
**Elimination:** multiply the second by 2 and subtract: $5y = 15$, same result.

### 12.4 Inequalities
Same rules as equations **except**: multiplying or dividing by a negative number **reverses** the inequality.
$$-3x + 4 > 10 \implies -3x > 6 \implies x < -2$$

### Practice 12
1. $7(x - 2) = 3x + 6$ 2. $\frac{2x-1}{3} = \frac{x+2}{2}$ 3. Solve $3x + 2y = 12$, $5x - 2y = 4$. 4. Solve $5 - 2x \le 11$. 5. Sum of three consecutive integers is 96. Find them.

**Answers:** 1) $x=5$ 2) $x=8$ 3) $x=2, y=3$ 4) $x \ge -3$ 5) 31, 32, 33

---

## Chapter 13: Geometry — Angles, Triangles, Pythagoras

### 13.1 Angle facts
- Angles on a straight line sum to 180°. Angles around a point sum to 360°.
- **Vertically opposite** angles are equal.
- **Parallel lines cut by a transversal:** corresponding angles equal, alternate angles equal, co-interior angles sum to 180°.

### 13.2 Triangles
- **Angle sum = 180°.** *Proof:* draw a line through one vertex parallel to the opposite side; alternate angles show the three angles form a straight line.
- Exterior angle = sum of the two opposite interior angles.
- Types: equilateral (all sides equal, each angle 60°), isosceles (two equal sides & base angles), scalene.
- **Polygon angle sum:** $(n - 2) \times 180°$. Each angle of a regular hexagon: $720°/6 = 120°$.

### 13.3 Congruence and similarity
- **Congruent** (identical): tests SSS, SAS, ASA, RHS.
- **Similar** (same shape, scaled): angles equal, sides in the same ratio. If the scale factor is $k$, areas scale by $k^2$ and volumes by $k^3$.

### 13.4 Pythagoras' theorem
In a right triangle with legs $a, b$ and hypotenuse $c$:
$$a^2 + b^2 = c^2$$

**Proof (rearrangement):** Put four copies of the triangle inside a square of side $a+b$. The leftover space is a tilted square of side $c$. So $(a+b)^2 = 4\cdot\frac12 ab + c^2$, i.e. $a^2 + 2ab + b^2 = 2ab + c^2$, giving $a^2 + b^2 = c^2$.

**Pythagorean triples:** (3,4,5), (5,12,13), (8,15,17), (7,24,25).

### 13.5 Circle facts
- The angle at the centre is twice the angle at the circumference on the same arc.
- The angle in a semicircle is 90°.
- Opposite angles of a cyclic quadrilateral sum to 180°.
- A tangent is perpendicular to the radius at the point of contact.

### Practice 13
1. Two angles of a triangle are 47° and 68°. Third angle? 2. Each interior angle of a regular decagon? 3. A ladder 13 m long reaches 12 m up a wall. How far is its foot from the wall? 4. Two similar triangles have sides in ratio 2:5. Ratio of areas?

**Answers:** 1) 65° 2) 144° 3) 5 m 4) 4:25

---

## Chapter 14: Area, Volume and Surface Area

### 14.1 More area formulas
| Shape | Area |
|---|---|
| Parallelogram | base × height |
| Trapezium | $\frac12(a + b)h$ |
| Rhombus | $\frac12 d_1 d_2$ |
| Triangle (Heron) | $\sqrt{s(s-a)(s-b)(s-c)}$, $s = \frac{a+b+c}{2}$ |
| Sector (angle $\theta°$) | $\frac{\theta}{360}\pi r^2$ |

### 14.2 Solids
| Solid | Volume | Surface area |
|---|---|---|
| Cuboid | $lbh$ | $2(lb + bh + hl)$ |
| Cylinder | $\pi r^2 h$ | $2\pi r h + 2\pi r^2$ |
| Cone | $\frac13 \pi r^2 h$ | $\pi r l + \pi r^2$ ($l$ = slant height $=\sqrt{r^2+h^2}$) |
| Sphere | $\frac43\pi r^3$ | $4\pi r^2$ |
| Hemisphere | $\frac23\pi r^3$ | $3\pi r^2$ (with base) |

**Insight:** a cone holds exactly $\frac13$ of the cylinder with the same base and height; a sphere holds $\frac23$ of its circumscribing cylinder (Archimedes' favourite result).

### Practice 14
1. Area of a trapezium with parallel sides 8 and 14, height 5. 2. Heron: triangle with sides 13, 14, 15. 3. Volume of a cone with $r = 3$, $h = 4$ (leave π). Its total surface area? 4. Surface area of a sphere of radius 7 ($\pi = 22/7$).

**Answers:** 1) 55 2) $s=21$, $\sqrt{21\cdot8\cdot7\cdot6} = 84$ 3) $12\pi$; $l=5$, $15\pi + 9\pi = 24\pi$ 4) 616

---

## Chapter 15: Data and Basic Statistics

### 15.1 Measures of centre
For data $x_1, \dots, x_n$:
- **Mean** $\bar{x} = \dfrac{x_1 + \cdots + x_n}{n}$
- **Median:** middle value after sorting (average the two middle values if $n$ is even).
- **Mode:** most frequent value.

### 15.2 Measures of spread
- **Range** = max − min.
- **Variance** $\sigma^2 = \dfrac{1}{n}\sum (x_i - \bar x)^2$; **standard deviation** $\sigma = \sqrt{\sigma^2}$.

Example: data 2, 4, 4, 4, 5, 5, 7, 9. Mean = 40/8 = 5. Squared deviations: 9,1,1,1,0,0,4,16 → sum 32 → variance 4 → SD 2.

### 15.3 Graphs
Bar charts (categories), histograms (grouped continuous data), pie charts (parts of a whole: angle = fraction × 360°), line graphs (change over time), scatter plots (relationship between two variables).

### 15.4 Basic probability
$$P(\text{event}) = \frac{\text{number of favourable outcomes}}{\text{total equally likely outcomes}}$$
$0 \le P \le 1$; $P(\text{not } A) = 1 - P(A)$. Rolling a die: $P(\text{even}) = \frac36 = \frac12$.

### Practice 15
1. Mean, median, mode of 3, 7, 7, 2, 9, 10, 4. 2. The mean of 5 numbers is 12; four of them are 10, 15, 8, 14. Find the fifth. 3. Two coins are tossed. P(at least one head)?

**Answers:** 1) mean 6, median 7, mode 7 2) 13 3) $\frac34$

> **Checkpoint II:** Solve $\frac{x+1}{2} - \frac{x-2}{3} = 2$ (answer $x = 5$); find the hypotenuse for legs 9 and 12 (15); compute $(-2)^{-3}$ ($-\frac18$).

---

# PART III — HIGH SCHOOL MATHEMATICS

---

## Chapter 16: Real Numbers and the Logic of Proof

### 16.1 The number systems
$$\mathbb{N} \subset \mathbb{Z} \subset \mathbb{Q} \subset \mathbb{R} \subset \mathbb{C}$$
- **Irrational numbers** cannot be written as $\frac pq$: $\sqrt2$, $\pi$, $e$. Their decimals never end or repeat.
- $\mathbb{R}$ (real numbers) = rationals + irrationals = every point on the number line.

### 16.2 Your first real proof: $\sqrt{2}$ is irrational
*Proof by contradiction.* Suppose $\sqrt2 = \frac{p}{q}$ in lowest terms. Then $p^2 = 2q^2$, so $p^2$ is even, so $p$ is even (an odd number squared is odd). Write $p = 2k$: $4k^2 = 2q^2$, so $q^2 = 2k^2$, so $q$ is even too. But then $\frac pq$ was not in lowest terms — contradiction. ∎

### 16.3 Logic vocabulary
- **Statement:** a sentence that is true or false.
- $P \Rightarrow Q$ ("if P then Q"). **Converse:** $Q \Rightarrow P$ (not automatically true!). **Contrapositive:** $\neg Q \Rightarrow \neg P$ (always equivalent to the original).
- $P \iff Q$: "if and only if".
- **Quantifiers:** $\forall$ (for all), $\exists$ (there exists).
- To disprove "for all", give **one counterexample**.

### 16.4 Proof methods (preview)
1. **Direct:** assume P, derive Q.
2. **Contradiction:** assume the opposite, reach an impossibility.
3. **Contrapositive.**
4. **Induction** (Chapter 23).

*Example (direct):* the sum of two odd numbers is even. $(2m+1) + (2n+1) = 2(m+n+1)$. ∎

### Practice 16
1. Prove $\sqrt3$ is irrational. 2. Give a counterexample to "every prime is odd". 3. State the contrapositive of "if $n^2$ is even then $n$ is even." 4. Is $\sqrt2 + \sqrt2$ irrational? Is $\sqrt2\cdot\sqrt2$?

**Answers:** 1) Same as for $\sqrt2$, using "if 3 divides $p^2$ then 3 divides $p$" (because 3 is prime). 2) 2 3) "If $n$ is odd then $n^2$ is odd." 4) $2\sqrt2$ is irrational; $\sqrt2\cdot\sqrt2 = 2$ is rational — so irrational × irrational can be rational.

---

## Chapter 17: Polynomials and Factorisation

### 17.1 Polynomials
$p(x) = a_n x^n + \dots + a_1 x + a_0$ with $a_n \ne 0$. **Degree** $n$. Linear (1), quadratic (2), cubic (3).

### 17.2 Factorisation techniques
1. **Common factor:** $6x^2 + 9x = 3x(2x + 3)$.
2. **Difference of squares:** $x^2 - 49 = (x-7)(x+7)$.
3. **Quadratics $x^2 + bx + c$:** find two numbers with product $c$, sum $b$. $x^2 + 5x + 6 = (x+2)(x+3)$.
4. **Splitting the middle term** for $ax^2 + bx + c$: find numbers with product $ac$, sum $b$.
   $6x^2 + 7x - 3$: $ac = -18$, numbers $9, -2$ → $6x^2 + 9x - 2x - 3 = 3x(2x+3) - (2x+3) = (3x - 1)(2x + 3)$.
5. **Cubes:** $a^3 \pm b^3 = (a \pm b)(a^2 \mp ab + b^2)$.
6. **Grouping:** $xy + 2x + 3y + 6 = x(y+2) + 3(y+2) = (x+3)(y+2)$.

### 17.3 Remainder and Factor Theorems
- **Remainder Theorem:** dividing $p(x)$ by $(x - a)$ leaves remainder $p(a)$.
- **Factor Theorem:** $(x - a)$ is a factor $\iff p(a) = 0$.

*Example:* $p(x) = x^3 - 6x^2 + 11x - 6$. $p(1) = 0$, so $(x - 1)$ is a factor. Dividing: $p(x) = (x-1)(x^2 - 5x + 6) = (x-1)(x-2)(x-3)$.

**Rational Root Theorem:** any rational root $\frac pq$ (lowest terms) of a polynomial with integer coefficients has $p \mid a_0$ and $q \mid a_n$.

### 17.4 Polynomial long division
$(2x^3 + 3x^2 - 5x + 1) \div (x + 2)$: quotient $2x^2 - x - 3$, remainder $7$. (Check: $p(-2) = -16 + 12 + 10 + 1 = 7$ ✓.)

### Practice 17
Factorise: 1) $x^2 - 9x + 20$ 2) $2x^2 - x - 15$ 3) $8x^3 - 27$ 4) $x^3 + 2x^2 - 5x - 6$ 5) $x^4 - 16$

**Answers:** 1) $(x-4)(x-5)$ 2) $(2x+5)(x-3)$ 3) $(2x-3)(4x^2+6x+9)$ 4) $(x+1)(x-2)(x+3)$ 5) $(x-2)(x+2)(x^2+4)$

---

## Chapter 18: Quadratic Equations

### 18.1 Three methods to solve $ax^2 + bx + c = 0$
1. **Factorise:** $x^2 - 5x + 6 = 0 \Rightarrow (x-2)(x-3) = 0 \Rightarrow x = 2, 3$. (If $AB = 0$ then $A = 0$ or $B = 0$.)
2. **Complete the square:** $x^2 + 6x - 7 = 0 \Rightarrow (x+3)^2 = 16 \Rightarrow x = 1$ or $x = -7$.
3. **Quadratic formula:**
$$x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$$

**Derivation:** divide by $a$: $x^2 + \frac ba x = -\frac ca$. Add $\left(\frac{b}{2a}\right)^2$: $\left(x + \frac{b}{2a}\right)^2 = \frac{b^2 - 4ac}{4a^2}$. Take square roots. ∎

### 18.2 The discriminant $D = b^2 - 4ac$
- $D > 0$: two distinct real roots.
- $D = 0$: one repeated root.
- $D < 0$: no real roots (two complex roots — Chapter 26).

### 18.3 Vieta's formulas
If roots are $\alpha, \beta$: $\alpha + \beta = -\frac{b}{a}$, $\alpha\beta = \frac{c}{a}$.

### 18.4 The graph: a parabola
$y = a(x - h)^2 + k$ has **vertex** $(h, k)$, opens up if $a > 0$, down if $a < 0$. Axis of symmetry $x = -\frac{b}{2a}$.

### Practice 18
1. Solve $3x^2 - 5x - 2 = 0$. 2. Solve $x^2 + 4x + 1 = 0$. 3. For what $k$ does $x^2 + kx + 9 = 0$ have equal roots? 4. Vertex of $y = 2x^2 - 8x + 3$. 5. If $\alpha, \beta$ are roots of $x^2 - 7x + 10 = 0$, find $\alpha^2 + \beta^2$.

**Answers:** 1) $x = 2, -\frac13$ 2) $x = -2 \pm\sqrt3$ 3) $k = \pm 6$ 4) $(2, -5)$ 5) $(\alpha+\beta)^2 - 2\alpha\beta = 49 - 20 = 29$

---

## Chapter 19: Functions and Graphs

### 19.1 Definition
A **function** $f: A \to B$ assigns to each element $x$ of the **domain** $A$ exactly one element $f(x)$ of the **codomain** $B$. The set of actual outputs is the **range**.

$f(x) = \sqrt{x - 1}$ has domain $x \ge 1$, range $[0, \infty)$.

### 19.2 Types
- **Injective (one-to-one):** $f(a) = f(b) \Rightarrow a = b$.
- **Surjective (onto):** every $b\in B$ is hit.
- **Bijective:** both — then an **inverse** $f^{-1}$ exists.
- **Even:** $f(-x) = f(x)$ (symmetric in y-axis, e.g. $x^2$, $\cos x$). **Odd:** $f(-x) = -f(x)$ (e.g. $x^3$, $\sin x$).

### 19.3 Composition and inverse
$(f \circ g)(x) = f(g(x))$. To find $f^{-1}$: write $y = f(x)$, solve for $x$, swap names.
$f(x) = 3x - 2 \Rightarrow f^{-1}(x) = \frac{x + 2}{3}$.

### 19.4 Graph transformations of $y = f(x)$
| New graph | Effect |
|---|---|
| $f(x) + c$ | shift up by $c$ |
| $f(x - c)$ | shift right by $c$ |
| $af(x)$ | vertical stretch by $a$ |
| $f(ax)$ | horizontal compression by $a$ |
| $-f(x)$ | reflect in x-axis |
| $f(-x)$ | reflect in y-axis |
| $\lvert f(x) \rvert$ | reflect negative parts upward |

### 19.5 Gallery of basic graphs
Lines $y = mx + c$ (slope $m$, intercept $c$), parabola $x^2$, cubic $x^3$, $\frac1x$ (hyperbola), $\sqrt{x}$, $|x|$, $e^x$, $\ln x$, $\sin x$, $\cos x$. **Sketch each of these from memory.**

### Practice 19
1. Domain of $\frac{1}{x^2 - 4}$. 2. $f(x) = x^2$, $g(x) = x + 3$: find $f\circ g$ and $g \circ f$. 3. Inverse of $f(x) = \frac{2x+1}{x-3}$. 4. Is $f(x) = x^3 - x$ even, odd, or neither?

**Answers:** 1) $x \ne \pm2$ 2) $(x+3)^2$; $x^2 + 3$ (not the same!) 3) $f^{-1}(x) = \frac{3x + 1}{x - 2}$ 4) odd

---

## Chapter 20: Exponentials and Logarithms

### 20.1 Exponential functions
$f(x) = a^x$ ($a > 0, a\neq1$). Growth if $a > 1$, decay if $0 < a < 1$. Models population, compound interest, radioactive decay.

### 20.2 The number $e$
$$e = \lim_{n\to\infty}\left(1 + \frac1n\right)^n \approx 2.71828$$
Continuous compounding: $A = Pe^{rt}$.

### 20.3 Logarithms
$\log_a x = y \iff a^y = x$. The log answers: "what power?" $\log_2 8 = 3$; $\log_{10} 0.01 = -2$. $\ln x = \log_e x$.

**Laws:**
1. $\log(xy) = \log x + \log y$
2. $\log\frac{x}{y} = \log x - \log y$
3. $\log x^n = n\log x$
4. **Change of base:** $\log_a x = \dfrac{\ln x}{\ln a}$
5. $\log_a 1 = 0$, $\log_a a = 1$, $a^{\log_a x} = x$

### 20.4 Solving exponential equations
$3^{x} = 20 \Rightarrow x = \frac{\ln 20}{\ln 3} \approx 2.727$.
Doubling time at rate $r$ (continuous): $2 = e^{rt} \Rightarrow t = \frac{\ln 2}{r} \approx \frac{0.693}{r}$ (the "rule of 70").

### Practice 20
1. $\log_3 81$ 2. Simplify $\log 50 + \log 2$ (base 10). 3. Solve $2^{x+1} = 32$. 4. Solve $\log_2(x) + \log_2(x - 2) = 3$. 5. How long does money take to triple at 6% continuous interest?

**Answers:** 1) 4 2) 2 3) $x=4$ 4) $x(x-2) = 8 \Rightarrow x = 4$ (reject $-2$) 5) $\frac{\ln 3}{0.06} \approx 18.3$ years

---

## Chapter 21: Trigonometry

### 21.1 Right-triangle definitions
For angle $\theta$ in a right triangle: **SOH-CAH-TOA**
$$\sin\theta = \frac{\text{opp}}{\text{hyp}}, \quad \cos\theta = \frac{\text{adj}}{\text{hyp}}, \quad \tan\theta = \frac{\text{opp}}{\text{adj}}$$
Reciprocals: $\csc = \frac1{\sin}$, $\sec = \frac1{\cos}$, $\cot = \frac{1}{\tan}$.

### 21.2 Standard values
| $\theta$ | 0° | 30° | 45° | 60° | 90° |
|---|---|---|---|---|---|
| $\sin$ | 0 | $\frac12$ | $\frac{\sqrt2}{2}$ | $\frac{\sqrt3}{2}$ | 1 |
| $\cos$ | 1 | $\frac{\sqrt3}{2}$ | $\frac{\sqrt2}{2}$ | $\frac12$ | 0 |
| $\tan$ | 0 | $\frac{1}{\sqrt3}$ | 1 | $\sqrt3$ | undefined |

### 21.3 Radians and the unit circle
$\pi \text{ radians} = 180°$. A point on the unit circle at angle $\theta$ is $(\cos\theta, \sin\theta)$ — this defines trig for **all** angles. Signs by quadrant: **A**ll, **S**in, **T**an, **C**os ("All Students Take Calculus").

Arc length $s = r\theta$; sector area $= \frac12 r^2\theta$ ($\theta$ in radians).

### 21.4 Identities
- **Pythagorean:** $\sin^2\theta + \cos^2\theta = 1$; $1 + \tan^2\theta = \sec^2\theta$; $1 + \cot^2\theta = \csc^2\theta$.
- **Compound angle:**
  $\sin(A \pm B) = \sin A\cos B \pm \cos A \sin B$
  $\cos(A \pm B) = \cos A\cos B \mp \sin A\sin B$
  $\tan(A\pm B) = \dfrac{\tan A \pm \tan B}{1 \mp \tan A\tan B}$
- **Double angle:** $\sin 2A = 2\sin A\cos A$; $\cos 2A = \cos^2 A - \sin^2 A = 1 - 2\sin^2 A = 2\cos^2 A - 1$.

### 21.5 Any triangle
- **Sine rule:** $\dfrac{a}{\sin A} = \dfrac{b}{\sin B} = \dfrac{c}{\sin C} = 2R$
- **Cosine rule:** $c^2 = a^2 + b^2 - 2ab\cos C$ (Pythagoras when $C = 90°$)
- **Area** $= \frac12 ab\sin C$

### 21.6 Graphs and equations
$\sin x$ and $\cos x$ have period $2\pi$, range $[-1,1]$. $\tan x$ has period $\pi$.
General solutions: $\sin x = \sin\alpha \Rightarrow x = n\pi + (-1)^n\alpha$; $\cos x = \cos\alpha \Rightarrow x = 2n\pi \pm \alpha$; $\tan x = \tan\alpha \Rightarrow x = n\pi + \alpha$.

### Practice 21
1. Convert 135° to radians. 2. Exact value of $\sin 75°$. 3. Prove $\dfrac{1 - \cos 2x}{\sin 2x} = \tan x$. 4. Triangle with $a = 7$, $b = 8$, $C = 60°$: find $c$. 5. Solve $2\sin x = 1$ for $0 \le x < 2\pi$.

**Answers:** 1) $\frac{3\pi}{4}$ 2) $\sin(45°+30°) = \frac{\sqrt6 + \sqrt2}{4}$ 3) $\frac{2\sin^2 x}{2\sin x\cos x} = \tan x$ 4) $c^2 = 49 + 64 - 56 = 57$, $c = \sqrt{57}$ 5) $\frac\pi6, \frac{5\pi}{6}$

---

## Chapter 22: Coordinate Geometry and Conic Sections

### 22.1 Points and lines
- Distance: $d = \sqrt{(x_2 - x_1)^2 + (y_2-y_1)^2}$
- Midpoint: $\left(\frac{x_1+x_2}{2}, \frac{y_1+y_2}{2}\right)$
- Section formula (ratio $m:n$): $\left(\frac{mx_2 + nx_1}{m+n}, \frac{my_2+ny_1}{m+n}\right)$
- Slope $m = \frac{y_2 - y_1}{x_2 - x_1}$. Parallel: equal slopes. Perpendicular: $m_1 m_2 = -1$.
- Line forms: $y = mx + c$; $y - y_1 = m(x - x_1)$; $ax + by + c = 0$.
- Distance from $(x_0,y_0)$ to $ax + by + c = 0$: $\dfrac{|ax_0 + by_0 + c|}{\sqrt{a^2+b^2}}$.

### 22.2 Conic sections
| Curve | Standard form | Key features |
|---|---|---|
| Circle | $(x-h)^2 + (y-k)^2 = r^2$ | centre $(h,k)$, radius $r$ |
| Parabola | $y^2 = 4ax$ | focus $(a,0)$, directrix $x=-a$ |
| Ellipse | $\frac{x^2}{a^2} + \frac{y^2}{b^2} = 1$ | $c^2 = a^2 - b^2$, foci $(\pm c, 0)$, $e = c/a < 1$ |
| Hyperbola | $\frac{x^2}{a^2} - \frac{y^2}{b^2} = 1$ | $c^2 = a^2 + b^2$, asymptotes $y = \pm\frac ba x$, $e > 1$ |

All conics are slices of a double cone; all are "points whose distance to a focus is $e$ times their distance to a directrix".

### Practice 22
1. Equation of the line through $(1, 2)$ and $(4, 11)$. 2. Line through $(2,3)$ perpendicular to $y = 2x + 1$. 3. Centre and radius of $x^2 + y^2 - 6x + 4y - 12 = 0$. 4. Foci of $\frac{x^2}{25} + \frac{y^2}{9} = 1$.

**Answers:** 1) $y = 3x - 1$ 2) $y = -\frac12 x + 4$ 3) $(x-3)^2 + (y+2)^2 = 25$: centre $(3,-2)$, $r = 5$ 4) $c = 4$: $(\pm4, 0)$

---

## Chapter 23: Sequences, Series and Induction

### 23.1 Arithmetic progression (AP)
$a, a+d, a+2d, \dots$ — $n$th term $a_n = a + (n-1)d$; sum $S_n = \frac n2[2a + (n-1)d] = \frac n2(a + l)$.

**Gauss's trick:** $1 + 2 + \dots + 100$: pair first and last → 50 pairs of 101 → 5050. In general $\sum_{k=1}^n k = \frac{n(n+1)}{2}$.

### 23.2 Geometric progression (GP)
$a, ar, ar^2, \dots$ — $a_n = ar^{n-1}$; $S_n = a\dfrac{r^n - 1}{r - 1}$ ($r\ne1$).
**Infinite GP** with $|r| < 1$: $S_\infty = \dfrac{a}{1 - r}$. E.g. $1 + \frac12 + \frac14 + \dots = 2$.

### 23.3 Useful sums
$$\sum_{k=1}^n k^2 = \frac{n(n+1)(2n+1)}{6}, \qquad \sum_{k=1}^n k^3 = \left(\frac{n(n+1)}{2}\right)^2$$

### 23.4 Mathematical induction
To prove $P(n)$ for all $n \ge 1$:
1. **Base case:** prove $P(1)$.
2. **Inductive step:** assume $P(k)$, prove $P(k+1)$.

Like dominoes: the first falls, and each one knocks the next.

*Example:* prove $\sum_{k=1}^n k = \frac{n(n+1)}{2}$. Base: $1 = 1$ ✓. Step: $\frac{k(k+1)}{2} + (k+1) = \frac{(k+1)(k+2)}{2}$ ✓. ∎

### 23.5 Sigma notation
$\sum_{i=1}^{n} f(i)$ means $f(1) + f(2) + \dots + f(n)$. Linear: $\sum(a f + b g) = a\sum f + b\sum g$.

### Practice 23
1. 20th term and sum of first 20 terms of $3, 7, 11, \dots$ 2. Sum of $2 + 6 + 18 + \dots$ (8 terms). 3. Write $0.\overline{45}$ as an infinite GP and sum it. 4. Prove by induction that $3^n - 1$ is even for all $n\ge1$.

**Answers:** 1) $a_{20} = 79$, $S_{20} = 820$ 2) $2\cdot\frac{3^8 - 1}{2} = 6560$ 3) $\frac{45}{100}/(1 - \frac{1}{100}) = \frac{45}{99} = \frac{5}{11}$ 4) Base: 2 ✓. Step: $3^{k+1} - 1 = 3(3^k - 1) + 2$, even + even. ∎

---

## Chapter 24: Counting — Permutations, Combinations, Binomial Theorem

### 24.1 Fundamental counting principle
If a task has $m$ ways then $n$ ways, together there are $m \times n$ ways. (3 shirts × 4 trousers = 12 outfits.)

### 24.2 Factorials
$n! = n(n-1)\cdots 2\cdot1$, $0! = 1$.

### 24.3 Permutations (order matters)
$${}^nP_r = \frac{n!}{(n-r)!}$$
Arrangements of the letters of BANANA: $\frac{6!}{3!\,2!} = 60$ (divide by repeats).

### 24.4 Combinations (order doesn't matter)
$${}^nC_r = \binom{n}{r} = \frac{n!}{r!\,(n-r)!}$$
Choosing a team of 3 from 10: $\binom{10}{3} = 120$.
**Pascal's rule:** $\binom{n}{r} = \binom{n-1}{r-1} + \binom{n-1}{r}$.

### 24.5 Binomial theorem
$$(a + b)^n = \sum_{r=0}^{n}\binom{n}{r}a^{n-r}b^r$$
Pascal's triangle gives the coefficients:
```
        1
       1 1
      1 2 1
     1 3 3 1
    1 4 6 4 1
```
$(x + 2)^4 = x^4 + 8x^3 + 24x^2 + 32x + 16$.

### 24.6 Pigeonhole principle
If $n+1$ objects go into $n$ boxes, some box has at least 2. (Among 13 people, two share a birth month.)

### Practice 24
1. How many 4-digit PINs have no repeated digits? 2. How many ways to choose 2 boys and 3 girls from 5 boys and 6 girls? 3. Coefficient of $x^3$ in $(2x - 1)^5$. 4. Arrangements of MISSISSIPPI.

**Answers:** 1) $10\cdot9\cdot8\cdot7 = 5040$ 2) $10 \times 20 = 200$ 3) $\binom{5}{2}(2)^3(-1)^2 = 80$ 4) $\frac{11!}{4!\,4!\,2!} = 34650$

---

## Chapter 25: Probability

### 25.1 Rules
- $P(A \cup B) = P(A) + P(B) - P(A\cap B)$
- Mutually exclusive: $P(A\cap B) = 0$.
- **Conditional:** $P(A\mid B) = \dfrac{P(A\cap B)}{P(B)}$.
- **Independent:** $P(A\cap B) = P(A)P(B)$.

### 25.2 Bayes' theorem
$$P(A\mid B) = \frac{P(B\mid A)\,P(A)}{P(B)}$$
*Example (medical test):* disease rate 1%, test detects 99% of cases, false positive rate 5%. If you test positive:
$$P(D\mid +) = \frac{0.99 \times 0.01}{0.99\times0.01 + 0.05\times0.99} = \frac{0.0099}{0.0594} \approx 16.7\%$$
Surprisingly low — because the disease is rare. This is why Bayes matters.

### 25.3 Random variables and expectation
A random variable $X$ assigns numbers to outcomes. **Expected value** $E[X] = \sum x\,P(X = x)$. **Variance** $\text{Var}(X) = E[X^2] - (E[X])^2$.

Fair die: $E[X] = 3.5$; $E[X^2] = \frac{91}{6}$; Var $= \frac{91}{6} - \frac{49}{4} = \frac{35}{12}$.

### 25.4 Binomial distribution
$n$ independent trials, success probability $p$:
$$P(X = k) = \binom{n}{k}p^k(1-p)^{n-k}, \quad E[X] = np, \quad \text{Var}(X) = np(1-p)$$

### Practice 25
1. Two dice: P(sum = 7)? 2. A bag has 4 red, 6 blue. Two drawn without replacement. P(both red)? 3. P(exactly 3 heads in 5 fair tosses)? 4. $P(A) = 0.5$, $P(B) = 0.4$, $P(A \cup B) = 0.7$. Are A, B independent?

**Answers:** 1) $\frac16$ 2) $\frac4{10}\cdot\frac39 = \frac{2}{15}$ 3) $\frac{10}{32} = \frac{5}{16}$ 4) $P(A\cap B) = 0.2 = 0.5\times0.4$ → yes

---

## Chapter 26: Complex Numbers

### 26.1 The imaginary unit
Define $i$ with $i^2 = -1$. Complex numbers: $z = a + bi$, $a = \text{Re}(z)$, $b = \text{Im}(z)$. Powers of $i$ cycle: $i, -1, -i, 1$.

### 26.2 Arithmetic
- $(2 + 3i) + (1 - i) = 3 + 2i$
- $(2 + 3i)(1 - i) = 2 - 2i + 3i - 3i^2 = 5 + i$
- **Conjugate** $\bar z = a - bi$; $z\bar z = a^2 + b^2 = |z|^2$.
- Division: multiply by the conjugate: $\frac{1}{1 + i} = \frac{1 - i}{2}$.

### 26.3 Polar form and Euler's formula
$z = r(\cos\theta + i\sin\theta) = re^{i\theta}$, $r = |z|$, $\theta = \arg z$.
$$e^{i\theta} = \cos\theta + i\sin\theta \qquad\Rightarrow\qquad e^{i\pi} + 1 = 0$$
Multiplying complex numbers **multiplies moduli and adds angles** — multiplication is rotation + scaling.

### 26.4 De Moivre's theorem and roots
$(\cos\theta + i\sin\theta)^n = \cos n\theta + i\sin n\theta$.
The $n$th roots of unity: $z^n = 1 \Rightarrow z = e^{2\pi i k/n}$, $k = 0,\dots,n-1$ — regular $n$-gon on the unit circle.

### 26.5 Fundamental Theorem of Algebra
Every polynomial of degree $n \ge 1$ with complex coefficients has exactly $n$ complex roots (counted with multiplicity). (Proved in Chapter 44.)

### Practice 26
1. $(3 - 2i)^2$ 2. $\frac{3 + 4i}{1 - 2i}$ 3. Modulus and argument of $1 + i\sqrt3$. 4. Compute $(1 + i)^8$. 5. Solve $z^2 + 2z + 5 = 0$.

**Answers:** 1) $5 - 12i$ 2) $\frac{(3+4i)(1+2i)}{5} = -1 + 2i$ 3) $2$, $\frac\pi3$ 4) $(\sqrt2 e^{i\pi/4})^8 = 16$ 5) $-1 \pm 2i$

---

## Chapter 27: Vectors and 3D Geometry

### 27.1 Vectors
A vector has magnitude and direction: $\vec v = (v_1, v_2, v_3) = v_1\hat i + v_2\hat j + v_3\hat k$. $|\vec v| = \sqrt{v_1^2 + v_2^2 + v_3^2}$.

### 27.2 Dot product
$$\vec a \cdot \vec b = a_1b_1 + a_2b_2 + a_3b_3 = |\vec a||\vec b|\cos\theta$$
$\vec a\perp\vec b \iff \vec a\cdot\vec b = 0$. Projection of $\vec a$ on $\vec b$: $\frac{\vec a\cdot\vec b}{|\vec b|}$.

### 27.3 Cross product
$$\vec a\times\vec b = \begin{vmatrix}\hat i & \hat j & \hat k\\ a_1 & a_2 & a_3 \\ b_1 & b_2 & b_3\end{vmatrix}$$
Perpendicular to both, magnitude $|\vec a||\vec b|\sin\theta$ = area of the parallelogram. Not commutative: $\vec a\times\vec b = -\vec b\times\vec a$.
**Scalar triple product** $\vec a\cdot(\vec b\times\vec c)$ = volume of the parallelepiped.

### 27.4 Lines and planes in 3D
- Line: $\vec r = \vec a + t\vec d$.
- Plane: $\vec n\cdot\vec r = d$, i.e. $ax + by + cz = d$ with normal $(a, b, c)$.
- Distance from point $(x_0,y_0,z_0)$ to the plane: $\dfrac{|ax_0 + by_0 + cz_0 - d|}{\sqrt{a^2+b^2+c^2}}$.

### Practice 27
1. Angle between $(1,2,2)$ and $(2,-1,2)$. 2. $(1,0,2)\times(0,1,3)$. 3. Plane through $(1,1,1)$ with normal $(2,-1,3)$. 4. Area of the triangle with vertices $(0,0,0)$, $(1,2,0)$, $(3,0,1)$.

**Answers:** 1) dot $= 4$, $|a||b| = 9$ → $\cos\theta = \frac49$ 2) $(-2, -3, 1)$ 3) $2x - y + 3z = 4$ 4) $\frac12|(2, -1, -6)| = \frac{\sqrt{41}}{2}$

---

## Chapter 28: Matrices and Determinants

### 28.1 Matrices
An $m\times n$ array of numbers. Add entrywise. **Multiply:** $(AB)_{ij} = \sum_k A_{ik}B_{kj}$ (row × column). Generally $AB \neq BA$.

$$\begin{pmatrix}1&2\\3&4\end{pmatrix}\begin{pmatrix}5&6\\7&8\end{pmatrix} = \begin{pmatrix}19 & 22\\ 43 & 50\end{pmatrix}$$

Identity $I$; transpose $A^T$ (swap rows and columns).

### 28.2 Determinants
$2\times2$: $\det\begin{pmatrix}a&b\\c&d\end{pmatrix} = ad - bc$.
$3\times 3$: expand along a row using cofactors.
Meaning: the factor by which the matrix scales area/volume (sign = orientation). $\det(AB) = \det A\det B$.

### 28.3 Inverse
$A^{-1}$ exists $\iff \det A \neq 0$. For $2\times2$:
$$A^{-1} = \frac{1}{ad - bc}\begin{pmatrix}d & -b \\ -c & a\end{pmatrix}$$

### 28.4 Solving systems
$A\vec x = \vec b \Rightarrow \vec x = A^{-1}\vec b$ (if invertible). **Cramer's rule:** $x_i = \frac{\det A_i}{\det A}$. In practice use **Gaussian elimination** (Chapter 38).

### Practice 28
1. $\det\begin{pmatrix}2&1&3\\0&-1&4\\1&2&0\end{pmatrix}$ 2. Inverse of $\begin{pmatrix}4&7\\2&6\end{pmatrix}$ 3. Solve $\begin{cases}2x + y = 5\\ x - 3y = -1\end{cases}$ using matrices.

**Answers:** 1) $2(0 - 8) - 1(0 - 4) + 3(0 + 1) = -16 + 4 + 3 = -9$ 2) $\frac{1}{10}\begin{pmatrix}6&-7\\-2&4\end{pmatrix}$ 3) $x = 2, y = 1$

> **Checkpoint III:** Solve $2^{2x} - 5\cdot2^x + 4 = 0$ (answer $x = 0$ or $2$); find $\binom{8}{3}$ (56); compute $\left|\frac{1+i}{1-i}\right|$ (1); prove $1 + 3 + 5 + \dots + (2n - 1) = n^2$ by induction.

---

# PART IV — CALCULUS

> Calculus is the mathematics of **change** (derivatives) and **accumulation** (integrals). The Fundamental Theorem says these are inverse operations.

---

## Chapter 29: Limits and Continuity

### 29.1 Intuition
$\lim_{x\to a} f(x) = L$ means: $f(x)$ gets as close as we like to $L$ when $x$ is close enough to $a$ (but $x \ne a$).

$\displaystyle\lim_{x\to2}\frac{x^2 - 4}{x - 2} = \lim_{x\to2}(x + 2) = 4$, even though the function is undefined at $x = 2$.

### 29.2 Formal ($\varepsilon$–$\delta$) definition
$$\lim_{x\to a}f(x) = L \iff \forall\varepsilon > 0\ \exists\delta > 0: 0 < |x - a| < \delta \Rightarrow |f(x) - L| < \varepsilon$$
*Example:* prove $\lim_{x\to3}(2x + 1) = 7$. Given $\varepsilon$, choose $\delta = \varepsilon/2$: then $|2x + 1 - 7| = 2|x - 3| < 2\delta = \varepsilon$. ∎

### 29.3 Limit laws and techniques
Limits respect $+, -, \times, \div$ (when the denominator's limit $\ne 0$). Techniques for "$\frac00$":
1. Factor and cancel.
2. Rationalise: $\lim_{x\to0}\frac{\sqrt{x+1} - 1}{x} = \lim\frac{1}{\sqrt{x+1} + 1} = \frac12$.
3. Standard limits:
$$\lim_{x\to0}\frac{\sin x}{x} = 1, \quad \lim_{x\to0}\frac{e^x - 1}{x} = 1, \quad \lim_{x\to0}\frac{\ln(1+x)}{x} = 1, \quad \lim_{x\to\infty}\left(1+\frac1x\right)^x = e$$
4. Limits at infinity: divide by the highest power. $\lim_{x\to\infty}\frac{3x^2 + 1}{5x^2 - x} = \frac35$.
5. **Squeeze theorem:** if $g \le f \le h$ and $g, h \to L$, then $f \to L$. E.g. $x^2\sin\frac1x \to 0$.

### 29.4 Continuity
$f$ is continuous at $a$ if $\lim_{x\to a}f(x) = f(a)$. Polynomials, $e^x$, $\sin$, $\cos$ are continuous everywhere.
**Intermediate Value Theorem (IVT):** if $f$ is continuous on $[a,b]$ and $k$ is between $f(a)$ and $f(b)$, then $f(c) = k$ for some $c \in [a,b]$. (Used to show equations have roots.)

### Practice 29
1. $\lim_{x\to 1}\frac{x^3 - 1}{x - 1}$ 2. $\lim_{x\to0}\frac{\sin 5x}{3x}$ 3. $\lim_{x\to\infty}\frac{2x^3 - x}{x^3 + 4}$ 4. Show $x^3 + x - 1 = 0$ has a root in $(0, 1)$.

**Answers:** 1) 3 2) $\frac53$ 3) 2 4) $f(0) = -1 < 0 < 1 = f(1)$; IVT.

---

## Chapter 30: Differentiation

### 30.1 Definition
The **derivative** is the instantaneous rate of change = slope of the tangent:
$$f'(x) = \lim_{h\to0}\frac{f(x+h) - f(x)}{h}$$
*From first principles:* $f(x) = x^2$: $\frac{(x+h)^2 - x^2}{h} = 2x + h \to 2x$.

### 30.2 Standard derivatives
| $f(x)$ | $f'(x)$ |
|---|---|
| $x^n$ | $nx^{n-1}$ |
| $e^x$ | $e^x$ |
| $a^x$ | $a^x\ln a$ |
| $\ln x$ | $\frac1x$ |
| $\sin x$ | $\cos x$ |
| $\cos x$ | $-\sin x$ |
| $\tan x$ | $\sec^2 x$ |
| $\arcsin x$ | $\frac{1}{\sqrt{1-x^2}}$ |
| $\arctan x$ | $\frac{1}{1+x^2}$ |

### 30.3 Rules
- **Sum/constant:** $(af + bg)' = af' + bg'$
- **Product:** $(fg)' = f'g + fg'$
- **Quotient:** $\left(\frac fg\right)' = \frac{f'g - fg'}{g^2}$
- **Chain:** $\frac{d}{dx}f(g(x)) = f'(g(x))\,g'(x)$ — "derivative of the outside × derivative of the inside".

*Examples:*
- $\frac{d}{dx}(x^2\sin x) = 2x\sin x + x^2\cos x$
- $\frac{d}{dx}e^{3x^2} = 6x\,e^{3x^2}$
- $\frac{d}{dx}\ln(\cos x) = -\tan x$

### 30.4 Implicit and logarithmic differentiation
Circle $x^2 + y^2 = 25$: $2x + 2y\,y' = 0 \Rightarrow y' = -\frac{x}{y}$.
$y = x^x$: $\ln y = x\ln x \Rightarrow \frac{y'}{y} = \ln x + 1 \Rightarrow y' = x^x(\ln x + 1)$.

### 30.5 Higher derivatives
$f''$ = rate of change of slope = **concavity** (acceleration in physics).

### Practice 30
Differentiate: 1) $3x^4 - 2\sqrt x + \frac5x$ 2) $\frac{x^2}{x + 1}$ 3) $\sin^3(2x)$ 4) $e^x\ln x$ 5) Find $\frac{dy}{dx}$ if $x^3 + y^3 = 6xy$.

**Answers:** 1) $12x^3 - \frac{1}{\sqrt x} - \frac{5}{x^2}$ 2) $\frac{x^2 + 2x}{(x+1)^2}$ 3) $6\sin^2(2x)\cos(2x)$ 4) $e^x\ln x + \frac{e^x}{x}$ 5) $\frac{2y - x^2}{y^2 - 2x}$

---

## Chapter 31: Applications of Derivatives

### 31.1 Tangents and normals
Tangent at $(a, f(a))$: $y - f(a) = f'(a)(x - a)$. Normal: slope $-\frac{1}{f'(a)}$.

### 31.2 Increasing/decreasing and extrema
- $f' > 0$ ⇒ increasing; $f' < 0$ ⇒ decreasing.
- **Critical points:** $f'(c) = 0$ or undefined.
- **Second derivative test:** $f''(c) > 0$ ⇒ local min; $f''(c) < 0$ ⇒ local max.
- On a closed interval, the global max/min is at a critical point or an endpoint (**Extreme Value Theorem**).

### 31.3 Optimisation recipe
1. Draw and label. 2. Write the quantity to optimise as a function of one variable. 3. Differentiate, set $= 0$. 4. Verify max/min. 5. Answer the question asked.

*Example:* a farmer has 200 m of fence for a rectangle along a river (no fence on the river side). Maximise area. $A = x(200 - 2x)$, $A' = 200 - 4x = 0 \Rightarrow x = 50$; area $= 50\times100 = 5000$ m².

### 31.4 Related rates
A balloon's radius grows at 2 cm/s. How fast does its volume grow when $r = 10$? $V = \frac43\pi r^3 \Rightarrow \frac{dV}{dt} = 4\pi r^2\frac{dr}{dt} = 4\pi(100)(2) = 800\pi$ cm³/s.

### 31.5 Mean Value Theorem
If $f$ is continuous on $[a,b]$ and differentiable on $(a, b)$, then for some $c$:
$$f'(c) = \frac{f(b) - f(a)}{b - a}$$
(Some instantaneous speed equals the average speed.)

### 31.6 L'Hôpital's rule
For $\frac00$ or $\frac{\infty}{\infty}$: $\lim\frac{f}{g} = \lim\frac{f'}{g'}$ (if the latter exists). $\lim_{x\to0}\frac{1 - \cos x}{x^2} = \lim\frac{\sin x}{2x} = \frac12$.

### 31.7 Newton's method
To solve $f(x) = 0$: $x_{n+1} = x_n - \frac{f(x_n)}{f'(x_n)}$. For $\sqrt2$ ($f = x^2 - 2$), from $x_0 = 1$: 1.5, 1.4167, 1.41422…

### Practice 31
1. Find and classify the stationary points of $f(x) = x^3 - 3x^2 - 9x + 5$. 2. An open box is made from a 12 cm × 12 cm square by cutting squares of side $x$ from the corners. Maximise its volume. 3. $\lim_{x\to\infty}\frac{\ln x}{x}$.

**Answers:** 1) $f' = 3(x-3)(x+1)$: local max at $x = -1$ ($f = 10$), local min at $x = 3$ ($f = -22$) 2) $V = x(12 - 2x)^2$, $V' = (12-2x)(12-6x) = 0 \Rightarrow x = 2$, $V = 128$ cm³ 3) 0

---

## Chapter 32: Integration

### 32.1 Antiderivatives
$F$ is an antiderivative of $f$ if $F' = f$. $\int f(x)\,dx = F(x) + C$.

| $\int f\,dx$ | Result |
|---|---|
| $x^n$ ($n\ne-1$) | $\frac{x^{n+1}}{n+1}$ |
| $\frac1x$ | $\ln\lvert x\rvert$ |
| $e^{x}$ | $e^{x}$ |
| $\sin x$ | $-\cos x$ |
| $\cos x$ | $\sin x$ |
| $\sec^2 x$ | $\tan x$ |
| $\frac{1}{1+x^2}$ | $\arctan x$ |
| $\frac{1}{\sqrt{1-x^2}}$ | $\arcsin x$ |

### 32.2 The definite integral (Riemann sums)
$$\int_a^b f(x)\,dx = \lim_{n\to\infty}\sum_{i=1}^n f(x_i^*)\Delta x$$
= signed area under the curve.

### 32.3 Fundamental Theorem of Calculus
1. If $F(x) = \int_a^x f(t)\,dt$, then $F'(x) = f(x)$.
2. $\int_a^b f(x)\,dx = F(b) - F(a)$ for any antiderivative $F$.

$\int_0^2 x^2\,dx = \left[\frac{x^3}{3}\right]_0^2 = \frac83$.

### 32.4 Techniques
1. **Substitution** (reverse chain rule): $\int 2x\cos(x^2)\,dx$, let $u = x^2$: $= \sin(x^2) + C$.
2. **Integration by parts:** $\int u\,dv = uv - \int v\,du$. Choose $u$ by **LIATE** (Log, Inverse trig, Algebraic, Trig, Exponential).
   $\int x e^x dx = xe^x - e^x + C$.
3. **Partial fractions:** $\int\frac{1}{x^2 - 1}dx = \int\frac12\left(\frac{1}{x-1} - \frac{1}{x+1}\right)dx = \frac12\ln\left|\frac{x-1}{x+1}\right| + C$.
4. **Trig substitution:** for $\sqrt{a^2 - x^2}$ use $x = a\sin\theta$; $\sqrt{a^2 + x^2}$: $x = a\tan\theta$; $\sqrt{x^2 - a^2}$: $x = a\sec\theta$.
5. **Trig identities:** $\int\sin^2 x\,dx = \frac{x}{2} - \frac{\sin 2x}{4} + C$.

### 32.5 Improper integrals
$\int_1^\infty\frac{1}{x^p}dx$ converges iff $p > 1$. $\int_0^\infty e^{-x}dx = 1$. **Gaussian:** $\int_{-\infty}^{\infty}e^{-x^2}dx = \sqrt\pi$.

### Practice 32
1. $\int(3x^2 - 4x + 5)\,dx$ 2. $\int_0^{\pi/2}\sin x\cos^2 x\,dx$ 3. $\int x\ln x\,dx$ 4. $\int\frac{x+5}{(x-1)(x+2)}dx$ 5. $\int_0^1 \frac{dx}{1+x^2}$

**Answers:** 1) $x^3 - 2x^2 + 5x + C$ 2) $\frac13$ 3) $\frac{x^2}{2}\ln x - \frac{x^2}{4} + C$ 4) $2\ln|x - 1| - \ln|x+2| + C$ 5) $\frac\pi4$

---

## Chapter 33: Applications of Integration

- **Area between curves:** $\int_a^b[f(x) - g(x)]\,dx$ where $f \ge g$. Area between $y = x$ and $y = x^2$: $\int_0^1(x - x^2)dx = \frac16$.
- **Volume of revolution** (disc): $V = \pi\int_a^b[f(x)]^2dx$. Sphere: $\pi\int_{-r}^r(r^2 - x^2)dx = \frac43\pi r^3$ ✓.
- **Shell method:** $V = 2\pi\int_a^b x f(x)\,dx$ (rotation about the y-axis).
- **Arc length:** $L = \int_a^b\sqrt{1 + [f'(x)]^2}\,dx$.
- **Average value:** $\frac{1}{b-a}\int_a^b f(x)\,dx$.
- **Physics:** displacement $= \int v\,dt$; work $= \int F\,dx$.
- **Probability:** for a density $p(x)$, $P(a\le X\le b) = \int_a^b p(x)\,dx$.

### Practice 33
1. Area enclosed by $y = 4 - x^2$ and the x-axis. 2. Volume when $y = \sqrt x$, $0\le x\le4$, rotates about the x-axis. 3. Average value of $\sin x$ on $[0,\pi]$.

**Answers:** 1) $\frac{32}{3}$ 2) $\pi\int_0^4 x\,dx = 8\pi$ 3) $\frac2\pi$

---

## Chapter 34: Infinite Series and Taylor Series

### 34.1 Convergence
$\sum a_n$ converges if its partial sums approach a limit.
- **Divergence test:** if $a_n \not\to 0$, the series diverges.
- **Harmonic series** $\sum\frac1n$ **diverges** (even though $\frac1n \to 0$!). Group: $1 + \frac12 + (\frac13+\frac14) + (\frac15 + \dots + \frac18) + \dots \ge 1 + \frac12 + \frac12 + \frac12 + \dots$
- **p-series:** $\sum\frac{1}{n^p}$ converges iff $p > 1$. $\sum\frac{1}{n^2} = \frac{\pi^2}{6}$ (Basel problem).

### 34.2 Tests
| Test | Statement |
|---|---|
| Comparison | $0\le a_n \le b_n$, $\sum b_n$ converges ⇒ $\sum a_n$ converges |
| Ratio | $L = \lim\lvert a_{n+1}/a_n\rvert$: $L < 1$ converges, $L > 1$ diverges |
| Root | $L = \lim\lvert a_n\rvert^{1/n}$: same conclusions |
| Integral | $\sum f(n)$ and $\int_1^\infty f$ behave alike (f positive, decreasing) |
| Alternating | $\sum(-1)^n b_n$ converges if $b_n \downarrow 0$ |

**Absolute convergence** ($\sum|a_n|$ converges) implies convergence. $\sum\frac{(-1)^{n+1}}{n} = \ln 2$ converges only conditionally.

### 34.3 Power series and Taylor series
$$f(x) = \sum_{n=0}^\infty\frac{f^{(n)}(a)}{n!}(x - a)^n$$
Key Maclaurin series ($a = 0$):
$$e^x = \sum_{n=0}^\infty\frac{x^n}{n!}, \quad \sin x = \sum_{n=0}^\infty\frac{(-1)^nx^{2n+1}}{(2n+1)!}, \quad \cos x = \sum_{n=0}^\infty\frac{(-1)^nx^{2n}}{(2n)!}$$
$$\frac{1}{1-x} = \sum_{n=0}^\infty x^n\ (|x|<1), \quad \ln(1+x) = \sum_{n=1}^\infty\frac{(-1)^{n+1}x^n}{n}\ (-1 < x \le 1)$$
$$(1 + x)^\alpha = 1 + \alpha x + \frac{\alpha(\alpha-1)}{2!}x^2 + \cdots\ (|x| < 1)$$
Plug $x = i\theta$ into $e^x$ and separate real/imaginary parts → **Euler's formula**.

**Radius of convergence** $R$: the series converges for $|x - a| < R$; find it with the ratio test.

### Practice 34
1. Does $\sum\frac{n}{2^n}$ converge? 2. Does $\sum\frac{1}{\sqrt n}$ converge? 3. Taylor series of $e^{-x^2}$. 4. Radius of convergence of $\sum\frac{x^n}{n\,3^n}$.

**Answers:** 1) Yes (ratio $\to \frac12$); its sum is 2 2) No ($p = \frac12$) 3) $\sum\frac{(-1)^nx^{2n}}{n!}$ 4) $R = 3$

---

## Chapter 35: Multivariable Calculus

### 35.1 Partial derivatives
For $f(x, y)$, $\frac{\partial f}{\partial x}$ treats $y$ as constant. $f = x^2y + \sin(xy)$: $f_x = 2xy + y\cos(xy)$.
**Clairaut:** $f_{xy} = f_{yx}$ for nice functions.

### 35.2 Gradient and directional derivatives
$\nabla f = \left(\frac{\partial f}{\partial x}, \frac{\partial f}{\partial y}, \frac{\partial f}{\partial z}\right)$ points in the direction of steepest increase. Directional derivative: $D_{\vec u}f = \nabla f\cdot\vec u$ ($|\vec u| = 1$).
**Chain rule:** $\frac{d}{dt}f(x(t), y(t)) = f_x x'(t) + f_y y'(t)$.

### 35.3 Optimisation
Critical points: $\nabla f = 0$. Second derivative test with $D = f_{xx}f_{yy} - f_{xy}^2$: $D > 0, f_{xx} > 0$ → min; $D > 0, f_{xx} < 0$ → max; $D < 0$ → saddle.
**Lagrange multipliers** (optimise $f$ subject to $g = c$): $\nabla f = \lambda\nabla g$.

### 35.4 Multiple integrals
$\iint_R f\,dA$, computed as iterated integrals (Fubini). Change of variables uses the **Jacobian**:
- Polar: $dA = r\,dr\,d\theta$
- Cylindrical: $dV = r\,dr\,d\theta\,dz$
- Spherical: $dV = \rho^2\sin\phi\,d\rho\,d\phi\,d\theta$

*Proof that $\int_{-\infty}^\infty e^{-x^2}dx = \sqrt\pi$:* square it: $I^2 = \iint e^{-(x^2+y^2)}dA = \int_0^{2\pi}\int_0^\infty e^{-r^2}r\,dr\,d\theta = 2\pi\cdot\frac12 = \pi$.

### 35.5 Vector calculus
- **Divergence** $\nabla\cdot\vec F$ (outflow per unit volume). **Curl** $\nabla\times\vec F$ (rotation).
- **Line integral** $\int_C\vec F\cdot d\vec r$ (work). If $\vec F = \nabla\phi$ (conservative), it equals $\phi(B) - \phi(A)$.
- **Green's theorem:** $\oint_C(P\,dx + Q\,dy) = \iint_D\left(\frac{\partial Q}{\partial x} - \frac{\partial P}{\partial y}\right)dA$
- **Stokes' theorem:** $\oint_{\partial S}\vec F\cdot d\vec r = \iint_S(\nabla\times\vec F)\cdot d\vec S$
- **Divergence (Gauss) theorem:** $\iint_{\partial V}\vec F\cdot d\vec S = \iiint_V\nabla\cdot\vec F\,dV$

All are versions of one idea: *the integral of a derivative over a region equals the integral of the function over its boundary* (generalised in Chapter 50).

### Practice 35
1. $\nabla f$ for $f = x^2 + 3xy - y^3$ at $(1, 2)$. 2. Classify the critical points of $f = x^3 - 3x + y^2$. 3. Maximise $xy$ subject to $x + y = 10$. 4. $\iint_D(x + y)\,dA$, $D = [0,1]\times[0,2]$. 5. Volume of the unit ball using spherical coordinates.

**Answers:** 1) $(2x + 3y, 3x - 3y^2) = (8, -9)$ 2) $(1, 0)$ min; $(-1, 0)$ saddle 3) 25 at $(5, 5)$ 4) 3 5) $\int_0^{2\pi}\int_0^\pi\int_0^1\rho^2\sin\phi = \frac43\pi$

---

## Chapter 36: Ordinary Differential Equations

### 36.1 What is an ODE?
An equation involving an unknown function and its derivatives: $y' = ky$ (growth), $my'' = -ky$ (spring).

### 36.2 First-order methods
1. **Separable:** $\frac{dy}{dx} = g(x)h(y) \Rightarrow \int\frac{dy}{h(y)} = \int g(x)\,dx$.
   $y' = ky \Rightarrow y = Ce^{kx}$.
2. **Linear:** $y' + P(x)y = Q(x)$. Integrating factor $\mu = e^{\int P\,dx}$, then $(\mu y)' = \mu Q$.
   $y' + 2y = e^{x}$: $\mu = e^{2x}$, $(e^{2x}y)' = e^{3x}$, $y = \frac{e^x}{3} + Ce^{-2x}$.
3. **Exact equations**, **Bernoulli equations** (substitution $v = y^{1-n}$).

### 36.3 Second-order linear with constant coefficients
$ay'' + by' + cy = 0$. Try $y = e^{rx}$ → **characteristic equation** $ar^2 + br + c = 0$:
- Distinct real $r_1, r_2$: $y = C_1e^{r_1x} + C_2e^{r_2x}$
- Repeated $r$: $y = (C_1 + C_2x)e^{rx}$
- Complex $\alpha\pm i\beta$: $y = e^{\alpha x}(C_1\cos\beta x + C_2\sin\beta x)$

Non-homogeneous: $y = y_h + y_p$ (find $y_p$ by **undetermined coefficients** or **variation of parameters**).

*Simple harmonic motion:* $y'' + \omega^2y = 0 \Rightarrow y = A\cos\omega t + B\sin\omega t$.

### 36.4 Systems and phase planes
$\vec x' = A\vec x$ is solved via eigenvalues of $A$ (Chapter 38): $\vec x = \sum c_ie^{\lambda_it}\vec v_i$. Eigenvalue signs determine stability (node, saddle, spiral, centre).

### 36.5 Laplace transform
$\mathcal L\{f\}(s) = \int_0^\infty e^{-st}f(t)\,dt$. Turns ODEs into algebra: $\mathcal L\{y'\} = sY - y(0)$. $\mathcal{L}\{1\} = \frac1s$, $\mathcal L\{e^{at}\} = \frac{1}{s - a}$, $\mathcal L\{\sin\omega t\} = \frac{\omega}{s^2 + \omega^2}$.

### 36.6 Existence and uniqueness (Picard–Lindelöf)
If $f(x, y)$ is continuous and Lipschitz in $y$, then $y' = f(x,y)$, $y(x_0) = y_0$ has a unique local solution.

### Practice 36
1. Solve $y' = xy^2$, $y(0) = 1$. 2. Solve $y' - y = x$. 3. Solve $y'' - 5y' + 6y = 0$. 4. Solve $y'' + 4y' + 4y = 0$. 5. Solve $y'' + 9y = 0$, $y(0) = 1$, $y'(0) = 6$.

**Answers:** 1) $y = \frac{2}{2 - x^2}$ 2) $y = Ce^x - x - 1$ 3) $C_1e^{2x} + C_2e^{3x}$ 4) $(C_1 + C_2x)e^{-2x}$ 5) $\cos 3x + 2\sin 3x$

> **Checkpoint IV:** Compute $\int_0^1 x^2e^x\,dx$ (answer $e - 2$); find the Taylor polynomial of degree 3 for $\ln(1 + x)$ ($x - \frac{x^2}{2} + \frac{x^3}{3}$); solve $y' = 2y$, $y(0) = 3$ ($3e^{2x}$).

---

# PART V — UNDERGRADUATE MATHEMATICS

> From here on, mathematics is about **definitions, theorems and proofs**. Read each theorem, try to prove it yourself before reading the proof, and invent your own examples and counterexamples.

---

## Chapter 37: Logic, Sets and Proof Techniques

### 37.1 Propositional logic
Connectives: $\neg$ (not), $\wedge$ (and), $\vee$ (or), $\Rightarrow$, $\iff$. $P\Rightarrow Q$ is false only when $P$ is true and $Q$ is false.
**De Morgan:** $\neg(P\wedge Q) \equiv \neg P\vee\neg Q$; $\neg(P \vee Q) \equiv \neg P\wedge\neg Q$.
**Negating quantifiers:** $\neg(\forall x\,P(x)) \equiv \exists x\,\neg P(x)$.

### 37.2 Sets
- $A\cup B$, $A\cap B$, $A\setminus B$, complement $A^c$, power set $\mathcal P(A)$ (if $|A| = n$, $|\mathcal P(A)| = 2^n$).
- **Cartesian product** $A\times B = \{(a,b)\}$.
- **Relations:** an **equivalence relation** is reflexive, symmetric and transitive; it splits a set into **equivalence classes**. (Example: $a\sim b \iff 3\mid(a - b)$ splits $\mathbb Z$ into 3 classes.)
- **Partial orders:** reflexive, antisymmetric, transitive.

### 37.3 Functions revisited, and cardinality
Two sets have the same **cardinality** if there is a bijection between them.
- $\mathbb N$, $\mathbb Z$, $\mathbb Q$ are **countable** (can be listed).
- **Cantor's diagonal argument:** $\mathbb R$ is **uncountable**. Suppose all reals in $(0,1)$ are listed; build a number whose $n$th digit differs from the $n$th digit of the $n$th number. It is not on the list. ∎
- **Cantor's theorem:** $|A| < |\mathcal P(A)|$ for every set $A$ — there are infinitely many sizes of infinity.

### 37.4 Proof toolbox
| Technique | When to use |
|---|---|
| Direct proof | Straightforward implication |
| Contrapositive | Negation of the conclusion is easier to use |
| Contradiction | Proving impossibility / irrationality / infinitude |
| Induction (weak/strong) | Statements indexed by $n$ |
| Construction | Proving existence |
| Counterexample | Disproving a universal claim |
| Cases | Splitting into finitely many situations |
| Pigeonhole | Showing some collision must happen |

*Euclid: there are infinitely many primes.* Suppose $p_1,\dots,p_n$ are all of them. $N = p_1\cdots p_n + 1$ is not divisible by any $p_i$ (remainder 1), so it has a prime factor not on the list. Contradiction. ∎

### 37.5 Axioms (a glimpse)
Modern mathematics is built on **ZFC set theory**. Gödel's incompleteness theorems show that any consistent, sufficiently strong system has true statements it cannot prove.

### Practice 37
1. Negate: "For every $\varepsilon > 0$ there is an $N$ such that for all $n > N$, $|a_n| < \varepsilon$." 2. Show $|\mathbb Z| = |\mathbb N|$. 3. Prove by strong induction that every $n\ge2$ has a prime factor. 4. Show "$a \sim b \iff a - b \in \mathbb Z$" is an equivalence relation on $\mathbb R$.

**Answers:** 1) "There is $\varepsilon > 0$ such that for every $N$ there exists $n > N$ with $|a_n| \ge \varepsilon$." 2) $f(n) = n/2$ for even $n$, $-(n-1)/2$ for odd $n$ (with $\mathbb N$ starting at 0) — or list $0, 1, -1, 2, -2, \dots$ 3) If $n$ is prime, done; otherwise $n = ab$ with $2 \le a < n$, and $a$ has a prime factor by hypothesis. 4) $a - a = 0$; $b - a = -(a - b)$; $(a - b) + (b - c) = a - c$.

---

## Chapter 38: Linear Algebra

> Possibly the most useful subject in all of mathematics: machine learning, physics, computer graphics, statistics, cryptography and economics are built on it.

### 38.1 Systems and Gaussian elimination
Write $A\vec x = \vec b$ as an augmented matrix; use row operations (swap, scale, add a multiple of one row to another) to reach **row echelon form**, then back-substitute. Solutions: none, exactly one, or infinitely many.

### 38.2 Vector spaces
A **vector space** over a field $F$ is a set $V$ with addition and scalar multiplication satisfying 8 axioms (associativity, commutativity, zero vector, inverses, distributivity, …).
Examples: $\mathbb R^n$; polynomials of degree $\le n$; $m\times n$ matrices; continuous functions on $[0,1]$.

- **Subspace:** non-empty, closed under addition and scalar multiplication.
- **Span:** all linear combinations $c_1\vec v_1 + \dots + c_k\vec v_k$.
- **Linear independence:** $\sum c_i\vec v_i = 0 \Rightarrow$ all $c_i = 0$.
- **Basis:** an independent spanning set. **Dimension:** the number of vectors in any basis (well-defined theorem!).

### 38.3 Linear maps
$T: V\to W$ is linear if $T(a\vec u + b\vec v) = aT\vec u + bT\vec v$. Every linear map between finite-dimensional spaces is a matrix (once bases are chosen).
- **Kernel** $\ker T = \{\vec v : T\vec v = 0\}$; **image** $\text{im}\,T$.
- **Rank–nullity theorem:** $\dim V = \dim\ker T + \dim\text{im}\,T$.
- **Invertible matrix theorem:** for square $A$, these are equivalent: $A$ invertible; $\det A\neq0$; $\ker A = \{0\}$; columns independent; rank $= n$; $0$ is not an eigenvalue.

### 38.4 Eigenvalues and eigenvectors
$A\vec v = \lambda\vec v$, $\vec v\neq0$. Find $\lambda$ from the **characteristic polynomial** $\det(A - \lambda I) = 0$.

*Example:* $A = \begin{pmatrix}2&1\\1&2\end{pmatrix}$: $(2 - \lambda)^2 - 1 = 0 \Rightarrow \lambda = 1, 3$, eigenvectors $(1,-1)$, $(1,1)$.

- **Diagonalisation:** $A = PDP^{-1}$ if $A$ has $n$ independent eigenvectors. Then $A^k = PD^kP^{-1}$ (fast powers — e.g. Fibonacci numbers in closed form).
- $\text{tr}A = \sum\lambda_i$, $\det A = \prod\lambda_i$.
- **Cayley–Hamilton:** $A$ satisfies its own characteristic polynomial.
- **Jordan normal form:** every complex square matrix is similar to a block-diagonal matrix of Jordan blocks.

### 38.5 Inner product spaces
$\langle\vec u,\vec v\rangle$ generalises the dot product. Norm $\|\vec v\| = \sqrt{\langle\vec v,\vec v\rangle}$.
- **Cauchy–Schwarz:** $|\langle u, v\rangle| \le\|u\|\|v\|$.
- **Gram–Schmidt** turns any basis into an orthonormal one (→ QR decomposition).
- **Orthogonal projection** and **least squares:** the best approximate solution of $A\vec x = \vec b$ solves $A^TA\vec x = A^T\vec b$. (This is linear regression.)

### 38.6 The Spectral Theorem and SVD
- **Spectral theorem:** a real symmetric matrix has real eigenvalues and an orthonormal eigenbasis: $A = QDQ^T$.
- **Singular value decomposition:** *every* $m\times n$ matrix factors as $A = U\Sigma V^T$ with $U, V$ orthogonal and $\Sigma$ diagonal (non-negative). Used in data compression, PCA, recommender systems.
- **Positive definite:** $\vec x^TA\vec x > 0$ for $\vec x \ne 0$ ⇔ all eigenvalues $> 0$.

### Practice 38
1. Are $(1,2,3), (4,5,6), (7,8,9)$ independent? 2. Find the rank and nullity of $\begin{pmatrix}1&2&3\\2&4&6\end{pmatrix}$. 3. Eigenvalues of $\begin{pmatrix}4&1\\2&3\end{pmatrix}$. 4. Orthonormalise $(1,1,0), (1,0,1)$. 5. Prove that eigenvectors of distinct eigenvalues are linearly independent (two-vector case).

**Answers:** 1) No: $(7,8,9) = 2(4,5,6) - (1,2,3)$ 2) rank 1, nullity 2 3) $\lambda^2 - 7\lambda + 10 = 0$: 2 and 5 4) $\frac{1}{\sqrt2}(1,1,0)$, $\frac{1}{\sqrt6}(1,-1,2)$ 5) If $a\vec v_1 + b\vec v_2 = 0$, apply $A$: $a\lambda_1\vec v_1 + b\lambda_2\vec v_2 = 0$. Subtract $\lambda_1\times$ the first equation: $b(\lambda_2 - \lambda_1)\vec v_2 = 0$, so $b = 0$, then $a = 0$. ∎

---

## Chapter 39: Real Analysis

> Analysis makes calculus rigorous. Every "obvious" fact from Part IV is proved here.

### 39.1 The real numbers
$\mathbb R$ is a **complete ordered field**. **Completeness (least upper bound) axiom:** every non-empty set bounded above has a **supremum** (least upper bound). This fails in $\mathbb Q$: $\{x\in\mathbb Q: x^2 < 2\}$ has no rational supremum.
**Archimedean property:** for any $x$ there is $n\in\mathbb N$ with $n > x$.

### 39.2 Sequences
$a_n\to L$ iff $\forall\varepsilon > 0\ \exists N\ \forall n > N: |a_n - L| < \varepsilon$.
- **Monotone Convergence Theorem:** bounded monotone sequences converge.
- **Bolzano–Weierstrass:** every bounded sequence has a convergent subsequence.
- **Cauchy sequences:** $\forall\varepsilon\ \exists N\ \forall m,n > N: |a_m - a_n| < \varepsilon$. In $\mathbb R$, Cauchy ⇔ convergent.
- $\limsup$ and $\liminf$.

### 39.3 Continuity, rigorously
$f$ is continuous at $a$ iff $x_n\to a \Rightarrow f(x_n)\to f(a)$ (sequential criterion), equivalently $\varepsilon$–$\delta$.
**Theorems:** IVT; **Extreme Value Theorem** (a continuous function on $[a,b]$ attains its max and min); **uniform continuity** — continuous on $[a,b]$ ⇒ uniformly continuous.

### 39.4 Differentiation
Rolle's theorem → Mean Value Theorem → Taylor's theorem with remainder:
$$f(x) = \sum_{k=0}^{n}\frac{f^{(k)}(a)}{k!}(x-a)^k + \frac{f^{(n+1)}(c)}{(n+1)!}(x - a)^{n+1}$$
Caution: there are continuous functions that are differentiable nowhere (Weierstrass function), and smooth functions not equal to their Taylor series ($e^{-1/x^2}$ at 0).

### 39.5 Riemann integration
Upper and lower Darboux sums; $f$ is integrable iff $U(f,P) - L(f,P)$ can be made arbitrarily small. Continuous functions on $[a,b]$ are integrable. Rigorous proof of the Fundamental Theorem of Calculus. (Limitations of the Riemann integral motivate Lebesgue — Chapter 47.)

### 39.6 Sequences and series of functions
- **Pointwise** vs **uniform** convergence: $f_n\to f$ uniformly iff $\sup_x|f_n(x) - f(x)|\to0$.
- $f_n(x) = x^n$ on $[0,1]$ converges pointwise to a *discontinuous* function — so pointwise limits can break continuity.
- **Uniform limits of continuous functions are continuous.** Uniform convergence allows swapping limit and integral.
- **Weierstrass M-test:** if $|f_n(x)|\le M_n$ and $\sum M_n < \infty$, then $\sum f_n$ converges uniformly.
- **Weierstrass approximation theorem:** every continuous function on $[a,b]$ is a uniform limit of polynomials.

### 39.7 Metric spaces (bridge to topology)
A metric $d$ satisfies $d(x,y)\ge0$ (= 0 iff $x = y$), symmetry, and the triangle inequality. Open/closed sets, **compactness** (every open cover has a finite subcover; in $\mathbb R^n$: closed and bounded — **Heine–Borel**), **completeness**, **Banach fixed-point theorem** (a contraction on a complete space has a unique fixed point — this proves Picard–Lindelöf).

### Practice 39
1. Prove $\frac{1}{n}\to0$ from the definition. 2. Find $\sup$ and $\inf$ of $\{1 - \frac1n: n\in\mathbb N\}$. 3. Show $f(x) = x^2$ is not uniformly continuous on $\mathbb R$. 4. Does $f_n(x) = \frac{x}{n}$ converge uniformly on $[0,1]$? On $\mathbb R$? 5. Prove a convergent sequence is bounded.

**Answers:** 1) Given $\varepsilon$, choose $N > 1/\varepsilon$ (Archimedean). 2) sup 1 (not attained), inf 0 3) Take $x_n = n$, $y_n = n + \frac1n$: $|x_n - y_n|\to0$ but $|f(x_n) - f(y_n)| = 2 + \frac{1}{n^2} > 2$. 4) Yes on $[0,1]$ ($\sup = \frac1n$); no on $\mathbb R$ ($\sup = \infty$). 5) With $\varepsilon = 1$, all terms beyond $N$ lie in $(L - 1, L + 1)$; take the max of these bounds and the finitely many earlier terms.

---

## Chapter 40: Abstract Algebra

### 40.1 Groups
A **group** $(G, *)$: closure, associativity, identity $e$, inverses. **Abelian** if commutative.
Examples: $(\mathbb Z, +)$; $(\mathbb Z_n, +)$ (clock arithmetic); $(\mathbb Q\setminus\{0\},\times)$; symmetries of a square $D_4$ (8 elements); permutations $S_n$ ($n!$ elements); invertible matrices $GL_n(\mathbb R)$.

- **Subgroup** $H\le G$. **Order** of an element: least $n$ with $g^n = e$. **Cyclic group** $\langle g\rangle$.
- **Lagrange's theorem:** for a finite group, $|H|$ divides $|G|$. *Corollary:* $g^{|G|} = e$; groups of prime order are cyclic.
- **Cosets** $gH$ partition $G$.
- **Homomorphism** $\varphi(ab) = \varphi(a)\varphi(b)$; **isomorphism** = bijective homomorphism (groups "the same").
- **Normal subgroup** $N\trianglelefteq G$ ($gNg^{-1} = N$) → **quotient group** $G/N$.
- **First Isomorphism Theorem:** $G/\ker\varphi\cong\text{im}\,\varphi$.
- **Group actions**, orbit–stabiliser theorem $|G| = |\text{Orb}(x)|\cdot|\text{Stab}(x)|$, **Burnside's lemma** (counting colourings up to symmetry), **Sylow theorems**.
- **Classification of finite abelian groups:** each is a product of cyclic groups $\mathbb Z_{p_1^{k_1}}\times\cdots$.

### 40.2 Rings and fields
A **ring** has $+$ (abelian group) and $\times$ (associative), with distributivity. Examples: $\mathbb Z$, $\mathbb Z_n$, polynomials $R[x]$, matrices.
- **Integral domain:** no zero divisors. **Field:** every non-zero element is invertible ($\mathbb Q, \mathbb R, \mathbb C, \mathbb Z_p$ for prime $p$).
- **Ideals** and **quotient rings** $R/I$. $\mathbb Z/n\mathbb Z = \mathbb Z_n$.
- $\mathbb Z_n$ is a field ⇔ $n$ is prime.
- $\mathbb R[x]/(x^2 + 1)\cong\mathbb C$ — complex numbers built algebraically!
- PID, UFD, Euclidean domains: where "unique factorisation" holds.

### 40.3 Preview of Galois theory
Field extensions, and the group of symmetries of the roots of a polynomial, explain why there is **no general formula** for degree-5 polynomial equations (Abel–Ruffini). Full treatment in Chapter 49.

### Practice 40
1. Is $(\mathbb Z, -)$ a group? 2. List the elements of order 4 in $\mathbb Z_{12}$. 3. Prove that a group in which $g^2 = e$ for all $g$ is abelian. 4. Can a group of order 15 have a subgroup of order 4? 5. Find the units of $\mathbb Z_{10}$.

**Answers:** 1) No — subtraction is not associative. 2) 3 and 9 3) $ab = (ab)^{-1} = b^{-1}a^{-1} = ba$. 4) No — 4 ∤ 15 (Lagrange). 5) $\{1, 3, 7, 9\}$

---

## Chapter 41: Discrete Mathematics and Graph Theory

### 41.1 Counting, advanced
- **Inclusion–exclusion:** $|A\cup B\cup C| = \sum|A| - \sum|A\cap B| + |A\cap B\cap C|$.
- **Derangements:** $D_n = n!\sum_{k=0}^n\frac{(-1)^k}{k!}\approx\frac{n!}{e}$.
- **Stars and bars:** non-negative integer solutions of $x_1 + \dots + x_k = n$: $\binom{n + k - 1}{k - 1}$.
- **Catalan numbers** $C_n = \frac{1}{n+1}\binom{2n}{n}$: 1, 1, 2, 5, 14, 42, … (balanced brackets, binary trees).

### 41.2 Recurrences and generating functions
Fibonacci $F_n = F_{n-1} + F_{n-2}$: characteristic equation $r^2 = r + 1$ gives **Binet's formula** $F_n = \frac{\varphi^n - \psi^n}{\sqrt5}$, $\varphi = \frac{1+\sqrt5}{2}$.
**Generating function** $\sum a_nx^n$ turns recurrences into algebra.

### 41.3 Graph theory
A **graph** $G = (V, E)$.
- **Handshake lemma:** $\sum\deg(v) = 2|E|$.
- **Trees:** connected, acyclic; a tree with $n$ vertices has $n - 1$ edges.
- **Euler circuit** (every edge once) exists iff connected and every degree is even (Königsberg bridges!).
- **Hamiltonian cycle** (every vertex once) — no easy criterion; NP-complete.
- **Planar graphs:** Euler's formula $V - E + F = 2$. $K_5$ and $K_{3,3}$ are not planar (Kuratowski).
- **Colouring:** Four Colour Theorem.
- **Algorithms:** BFS/DFS, Dijkstra (shortest paths), Kruskal/Prim (minimum spanning tree), max-flow min-cut.

### 41.4 Logic and computation
Boolean algebra, automata, **Big-O** notation, P vs NP.

### Practice 41
1. How many integers 1–100 are divisible by 2, 3, or 5? 2. Number of solutions of $x + y + z = 10$ in non-negative integers. 3. A graph has degrees 3,3,2,2,2. How many edges? 4. A connected planar graph has 10 vertices and 15 edges. How many faces?

**Answers:** 1) $50 + 33 + 20 - 16 - 10 - 6 + 3 = 74$ 2) $\binom{12}{2} = 66$ 3) 6 4) $F = 2 - 10 + 15 = 7$

---

## Chapter 42: Number Theory

### 42.1 Divisibility and the Euclidean algorithm
**Bézout's identity:** $\gcd(a, b) = ax + by$ for some integers $x, y$ (found with the *extended* Euclidean algorithm).
*Example:* $\gcd(240, 46) = 2 = 240(-9) + 46(47)$.

### 42.2 Modular arithmetic
$a\equiv b\pmod n$ iff $n\mid(a - b)$. You can add, subtract and multiply congruences. $a$ has an inverse mod $n$ iff $\gcd(a,n) = 1$.

- **Fermat's little theorem:** $p$ prime, $p\nmid a$ ⇒ $a^{p-1}\equiv1\pmod p$.
- **Euler's theorem:** $a^{\varphi(n)}\equiv1\pmod n$ when $\gcd(a, n) = 1$, where $\varphi(n)$ counts $1\le k\le n$ coprime to $n$; $\varphi(p^k) = p^k - p^{k-1}$, and $\varphi$ is multiplicative.
- **Chinese Remainder Theorem:** if $n_1,\dots,n_k$ are pairwise coprime, the system $x\equiv a_i\pmod{n_i}$ has a unique solution mod $n_1\cdots n_k$.
- **Wilson's theorem:** $(p-1)!\equiv-1\pmod p$.

### 42.3 Application: RSA cryptography
Choose primes $p, q$; $n = pq$; $\varphi = (p-1)(q-1)$; pick $e$ coprime to $\varphi$; $d = e^{-1}\bmod\varphi$.
Encrypt $c = m^e\bmod n$; decrypt $m = c^d\bmod n$ (works by Euler's theorem). Security rests on the difficulty of factoring $n$.

*Toy example:* $p = 5$, $q = 11$, $n = 55$, $\varphi = 40$, $e = 3$, $d = 27$ ($3\cdot27 = 81\equiv1$). Message $m = 2$: $c = 8$; $8^{27}\bmod 55 = 2$ ✓.

### 42.4 Further topics
Quadratic residues and the **Law of Quadratic Reciprocity**; Diophantine equations ($x^2 + y^2 = z^2$ parametrised by $(m^2 - n^2, 2mn, m^2 + n^2)$; Pell's equation $x^2 - Dy^2 = 1$); the **Prime Number Theorem** $\pi(x)\sim\frac{x}{\ln x}$; the **Riemann zeta function** $\zeta(s) = \sum n^{-s} = \prod_p(1 - p^{-s})^{-1}$ and the Riemann Hypothesis.

### Practice 42
1. Find $3^{100}\bmod 7$. 2. Find the inverse of 7 mod 26. 3. Solve $x\equiv2\pmod3$, $x\equiv3\pmod5$. 4. $\varphi(36)$. 5. Last two digits of $7^{2026}$.

**Answers:** 1) $3^6\equiv1$, $100 = 6\cdot16 + 4$, $3^4 = 81\equiv4$ 2) 15 ($105 = 4\cdot26 + 1$) 3) $x\equiv8\pmod{15}$ 4) $36\cdot\frac12\cdot\frac23 = 12$ 5) $7^4 = 2401\equiv1\pmod{100}$; $2026 = 4\cdot506 + 2$, so $7^2 = 49$

---

## Chapter 43: Probability Theory and Statistics

### 43.1 Random variables
- **Discrete:** probability mass function $p(x)$. **Continuous:** density $f(x)$ with $P(a\le X\le b) = \int_a^bf$.
- CDF $F(x) = P(X\le x)$.
- $E[X]$ is linear: $E[aX + bY] = aE[X] + bE[Y]$ (always, even if dependent!).
- $\text{Var}(X) = E[(X - \mu)^2]$; $\text{Var}(aX + b) = a^2\text{Var}(X)$; for independent $X, Y$: $\text{Var}(X + Y) = \text{Var}X + \text{Var}Y$.
- Covariance and correlation $\rho = \frac{\text{Cov}(X,Y)}{\sigma_X\sigma_Y}\in[-1,1]$.

### 43.2 Important distributions
| Distribution | PMF/PDF | Mean | Variance |
|---|---|---|---|
| Bernoulli($p$) | $p^x(1-p)^{1-x}$ | $p$ | $p(1-p)$ |
| Binomial($n,p$) | $\binom nk p^k(1-p)^{n-k}$ | $np$ | $np(1-p)$ |
| Geometric($p$) | $(1-p)^{k-1}p$ | $1/p$ | $(1-p)/p^2$ |
| Poisson($\lambda$) | $e^{-\lambda}\lambda^k/k!$ | $\lambda$ | $\lambda$ |
| Uniform($a,b$) | $\frac{1}{b - a}$ | $\frac{a+b}{2}$ | $\frac{(b-a)^2}{12}$ |
| Exponential($\lambda$) | $\lambda e^{-\lambda x}$ | $1/\lambda$ | $1/\lambda^2$ |
| Normal($\mu,\sigma^2$) | $\frac{1}{\sigma\sqrt{2\pi}}e^{-(x-\mu)^2/2\sigma^2}$ | $\mu$ | $\sigma^2$ |

**68–95–99.7 rule** for the normal distribution (within 1, 2, 3 standard deviations).

### 43.3 Limit theorems
- **Markov:** $P(X\ge a)\le\frac{E[X]}{a}$. **Chebyshev:** $P(|X - \mu|\ge k\sigma)\le\frac{1}{k^2}$.
- **Law of Large Numbers:** the sample mean $\bar X_n\to\mu$.
- **Central Limit Theorem:** $\frac{\bar X_n - \mu}{\sigma/\sqrt n}\to N(0,1)$ in distribution — whatever the original distribution (finite variance). This is why the bell curve is everywhere.

### 43.4 Statistical inference
- **Estimators:** unbiased, consistent; **maximum likelihood estimation** (MLE).
- **Confidence interval** for a mean: $\bar x\pm z_{\alpha/2}\frac{\sigma}{\sqrt n}$ (use the $t$-distribution if $\sigma$ is unknown and $n$ is small). 95%: $z = 1.96$.
- **Hypothesis testing:** null $H_0$, alternative $H_1$, test statistic, **p-value** = probability of data at least this extreme if $H_0$ is true. Type I error (false positive, rate $\alpha$), Type II (false negative).
- **Linear regression:** $\hat y = \beta_0 + \beta_1 x$ via least squares: $\beta_1 = \frac{\text{Cov}(x,y)}{\text{Var}(x)}$, $\beta_0 = \bar y - \beta_1\bar x$.
- **Bayesian statistics:** posterior ∝ likelihood × prior.

### 43.5 Markov chains
States with transition matrix $P$; the distribution evolves as $\pi_{n+1} = \pi_nP$. Under mild conditions there is a unique **stationary distribution** $\pi = \pi P$ (basis of Google PageRank and MCMC).

### Practice 43
1. A call centre gets on average 3 calls per minute (Poisson). P(no calls in a minute)? 2. $X\sim N(100, 15^2)$. Roughly what fraction exceeds 130? 3. Average of 100 fair dice rolls: approximate SD? 4. Find $E[X]$ for the density $f(x) = 2x$ on $[0,1]$.

**Answers:** 1) $e^{-3}\approx0.0498$ 2) $z = 2$ → about 2.5% (more precisely 2.28%) 3) $\sqrt{35/12}/10\approx0.171$ 4) $\int_0^1 2x^2dx = \frac23$

---

## Chapter 44: Complex Analysis

### 44.1 Holomorphic functions
$f: \mathbb C\to\mathbb C$ is **holomorphic** if $f'(z) = \lim_{h\to0}\frac{f(z+h) - f(z)}{h}$ exists ($h$ complex!). Writing $f = u + iv$, this requires the **Cauchy–Riemann equations**:
$$u_x = v_y, \qquad u_y = -v_x$$
Consequence: $u$ and $v$ are **harmonic** ($\nabla^2u = 0$).
Examples: polynomials, $e^z$, $\sin z$. Non-example: $\bar z$.

### 44.2 Complex integration
- **Cauchy's theorem:** if $f$ is holomorphic inside and on a closed curve $C$, then $\oint_Cf(z)\,dz = 0$.
- **Cauchy's integral formula:** $f(a) = \frac{1}{2\pi i}\oint_C\frac{f(z)}{z - a}dz$ — the values inside are determined by values on the boundary!
- Consequences: holomorphic ⇒ infinitely differentiable ⇒ **analytic** (equal to its power series).
- **Liouville's theorem:** a bounded entire function is constant. ⇒ **Fundamental Theorem of Algebra** (if $p$ had no root, $1/p$ would be bounded and entire).
- **Maximum modulus principle.**

### 44.3 Laurent series and residues
Near a singularity, $f(z) = \sum_{n=-\infty}^{\infty}a_n(z - a)^n$. The **residue** is $a_{-1}$.
**Residue theorem:** $\oint_Cf(z)\,dz = 2\pi i\sum\text{Res}(f, a_k)$.

*Application:* $\int_{-\infty}^{\infty}\frac{dx}{1 + x^2}$: close in the upper half-plane; pole at $i$ with residue $\frac{1}{2i}$; integral $= 2\pi i\cdot\frac{1}{2i} = \pi$.

### 44.4 Further topics
Conformal maps (angle-preserving), Möbius transformations, the Riemann mapping theorem, analytic continuation (how $\zeta(s)$ is defined for all $s\ne1$).

### Practice 44
1. Is $f(z) = z^2$ holomorphic? Verify Cauchy–Riemann. 2. $\oint_{|z|=2}\frac{e^z}{z - 1}dz$. 3. Residue of $\frac{1}{z^2(z - 1)}$ at $z = 0$. 4. Evaluate $\int_{-\infty}^\infty\frac{dx}{(x^2+1)^2}$.

**Answers:** 1) $u = x^2 - y^2$, $v = 2xy$: $u_x = 2x = v_y$, $u_y = -2y = -v_x$ ✓ 2) $2\pi ie$ 3) $\frac{1}{z^2}\cdot\frac{-1}{1 - z} = -\frac{1}{z^2}(1 + z + \dots)$ → residue $-1$ 4) Pole of order 2 at $i$: residue $\frac{d}{dz}(z + i)^{-2}|_{i} = -2(2i)^{-3} = \frac{1}{4i}$ → $\frac\pi2$

---

## Chapter 45: Point-Set Topology

### 45.1 Topological spaces
A **topology** on $X$ is a collection $\tau$ of "open" subsets with: $\emptyset, X\in\tau$; arbitrary unions and finite intersections of open sets are open. Topology studies properties preserved by continuous deformation ("a coffee mug is a doughnut").

- **Continuous map:** preimages of open sets are open.
- **Homeomorphism:** continuous bijection with continuous inverse.
- Constructions: subspace, product, quotient topologies (gluing: a square with opposite edges glued → torus).

### 45.2 Key properties
- **Hausdorff:** distinct points have disjoint neighbourhoods.
- **Compact:** every open cover has a finite subcover. Continuous images of compact sets are compact; closed subsets of compact sets are compact; **Tychonoff:** arbitrary products of compact spaces are compact.
- **Connected:** not a union of two disjoint non-empty open sets. **Path-connected** ⇒ connected. Continuous images of connected sets are connected (⇒ IVT).
- Separation axioms, countability axioms, **Urysohn's lemma**, metrisation theorems.

### Practice 45
1. Is $(0,1)$ compact? $[0,1]$? 2. Show $[0,1]$ and $(0,1)$ are not homeomorphic. 3. Show $\mathbb R$ and $\mathbb R^2$ are not homeomorphic.

**Answers:** 1) No (cover by $(\frac1n, 1)$ has no finite subcover); yes (Heine–Borel). 2) Compactness is preserved by homeomorphisms. 3) Removing a point disconnects $\mathbb R$ but not $\mathbb R^2$.

---

## Chapter 46: Numerical Methods

- **Root finding:** bisection (slow, safe), Newton (fast, quadratic convergence near a simple root), secant.
- **Interpolation:** Lagrange polynomials, splines.
- **Numerical integration:** trapezoidal rule (error $O(h^2)$), **Simpson's rule** $\int_a^bf\approx\frac{h}{3}[f_0 + 4f_1 + 2f_2 + 4f_3 + \dots + f_n]$ (error $O(h^4)$), Gaussian quadrature.
- **ODEs:** Euler's method $y_{n+1} = y_n + hf(x_n, y_n)$ (first order); **Runge–Kutta 4** (fourth order).
- **Linear algebra:** LU decomposition, iterative methods (Jacobi, Gauss–Seidel, conjugate gradient), power iteration for the largest eigenvalue.
- **Floating-point arithmetic:** rounding error, catastrophic cancellation, condition numbers.

### Practice 46
1. Use Euler's method with $h = 0.1$ for $y' = y$, $y(0) = 1$, to estimate $y(0.2)$. 2. Simpson's rule with 2 intervals for $\int_0^2x^3dx$.

**Answers:** 1) $1.1^2 = 1.21$ (exact $e^{0.2}\approx1.2214$) 2) $\frac13[0 + 4(1) + 8] = 4$ — exact, since Simpson is exact for cubics.

> **Checkpoint V:** Prove that the image of a compact set under a continuous function is compact; prove every group of prime order is cyclic; diagonalise $\begin{pmatrix}1&2\\2&1\end{pmatrix}$ (eigenvalues 3, −1); evaluate $\int_0^{2\pi}\frac{d\theta}{2 + \cos\theta}$ by residues (answer $\frac{2\pi}{\sqrt3}$).

---

# PART VI — GRADUATE MATHEMATICS

> At this level a single chapter would normally be a full year-long course and a 400-page textbook. These chapters give you the **map**: the core definitions, the landmark theorems, why they matter, and a few exercises to test your understanding. Use the reading list (Appendix D) for the full treatment.

---

## Chapter 47: Measure Theory and Lebesgue Integration

### 47.1 Why a new integral?
The Riemann integral fails for functions like $\mathbf 1_{\mathbb Q}$ (1 on rationals, 0 on irrationals), and it handles limits badly. Lebesgue's idea: **slice the range, not the domain**.

### 47.2 σ-algebras and measures
A **σ-algebra** $\mathcal F$ on $X$ contains $X$ and is closed under complements and countable unions. A **measure** $\mu:\mathcal F\to[0,\infty]$ has $\mu(\emptyset) = 0$ and is **countably additive**: $\mu(\bigsqcup A_i) = \sum\mu(A_i)$.
- **Lebesgue measure** on $\mathbb R$: $\mu([a,b]) = b - a$. Countable sets have measure zero — so $\mu(\mathbb Q) = 0$.
- **Carathéodory extension theorem** builds measures from outer measures.
- **Vitali set:** using the Axiom of Choice, there exist non-measurable sets — not every set can be given a length.
- The **Cantor set** is uncountable yet has measure zero.

### 47.3 The Lebesgue integral
For simple functions $s = \sum c_i\mathbf 1_{A_i}$: $\int s\,d\mu = \sum c_i\mu(A_i)$. For $f\ge0$ measurable: $\int f = \sup\{\int s: 0\le s\le f\}$. Then $\int\mathbf 1_{\mathbb Q}\,d\mu = 0$.

### 47.4 The convergence theorems (the whole point)
- **Monotone Convergence:** $0\le f_n\uparrow f$ ⇒ $\int f_n\to\int f$.
- **Fatou's lemma:** $\int\liminf f_n\le\liminf\int f_n$.
- **Dominated Convergence:** $f_n\to f$ a.e. and $|f_n|\le g$ with $\int g < \infty$ ⇒ $\int f_n\to\int f$.
- **Fubini–Tonelli:** swap the order of integration (non-negative or absolutely integrable).

### 47.5 $L^p$ spaces
$L^p = \{f: \int|f|^p < \infty\}$ (functions equal a.e. are identified), $\|f\|_p = (\int|f|^p)^{1/p}$.
- **Hölder:** $\int|fg|\le\|f\|_p\|g\|_q$, $\frac1p + \frac1q = 1$. **Minkowski:** triangle inequality.
- **Riesz–Fischer:** $L^p$ is complete.
- **Radon–Nikodym theorem:** if $\nu\ll\mu$, then $\nu(A) = \int_Af\,d\mu$ for some density $f = \frac{d\nu}{d\mu}$.

### Exercises 47
1. Show every countable set has Lebesgue measure 0. 2. Compute $\lim_{n\to\infty}\int_0^1\frac{n x}{1 + n^2x^2}dx$ using DCT or directly. 3. Give an example where $f_n\to0$ pointwise but $\int f_n\not\to0$.

**Hints/Answers:** 1) Cover the $k$th point with an interval of length $\varepsilon/2^k$. 2) Substituting $u = nx$: $\frac{\ln(1 + n^2)}{2n}\to0$. 3) $f_n = n\mathbf 1_{(0, 1/n)}$: $\int f_n = 1$ for all $n$.

---

## Chapter 48: Functional Analysis

> Linear algebra in infinite dimensions. The language of quantum mechanics, PDEs, signal processing, and optimisation.

### 48.1 Normed, Banach and Hilbert spaces
- **Banach space:** complete normed vector space ($L^p$, $C[a,b]$ with sup norm, $\ell^p$).
- **Hilbert space:** complete inner-product space ($L^2$, $\ell^2$). Every Hilbert space has an orthonormal basis; **Parseval:** $\|x\|^2 = \sum|\langle x, e_n\rangle|^2$.
- **Projection theorem:** every closed subspace has an orthogonal complement.
- **Riesz representation:** every bounded linear functional on a Hilbert space is $x\mapsto\langle x, y\rangle$ for a unique $y$.

### 48.2 The "big four" theorems
1. **Hahn–Banach:** bounded linear functionals extend from subspaces with the same norm (so the dual space is rich).
2. **Uniform Boundedness (Banach–Steinhaus):** pointwise-bounded families of operators are uniformly bounded.
3. **Open Mapping:** surjective bounded operators between Banach spaces are open.
4. **Closed Graph:** an operator with closed graph is bounded.
(2–4 rely on the **Baire category theorem**.)

### 48.3 Operators and spectral theory
- Bounded operators, adjoints $T^*$, self-adjoint, unitary, compact operators.
- **Spectral theorem for compact self-adjoint operators:** $T = \sum\lambda_n\langle\cdot, e_n\rangle e_n$, eigenvalues $\to0$ — the infinite-dimensional version of $A = QDQ^T$.
- Unbounded operators (e.g. $\frac{d}{dx}$) — the setting of quantum mechanics.

### 48.4 Fourier analysis
On $L^2[-\pi,\pi]$, $\{e^{inx}/\sqrt{2\pi}\}$ is an orthonormal basis: every $f$ is a **Fourier series** $f = \sum c_ne^{inx}$, $c_n = \frac{1}{2\pi}\int_{-\pi}^{\pi}f(x)e^{-inx}dx$.
**Fourier transform** $\hat f(\xi) = \int f(x)e^{-2\pi ix\xi}dx$; **Plancherel** ($\|\hat f\|_2 = \|f\|_2$); convolution becomes multiplication. Weak topologies, distributions (generalised functions like the Dirac delta), Sobolev spaces.

### Exercises 48
1. Show that in a Hilbert space $\|x + y\|^2 + \|x - y\|^2 = 2\|x\|^2 + 2\|y\|^2$. 2. Use Parseval on the Fourier series of $f(x) = x$ on $[-\pi,\pi]$ to show $\sum\frac{1}{n^2} = \frac{\pi^2}{6}$. 3. Show the unit ball in $\ell^2$ is not compact.

**Hints:** 1) Expand both inner products. 2) $x = \sum_{n\ge1}\frac{2(-1)^{n+1}}{n}\sin nx$; Parseval gives $\frac1\pi\int_{-\pi}^{\pi}x^2dx = \sum\frac{4}{n^2}$, i.e. $\frac{2\pi^2}{3} = 4\sum\frac1{n^2}$. 3) The basis vectors $e_n$ satisfy $\|e_n - e_m\| = \sqrt2$: no convergent subsequence.

---

## Chapter 49: Advanced Algebra — Rings, Modules, Fields, Galois Theory

### 49.1 Rings and modules
- Prime and maximal ideals: $R/P$ is a domain ⇔ $P$ prime; $R/M$ is a field ⇔ $M$ maximal.
- Localisation, Noetherian rings, **Hilbert's basis theorem** ($R$ Noetherian ⇒ $R[x]$ Noetherian).
- **Modules** = vector spaces over a ring. **Structure theorem for finitely generated modules over a PID** — it implies both the classification of finite abelian groups and the Jordan normal form.
- Tensor products, exact sequences, $\text{Hom}$ (foundations of homological algebra).

### 49.2 Field extensions
- Degree $[L:K] = \dim_KL$; **tower law** $[M:K] = [M:L][L:K]$.
- Algebraic vs transcendental elements; minimal polynomials. $[\mathbb Q(\sqrt[3]2):\mathbb Q] = 3$.
- **Ruler-and-compass constructions:** constructible numbers lie in towers of degree $2^k$, so doubling the cube ($\sqrt[3]{2}$) and trisecting $60°$ are impossible. Squaring the circle is impossible because $\pi$ is transcendental.
- Splitting fields, algebraic closure, **finite fields** $\mathbb F_{p^n}$ (exist and are unique for each prime power; used in coding theory and cryptography).

### 49.3 Galois theory
For a Galois extension $L/K$, the **Galois group** $\text{Gal}(L/K)$ is the group of automorphisms of $L$ fixing $K$.
**Fundamental Theorem of Galois Theory:** there is an inclusion-reversing bijection between subgroups of $\text{Gal}(L/K)$ and intermediate fields $K\subseteq F\subseteq L$.
**Solvability by radicals:** a polynomial is solvable by radicals ⇔ its Galois group is a **solvable group**. $S_5$ is not solvable, and $x^5 - 4x + 2$ has Galois group $S_5$ — so it **cannot be solved by radicals**.

### Exercises 49
1. Find $[\mathbb Q(\sqrt2,\sqrt3):\mathbb Q]$ and its Galois group. 2. Show $x^2 + x + 1$ is irreducible over $\mathbb F_2$ and build $\mathbb F_4$. 3. Why is a regular 7-gon not constructible?

**Answers:** 1) 4; $\mathbb Z_2\times\mathbb Z_2$ 2) It has no roots in $\mathbb F_2$ (degree 2 ⇒ irreducible); $\mathbb F_4 = \mathbb F_2[x]/(x^2 + x + 1) = \{0, 1, \alpha, \alpha + 1\}$ 3) $\cos\frac{2\pi}{7}$ has degree 3 over $\mathbb Q$, not a power of 2.

---

## Chapter 50: Differential Geometry and Manifolds

### 50.1 Curves and surfaces (classical)
- Curves: arc length, **curvature** $\kappa$, torsion $\tau$; the Frenet–Serret frame.
- Surfaces: first and second fundamental forms, principal curvatures, **Gaussian curvature** $K = \kappa_1\kappa_2$.
- **Theorema Egregium (Gauss):** $K$ depends only on distances within the surface — so you cannot flatten an orange peel without tearing (sphere $K > 0$, plane $K = 0$), which is why every flat map of the Earth distorts.
- **Gauss–Bonnet:** $\int_MK\,dA = 2\pi\chi(M)$ — geometry (curvature) determines topology (Euler characteristic).

### 50.2 Smooth manifolds
A **manifold** is a space that looks locally like $\mathbb R^n$ (charts, smooth transition maps). Examples: spheres $S^n$, tori, $SO(3)$ (rotations), projective spaces.
- Tangent spaces $T_pM$, vector fields, flows, Lie brackets.
- **Differential forms** and the exterior derivative $d$ ($d^2 = 0$).
- **Generalised Stokes' theorem:**
$$\int_M d\omega = \int_{\partial M}\omega$$
This single formula contains the FTC, Green, Stokes and Gauss theorems.
- **de Rham cohomology** $H^k_{dR}(M) = \frac{\ker d}{\text{im}\, d}$ — detects holes using calculus.

### 50.3 Riemannian geometry and Lie groups
- **Riemannian metric**, geodesics, Levi-Civita connection, Riemann curvature tensor. General relativity is written in this language: $G_{\mu\nu} = 8\pi T_{\mu\nu}$.
- **Lie groups** (groups that are manifolds, e.g. $SO(n)$, $SU(n)$) and their **Lie algebras** — the mathematics of continuous symmetry and the Standard Model of physics.

### Exercises 50
1. Curvature of a circle of radius $R$. 2. Verify Gauss–Bonnet for the unit sphere ($\chi = 2$). 3. Show $d(f\,dx + g\,dy) = (g_x - f_y)\,dx\wedge dy$ and relate it to Green's theorem.

**Answers:** 1) $\kappa = 1/R$ 2) $K = 1$, area $4\pi = 2\pi\cdot2$ ✓ 3) $df\wedge dx = f_y\,dy\wedge dx = -f_y\,dx\wedge dy$; Stokes for this 1-form on a planar region *is* Green's theorem.

---

## Chapter 51: Algebraic Topology

> Turn topological questions ("are these spaces the same?") into algebraic ones ("are these groups isomorphic?").

### 51.1 Homotopy and the fundamental group
- Two maps are **homotopic** if one can be continuously deformed into the other.
- The **fundamental group** $\pi_1(X, x_0)$ = loops at $x_0$ up to homotopy, with concatenation.
  $\pi_1(\mathbb R^n) = 0$, $\pi_1(S^1) = \mathbb Z$ (winding number), $\pi_1(S^2) = 0$, $\pi_1(\text{torus}) = \mathbb Z^2$.
- **Covering spaces** correspond to subgroups of $\pi_1$ (a Galois-like correspondence).
- **Seifert–van Kampen theorem** computes $\pi_1$ of glued spaces.

**Applications:**
- **Brouwer fixed point theorem:** every continuous $f: D^2\to D^2$ has a fixed point. (If not, you could retract the disc onto its boundary circle, contradicting $\pi_1(D^2) = 0\neq\mathbb Z = \pi_1(S^1)$.)
- Fundamental Theorem of Algebra (another proof).

### 51.2 Homology
**Simplicial/singular homology** $H_n(X)$ counts $n$-dimensional holes. $H_n(S^k) = \mathbb Z$ for $n = 0, k$ ($k\geq1$), else 0.
- **Euler characteristic** $\chi = \sum(-1)^n\text{rank}\,H_n = V - E + F$.
- Long exact sequences, Mayer–Vietoris, cohomology and cup products, Poincaré duality.
- **Hairy ball theorem:** every continuous tangent vector field on $S^2$ vanishes somewhere — you can't comb a hairy ball flat (and at any moment there is somewhere on Earth with no wind).

### 51.3 Higher homotopy and beyond
$\pi_n(X)$, fibrations, $\pi_3(S^2) = \mathbb Z$ (Hopf fibration), spectral sequences, K-theory. The **Poincaré conjecture** (every simply connected closed 3-manifold is $S^3$) was proved by Perelman (2003).

### Exercises 51
1. Compute $\chi$ for the sphere, the torus, and the surface of genus $g$. 2. Why is $\mathbb R^2\setminus\{0\}$ not homeomorphic to $\mathbb R^2$? 3. Show that a retraction $D^n\to S^{n-1}$ cannot exist using $H_{n-1}$.

**Answers:** 1) $2$, $0$, $2 - 2g$ 2) $\pi_1 = \mathbb Z$ vs $0$ 3) The inclusion followed by the retraction would be the identity on $H_{n-1}(S^{n-1}) = \mathbb Z$ but factor through $H_{n-1}(D^n) = 0$.

---

## Chapter 52: Partial Differential Equations

### 52.1 The three classical equations
| Type | Equation | Models | Behaviour |
|---|---|---|---|
| Elliptic | $\nabla^2u = 0$ (Laplace) | steady temperature, electrostatics | smooth, max principle |
| Parabolic | $u_t = k\nabla^2u$ (heat) | diffusion | smooths instantly, irreversible |
| Hyperbolic | $u_{tt} = c^2\nabla^2u$ (wave) | vibrations, light, sound | finite speed, preserves singularities |

### 52.2 Classical methods
- **Separation of variables + Fourier series.** Heat equation on $[0, L]$ with $u = 0$ at the ends:
$$u(x,t) = \sum_{n=1}^\infty b_n e^{-k(n\pi/L)^2t}\sin\frac{n\pi x}{L}$$
- **d'Alembert's solution** of the 1D wave equation: $u = F(x - ct) + G(x + ct)$.
- **Fourier transform** methods; the **heat kernel** $\frac{1}{\sqrt{4\pi kt}}e^{-x^2/4kt}$.
- **Green's functions**, the method of characteristics (first-order PDEs), Sturm–Liouville theory.

### 52.3 Modern theory
Weak solutions, Sobolev spaces $H^k$, the Lax–Milgram theorem, energy estimates, regularity theory, nonlinear PDE (Navier–Stokes — a Millennium Prize problem), calculus of variations (Euler–Lagrange equations: the minimiser of $\int L(x, u, u')dx$ satisfies $\frac{\partial L}{\partial u} - \frac{d}{dx}\frac{\partial L}{\partial u'} = 0$).

### Exercises 52
1. Verify $u = e^{-k t}\sin x$ solves $u_t = ku_{xx}$. 2. Solve $u_{tt} = u_{xx}$ with $u(x,0) = \sin x$, $u_t(x, 0) = 0$. 3. Find the Euler–Lagrange equation for $\int\sqrt{1 + y'^2}\,dx$ (shortest path).

**Answers:** 1) $u_t = -ke^{-kt}\sin x = ku_{xx}$ ✓ 2) $u = \sin x\cos t$ 3) $\frac{d}{dx}\frac{y'}{\sqrt{1+y'^2}} = 0\Rightarrow y' = $ const: straight lines.

---

## Chapter 53: Advanced Probability (Measure-Theoretic)

- A **probability space** $(\Omega,\mathcal F, P)$ is a measure space with $P(\Omega) = 1$; random variables are measurable functions; $E[X] = \int X\,dP$.
- Modes of convergence: almost sure ⇒ in probability ⇒ in distribution; $L^p$ ⇒ in probability.
- **Borel–Cantelli lemmas**, Kolmogorov's 0–1 law, the **Strong Law of Large Numbers**.
- **Characteristic functions** $\varphi_X(t) = E[e^{itX}]$ and Lévy's continuity theorem → a rigorous proof of the CLT.
- **Conditional expectation** $E[X\mid\mathcal G]$ (via Radon–Nikodym), **martingales** (fair games), optional stopping, martingale convergence.
- **Brownian motion**, Itô calculus: $d(f(B_t)) = f'(B_t)\,dB_t + \frac12f''(B_t)\,dt$ (the extra term is what makes stochastic calculus different) → stochastic differential equations and the Black–Scholes formula in finance.

### Exercises 53
1. Show that if $\sum P(A_n) < \infty$ then a.s. only finitely many $A_n$ occur. 2. Show that a simple symmetric random walk $S_n$ is a martingale. 3. Use Itô's formula to compute $d(B_t^2)$.

**Answers:** 1) $P(\limsup A_n)\le\sum_{n\ge N}P(A_n)\to0$ 2) $E[S_{n+1}\mid S_n] = S_n + \frac12(1) + \frac12(-1) = S_n$ 3) $2B_t\,dB_t + dt$

---

## Chapter 54: Gateways to Research

### 54.1 Algebraic geometry
Geometry of solution sets of polynomial equations. Affine and projective varieties; **Hilbert's Nullstellensatz** (a dictionary between ideals and geometric sets); schemes (Grothendieck); elliptic curves $y^2 = x^3 + ax + b$ — they have a group law, were central to the proof of **Fermat's Last Theorem** (Wiles, 1995), and are used in modern cryptography (ECC).

### 54.2 Category theory
The mathematics of mathematical structure. **Categories** (objects + arrows), **functors** (structure-preserving maps between categories, e.g. $\pi_1$: Spaces → Groups), **natural transformations**, universal properties, limits/colimits, **adjunctions**, the **Yoneda lemma**. It unifies algebra, topology and logic, and underlies functional programming.

### 54.3 Representation theory
Study groups by how they act linearly: $\rho: G\to GL(V)$. **Maschke's theorem**, **Schur's lemma**, character theory (orthogonality relations; the number of irreducible representations equals the number of conjugacy classes). Applications: chemistry (molecular symmetry), particle physics, the Langlands program.

### 54.4 Other living fields
Analytic number theory, arithmetic geometry, dynamical systems and chaos, ergodic theory, harmonic analysis, mathematical logic and model theory, set theory (forcing, large cardinals), combinatorics (Ramsey theory, probabilistic method, additive combinatorics), optimisation and convex analysis, information theory, mathematical physics, geometric group theory, low-dimensional topology, knot theory, operator algebras, homotopy type theory.

### 54.5 How to begin research
1. Master one area deeply (2–3 graduate textbooks).
2. Read survey articles, then recent papers on arXiv.org.
3. Re-prove known results in your own way; ask "what if I change this hypothesis?"
4. Find a mentor/advisor; attend seminars (many are online).
5. Learn LaTeX and a proof assistant (Lean) — the future of rigorous mathematics.

> **Graduate qualifying-exam checkpoint:** Can you state and prove: Dominated Convergence, Hahn–Banach, the Fundamental Theorem of Galois Theory, $\pi_1(S^1) = \mathbb Z$, the Cauchy integral formula, and the Spectral Theorem for compact self-adjoint operators? If yes, you are ready for research-level reading.

---

# PART VII — APPENDICES

---

## Appendix A: Symbols and Notation

| Symbol | Meaning | Symbol | Meaning |
|---|---|---|---|
| $\mathbb N,\mathbb Z,\mathbb Q,\mathbb R,\mathbb C$ | naturals, integers, rationals, reals, complex | $\in$, $\notin$ | is / is not an element of |
| $\subseteq$, $\subset$ | subset, proper subset | $\cup$, $\cap$ | union, intersection |
| $\emptyset$ | empty set | $A\setminus B$ | set difference |
| $\forall$, $\exists$ | for all, there exists | $\exists!$ | there exists exactly one |
| $\Rightarrow$, $\iff$ | implies, if and only if | $\neg,\wedge,\vee$ | not, and, or |
| $\sum$, $\prod$ | sum, product | $n!$ | factorial |
| $\binom nk$ | binomial coefficient | $\lvert x\rvert$ | absolute value / size |
| $\lfloor x\rfloor$, $\lceil x\rceil$ | floor, ceiling | $a\mid b$ | $a$ divides $b$ |
| $a\equiv b\pmod n$ | congruence | $\gcd$, $\text{lcm}$ | greatest common divisor, least common multiple |
| $f: A\to B$ | function from A to B | $f\circ g$ | composition |
| $f^{-1}$ | inverse function | $\lim$ | limit |
| $f'$, $\frac{dy}{dx}$ | derivative | $\frac{\partial f}{\partial x}$ | partial derivative |
| $\int$, $\oint$ | integral, closed contour integral | $\nabla$ | gradient (nabla) |
| $\nabla\cdot$, $\nabla\times$ | divergence, curl | $\nabla^2$, $\Delta$ | Laplacian |
| $\vec v$, $\mathbf v$ | vector | $\lVert v\rVert$ | norm |
| $\langle u,v\rangle$ | inner product | $A^T$, $A^*$ | transpose, adjoint |
| $\det$, $\text{tr}$ | determinant, trace | $\ker$, $\text{im}$ | kernel, image |
| $\cong$ | isomorphic | $\simeq$ | homotopy equivalent |
| $\trianglelefteq$ | normal subgroup | $G/N$ | quotient |
| $\infty$ | infinity | $\aleph_0$ | cardinality of $\mathbb N$ |
| $\sim$ | equivalent / asymptotic | $O(\cdot)$, $o(\cdot)$ | big-O, little-o |
| $\mathbb P$, $E$, $\text{Var}$ | probability, expectation, variance | ∎ or $\square$ | end of proof |

---

## Appendix B: Master Formula Sheet

**Algebra**
- $(a\pm b)^2 = a^2\pm2ab + b^2$; $a^2 - b^2 = (a-b)(a+b)$; $a^3\pm b^3 = (a\pm b)(a^2\mp ab + b^2)$
- Quadratic formula: $x = \frac{-b\pm\sqrt{b^2 - 4ac}}{2a}$
- $\log_a(xy) = \log_ax + \log_ay$; $\log_ax^n = n\log_ax$; $\log_ax = \frac{\ln x}{\ln a}$
- AP: $S_n = \frac n2(2a + (n-1)d)$; GP: $S_n = a\frac{r^n - 1}{r - 1}$, $S_\infty = \frac{a}{1-r}$
- $(a+b)^n = \sum_{k=0}^n\binom nk a^{n-k}b^k$

**Geometry & trigonometry**
- Circle: $C = 2\pi r$, $A = \pi r^2$. Sphere: $V = \frac43\pi r^3$, $S = 4\pi r^2$. Cone: $V = \frac13\pi r^2h$. Cylinder: $V = \pi r^2h$
- $\sin^2x + \cos^2x = 1$; $\sin2x = 2\sin x\cos x$; $\cos2x = 1 - 2\sin^2x$
- $\sin(A\pm B) = \sin A\cos B\pm\cos A\sin B$; $\cos(A\pm B) = \cos A\cos B\mp\sin A\sin B$
- Sine rule $\frac{a}{\sin A} = 2R$; cosine rule $c^2 = a^2 + b^2 - 2ab\cos C$
- $e^{i\theta} = \cos\theta + i\sin\theta$

**Calculus**
- $(fg)' = f'g + fg'$; $(f/g)' = \frac{f'g - fg'}{g^2}$; $(f\circ g)' = (f'\circ g)\cdot g'$
- $\int u\,dv = uv - \int v\,du$; $\int_a^bf = F(b) - F(a)$
- Taylor: $f(x) = \sum\frac{f^{(n)}(a)}{n!}(x-a)^n$
- $e^x = \sum\frac{x^n}{n!}$; $\sin x = x - \frac{x^3}{3!} + \frac{x^5}{5!} - \cdots$; $\cos x = 1 - \frac{x^2}{2!} + \frac{x^4}{4!} - \cdots$
- $\int_{-\infty}^\infty e^{-x^2}dx = \sqrt\pi$; $\sum_{n\ge1}\frac1{n^2} = \frac{\pi^2}{6}$

**Linear algebra**
- $\det\begin{pmatrix}a&b\\c&d\end{pmatrix} = ad - bc$; $A^{-1} = \frac{1}{ad - bc}\begin{pmatrix}d&-b\\-c&a\end{pmatrix}$
- $\det(A - \lambda I) = 0$; rank + nullity = $n$; $A = PDP^{-1}$; $A = U\Sigma V^T$

**Probability**
- $P(A\mid B) = \frac{P(A\cap B)}{P(B)}$; Bayes $P(A\mid B) = \frac{P(B\mid A)P(A)}{P(B)}$
- Binomial: mean $np$, variance $np(1-p)$; Poisson: mean = variance = $\lambda$
- Normal density $\frac{1}{\sigma\sqrt{2\pi}}e^{-(x-\mu)^2/(2\sigma^2)}$; CLT: $\bar X\approx N(\mu,\sigma^2/n)$

---

## Appendix C: The Greek Alphabet

| Letter | Name | Common use | Letter | Name | Common use |
|---|---|---|---|---|---|
| $\alpha$ | alpha | angles, roots | $\nu$ | nu | frequency |
| $\beta$ | beta | angles, coefficients | $\xi$ | xi | variable |
| $\gamma$ | gamma | Euler's constant | $\pi$ | pi | 3.14159… |
| $\delta,\Delta$ | delta | small change | $\rho$ | rho | density, correlation |
| $\varepsilon$ | epsilon | small positive number | $\sigma,\Sigma$ | sigma | standard deviation, sum |
| $\zeta$ | zeta | Riemann zeta | $\tau$ | tau | torsion, time |
| $\eta$ | eta | efficiency | $\varphi,\phi$ | phi | golden ratio, totient, angle |
| $\theta$ | theta | angles | $\chi$ | chi | Euler characteristic, $\chi^2$ |
| $\kappa$ | kappa | curvature | $\psi$ | psi | wave function |
| $\lambda$ | lambda | eigenvalues, rates | $\omega,\Omega$ | omega | angular frequency, sample space |
| $\mu$ | mu | mean, measure | $\iota$, $\upsilon$, $o$ | iota, upsilon, omicron | rarely used |

---

## Appendix D: Recommended Books per Level

**Foundations (Parts I–II)**
- NCERT Mathematics, Classes 1–8 (free online)
- *Khan Academy* (free, Arithmetic through Pre-Algebra)
- Gelfand & Shen, *Algebra*

**High school (Part III)**
- NCERT Mathematics, Classes 9–12; R.D. Sharma / R.S. Aggarwal for practice
- S.L. Loney, *Plane Trigonometry* and *Coordinate Geometry*
- Hall & Knight, *Higher Algebra*
- Art of Problem Solving: *Introduction to Algebra*, *Counting & Probability*, *Precalculus*

**Calculus (Part IV)**
- Stewart, *Calculus*; Thomas, *Calculus*
- Spivak, *Calculus* (rigorous — a bridge to analysis)
- Apostol, *Calculus* Vols. 1–2
- Simmons, *Differential Equations with Applications and Historical Notes*
- 3Blue1Brown, *Essence of Calculus* (YouTube)

**Undergraduate (Part V)**
- Proofs: Velleman, *How to Prove It*; Hammack, *Book of Proof* (free)
- Linear algebra: Strang, *Introduction to Linear Algebra* (and MIT OCW 18.06); Axler, *Linear Algebra Done Right*
- Analysis: Abbott, *Understanding Analysis*; Rudin, *Principles of Mathematical Analysis*
- Algebra: Pinter, *A Book of Abstract Algebra*; Dummit & Foote, *Abstract Algebra*; Artin, *Algebra*
- Discrete: Rosen, *Discrete Mathematics*
- Number theory: Niven–Zuckerman–Montgomery; Burton, *Elementary Number Theory*
- Probability & statistics: Blitzstein & Hwang, *Introduction to Probability* (free); Wasserman, *All of Statistics*
- Complex analysis: Needham, *Visual Complex Analysis*; Stein & Shakarchi, *Complex Analysis*
- Topology: Munkres, *Topology*

**Graduate (Part VI)**
- Measure theory: Folland, *Real Analysis*; Royden; Stein & Shakarchi, *Real Analysis*
- Functional analysis: Kreyszig (accessible); Brezis; Conway
- Algebra: Lang, *Algebra*; Atiyah–Macdonald, *Commutative Algebra*
- Differential geometry: do Carmo; Lee, *Introduction to Smooth Manifolds*
- Algebraic topology: Hatcher, *Algebraic Topology* (free)
- PDE: Evans, *Partial Differential Equations*
- Probability: Durrett, *Probability: Theory and Examples* (free)
- Algebraic geometry: Hartshorne; Vakil, *The Rising Sea* (free)
- Category theory: Riehl, *Category Theory in Context* (free)

**Free online courses:** MIT OpenCourseWare (18.01–18.06, 18.100, 18.701…), NPTEL (free IIT/IISc courses), Khan Academy, and the Lean "Natural Number Game" (an introduction to proof assistants).

---

## Appendix E: A Study Plan and Self-Assessment Checklists

### E.1 Daily routine (1.5–2 hours)
1. **15 min:** review yesterday's notes and redo one problem from memory.
2. **45 min:** read a new section with pencil and paper; re-derive every example.
3. **45 min:** exercises (at least 5; ensure at least one is hard).
4. **5 min:** write a 3-line summary in your own words.

**Weekly:** one "mixed review" session with problems from all previous chapters (spaced repetition beats cramming).

### E.2 Self-assessment checklists
Tick each when you can do it **without notes**.

**Level 1 — Primary/Middle**
- [ ] Four operations on fractions and decimals
- [ ] Percentages, ratio, simple and compound interest
- [ ] Integers and exponent laws
- [ ] Solve linear equations and 2×2 systems
- [ ] Pythagoras, areas and volumes

**Level 2 — High school**
- [ ] Factorise polynomials; solve quadratics three ways
- [ ] Sketch and transform the basic functions
- [ ] Logs and exponentials; trig identities and equations
- [ ] Permutations, combinations, binomial theorem, conditional probability, Bayes
- [ ] Complex numbers in polar form; vectors; 3×3 determinants
- [ ] Proof by induction and by contradiction

**Level 3 — Calculus**
- [ ] Limits, including L'Hôpital
- [ ] All derivative rules; optimisation and related rates
- [ ] Integration by substitution, parts and partial fractions
- [ ] Series convergence tests; Taylor series
- [ ] Partial derivatives, multiple integrals, the vector calculus theorems
- [ ] Solve first-order and constant-coefficient second-order ODEs

**Level 4 — Undergraduate**
- [ ] Write clean $\varepsilon$–$\delta$ and $\varepsilon$–$N$ proofs
- [ ] Rank–nullity, diagonalisation, the spectral theorem, SVD
- [ ] Group theory up to the isomorphism theorems and Sylow
- [ ] Modular arithmetic, CRT, RSA
- [ ] CLT and hypothesis testing
- [ ] Contour integration with residues
- [ ] Compactness and connectedness

**Level 5 — Graduate**
- [ ] Lebesgue integral and convergence theorems
- [ ] Hilbert/Banach space theory; the big four theorems
- [ ] Galois correspondence
- [ ] Manifolds, differential forms, Stokes
- [ ] Fundamental group and homology computations
- [ ] Classical PDE solution methods; Sobolev spaces

---

### A Final Word

Every mathematician once struggled with fractions. The difference between people who "are good at maths" and those who aren't is mostly **time spent with a pencil, patience with confusion, and refusing to skip steps**. Feeling stuck is normal — it's what learning feels like from the inside. Come back to a hard problem tomorrow; your brain keeps working on it overnight.

*Start at Chapter 1. Do every exercise. Keep going.*

---
**End of book.**
