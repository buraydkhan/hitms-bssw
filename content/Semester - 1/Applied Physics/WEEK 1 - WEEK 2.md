 # WEEK 1
## INTRODUCTION

> [!NOTE] Basics
> Physics is the fundamental branch of science concerned with the nature and properties of matter, energy, space, and time.
> 
> **Base (Fundamental) Quantities and SI Units**
> Base quantities are independent physical quantities that cannot be defined in terms of other physical quantities. They serve as the foundation for the entire metric measurement system (International System of Units, SI).

| Base Quantity       | Symbol | SI UNIT  | NOTATION |
| ------------------- | ------ | -------- | -------- |
| length              | l      | meter    | m        |
| mass                | m      | kilogram | kg       |
| time                | t      | seconds  | s        |
| temperature         | T      | kelvin   | k        |
| current             | I      | ampere   | A        |
| luminous intensity  | $I_v$  | candela  | cd       |
| amount of substance | n      | mole     | mol      |
|                     |        |          |          |

> [!NOTE] Concepts
> **Derived quantities** are physical quantities defined mathematically through combinations of base quantities.
> **Scientific Notation**
> Scientific notation is a method of writing very large or very small numbers compactly using powers of $10$.
> - **Standard Form:** $N \times 10^n$
>     - $N$ is a number greater than or equal to $1$ and less than $10$ ($1 \le N < 10$).
>     - $n$ is an integer exponent (positive for large values, negative for small values).
> - **Examples:**
>     - Speed of light: $300,000,000 \text{ m/s} = 3 \times 10^8 \text{ m/s}$
>     - Charge of an electron: $0.00000000000000000016 \text{ C} = 1.6 \times 10^{-19} \text{ C}$

## Scalars and Vectors

> [!NOTE] Introduction
> **Fundamentals of Scalars and Vectors**
> 
> - **Scalar:** A physical quantity described entirely by its magnitude (a numeric value and a unit). Examples: Mass, speed, distance, temperature.
> - **Vector:** A physical quantity that requires both a magnitude and a direction to be fully defined. Examples: Displacement, velocity, force, acceleration, momentum.
> 
> 
> **Vector Use Cases**
> 
> - **Game Development & Computer Graphics:** Calculating character movement, 
> - **Physics & Engineering:** Analyzing force distributions on bridges, trajectory motion, and fluid dynamics.
> - **Navigation & Robotics:** Determining GPS coordinates, flight paths, and robotic arm movements.

COMPARISON BETWEEN SCALAR AND VECTOR

| Feature                  | Scalar Quantity                                                         | Vector Quantity                                              |
| ------------------------ | ----------------------------------------------------------------------- | ------------------------------------------------------------ |
| Specification            | Magnitude only                                                          | Magnitude and Direction                                      |
| Algebra Rules            | Follows ordinary arithmetic ($2\text{ kg} + 3\text{ kg} = 5\text{ kg}$) | Follows vector algebra rules (head-to-tail rule, components) |
| Change in Quantity       | Changes if magnitude changes                                            | Changes if magnitude, direction, or both change              |
| Graphical Representation | Ordinary number with units                                              | Directed line segment (arrow)                                |

> [!NOTE] Characteristics & Properties of Vectors
> 
> - **Characteristics:** A vector possesses a starting point (initial point/tail), a magnitude (length of the arrow), and a direction (heading/angle).
> - **Key Properties:**
>     
>     - **Commutative Property of Addition:** $\vec{A} + \vec{B} = \vec{B} + \vec{A}$
>         
>     - **Associative Property of Addition:** $(\vec{A} + \vec{B}) + \vec{C} = \vec{A} + (\vec{B} + \vec{C})$
>         
>     - **Distributive Property:** $k(\vec{A} + \vec{B}) = k\vec{A} + k\vec{B}$ (where $k$ is a scalar)
>         
>     - **Parallel Shift:** A vector remains unchanged if translated parallel to itself without altering length or angle.

> [!NOTE] Types of Vectors
> - **Equal Vectors:** Vectors with the same magnitude and direction, regardless of initial positions.
>     
> - **Negative Vector:** A vector with equal magnitude to a given vector but pointing in the exact opposite direction ($180^\circ$ opposite).
>     
> - **Null Vector (Zero Vector):** A vector with zero magnitude and an arbitrary direction, represented as $\vec{0}$.
>     
> - **Unit Vector:** A vector of magnitude $1$ indicating a specific direction ($\hat{a} = \frac{\vec{A}}{\vert{}\vec{A}\vert{}}$). Standard unit vectors along axes are $\hat{i}, \hat{j}, \hat{k}$.
>     
> - **Position Vector:** A vector specifying the position of a point relative to the origin, written as $\vec{r} = x\hat{i} + y\hat{j} + z\hat{k}$.
>     
> - **Initial Vector:** A vector anchored at a specific starting location (also called a bound vector).
>     
> - **Collinear Vectors:** Vectors acting along the same line or parallel lines.
>     
> - **Coplanar Vectors:** Vectors lying in the same two-dimensional plane.

