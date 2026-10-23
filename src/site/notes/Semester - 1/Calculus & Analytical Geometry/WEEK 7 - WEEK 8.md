---
{"dg-publish":true,"permalink":"/semester-1/calculus-and-analytical-geometry/week-7-week-8/","dg-note-properties":{}}
---

# WEEK 7

## Derivative Formulas by Theorems

### **Key Rules & Theorems**

> [!NOTE]
> - **Constant Rule:** $\frac{d}{dx}(c) = 0$
>     
>       
>     
> - **Power Rule:** $\frac{d}{dx}(x^n) = n x^{n-1}$
>     
>       
>     
> - **Sum & Difference Rule:** $\frac{d}{dx}[f(x) \pm g(x)] = f'(x) \pm g'(x)$
>     
>       
>     
> - **Product Rule:** $\frac{d}{dx}[f(x)g(x)] = f'(x)g(x) + f(x)g'(x)$
>     
>       
>     
> - **Quotient Rule:** $\frac{d}{dx}\left[\frac{f(x)}{g(x)}\right] = \frac{f'(x)g(x) - f(x)g'(x)}{[g(x)]^2}$
>     
>       
>     
> - **Chain Rule:** $\frac{d}{dx}[f(g(x))] = f'(g(x)) \cdot g'(x)$
>     
>       

    

> [!QUESTION]
> ### **Practice Questions**
> 
> 1. Find the derivative of $f(x) = 4x^5 - 3x^3 + 7x - 9$.
>     
>       
>     
> 2. Find the derivative of $h(x) = (2x^2 - 3)(5x + 1)$ using the product rule.
>     
>       
>     
> 3. Find the derivative of $y = (3x^2 - 4x)^6$ using the chain rule.
>     
>       

    

## Implicit Differentiation

### **Concept Summary**

Used when an equation cannot be easily solved explicitly for $y$ in terms of $x$. Differentiate both sides of the equation with respect to $x$, treating $y$ as a function of $x$ (meaning every time you differentiate a $y$ term, multiply by $\frac{dy}{dx}$ using the chain rule), and then isolate $\frac{dy}{dx}$.

  

### **Practice Questions**

1. Find $\frac{dy}{dx}$ for the circle equation: $x^2 + y^2 = 25$.
    
      
    
2. Find $\frac{dy}{dx}$ for the curve: $x^3 + y^3 = 6xy$.
    
      
    
3. Find $\frac{dy}{dx}$ for: $\sin(y) + x^2 = y$.
    
      
    

## Exponential and Logarithmic Derivatives

### **Key Formulas**

> [!NOTE]
> - **Natural Exponential:** $\frac{d}{dx}(e^x) = e^x$ and $\frac{d}{dx}(e^{u}) = e^{u} \cdot u'$
>     
>       
>     
> - **General Exponential:** $\frac{d}{dx}(a^x) = a^x \ln(a)$
>     
>       
>     
> - **Natural Logarithm:** $\frac{d}{dx}(\ln x) = \frac{1}{x}$ and $\frac{d}{dx}(\ln u) = \frac{1}{u} \cdot u'$
>     
>       
>     
> - **General Logarithm:** $\frac{d}{dx}(\log_a x) = \frac{1}{x \ln(a)}$
>     
>       

    

### **Practice Questions**

> [!QUESTION]
> 1. Find the derivative of $f(x) = e^{4x^2 - 3x}$.
>     
>       
>     
> 2. Find the derivative of $g(x) = \ln(x^3 + 5x)$.
>     
>       
>     
> 3. Find the derivative of $y = x^2 \cdot 3^x$.
>     
>       
>     
> 

## Indeterminate Forms & L'Hôpital's Rule

When evaluating a limit results in an indeterminate form such as $\frac{0}{0}$ or $\frac{\infty}{\infty}$, **L'Hôpital's Rule** states that:

  

$$\lim_{x \to a} \frac{f(x)}{g(x)} = \lim_{x \to a} \frac{f'(x)}{g'(x)}$$

_(provided the limit on the right exists or is infinite)._

  

### **Practice Questions**

> [!QUESTION]
> 1. Evaluate using L'Hôpital's Rule: $\lim_{x \to 0} \frac{\sin(5x)}{x}$
>     
>       
>     
> 2. Evaluate using L'Hôpital's Rule: $\lim_{x \to 1} \frac{x^3 - 1}{x^2 - 1}$
>     
>       
>     
> 3. Evaluate using L'Hôpital's Rule: $\lim_{x \to \infty} \frac{\ln(x)}{x}$

