---
{"dg-publish":true,"permalink":"/semester-1/calculus-and-analytical-geometry/week-5-week-6/","dg-note-properties":{}}
---

## Slope of a Line & Its Types

The **slope** ($m$) measures the steepness and direction of a straight line, defined as the ratio of vertical change ("rise") to horizontal change ("run"):

$$m = \frac{\Delta y}{\Delta x} = \frac{y_2 - y_1}{x_2 - x_1} = \tan(\theta)$$

where $\theta$ is the angle of inclination measured counterclockwise from the positive $x$-axis.

```
  Positive Slope         Negative Slope           Zero Slope           Undefined Slope
     m > 0                  m < 0                   m = 0                 m = undefined
       ^                      ^                       ^                        ^
       │   /                  │ \                     │                        │  │
       │  /                   │  \             ───────┼───────                 │  │
       │ /                    │   \                   │                        │  │
  ─────┴────>            ─────┴────>             ─────┴────>              ─────┴──┼──>
```

|**Type**|**Condition**|**Description**|**Behavior**|
|---|---|---|---|
|**Positive Slope**|$m > 0$|Slants upwards from left to right ($\theta < 90^\circ$).|As $x$ increases, $y$ increases.|
|**Negative Slope**|$m < 0$|Slants downwards from left to right ($90^\circ < \theta < 180^\circ$).|As $x$ increases, $y$ decreases.|
|**Zero Slope**|$m = 0$|Horizontal line ($\theta = 0^\circ$).|$y$ remains constant as $x$ changes.|
|**Undefined Slope**|Division by $0$|Vertical line ($\theta = 90^\circ$).|$x$ remains constant while $y$ changes.|

## Secant, Tangent, and Normal Lines

```
                        /  [Normal Line]
                       /
                      /     * (a, f(a))
  ───────────────────*────────────────── [Tangent Line]
                    / \
                   /   \___ f(x)
                  /
       *─────────* [Secant Line]
     (x1, y1)  (x2, y2)
```

> [!NOTE]
> - **Secant Line**: A straight line passing through **two distinct points** $(x_1, f(x_1))$ and $(x_2, f(x_2))$ on a curve. Its slope represents the **average rate of change** over that interval.
>     
> - **Tangent Line**: A straight line that touches a curve at a **single specific point** $(a, f(a))$ without crossing it locally. Its slope represents the **instantaneous rate of change** (the derivative) at $x = a$.
>     
> - **Normal Line**: A line **perpendicular** to the tangent line at the exact point of contact $(a, f(a))$.

### Slopes & Equations

> [!NOTE]
> If $m_{\tan} = f'(a)$ is the slope of the tangent line at $(a, f(a))$:
> 
> - **Tangent Line Equation**:
>     
>     $$y - f(a) = f'(a)(x - a)$$
>     
> - **Normal Line Equation** (since $m_{\text{normal}} \cdot m_{\tan} = -1$):
>     
>     $$y - f(a) = -\frac{1}{f'(a)}(x - a) \quad \text{(for } f'(a) \neq 0\text{)}$$
>     

## Rates of Change & Physical Meaning

> [!NOTE]
> ### Average vs. Instantaneous Rate of Change
> 
> - **Average Rate of Change**: Measures how much a quantity changes on average over a given interval $[a, b]$.
>     
>     $$\text{Average Rate of Change} = \frac{\Delta y}{\Delta x} = \frac{f(b) - f(a)}{b - a}$$
>     
> - **Instantaneous Rate of Change**: Measures the exact rate at which a quantity changes at a specific instant ($x = a$). This is obtained by shrinking the interval size to zero using limits:
>     
>     $$\text{Instantaneous Rate of Change} = \lim_{\Delta x \to 0} \frac{\Delta y}{\Delta x} = f'(a)$$
>     

### Physical Interpretation of Derivatives

> [!NOTE]
> In physics and real-world application, the derivative represents the sensitive response of one quantity relative to another:
> 
> - **Position ($s(t)$) $\rightarrow$ Velocity ($v(t)$)**: $v(t) = \frac{ds}{dt}$ (Rate of change of displacement over time).
>     
> - **Velocity ($v(t)$) $\rightarrow$ Acceleration ($a(t)$)**: $a(t) = \frac{dv}{dt} = \frac{d^2s}{dt^2}$ (Rate of change of velocity over time).
>     
> - **Economics**: Marginal Cost $MC = \frac{dC}{dx}$ (Cost to produce one additional unit $x$).
>     
> - **Thermodynamics**: Heat Flow $\frac{dQ}{dt}$ (Rate of heat transfer over time).

## Graphical Interpretation of the Derivative

> [!NOTE]
> Graphically, the derivative of a function $y = f(x)$ evaluated at a point $x = a$:
> 
> 1. Is the **slope of the tangent line** to the curve at $(a, f(a))$.
>     
> 2. Indicates the **local direction** of the function at that point:
>     
>     - If $f'(a) > 0$, the function is **increasing** at $x = a$.
>         
>     - If $f'(a) < 0$, the function is **decreasing** at $x = a$.
>         
>     - If $f'(a) = 0$, the function has a **horizontal tangent** (potential peak, trough, or inflection point).
>         

