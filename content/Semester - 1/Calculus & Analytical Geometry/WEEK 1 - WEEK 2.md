# WEEK 1

### CALCULUS : 

> [!NOTE] Definition and Usecase :
> Important branch of mathematics that deals with change, motion and acceleration.
> - IMPORTANCE OF CALCULUS : Calculus is important because it provides mathematical tools for understanding change,motion,growth and accumulation. It has applications in many fields.
> - Key Importance of Calculus :
> 1. Science & Physics : Used to study motion,velocity,acceleration,force, and energy.
> 2. Engineering : Helps in designing structures,machines,electrical systems, and optimizing engineering processes.
> 3. Economics & Business : Used to analyze costs, revenue,profit,growth, and optimization.

> [!NOTE] Types
> - DIFFERENTIAL CALCULUS : Deals with the rate of change of a quantity and the slope of the curves. The derivatives is its fundamental. Helps us determine how quickly one quantity changes with respect to another. Example : Finding the speed of a moving car from its position 
> - INTEGRAL CALCULUS : Deals with the accumulation of quantities, areas under the curves and total quantities. Its fundamental concept is integration. Helps us find the total amount accumulated when small quantities are added together. Example : Finding the area under a curve.
> - INTEGRATION : Combines continuous pieces to calculate the total accumulated amount. Geometrically, it measures the area under the curve across an interval.

### Functions : 

> [!NOTE] What is Function ?
> In mathematics, a **function** is a relation between a set of inputs and a set of permissible outputs, where **each input is related to exactly one output**.
> - SETS : - Sets do not contain duplicate elements (e.g., $\{1, 2, 2, 3\}$ is simplified to $\{1, 2, 3\}$).
> 

| Set Type                          | Description                                                                                        |
| --------------------------------- | -------------------------------------------------------------------------------------------------- |
| Empty Set ($\emptyset$ or $\{\}$) | A set containing no elements                                                                       |
| Universal Set ($U$)               | A set containing all possible elements under consideration                                         |
| Subset ($A \subseteq B$)          | Set $A$ where every element is also in set $B$                                                     |
| Power Set ($\mathcal{P}(A)$)      | The set of all subsets of $A$. If $\vert{}A\vert{} = n$, then $\vert{}\mathcal{P}(A)\vert{} = 2^n$ |

> [!QUESTION]  Q : $A = \{1, 2\}, B = \{a, b\} \text{ find } A \times B = ?$
>
> $\text{Sol:- } A \times B = \{(1, a), (1, b), (2, a), (2, b)\} \quad \because 2^n \Rightarrow 2^4 = 16$
> $O(A \times B) = 4$
> $R_1 = \emptyset, R_2 = \{(1, a)\}, R_3 = \{(1, b)\}, R_4 = \{(2, a)\}, R_5 = \{(2, b)\}$
> $R_6 = \{(1, a), (1, b)\}, R_7 = \{(2, a), (2, b)\}, R_8 = \{(1, a), (2, a)\}$
> $R_9 = \{(1, a), (2, b)\}, R_{10} = \{(1, b), (2, a)\}, R_{11} = \{(1, b), (2, b)\}$
> $R_{12} = \{(1, a), (1, b), (2, a)\}, R_{13} = \{(1, a), (1, b), (2, b)\}$
> $R_{14} = \{(2, a), (2, b), (1, a)\}, R_{15} = \{(2, a), (2, b), (2, b)\}$
> $R_{16} = \{(1, a), (1, b), (2, a), (2, b)\}$

> [!NOTE] Terminologies :
> 
>1. **Cartesian Product ($A \times B$):** The set of all possible ordered pairs where the first element belongs to $A$ and the second to $B$. Since $O(A \times B) = 4$, the number of possible binary relations is $2^4 = 16$.
> 2. **Relations ($R_1$ to $R_{16}$):** Subsets of the Cartesian product $A \times B$. The image lists all 16 possible relations derived from the power set.
> 3. **Domain:** The set of all input elements available in the domain set.
> 4. **Pre-image:** An individual input element in the domain that maps to a specific element in the target set.
> 5. **Co-domain:** The entire set of potential output values.
> 6. **Range (Images):** The subset of the co-domain containing elements actually mapped from inputs.

![[Gemini_Generated_Image_tdutostdutostdut.jpeg|487]]

### Types of Function :