> [!NOTE] **Representation & Notations of Vectors**
> - **Mathematical Notation:** Written as bold text ($\mathbf{A}$), with an arrow top ($\vec{A}$), or with a bar underneath ($\underline{A}$). Magnitude is represented as $\vert{}\vec{A}\vert{}$ or simply $A$.
>     
> - **Graphical Representation:** Represented by a straight line segment with an arrowhead:
>     
>     - **Length of Arrow:** Represents magnitude (scaled).
>         
>     - **Arrowhead:** Pointing in the direction of the vector.
>         
>     - **Tail:** The starting point.

> [!NOTE] **Cartesian Plane, Rectangular Quadrants, & Trigonometry**
> - The Cartesian coordinate system divides a 2D plane into four quadrants using perpendicular axes ($X$ and $Y$).
> 
> ```
>         Y-axis
>           |
>    Q-II   |   Q-I
>   (-, +)  |  (+, +)
> ----------+---------- X-axis
>    Q-III  |   Q-IV
>   (-, -)  |  (+, -)
>           |
> ```
> 
> - **Radius Vector ($r$):** The distance from the origin $(0,0)$ to point $(x,y)$. By the **Pythagoras Theorem**:
>     
>     $$r = \sqrt{x^2 + y^2}$$
>     
> - **Trigonometric Functions:**
>     
>     $$\sin\theta = \frac{\text{Opposite}}{\text{Hypotenuse}} = \frac{y}{r}$$
>     
>     $$\cos\theta = \frac{\text{Adjacent}}{\text{Hypotenuse}} = \frac{x}{r}$$
>     
>     $$\tan\theta = \frac{\text{Opposite}}{\text{Adjacent}} = \frac{y}{x}$$

> [!NOTE] **Vector Directions & Measurement Methods**
> Vector direction is usually measured as an angle $\theta$ relative to a reference axis (typically the positive x-axis).
> 
> - **Counter-Clockwise (Anti-Clockwise):** Measured moving counter-clockwise from the positive x-axis. Standard mathematical convention; angles are **positive**.
>     
> - **Clockwise:** Measured moving clockwise from the positive x-axis or North reference. Angles are **negative** in Cartesian systems, or expressed as bearings in navigation (e.g., $090^\circ$ for East).
>     
> - **Conversion:** An anti-clockwise angle of $\theta$ corresponds to a clockwise angle of $360^\circ - \theta$.

> [!NOTE] **Addition, Subtraction, & Rectangular Components**
> **1. Graphical Method (Head-to-Tail Rule)**
> 
> To add $\vec{A}$ and $\vec{B}$, place the tail of $\vec{B}$ at the head of $\vec{A}$. The resultant $\vec{R} = \vec{A} + \vec{B}$ is drawn from the tail of $\vec{A}$ to the head of $\vec{B}$. Subtraction is done by adding the negative vector: $\vec{A} - \vec{B} = \vec{A} + (-\vec{B})$.
> 
> **2. Rectangular Components**
> 
> Any 2D vector $\vec{A}$ at angle $\theta$ with the x-axis can be resolved into two perpendicular components:
> 
> - **X-component:** $A_x = A \cos\theta$
>     
> - **Y-component:** $A_y = A \sin\theta$
>     
> - **Vector Form:** $\vec{A} = A_x\hat{i} + A_y\hat{j}$
>     
> 
> **3. Component Method for Addition/Subtraction**
> 
> Given $\vec{A} = A_x\hat{i} + A_y\hat{j}$ and $\vec{B} = B_x\hat{i} + B_y\hat{j}$:
> 
> - **Resultant Vector:** $\vec{R} = (A_x \pm B_x)\hat{i} + (A_y \pm B_y)\hat{j}$
>     
> - **Magnitude:** $R = \sqrt{R_x^2 + R_y^2}$
>     
> - **Direction Angle:** $\theta = \tan^{-1}\left(\left\vert{}\frac{R_y}{R_x}\right\vert{}\right)$ (adjusted according to quadrant sign of $R_x$ and $R_y$).

