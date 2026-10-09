---
{"dg-publish":true,"permalink":"/semester-1/calculus-and-analytical-geometry/week-3-week-4/","dg-note-properties":{}}
---

# WEEK 3 

## Composite and Inverse Functions

> [!NOTE] Explanation
> ## 1. Composite Functions
> 
> ### Definition
> 
> A **composite function** is formed when one function is applied to the result of another function. If $f$ and $g$ are two functions, the composite function $(f \circ g)(x)$, read as "$f$ of $g$ of $x$", is defined as:
> 
> $$(f \circ g)(x) = f(g(x))$$
> 
> Here, $x$ is first input into $g(x)$, and the resulting output becomes the input for $f(x)$. The domain of $f \circ g$ consists of all $x$ in the domain of $g$ such that $g(x)$ is in the domain of $f$.
> 
> ### Questions & Solutions
> 
> #### **Question 1**
> 
> Given $f(x) = 2x + 3$ and $g(x) = x^2 - 1$:
> 
> 1. Find $(f \circ g)(x)$.
>     
> 2. Evaluate $(g \circ f)(2)$.
>     
> 
> **Solution:**
> 
> 1. **Find $(f \circ g)(x)$:**
>     
>     $$(f \circ g)(x) = f(g(x)) = f(x^2 - 1)$$
>     
>     Substitute $x^2 - 1$ into $f(x)$:
>     
>     $$(f \circ g)(x) = 2(x^2 - 1) + 3 = 2x^2 - 2 + 3 = 2x^2 + 1$$
>     
> 2. **Evaluate $(g \circ f)(2)$:**
>     
>     First, find $f(2)$:
>     
>     $$f(2) = 2(2) + 3 = 7$$
>     
>     Now, substitute $f(2) = 7$ into $g(x)$:
>     
>     $$g(f(2)) = g(7) = 7^2 - 1 = 49 - 1 = 48$$
>     
> 
> #### **Question 2**
> 
> Given $f(x) = \sqrt{x + 2}$ and $g(x) = 3x - 5$:
> 
> 1. Find $(f \circ g)(x)$.
>     
> 2. State the domain of $(f \circ g)(x)$.
>     
> 
> **Solution:**
> 
> 1. **Find $(f \circ g)(x)$:**
>     
>     $$(f \circ g)(x) = f(g(x)) = f(3x - 5)$$
>     
>     Substitute $3x - 5$ into $f(x)$:
>     
>     $$(f \circ g)(x) = \sqrt{(3x - 5) + 2} = \sqrt{3x - 3}$$
>     
> 2. **Find the Domain:**
>     
>     For a square root function with real outputs, the expression under the radical must be non-negative:
>     
>     $$3x - 3 \ge 0 \implies 3x \ge 3 \implies x \ge 1$$
>     
>     **Domain:** $[1, \infty)$ or $\{x \in \mathbb{R} \mid x \ge 1\}$.
>     
> 
> ## 2. Inverse Functions
> 
> ### Definition
> 
> An **inverse function**, denoted as $f^{-1}(x)$, reverses the operation performed by $f(x)$. If $f(a) = b$, then $f^{-1}(b) = a$.
> 
> For a function to have an inverse, it must be **one-to-one** (bijective), meaning every output corresponds to exactly one input (it passes both the vertical and horizontal line tests).
> 
> The defining property of an inverse function is:
> 
> $$f(f^{-1}(x)) = x \quad \text{and} \quad f^{-1}(f(x)) = x$$

### Questions & Solutions

> [!question] Practice Questions
> 
> #### **Question 1**
> 
> Find the inverse of the linear function $f(x) = 3x - 7$.
> 
> **Solution:**
> 
> 1. Replace $f(x)$ with $y$:
>     
>     $$y = 3x - 7$$
>     
> 2. Swap $x$ and $y$ to set up the inverse relationship:
>     
>     $$x = 3y - 7$$
>     
> 1. Solve for $y$:
>     
>     $$x + 7 = 3y \implies y = \frac{x + 7}{3}$$
>     
> 2. Replace $y$ with $f^{-1}(x)$:
>     
>     $$f^{-1}(x) = \frac{x + 7}{3}$$
>     
> 
> #### **Question 2**
> 
> Find the inverse of the rational function $f(x) = \frac{2x + 1}{x - 3}$ for $x \neq 3$.
> 
> **Solution:**
> 
> 3. Set $y = f(x)$:
>     
>     $$y = \frac{2x + 1}{x - 3}$$
>     
> 4. Swap $x$ and $y$:
>     
>     $$x = \frac{2y + 1}{y - 3}$$
>     
> 5. Clear the denominator and solve for $y$:
>     
>     $$x(y - 3) = 2y + 1$$
>     
>     $$xy - 3x = 2y + 1$$
>     
>     $$xy - 2y = 3x + 1$$
>     
>     $$y(x - 2) = 3x + 1$$
>     
>     $$y = \frac{3x + 1}{x - 2}$$
>     
> 6. Express in inverse notation:
>     
>     $$f^{-1}(x) = \frac{3x + 1}{x - 2} \quad (x \neq 2)$$
>     
> 