> [!NOTE] Types
> ### 1. Mapping / Set-Theoretic Functions
> 
> - **One-to-One (Injective):** Every distinct element in the domain maps to a distinct, unique element in the codomain. No two inputs share the same output ($f(a) = f(b) \implies a = b$).
>     
>     - _Example:_ $f(x) = 3x + 2$
>         
> - **Many-to-One:** Two or more distinct inputs from the domain map to the exact same output in the codomain.
>     
>     - _Example:_ $f(x) = x^2$ (since both $x = 2$ and $x = -2$ output $y = 4$)
>         
> - **Onto (Surjective):** Every element in the codomain is mapped to by at least one element in the domain. The range equals the codomain.
>     
>     - _Example:_ $f(x) = x^3$ (where domain and codomain are all real numbers $\mathbb{R}$)
>         
> - **Bijective:** A function that is simultaneously **both One-to-One and Onto**. It establishes a perfect one-to-one correspondence, meaning every element in the domain maps to a unique element in the codomain, and no codomain element is left over.
>     
>     - _Example:_ $f(x) = 2x - 5$ (over domain $\mathbb{R}$ and codomain $\mathbb{R}$)
>         
> 
> ### 2. Basic Algebraic & Special Functions
> 
> - **Constant Function:** Outputs the exact same fixed value $c$ regardless of the input value.
>     
>     - _Example:_ $f(x) = 7$
>         
> - **Identity Function:** Outputs the exact same value that was passed into it ($f(x) = x$).
>     
>     - _Example:_ $f(x) = x$
>         
> - **Absolute Value Function:** Outputs the non-negative magnitude (distance from zero) of a real input.
>     
>     - _Example:_ $f(x) = \vert{}x\vert{} = \begin{cases} x & \text{if } x \ge 0 \\ -x & \text{if } x < 0 \end{cases}$
>         
> - **Piecewise Function:** Defined by different sub-expressions or formulas over distinct intervals of the domain.
>     
>     - _Example:_ $f(x) = \begin{cases} x^2 & \text{if } x < 0 \\ 2x + 1 & \text{if } x \ge 0 \end{cases}$
>         
> 
> ### 3. Structural & Algebraic Form Functions
> 
> - **Polynomial Function:** Built using non-negative integer powers of $x$ combined with constant coefficients.
>     
>     - _Example:_ $f(x) = 4x^3 - 2x^2 + x - 9$
>         
> - **Rational Function:** A ratio or quotient of two polynomial functions $\frac{P(x)}{Q(x)}$ where $Q(x) \neq 0$.
>     
>     - _Example:_ $f(x) = \frac{x^2 + 3}{x - 2}$
>         
> - **Irrational Function:** Contains variables under fractional exponents or radical signs that cannot be reduced to a purely rational expression.
>     
>     - _Example:_ $f(x) = \sqrt{x^2 + 5}$
>         
> - **Transcendental Function:** Non-algebraic functions that cannot be expressed as a finite sequence of basic algebraic operations (addition, multiplication, roots). Includes trigonometric, exponential, and logarithmic forms.
>     
>     - _Example:_ $f(x) = \sin(x) + e^{2x} - \ln(x)$
>         
> 
> ### 4. Representation & Symmetry Functions
> 
> - **Explicit Function:** The dependent variable $y$ is isolated cleanly on one side of the equation in terms of the independent variable $x$.
>     
>     - _Example:_ $y = 3x^2 - 4x + 1$
>         
> - **Implicit Function:** The variables $x$ and $y$ are intertwined together in an equation without $y$ being explicitly isolated.
>     
>     - _Example:_ $x^2 + y^2 - 25 = 0$
>         
> - **Even Function:** Symmetric across the y-axis. Satisfies the property $f(-x) = f(x)$.
>     
>     - _Example:_ $f(x) = x^4 + \cos(x)$
>         
> - **Odd Function:** Symmetric with respect to the origin. Satisfies the property $f(-x) = -f(x)$.
>     
>     - _Example:_ $f(x) = x^3 + \sin(x)$

> [!question] Questions
> 
> **1)** $f(x) = -x^2 + 10$
> 
> - **Written:**
>     
>     - $\text{Sol:- } f(x) = -x^2 + 10$
>         
>     - $\text{Put } x = -x$
>         
>     - $f(-x) = -(-x)^2 + 10$
>         
>     - $f(-x) = -x^2 + 10$
>         
>     - $f(x) = f(-x) \implies -x^2 + 10 = -x^2 + 10$
>         
>     - "Hence, function is even"
>         
> - **Status:** Correct.
>     
> 
> **2)** $f(x) = x\sqrt{x^2 - 1}$
> 
> - **Written:**
>     
>     - $\text{Sol:- } f(x) = x\sqrt{x^2 - 1}$
>         
>     - $\text{Put } x = -x$
>         
>     - $f(-x) = -x\sqrt{(-x)^2 - 1} = -x\sqrt{x^2 - 1} = -f(x)$
>         
>     - "Hence odd"
>         
> - **Status:** Correct.
>     
> 
> **3)** $f(x) = \vert{}x + 4\vert{}$
> 
> - **Written:**
>     
>     - $\text{Sol:- } f(x) = \vert{}x + 4\vert{}$
>         
>     - $\text{Put } x = -x$
>         
>     - $f(-x) = \vert{}-x + 4\vert{} = \vert{}4 - x\vert{}$
>         
>     - $f(-x) \neq f(x)$, not even
>         
>     - $f(-x) \neq -f(x)$, not odd
>         
>     - "It's neither"
>         
> - **Status:** Correct.
>     
> 
> **4)** $f(x) = x + \sin(x)$
> 
> - **Written:**
>     
>     - $\text{Sol:- } f(-x) = -x + \sin(-x) = -(x + \sin(x)) = -f(x)$
>         
>     - "It's odd function"
>         
>     - Written conclusion at the bottom states $f(-x) = f(x)$.
>         
> - **Status:** Contains a mistake in the concluding statement. Since $\sin(-x) = -\sin(x)$, we have $f(-x) = -x - \sin(x) = -(x + \sin(x)) = -f(x)$. The conclusion should be written as $f(-x) = -f(x)$ instead of $f(-x) = f(x)$.
>     
> 
> **5)** $f(x) = x^3 + \cos(x)$
> 
> - **Written:**
>     
>     - $\text{Sol:- } f(-x) = (-x)^3 + \cos(-x) = -x^3 + \cos(x)$
>         
>     - "odd function" crossed out, corrected to "Neither"
>         
>     - $f(-x) \neq -f(x), f(-x) \neq f(x)$
>         
> - **Status:** Correct (the final answer is neither even nor odd because $-x^3 + \cos(x)$ is equal to neither $x^3 + \cos(x)$ nor $-(x^3 + \cos(x))$).
>     
> 
> **6)** $f(x) = x\sin(x) + \cos(x)$
> 
> - **Written:**
>     
>     - $\text{Sol:- } (-x)\sin(-x) + \cos(-x) = (-x)(-\sin(x)) + \cos(x) = x\sin(x) + \cos(x)$
>         
>     - "even function"
>         
> - **Status:** Correct.

# WEEK 2