> [!NOTE] **Vector Products: Dot and Cross Product**
> ### Dot Product (Scalar Product)
> 
> Multiplies two vectors to yield a **scalar value**.
> 
> $$\vec{A} \cdot \vec{B} = \vert{}\vec{A}\vert{}\vert{}\vec{B}\vert{}\cos\theta = A_x B_x + A_y B_y + A_z B_z$$
> 
> - **Commutative:** $\vec{A} \cdot \vec{B} = \vec{B} \cdot \vec{A}$
>     
> - **Orthogonal Vectors ($\theta = 90^\circ$):** $\vec{A} \cdot \vec{B} = 0$
>     
> - **Unit Vectors:** $\hat{i} \cdot \hat{i} = \hat{j} \cdot \hat{j} = \hat{k} \cdot \hat{k} = 1$, and $\hat{i} \cdot \hat{j} = 0$
>     
> 
> ### Cross Product (Vector Product)
> 
> Multiplies two vectors to yield a **third vector** perpendicular to the plane containing both.
> 
> $$\vec{A} \times \vec{B} = (\vert{}\vec{A}\vert{}\vert{}\vec{B}\vert{}\sin\theta)\,\hat{n}$$
> 
> _(where $\hat{n}$ is the unit normal vector given by the Right-Hand Rule)_
> 
> - **Anti-Commutative:** $\vec{A} \times \vec{B} = -(\vec{B} \times \vec{A})$
>     
> - **Parallel/Collinear Vectors ($\theta = 0^\circ \text{ or } 180^\circ$):** $\vec{A} \times \vec{B} = \vec{0}$
>     
> - **Unit Vectors:** $\hat{i} \times \hat{i} = \vec{0}$, $\hat{i} \times \hat{j} = \hat{k}$, $\hat{j} \times \hat{k} = \hat{i}$, $\hat{k} \times \hat{i} = \hat{j}$