## Derivative from First Principles (Definition of Derivative)

> [!NOTE]
> The **First Principle Method** computes the derivative directly from its limit-based fundamental definition:
> 
> $$f'(x) = \lim_{h \to 0} \frac{f(x+h) - f(x)}{h}$$
> 
> ### Standard Steps for First Principle:
> 
> 1. Substitute $x+h$ into the function to find $f(x+h)$.
>     
> 2. Set up the difference quotient: $\frac{f(x+h) - f(x)}{h}$.
>     
> 3. Simplify the numerator algebraically to cancel out the single $h$ in the denominator.
>     
> 4. Evaluate the limit by taking $h \to 0$.
>     

## Questions with Step-by-Step Solutions

> [!question] Practice Questions
> ### Question 1: First Principle Method
> 
> Find the derivative of $f(x) = x^2 + 3x$ using the First Principle Method.
> 
> **Solution:**
> 
> 1. State the formula:
>     
>     $$f'(x) = \lim_{h \to 0} \frac{f(x+h) - f(x)}{h}$$
>     
> 2. Evaluate $f(x+h)$:
>     
>     $$f(x+h) = (x+h)^2 + 3(x+h) = x^2 + 2xh + h^2 + 3x + 3h$$
>     
> 1. Subtract $f(x)$ from $f(x+h)$:
>     
>     $$f(x+h) - f(x) = (x^2 + 2xh + h^2 + 3x + 3h) - (x^2 + 3x) = 2xh + h^2 + 3h$$
>     
> 2. Form the difference quotient and factor out $h$:
>     
>     $$\frac{f(x+h) - f(x)}{h} = \frac{h(2x + h + 3)}{h} = 2x + h + 3$$
>     
> 3. Evaluate the limit as $h \to 0$:
>     
>     $$f'(x) = \lim_{h \to 0} (2x + h + 3) = 2x + 0 + 3 = 2x + 3$$
>     
> 
> ### Question 2: Tangent and Normal Lines
> 
> Find the equations of the tangent line and normal line to the curve $f(x) = x^3 - 2x$ at the point where $x = 2$.
> 
> **Solution:**
> 
> 4. Find the $y$-coordinate at $x = 2$:
>     
>     $$f(2) = (2)^3 - 2(2) = 8 - 4 = 4 \implies \text{Point } P = (2, 4)$$
>     
> 5. Compute the derivative $f'(x)$ to find the slope function:
>     
>     $$f'(x) = \frac{d}{dx}(x^3 - 2x) = 3x^2 - 2$$
>     
> 6. Calculate the tangent slope ($m_{\tan}$) at $x = 2$:
>     
>     $$m_{\tan} = f'(2) = 3(2)^2 - 2 = 12 - 2 = 10$$
>     
> 7. Find the Tangent Line equation:
>     
>     $$y - 4 = 10(x - 2) \implies y - 4 = 10x - 20 \implies y = 10x - 16$$
>     
> 8. Find the Normal Line equation ($m_{\text{normal}} = -\frac{1}{m_{\tan}} = -\frac{1}{10}$):
>     
>     $$y - 4 = -\frac{1}{10}(x - 2)$$
>     
>     $$10(y - 4) = -(x - 2) \implies 10y - 40 = -x + 2 \implies x + 10y - 42 = 0$$
>     
> 
> ### Question 3: Average vs. Instantaneous Rate of Change
> 
> The distance $s$ (in meters) traveled by a moving object after time $t$ (in seconds) is given by $s(t) = 5t^2 + 2t$.
> 
> 9. Find the average velocity of the object between $t = 1\text{ s}$ and $t = 3\text{ s}$.
>     
> 10. Find the instantaneous velocity of the object at $t = 3\text{ s}$.
>     
> 
> **Solution:**
> 
> 11. **Average Velocity:**
>     
>     Calculate position at $t = 1$ and $t = 3$:
>     
>     $$s(1) = 5(1)^2 + 2(1) = 7\text{ m}$$
>     
>     $$s(3) = 5(3)^2 + 2(3) = 45 + 6 = 51\text{ m}$$
>     
>     Apply average rate formula:
>     
>     $$\text{Average Velocity} = \frac{s(3) - s(1)}{3 - 1} = \frac{51 - 7}{2} = \frac{44}{2} = 22\text{ m/s}$$
>     
> 12. **Instantaneous Velocity:**
>     
>     Compute derivative $v(t) = s'(t)$:
>     
>     $$v(t) = \frac{d}{dt}(5t^2 + 2t) = 10t + 2$$
>     
>     Evaluate at $t = 3$:
>     
>     $$v(3) = 10(3) + 2 = 32\text{ m/s}$$

[[Semester - 1/Calculus & Analytical Geometry/WEEK 3 - WEEK 4\|WEEK 3 - WEEK 4]]