## Practice Questions

> [!QUESTION]
> ## Derivative Formulas by Theorems
> 
> ### **Question 1:** Find $f'(x)$ for $f(x) = 4x^5 - 3x^3 + 7x - 9$
> 
> - **Apply Power Rule:** $\frac{d}{dx}(x^n) = n x^{n-1}$
>     
>     $$f'(x) = 4(5x^4) - 3(3x^2) + 7(1) - 0$$
>     
>     $$\mathbf{f'(x) = 20x^4 - 9x^2 + 7}$$
>     
> 
> ### **Question 2:** Find $h'(x)$ for $h(x) = (2x^2 - 3)(5x + 1)$ using Product Rule
> 
> - **Product Rule:** $\frac{d}{dx}[u \cdot v] = u'v + uv'$
>     
> - Let $u = 2x^2 - 3 \implies u' = 4x$
>     
> - Let $v = 5x + 1 \implies v' = 5$
>     
>     $$h'(x) = (4x)(5x + 1) + (2x^2 - 3)(5)$$
>     
>     $$h'(x) = 20x^2 + 4x + 10x^2 - 15$$
>     
>     $$\mathbf{h'(x) = 30x^2 + 4x - 15}$$
>     
> 
> ### **Question 3:** Find $y'$ for $y = (3x^2 - 4x)^6$ using Chain Rule
> 
> - **Chain Rule:** $\frac{d}{dx}[u^n] = n u^{n-1} \cdot u'$
>     
> - Let $u = 3x^2 - 4x \implies u' = 6x - 4$
>     
>     $$y' = 6(3x^2 - 4x)^5 \cdot (6x - 4)$$
>     
>     $$\mathbf{y' = 6(6x - 4)(3x^2 - 4x)^5 = (36x - 24)(3x^2 - 4x)^5}$$
>     
> 
> ## Implicit Differentiation
> 
> ### **Question 1:** Find $\frac{dy}{dx}$ for $x^2 + y^2 = 25$
> 
> Differentiate both sides with respect to $x$:
> 
> $$2x + 2y \frac{dy}{dx} = 0$$
> 
> $$2y \frac{dy}{dx} = -2x$$
> 
> $$\mathbf{\frac{dy}{dx} = -\frac{x}{y}}$$
> 
> ### **Question 2:** Find $\frac{dy}{dx}$ for $x^3 + y^3 = 6xy$
> 
> Differentiate both sides with respect to $x$ (use Product Rule on $6xy$):
> 
> $$3x^2 + 3y^2 \frac{dy}{dx} = 6y + 6x \frac{dy}{dx}$$
> 
> Group $\frac{dy}{dx}$ terms on one side:
> 
> $$3y^2 \frac{dy}{dx} - 6x \frac{dy}{dx} = 6y - 3x^2$$
> 
> $$\frac{dy}{dx}(3y^2 - 6x) = 6y - 3x^2$$
> 
> $$\mathbf{\frac{dy}{dx} = \frac{6y - 3x^2}{3y^2 - 6x} = \frac{2y - x^2}{y^2 - 2x}}$$
> 
> ### **Question 3:** Find $\frac{dy}{dx}$ for $\sin(y) + x^2 = y$
> 
> Differentiate both sides with respect to $x$:
> 
> $$\cos(y) \frac{dy}{dx} + 2x = \frac{dy}{dx}$$
> 
> Isolate $\frac{dy}{dx}$:
> 
> $$2x = \frac{dy}{dx} - \cos(y) \frac{dy}{dx}$$
> 
> $$2x = \frac{dy}{dx}(1 - \cos(y))$$
> 
> $$\mathbf{\frac{dy}{dx} = \frac{2x}{1 - \cos(y)}}$$
> 
> ## Exponential and Logarithmic Derivatives
> 
> ### **Question 1:** Find $f'(x)$ for $f(x) = e^{4x^2 - 3x}$
> 
> - **Rule:** $\frac{d}{dx}(e^u) = e^u \cdot u'$
>     
> - Let $u = 4x^2 - 3x \implies u' = 8x - 3$
>     
>     $$\mathbf{f'(x) = (8x - 3)e^{4x^2 - 3x}}$$
>     
> 
> ### **Question 2:** Find $g'(x)$ for $g(x) = \ln(x^3 + 5x)$
> 
> - **Rule:** $\frac{d}{dx}(\ln u) = \frac{u'}{u}$
>     
> - Let $u = x^3 + 5x \implies u' = 3x^2 + 5$
>     
>     $$\mathbf{g'(x) = \frac{3x^2 + 5}{x^3 + 5x}}$$
>     
> 
> ### **Question 3:** Find $y'$ for $y = x^2 \cdot 3^x$
> 
> - **Rule:** Product Rule with $\frac{d}{dx}(a^x) = a^x \ln(a)$
>     
> - Let $u = x^2 \implies u' = 2x$
>     
> - Let $v = 3^x \implies v' = 3^x \ln(3)$
>     
>     $$y' = (2x)(3^x) + (x^2)(3^x \ln(3))$$
>     
>     $$\mathbf{y' = x \cdot 3^x (2 + x \ln(3))}$$
>     
> 
> ## Indeterminate Forms & L'Hôpital's Rule
> 
> ### **Question 1:** Evaluate $\lim_{x \to 0} \frac{\sin(5x)}{x}$
> 
> - Direct substitution gives $\frac{\sin(0)}{0} = \frac{0}{0}$ (Indeterminate Form).
>     
> - **Apply L'Hôpital's Rule:**
>     
>     $$\lim_{x \to 0} \frac{\frac{d}{dx}[\sin(5x)]}{\frac{d}{dx}[x]} = \lim_{x \to 0} \frac{5 \cos(5x)}{1}$$
>     
>     $$= 5 \cos(0) = 5(1) = \mathbf{5}$$
>     
> 
> ### **Question 2:** Evaluate $\lim_{x \to 1} \frac{x^3 - 1}{x^2 - 1}$
> 
> - Direct substitution gives $\frac{1-1}{1-1} = \frac{0}{0}$ (Indeterminate Form).
>     
> - **Apply L'Hôpital's Rule:**
>     
>     $$\lim_{x \to 1} \frac{\frac{d}{dx}[x^3 - 1]}{\frac{d}{dx}[x^2 - 1]} = \lim_{x \to 1} \frac{3x^2}{2x}$$
>     
>     $$= \frac{3(1)^2}{2(1)} = \mathbf{\frac{3}{2}}$$
>     
> 
> ### **Question 3:** Evaluate $\lim_{x \to \infty} \frac{\ln(x)}{x}$
> 
> - Direct substitution gives $\frac{\infty}{\infty}$ (Indeterminate Form).
>     
> - **Apply L'Hôpital's Rule:**
>     
>     $$\lim_{x \to \infty} \frac{\frac{d}{dx}[\ln(x)]}{\frac{d}{dx}[x]} = \lim_{x \to \infty} \frac{\frac{1}{x}}{1} = \lim_{x \to \infty} \frac{1}{x}$$
>     
>     $$= \frac{1}{\infty} = \mathbf{0}$$

# WEEK 8

## Increasing and Decreasing Functions

A function is **increasing** if its graph goes upwards as you move from left to right, and **decreasing** if its graph goes downwards.

```
       Increasing Function                  Decreasing Function
          Slope > 0                            Slope < 0
             ^                                    ^
             │     /                              │  \
             │    /                               │   \
             │   /                                │    \
        ─────┴──/──>                         ─────┴─────\─>
```

### The Derivative Test

Because the derivative $f'(x)$ represents the slope of the tangent line at any point:

- **Increasing**: $f'(x) > 0$ on an interval (positive slope).
    
- **Decreasing**: $f'(x) < 0$ on an interval (negative slope).
    
- **Constant / Turning Point**: $f'(x) = 0$ (horizontal line).
    

> [!QUESTION] Example
> ### Example Problem: Find Increasing/Decreasing Intervals
> 
> Determine where $f(x) = x^2 - 4x + 5$ is increasing and decreasing.
> 
> **Solution:**
> 
> 1. **Find the derivative**:
>     
>     $$f'(x) = 2x - 4$$
>     
> 2. **Find the critical point** (where $f'(x) = 0$):
>     
>     $$2x - 4 = 0 \implies 2x = 4 \implies x = 2$$
>     
> 1. **Test intervals around $x = 2$**:
>     
>     - For $x < 2$ (e.g., $x = 0$): $f'(0) = 2(0) - 4 = -4 < 0$ $\rightarrow$ **Decreasing** on $(-\infty, 2)$
>         
>     - For $x > 2$ (e.g., $x = 3$): $f'(3) = 2(3) - 4 = 2 > 0$ $\rightarrow$ **Increasing** on $(2, \infty)$
>         

## Rolle's Theorem

**The Big Idea:** If a continuous curve starts and ends at the **same height**, it must flatten out (have a horizontal tangent line where slope = 0) at least once in between.

```
    y ▲         f(a) = f(b)
      │          ___*___  ← Peak where f'(c) = 0
      │         /       \
f(a) ─┼─ *─────/─────────\* ─ f(b)
      │  a                 b
      └──────────────────────► x
```

### The 3 Required Conditions:

For a function $f(x)$ on an interval $[a, b]$:

1. $f(x)$ is **continuous** on the closed interval $[a, b]$ (no breaks or jumps).
    
2. $f(x)$ is **differentiable** on the open interval $(a, b)$ (no sharp corners).
    
3. $f(a) = f(b)$ (the start and end points have equal $y$-values).
    

### Conclusion:

There is at least one point $c$ in $(a, b)$ where the derivative is zero:

$$f'(c) = 0$$

> [!QUESTION] Example
> ### Example Problem: Rolle's Theorem
> 
> Verify Rolle's Theorem for $f(x) = x^2 - 4x + 3$ on the interval $[1, 3]$ and find $c$.
> 
> **Solution:**
> 
> 1. **Check conditions**:
>     
>     - It is a polynomial, so it is continuous on $[1, 3]$ and differentiable on $(1, 3)$.
>         
>     - $f(1) = (1)^2 - 4(1) + 3 = 0$
>         
>     - $f(3) = (3)^2 - 4(3) + 3 = 0$
>         
>     - Since $f(1) = f(3) = 0$, Rolle's Theorem applies.
>         
> 2. **Find $c$**:
>     
>     $$f'(x) = 2x - 4$$
>     
>     Set $f'(c) = 0$:
>     
>     $$2c - 4 = 0 \implies c = 2$$
>     
> 
> Since $c = 2$ lies inside the open interval $(1, 3)$, Rolle's Theorem is verified.

## Mean Value Theorem (MVT)

**The Big Idea:** The Mean Value Theorem is a slanted version of Rolle's Theorem. It says that at least one point on a smooth curve has an **instantaneous slope** equal to the **average slope** connecting its endpoints.

_Analogy:_ If you drive $100\text{ km}$ in $1\text{ hour}$ (average speed $100\text{ km/h}$), at least once during your trip your speedometer must have read exactly $100\text{ km/h}$.

```
    y ▲
      │               * (b, f(b))
      │              /
      │        *    /  ← Tangent line at x = c is parallel
      │       /    /     to secant line connecting endpoints
      │      /    /
      │     *    /
      │  (a, f(a))
      └──────────────────────► x
```

### The 2 Required Conditions:

For a function $f(x)$ on an interval $[a, b]$:

1. $f(x)$ is **continuous** on $[a, b]$.
    
2. $f(x)$ is **differentiable** on $(a, b)$.
    

### Conclusion:

There exists at least one point $c$ in $(a, b)$ where:

$$f'(c) = \frac{f(b) - f(a)}{b - a}$$

> [!QUESTION] Example
> ### Example Problem: Mean Value Theorem
> 
> Find the value of $c$ that satisfies the Mean Value Theorem for $f(x) = x^2$ on the interval $[1, 3]$.
> 
> **Solution:**
> 
> 1. **Check conditions**: $f(x) = x^2$ is continuous on $[1, 3]$ and differentiable on $(1, 3)$.
>     
> 2. **Calculate average rate of change (Secant Slope)**:
>     
>     $$f(1) = 1^2 = 1, \quad f(3) = 3^2 = 9$$
>     
>     $$\text{Average Slope} = \frac{f(3) - f(1)}{3 - 1} = \frac{9 - 1}{2} = \frac{8}{2} = 4$$
>     
> 1. **Find $c$ (Instantaneous Slope)**:
>     
>     $$f'(x) = 2x \implies f'(c) = 2c$$
>     
>     Set $f'(c)$ equal to the average slope:
>     
>     $$2c = 4 \implies c = 2$$
>     
> 
> Since $c = 2$ is inside $(1, 3)$, MVT is satisfied.
> 

## Quick Comparison Summary

|**Feature**|**Rolle's Theorem**|**Mean Value Theorem**|
|---|---|---|
|**Continuity & Differentiability**|Required on $[a, b]$ and $(a, b)$|Required on $[a, b]$ and $(a, b)$|
|**Endpoint Condition**|Requires $f(a) = f(b)$|No endpoint condition required|
|**Formula**|$f'(c) = 0$|$f'(c) = \frac{f(b) - f(a)}{b - a}$|
|**Interpretation**|Finds where slope is **horizontal**|Finds where slope equals the **secant line**|