## 3. Limit of a Function

> [!NOTE] Explanation
> ### Concept & Definition
> 
> The **limit** of a function $f(x)$ describes the behavior of $f(x)$ as the input $x$ approaches a specific value $c$, without necessarily reaching $c$ itself.
> 
> Written as:
> 
> $$\lim_{x \to c} f(x) = L$$
> 
> This reads: _"The limit of $f(x)$ as $x$ approaches $c$ is equal to $L$."_
> 
> It means that as $x$ gets arbitrarily close to $c$ (from both left and right), $f(x)$ gets arbitrarily close to the real number $L$.
> 
> ### Key Properties
> 
> - **One-Sided Limits:**
>     
>     - Left-hand limit: $\lim_{x \to c^-} f(x)$ ($x$ approaches $c$ from values smaller than $c$).
>         
>     - Right-hand limit: $\lim_{x \to c^+} f(x)$ ($x$ approaches $c$ from values larger than $c$).
>         
> - **Existence Condition:** A two-sided limit exists if and only if both one-sided limits exist and are equal:
>     
>     $$\lim_{x \to c} f(x) = L \iff \lim_{x \to c^-} f(x) = \lim_{x \to c^+} f(x) = L$$
>     
> 

## 4. Function Graphs

> [!NOTE] Explanation
> A **graph of a function** $f$ is the visual collection of all coordinate pairs $(x, y)$ in the Cartesian plane such that $y = f(x)$.
> 
> ### Core Features of Graphs
> 
> - **Domain & Range:** The domain spans all valid horizontal values ($x$-axis), while the range spans all achievable vertical values ($y$-axis).
>     
> - **Intercepts:**
>     
>     - **$x$-intercepts (Roots/Zeros):** Points where the graph crosses the $x$-axis ($f(x) = 0$).
>         
>     - **$y$-intercept:** Point where the graph crosses the $y$-axis ($x = 0$).
>         
> - **Symmetry:**
>     
>     - **Even Functions:** $f(-x) = f(x)$ — Symmetric across the $y$-axis (e.g., $f(x) = x^2$).
>         
>     - **Odd Functions:** $f(-x) = -f(x)$ — Symmetric about the origin (e.g., $f(x) = x^3$).
>         
> 
> ### Common Basic Function Shapes
> 
> - **Linear:** $f(x) = mx + b$ $\rightarrow$ Straight line with slope $m$.
>     
> - **Quadratic:** $f(x) = x^2$ $\rightarrow$ U-shaped parabola.
>     
> - **Absolute Value:** $f(x) = \vert{}x\vert{}$ $\rightarrow$ V-shaped graph.
>     
> - **Cubic:** $f(x) = x^3$ $\rightarrow$ S-curve passing through the origin.
>     
> - **Square Root:** $f(x) = \sqrt{x}$ $\rightarrow$ Half-parabola opening to the right, starting at $(0,0)$.
>     
> 
> ### Graph Transformations (from $y = f(x)$)
> 
> - **Vertical Shift:** $y = f(x) + k$ (Shifts up by $k$ if $k > 0$, down if $k < 0$).
>     
> - **Horizontal Shift:** $y = f(x - h)$ (Shifts right by $h$ if $h > 0$, left if $h < 0$).
>     
> - **Reflection:**
>     
>     - $y = -f(x)$ reflects across the $x$-axis.
>         
>     - $y = f(-x)$ reflects across the $y$-axis.
>         
> - **Inverse Function Graphing:** The graph of $f^{-1}(x)$ is the exact reflection of the graph of $f(x)$ across the line $y = x$.

# WEEK 4

## 1. Core Intuition: What is a Limit?