> [!question] Practice Questions
> ### Question 1: Resolving Components & Vector Addition
> 
> Two forces act on an object at the origin:
> 
> - $\vec{F}_1$ has a magnitude of $10\text{ N}$ at an angle of $30^\circ$ above the positive x-axis.
>     
> - $\vec{F}_2$ has a magnitude of $15\text{ N}$ directed purely along the positive y-axis ($90^\circ$).
>     
> 
> Find the magnitude and direction of the resultant force $\vec{R} = \vec{F}_1 + \vec{F}_2$.
> 
> #### Solution:
> 
> **Step 1: Resolve vectors into x and y components.**
> 
> - **For $\vec{F}_1$:**
>     
>     $$F_{1x} = 10 \cos(30^\circ) = 10 \times \frac{\sqrt{3}}{2} \approx 8.66\text{ N}$$
>     
>     $$F_{1y} = 10 \sin(30^\circ) = 10 \times 0.5 = 5.00\text{ N}$$
>     
> - **For $\vec{F}_2$:**
>     
>     $$F_{2x} = 15 \cos(90^\circ) = 0\text{ N}$$
>     
>     $$F_{2y} = 15 \sin(90^\circ) = 15.00\text{ N}$$
>     
> 
> **Step 2: Add components to find resultant components.**
> 
> $$R_x = F_{1x} + F_{2x} = 8.66 + 0 = 8.66\text{ N}$$
> 
> $$R_y = F_{1y} + F_{2y} = 5.00 + 15.00 = 20.00\text{ N}$$
> 
> **Step 3: Calculate the magnitude of the resultant.**
> 
> $$R = \sqrt{R_x^2 + R_y^2} = \sqrt{(8.66)^2 + (20.00)^2} = \sqrt{75 + 400} = \sqrt{475} \approx 21.79\text{ N}$$
> 
> **Step 4: Calculate the direction angle $\theta$.**
> 
> $$\theta = \tan^{-1}\left(\frac{R_y}{R_x}\right) = \tan^{-1}\left(\frac{20.00}{8.66}\right) \approx \tan^{-1}(2.309) \approx 66.58^\circ$$
> 
> **Final Answer:** Magnitude $\approx 21.79\text{ N}$ at an angle of $66.58^\circ$ above the positive x-axis.
> 
> ### Question 2: Dot Product & Angle Between Vectors
> 
> Given two vectors:
> 
> $$\vec{A} = 3\hat{i} + 4\hat{j}$$
> 
> $$\vec{B} = 2\hat{i} - 2\hat{j}$$
> 
> 1. Calculate the dot product $\vec{A} \cdot \vec{B}$.
>     
> 2. Determine the angle $\theta$ between vectors $\vec{A}$ and $\vec{B}$.
>     
> 
> #### Solution:
> 
> **Step 1: Calculate the dot product using components.**
> 
> $$\vec{A} \cdot \vec{B} = (A_x \cdot B_x) + (A_y \cdot B_y)$$
> 
> $$\vec{A} \cdot \vec{B} = (3 \cdot 2) + (4 \cdot (-2)) = 6 - 8 = -2$$
> 
> **Step 2: Find the magnitudes of $\vec{A}$ and $\vec{B}$.**
> 
> $$\vert{}\vec{A}\vert{} = \sqrt{3^2 + 4^2} = \sqrt{9 + 16} = \sqrt{25} = 5$$
> 
> $$\vert{}\vec{B}\vert{} = \sqrt{2^2 + (-2)^2} = \sqrt{4 + 4} = \sqrt{8} = 2\sqrt{2} \approx 2.83$$
> 
> **Step 3: Use the dot product formula to solve for $\theta$.**
> 
> $$\vec{A} \cdot \vec{B} = \vert{}\vec{A}\vert{}\vert{}\vec{B}\vert{}\cos\theta$$
> 
> $$-2 = (5)(2\sqrt{2})\cos\theta$$
> 
> $$\cos\theta = \frac{-2}{10\sqrt{2}} = \frac{-1}{5\sqrt{2}} \approx -0.1414$$
> 
> $$\theta = \cos^{-1}(-0.1414) \approx 98.13^\circ$$
> 
> **Final Answer:**
> 
> 1. Dot product = $-2$
>     
> 2. Angle $\theta \approx 98.13^\circ$
>     
> 
> ### Question 3: Cross Product
> 
> Calculate the cross product $\vec{A} \times \vec{B}$ for the following vectors:
> 
> $$\vec{A} = 2\hat{i} + 1\hat{j} + 0\hat{k}$$
> 
> $$\vec{B} = 0\hat{i} + 3\hat{j} + 4\hat{k}$$
> 
> #### Solution:
> 
> **Step 1: Set up the determinant formula.**
> 
> $$\vec{A} \times \vec{B} = \begin{vmatrix} \hat{i} & \hat{j} & \hat{k} \\ 2 & 1 & 0 \\ 0 & 3 & 4 \end{vmatrix}$$
> 
> **Step 2: Expand the determinant.**
> 
> $$\vec{A} \times \vec{B} = \hat{i}\big((1 \cdot 4) - (0 \cdot 3)\big) - \hat{j}\big((2 \cdot 4) - (0 \cdot 0)\big) + \hat{k}\big((2 \cdot 3) - (1 \cdot 0)\big)$$
> 
> $$\vec{A} \times \vec{B} = \hat{i}(4 - 0) - \hat{j}(8 - 0) + \hat{k}(6 - 0)$$
> 
> $$\vec{A} \times \vec{B} = 4\hat{i} - 8\hat{j} + 6\hat{k}$$
> 
> **Final Answer:** $\vec{A} \times \vec{B} = 4\hat{i} - 8\hat{j} + 6\hat{k}$
> 
> ### Question 4: Unit Vector & Position Vector
> 
> A point $P$ has coordinates $(6, -8)$ in a Cartesian plane.
> 
> 1. Write the position vector $\vec{r}$ of point $P$.
>     
> 2. Calculate its magnitude $\vert{}\vec{r}\vert{}$.
>     
> 3. Find the unit vector $\hat{r}$ pointing in the same direction.
>     
> 
> #### Solution:
> 
> **Step 1: Position Vector**
> 
> $$\vec{r} = 6\hat{i} - 8\hat{j}$$
> 
> **Step 2: Magnitude**
> 
> $$\vert{}\vec{r}\vert{} = \sqrt{6^2 + (-8)^2} = \sqrt{36 + 64} = \sqrt{100} = 10$$
> 
> **Step 3: Unit Vector**
> 
> $$\hat{r} = \frac{\vec{r}}{\vert{}\vec{r}\vert{}} = \frac{6\hat{i} - 8\hat{j}}{10} = \frac{6}{10}\hat{i} - \frac{8}{10}\hat{j} = 0.6\hat{i} - 0.8\hat{j}$$
> 
> **Final Answer:**
> 
> 4. $\vec{r} = 6\hat{i} - 8\hat{j}$
>     
> 5. Magnitude = $10$
>     
> 6. $\hat{r} = 0.6\hat{i} - 0.8\hat{j}$