> [!NOTE]
> A **limit** describes the value a function $f(x)$ approaches as $x$ gets infinitely close to a specific number $a$.
> 
> $$\lim_{x \to a} f(x) = L$$
> 
> _It does not matter what $f(x)$ actually equals at $x = a$—only what it approaches as you get nearby._
> 

## 2. One-Sided Limits (Right-Hand & Left-Hand)

> [!NOTE]
> To approach a point $a$, you can come from two directions on the number line:
> 
> - **Left-Hand Limit (LHL):** Approaching $a$ from values smaller than $a$ ($x \to a^-$).
>     
>     $$\lim_{x \to a^-} f(x) = L_1$$
>     
> - **Right-Hand Limit (RHL):** Approaching $a$ from values larger than $a$ ($x \to a^+$).
>     
>     $$\lim_{x \to a^+} f(x) = L_2$$
>     

## 3. Existence & Uniqueness of a Limit

> [!NOTE]
> ### Existence Rule
> 
> The general limit $\lim_{x \to a} f(x)$ exists if and only if **both one-sided limits exist and are equal**:
> 
> $$\lim_{x \to a} f(x) = L \iff \lim_{x \to a^-} f(x) = \lim_{x \to a^+} f(x) = L$$
> 
> If $\text{LHL} \neq \text{RHL}$, or if either side shoots off to $\pm\infty$ without settling, the limit **does not exist (DNE)**.
> 
> ### Uniqueness Rule
> 
> If a limit exists at a point, **its value is unique**. A function cannot approach two different limits simultaneously at the same target point.

## 4. Fundamental Theorem of Limits (Properties)

> [!NOTE]
> 
> If $\lim_{x \to a} f(x) = L$ and $\lim_{x \to a} g(x) = M$, the following operational rules hold:
> 
> 1. **Sum/Difference Rule:** $\lim_{x \to a} [f(x) \pm g(x)] = L \pm M$
>     
> 2. **Constant Multiple Rule:** $\lim_{x \to a} [c \cdot f(x)] = c \cdot L$
>     
> 3. **Product Rule:** $\lim_{x \to a} [f(x) \cdot g(x)] = L \cdot M$
>     
> 4. **Quotient Rule:** $\lim_{x \to a} \frac{f(x)}{g(x)} = \frac{L}{M} \quad (\text{provided } M \neq 0)$
>     
> 5. **Power Rule:** $\lim_{x \to a} [f(x)]^n = L^n$
>     
> 6. **Root Rule:** $\lim_{x \to a} \sqrt[n]{f(x)} = \sqrt[n]{L} \quad (\text{if } n \text{ is even, requires } L > 0)$
>     
> 

## 5. Key Limit Formulas

> [!NOTE]
> 
> ### Algebraic Limits
> 
> - Direct Substitution: For any continuous function (like polynomials), $\lim_{x \to a} P(x) = P(a)$.
>     
> - Standard Algebraic Identity:
>     
>     $$\lim_{x \to a} \frac{x^n - a^n}{x - a} = n a^{n-1}$$
>     
> 
> ### Trigonometric Limits
> 
> - $$\lim_{x \to 0} \frac{\sin x}{x} = 1 \quad (\text{where } x \text{ is in radians})$$
>     
> - $$\lim_{x \to 0} \frac{1 - \cos x}{x} = 0$$
>     
> - $$\lim_{x \to 0} \frac{\tan x}{x} = 1$$
>     
> 
> ### Exponential & Logarithmic Limits
> 
> - $$\lim_{x \to 0} \frac{e^x - 1}{x} = 1$$
>     
> - $$\lim_{x \to 0} \frac{a^x - 1}{x} = \ln(a) \quad (a > 0)$$
>     
> - $$\lim_{x \to 0} \frac{\ln(1 + x)}{x} = 1$$
>     
> - Definition of $e$:
>     
>     $$\lim_{x \to \infty} \left(1 + \frac{1}{x}\right)^x = e \quad \text{or} \quad \lim_{x \to 0} (1 + x)^{\frac{1}{x}} = e$$
>     

## 6. Limits at Infinity ($\to \infty$)

> [!NOTE]
> When evaluating behavior as $x \to \infty$ or $x \to -\infty$:
> 
> - **Fundamental Rule:** $\lim_{x \to \infty} \frac{1}{x^n} = 0 \quad (\text{for } n > 0)$.
>     
> 
> ### Algebraic Rational Functions $\lim_{x \to \infty} \frac{P(x)}{Q(x)}$:
> 
> Divide every term by the highest power of $x$ in the denominator:
> 
> 1. **Degree of Numerator < Degree of Denominator:** Limit is **$0$**.
>     
>     $$\lim_{x \to \infty} \frac{2x + 1}{x^2 + 3} = 0$$
>     
> 2. **Degree of Numerator = Degree of Denominator:** Limit is the **ratio of leading coefficients**.
>     
>     $$\lim_{x \to \infty} \frac{5x^2 + 2}{3x^2 - 1} = \frac{5}{3}$$
>     
> 1. **Degree of Numerator > Degree of Denominator:** Limit is **$\pm\infty$** (DNE).
>     
> 

## 7. Continuity & Discontinuity

> [!NOTE]
> ### What is Continuity? (Easy Explanation)
> 
> Graphically, a function is **continuous** if you can draw its graph without lifting your pencil off the paper.
> 
> ### The 3 Conditions for Continuity at $x = a$:
> 
> A function $f(x)$ is continuous at $x = a$ if and only if:
> 
> 1. **$f(a)$ is defined** (the point exists).
>     
> 2. **$\lim_{x \to a} f(x)$ exists** ($\text{LHL} = \text{RHL}$).
>     
> 3. **$\lim_{x \to a} f(x) = f(a)$** (the limit equals the actual point value).
>     
> 
> ### Types of Discontinuity
> 
> When any of the 3 conditions fail, $f(x)$ has a discontinuity:
> 
> 4. **Removable (Point) Discontinuity:**
>     
>     - The limit exists, but $f(a)$ is undefined or doesn't equal the limit.
>         
>     - _Visual:_ A smooth line with a single "hole" in it.
>         
> 5. **Jump Discontinuity:**
>     
>     - LHL and RHL both exist, but they are not equal ($\text{LHL} \neq \text{RHL}$).
>         
>     - _Visual:_ The graph "jumps" vertically from one piece to another (common in piecewise functions).
>         
> 6. **Infinite (Essential) Discontinuity:**
>     
>     - One or both one-sided limits go to $\pm\infty$.
>         
>     - _Visual:_ A vertical asymptote (e.g., $f(x) = \frac{1}{x}$ at $x = 0$).

> [!question] Questions
> ## 1. One-Sided Limits & Existence
> 
> **Question:**
> 
> Consider the piecewise function:
> 
> $$f(x) = \begin{cases} 2x + 1 & \text{if } x < 2 \\ 7 - x & \text{if } x \ge 2 \end{cases}$$
> 
> 1. Find $\lim_{x \to 2^-} f(x)$.
>     
> 2. Find $\lim_{x \to 2^+} f(x)$.
>     
> 3. Does $\lim_{x \to 2} f(x)$ exist? Explain.
>     
> 
> **Answer:**
> 
> 4. **Left-Hand Limit ($x \to 2^-$):** Use $f(x) = 2x + 1$:
>     
>     $$\lim_{x \to 2^-} (2x + 1) = 2(2) + 1 = 5$$
>     
> 5. **Right-Hand Limit ($x \to 2^+$):** Use $f(x) = 7 - x$:
>     
>     $$\lim_{x \to 2^+} (7 - x) = 7 - 2 = 5$$
>     
> 6. **Existence:** Since $\text{LHL} = \text{RHL} = 5$, the general limit **exists** and equals $5$:
>     
>     $$\lim_{x \to 2} f(x) = 5$$
>     
> 
> ## 2. Fundamental Properties of Limits
> 
> **Question:**
> 
> Given that $\lim_{x \to 3} g(x) = 4$ and $\lim_{x \to 3} h(x) = -2$, evaluate:
> 
> $$\lim_{x \to 3} \frac{[g(x)]^2 + 2h(x)}{g(x) - h(x)}$$
> 
> **Answer:**
> 
> Apply the Sum, Power, Constant Multiple, and Quotient Rules:
> 
> $$\lim_{x \to 3} \frac{[g(x)]^2 + 2h(x)}{g(x) - h(x)} = \frac{(\lim_{x \to 3} g(x))^2 + 2(\lim_{x \to 3} h(x))}{\lim_{x \to 3} g(x) - \lim_{x \to 3} h(x)}$$
> 
> Substitute the known values:
> 
> $$= \frac{(4)^2 + 2(-2)}{4 - (-2)} = \frac{16 - 4}{4 + 2} = \frac{12}{6} = 2$$
> 
> ## 3. Algebraic Limits
> 
> **Question:**
> 
> Evaluate the following algebraic limit:
> 
> $$\lim_{x \to 4} \frac{x^2 - 16}{x - 4}$$
> 
> **Answer:**
> 
> Direct substitution gives $\frac{4^2 - 16}{4 - 4} = \frac{0}{0}$ (an indeterminate form). Factor the numerator:
> 
> $$\lim_{x \to 4} \frac{(x - 4)(x + 4)}{x - 4}$$
> 
> Cancel out the common term $(x - 4)$:
> 
> $$= \lim_{x \to 4} (x + 4) = 4 + 4 = 8$$
> 
> ## 4. Trigonometric Limits
> 
> **Question:**
> 
> Evaluate:
> 
> $$\lim_{x \to 0} \frac{\sin(5x)}{3x}$$
> 
> **Answer:**
> 
> Use the fundamental trigonometric limit identity $\lim_{u \to 0} \frac{\sin u}{u} = 1$.
> 
> Multiply numerator and denominator to get $5x$ inside the sine argument:
> 
> $$\lim_{x \to 0} \left( \frac{5}{3} \cdot \frac{\sin(5x)}{5x} \right) = \frac{5}{3} \lim_{5x \to 0} \left( \frac{\sin(5x)}{5x} \right) = \frac{5}{3} (1) = \frac{5}{3}$$
> 
> ## 5. Exponential & Logarithmic Limits
> 
> **Question:**
> 
> Evaluate:
> 
> $$\lim_{x \to 0} \frac{e^{4x} - 1}{x}$$
> 
> **Answer:**
> 
> Recall the formula $\lim_{u \to 0} \frac{e^u - 1}{u} = 1$. Let $u = 4x$:
> 
> $$\lim_{x \to 0} \frac{e^{4x} - 1}{x} = \lim_{x \to 0} \left( 4 \cdot \frac{e^{4x} - 1}{4x} \right) = 4 (1) = 4$$
> 
> ## 6. Limits at Infinity
> 
> **Question:**
> 
> Evaluate:
> 
> $$\lim_{x \to \infty} \frac{3x^3 - 5x + 2}{7x^3 + 2x^2 - 1}$$
> 
> **Answer:**
> 
> Divide every term by the highest power of $x$ in the denominator ($x^3$):
> 
> $$\lim_{x \to \infty} \frac{\frac{3x^3}{x^3} - \frac{5x}{x^3} + \frac{2}{x^3}}{\frac{7x^3}{x^3} + \frac{2x^2}{x^3} - \frac{1}{x^3}} = \lim_{x \to \infty} \frac{3 - \frac{5}{x^2} + \frac{2}{x^3}}{7 + \frac{2}{x} - \frac{1}{x^3}}$$
> 
> Since $\lim_{x \to \infty} \frac{1}{x^n} = 0$:
> 
> $$= \frac{3 - 0 + 0}{7 + 0 - 0} = \frac{3}{7}$$
> 
> ## 7. Continuity & Discontinuity Analysis
> 
> **Question:**
> 
> Determine whether $g(x)$ is continuous at $x = 3$. If discontinuous, state the type of discontinuity.
> 
> $$g(x) = \begin{cases} \frac{x^2 - 9}{x - 3} & \text{if } x \neq 3 \\ 4 & \text{if } x = 3 \end{cases}$$
> 
> **Answer:**
> 
> Check the 3 conditions for continuity at $x = 3$:
> 
> 7. **$g(3)$ is defined:**
>     
>     $$g(3) = 4$$
>     
> 8. **$\lim_{x \to 3} g(x)$ exists:**
>     
>     $$\lim_{x \to 3} \frac{x^2 - 9}{x - 3} = \lim_{x \to 3} \frac{(x - 3)(x + 3)}{x - 3} = \lim_{x \to 3} (x + 3) = 6$$
>     
> 9. **Compare limit to value:**
>     
>     $$\lim_{x \to 3} g(x) = 6 \neq g(3) = 4$$
>     
> 
> **Conclusion:**
> 
> $g(x)$ fails condition 3. Therefore, $g(x)$ is **discontinuous at $x = 3$**.
> 
> Because the limit exists ($\text{LHL} = \text{RHL} = 6$) but does not equal $g(3)$, this is a **removable (point) discontinuity**.

[[Semester - 1/Calculus & Analytical Geometry/WEEK 5 - WEEK 6\|WEEK 5 - WEEK 6]]