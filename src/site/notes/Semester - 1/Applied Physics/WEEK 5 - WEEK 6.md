---
{"dg-publish":true,"permalink":"/semester-1/applied-physics/week-5-week-6/","dg-note-properties":{}}
---

# WEEK 5

**Thermodynamics** is the branch of physical science that deals with heat, work, temperature, and their relationship to energy, radiation, and physical properties of matter.

## Thermodynamic Systems and Types

A **system** is a defined quantity of matter or region in space chosen for study. Everything outside the system is the **surroundings**, separated from the system by a real or imaginary **boundary**

```
               SURROUNDINGS
    ┌───────────────────────────────┐
    │          BOUNDARY             │
    │      ┌─────────────────┐      │
    │      │                 │      │
    │  ───>│     SYSTEM      │───>  │
    │ Mass/│                 │Mass/ │
    │ Energy│                 │Energy│
    │      └─────────────────┘      │
    └───────────────────────────────┘
```

> [!NOTE]
> - **Open System (Control Volume)**: Both mass and energy can cross the boundary (e.g., pumps, turbines, internal combustion engines, human bodies).
>     
> - **Closed System (Control Mass)**: Energy can cross the boundary, but mass cannot cross (e.g., a sealed piston-cylinder assembly).
>     
> - **Isolated System**: Neither mass nor energy can cross the boundary (e.g., a perfectly insulated thermos flask, or the Universe as a whole).

## Thermodynamic Properties

A property is any measurable characteristic of a system in equilibrium.

|**Property Type**|**Definition**|**Key Characteristics**|**Examples**|
|---|---|---|---|
|**Intensive**|Independent of the mass or size of the system.|Value remains unchanged if the system is divided in half.|Temperature ($T$), Pressure ($P$), Density ($\rho$), Specific Volume ($v$).|
|**Extensive**|Depends on the total mass or size of the system.|Values are additive; dividing the system halves the value.|Total Mass ($m$), Total Volume ($V$), Internal Energy ($U$), Enthalpy ($H$).|

_Note: Any extensive property divided by mass becomes an **intensive (specific)** property (e.g., Specific Volume $v = \frac{V}{m}$)._

## Types of Pressure

> [!NOTE]
> Pressure ($P$) is the normal force exerted by a fluid per unit area:
> 
> $$P = \frac{F}{A}$$
> 
> - **Atmospheric Pressure ($P_{\text{atm}}$)**: Pressure exerted by the weight of the Earth's atmosphere. At sea level, standard atmospheric pressure is $1\text{ atm} = 101.325\text{ kPa} = 1.01325\text{ bar} = 760\text{ mmHg}$.
>     
> - **Absolute Pressure ($P_{\text{abs}}$)**: The actual total pressure relative to absolute zero pressure (perfect vacuum).
>     
> - **Gauge Pressure ($P_{\text{gauge}}$)**: Pressure measured relative to local atmospheric pressure (when $P_{\text{abs}} > P_{\text{atm}}$).
>     
>     $$P_{\text{abs}} = P_{\text{atm}} + P_{\text{gauge}}$$
>     
> - **Vacuum Pressure ($P_{\text{vac}}$)**: Pressure measured below local atmospheric pressure (when $P_{\text{abs}} < P_{\text{atm}}$).
>     
>     $$P_{\text{abs}} = P_{\text{atm}} - P_{\text{vac}}$$
>     

## Standard Conditions: STP vs. NTP

|**Parameter**|**STP (Standard Temperature & Pressure)**|**NTP (Normal Temperature & Pressure)**|
|---|---|---|
|**Standardizing Body**|IUPAC|NIST / Standard Engineering|
|**Temperature**|$0^\circ\text{C}$ ($273.15\text{ K}$)|$20^\circ\text{C}$ ($293.15\text{ K}$)|
|**Pressure**|$1\text{ bar}$ ($100\text{ kPa}$) or $1\text{ atm}$ ($101.325\text{ kPa}$)|$1\text{ atm}$ ($101.325\text{ kPa}$)|
|**Molar Volume of Ideal Gas**|$22.71\text{ L/mol}$ (at $1\text{ bar}$) / $22.414\text{ L/mol}$ (at $1\text{ atm}$)|$24.05\text{ L/mol}$|

## Point Functions vs. Path Functions

|**Feature**|**Point Functions (State Functions)**|**Path Functions**|
|---|---|---|
|**Dependence**|Depend **only on the state** of the system, not how it arrived there.|Depend on the **specific path or process** taken between states.|
|**Differential**|Exact differentials (written as $dP, dT$).|Inexact differentials (written as $\delta Q, \delta W$).|
|**Cyclic Integral**|$\oint dX = 0$ over a closed cycle.|$\oint \delta X \neq 0$ over a closed cycle.|
|**Examples**|Pressure ($P$), Temperature ($T$), Volume ($V$), Internal Energy ($U$), Entropy ($S$).|Heat transfer ($Q$), Work done ($W$).|

## Heat and Work

Both heat and work are **transient forms of energy** that exist only while crossing system boundaries (path functions).

> [!NOTE]
> ### Heat ($Q$)
> 
> Energy transfer caused solely by a **temperature difference** between the system and its surroundings.
> 
> - **Sign Convention**:
>     
>     - $+Q$: Heat absorbed **by** the system (from surroundings).
>         
>     - $-Q$: Heat rejected **by** the system (to surroundings).
> 
> ### Work ($W$)
> 
> Energy transfer associated with a force acting through a distance, or any interaction whose sole effect could be reduced to raising a weight.
> 
> - **Boundary Work** ($P$-$V$ work for a reversible process):
>     
>     $$W = \int_{V_1}^{V_2} P \, dV$$
>     
> - **Sign Convention**:
>     
>     - $+W$: Work done **by** the system (on surroundings).
>         
>     - $-W$: Work done **on** the system (by surroundings).


## Core Concepts & Formulas

|**Concept**|**Definition & Description**|**Mathematical Formula**|**Units**|
|---|---|---|---|
|**Work ($W$)**|Measure of energy transferred when a force causes displacement in the direction of the force.|$W = F d \cos\theta$|Joules ($\text{J}$)|
|**Kinetic Energy ($KE$)**|Energy possessed by an object due to its motion.|$KE = \frac{1}{2}m v^2$|Joules ($\text{J}$)|
|**Gravitational Potential Energy ($PE_g$)**|Energy stored in an object due to its vertical position in a gravitational field.|$PE_g = mgh$|Joules ($\text{J}$)|
|**Elastic Potential Energy ($PE_e$)**|Energy stored as a result of deforming an elastic object (e.g., stretching a spring).|$PE_e = \frac{1}{2} k x^2$|Joules ($\text{J}$)|
|**Power ($P$)**|The rate at which work is done or energy is transferred over time.|$P = \frac{W}{t} = F v$|Watts ($\text{W}$)|
|**Efficiency ($\eta$)**|The percentage of total input energy that is converted into useful output energy.|$\eta = \left( \frac{E_{\text{useful}}}{E_{\text{total}}} \right) \times 100\%$|Percentage ($\%$)|

### Energy Stores, Pathways & Sources

Energy cannot be created or destroyed, only transferred between stores via specific pathways (Law of Conservation of Energy).

### Energy Stores

> [!NOTE]
> 
> - **Kinetic Store**: Energy of moving objects.
>     
> - **Gravitational Store**: Energy due to position in a gravitational field.
>     
> - **Chemical Store**: Energy stored in chemical bonds (e.g., food, batteries, fuels).
>     
> - **Elastic Store**: Energy stored in stretched or compressed objects.
>     
> - **Thermal Store**: Sum of microscopic kinetic and potential energies of particles in a system.
>     
> - **Nuclear Store**: Energy stored in the nucleus of an atom.
>     
> - **Electrostatic & Magnetic Stores**: Energy stored in interacting electric charges or magnetic poles.

### Transfer Pathways

> [!NOTE]
> 
> - **Mechanical Pathway**: Force acting over a distance (doing work).
>     
> - **Electrical Pathway**: Moving charge driven by a potential difference.
>     
> - **Heating Pathway**: Temperature difference driving heat flow via conduction, convection, or radiation.
>     
> - **Radiation Pathway**: Energy carried by light waves, sound waves, or electromagnetic radiation.

### Energy Sources

- **Renewable**: Naturally replenished on human timescales (Solar, Wind, Hydroelectric, Geothermal, Tidal, Biomass).
    
- **Non-Renewable**: Finite reserves depleted faster than created (Fossil Fuels: Coal, Oil, Natural Gas; Nuclear Fuel: Uranium).

## Work-Energy Theorem & Conservation

> [!NOTE] Definition
> The **Work-Energy Theorem** states that the net work done by all forces acting on an object equals the change in its kinetic energy:
> 
> $$W_{\text{net}} = \Delta KE = KE_f - KE_i = \frac{1}{2} m v_f^2 - \frac{1}{2} m v_i^2$$
> 
> In a closed, conservative system (ignoring non-conservative forces like friction or air resistance), the total mechanical energy remains constant:
> 
> $$E_{\text{total}} = KE_i + PE_i = KE_f + PE_f$$
> 
> When friction or resistance is present, mechanical energy converts into thermal energy ($E_{\text{thermal}}$):
> 
> $$W_{\text{ext}} = \Delta KE + \Delta PE + W_{\text{friction}}$$
> 

## Practice Questions & Step-by-Step Solutions

> [!question] Practice Questions
> ### Question 1: Work-Energy Theorem
> 
> A $1200\text{ kg}$ car accelerates from rest along a flat road. A constant net forward force of $3000\text{ N}$ acts on the car over a distance of $150\text{ m}$. What is the final velocity of the car?
> 
> **Solution:**
> 
> 1. Calculate the net work done on the car:
>     
>     $$W_{\text{net}} = F \cdot d = 3000\text{ N} \times 150\text{ m} = 450,000\text{ J}$$
>     
> 2. Apply the Work-Energy Theorem ($KE_i = 0$ because it starts from rest):
>     
>     $$W_{\text{net}} = \frac{1}{2} m v_f^2 - \frac{1}{2} m v_i^2$$
>     
>     $$450,000 = \frac{1}{2} (1200) v_f^2 - 0$$
>     
>     $$450,000 = 600 v_f^2$$
>     
> 1. Solve for $v_f$:
>     
>     $$v_f^2 = \frac{450,000}{600} = 750$$
>     
>     $$v_f = \sqrt{750} \approx 27.39\text{ m/s}$$
>     
> 
> ### Question 2: Power & Efficiency
> 
> An electric motor consumes $2000\text{ W}$ of electrical power while lifting a $100\text{ kg}$ crate vertically through a height of $12\text{ m}$ in $8\text{ s}$. (Assume $g = 9.8\text{ m/s}^2$).
> 
> 2. Calculate the useful power output of the motor.
>     
> 3. Determine the efficiency of the motor.
>     
> 
> **Solution:**
> 
> 4. **Useful Work & Power Output:**
>     
>     Useful energy output equals the gain in gravitational potential energy ($\Delta PE_g$):
>     
>     $$W_{\text{useful}} = mgh = 100\text{ kg} \times 9.8\text{ m/s}^2 \times 12\text{ m} = 11,760\text{ J}$$
>     
>     Useful power output ($P_{\text{out}}$):
>     
>     $$P_{\text{out}} = \frac{W_{\text{useful}}}{t} = \frac{11,760\text{ J}}{8\text{ s}} = 1470\text{ W}$$
>     
> 5. **Efficiency Calculation:**
>     
>     $$\eta = \left( \frac{P_{\text{out}}}{P_{\text{in}}} \right) \times 100\% = \left( \frac{1470\text{ W}}{2000\text{ W}} \right) \times 100\% = 73.5\%$$


## Thermodynamic Equilibrium & Zeroth Law

> [!NOTE] Thermodynamic Equilibrium
> A system is in **thermodynamic equilibrium** if it simultaneously satisfies three forms of equilibrium:
> 
> 1. **Thermal Equilibrium**: Uniform temperature throughout the system (no heat flux).
>     
> 2. **Mechanical Equilibrium**: No unbalanced forces or pressure gradients within the system or at boundaries.
>     
> 3. **Chemical Equilibrium**: No net chemical reactions occur, and chemical composition remains constant over time.

### Zeroth Law of Thermodynamics

> **Statement**: If two bodies ($A$ and $B$) are each in thermal equilibrium with a third body ($C$), then they are also in thermal equilibrium with each other.

```
    ┌───────┐           ┌───────┐
    │   A   │───────┬───│   B   │
    └───────┘       │   └───────┘
        │           │       │
        └───────┐   │   ┌───┘
                ▼   ▼   ▼
               ┌─────────┐
               │    C    │
               └─────────┘
    If TA = TC and TB = TC, then TA = TB.
```

**Significance**: The Zeroth Law establishes **temperature** as a valid, measurable physical property and forms the operational foundation of all thermometers.

## Summary of the Four Laws of Thermodynamics

> [!NOTE]
> 
> 1. **Zeroth Law**: Defines temperature and thermal equilibrium.
>     
> 2. **First Law (Conservation of Energy)**: Energy cannot be created or destroyed, only transformed.
>     
>     $$\Delta U = Q - W$$
>     
> 1. **Second Law (Direction of Processes)**: Heat cannot spontaneously flow from a colder body to a hotter body without external work; entropy of an isolated system always increases over time ($\Delta S_{\text{univ}} \ge 0$).
>     
> 2. **Third Law (Absolute Zero)**: As the absolute temperature of a pure crystalline substance approaches zero ($0\text{ K}$), its entropy approaches zero.

# WEEK 6

**Uniform Circular Motion (UCM)** occurs when an object travels along a circular path of radius r at a **constant speed** v. Although the speed remains constant, the velocity vector continuously changes direction, meaning the object undergoes continuous acceleration directed toward the center of the circle.

## Key Variables and Parameters

| Parameter            | Symbol | Formula          | SI Unit                    | Description                                   |
| -------------------- | ------ | ---------------- | -------------------------- | --------------------------------------------- |
| **Period**           | T      | T=f1​=v2πr​      | Seconds (s)                | Time taken to complete one full revolution.   |
| **Frequency**        | f      | f=T1​=2πω​       | Hertz (Hz or s−1)          | Number of complete revolutions per unit time. |
| **Angular Velocity** | ω      | ω=ΔtΔθ​=T2π​=2πf | Radians per second (rad/s) | Rate of change of angular displacement.       |
| **Linear Velocity**  | v      | v=ωr=T2πr​       | Meters per second (m/s)    | Tangential speed along the circular path.     |

## Centripetal Acceleration (ac​)

Because velocity is a vector quantity (having both magnitude and direction), a change in direction constitutes acceleration. In UCM, this acceleration points toward the center of the rotation axis and is called **centripetal acceleration**.

ac​=rv2​=ω2r

## Derivations of Centripetal Acceleration

### Method 1: Calculus and Vector Differentiation (Rigorous)

Let a particle move counterclockwise in a circle of radius r centered at the origin, with constant angular velocity ω.

```
                  y ▲
                    │      * P(r, θ)
                    │     /│
                    │    / │
                    │   /  │ r sin(ωt)
                    │  / θ │
                    └─┴────┴────► x
                       r cos(ωt)
```

> [!NOTE]
> 1. **Position Vector r![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)(t)**:
>     
>     r![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)(t)=rcos(ωt)i^+rsin(ωt)j^​
>     
> 2. **Velocity Vector v![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)(t)** (First derivative with respect to time t):
>     
>     v![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)(t)=dtdr![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)​=−rωsin(ωt)i^+rωcos(ωt)j^​
>     
> 1. **Acceleration Vector a![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)(t)** (Second derivative with respect to time t):
>     
>     a![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)(t)=dtdv![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)​=−rω2cos(ωt)i^−rω2sin(ωt)j^​
>     
> 2. **Simplify using Position Vector**:
>     
>     a![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)(t)=−ω2[rcos(ωt)i^+rsin(ωt)j^​]=−ω2r![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)(t)
>     
> 3. **Magnitude and Direction**:
>     
>     - **Direction**: The negative sign indicates a![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)(t) points directly opposite to the position vector r![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)(t) (toward the origin/center).
>         
>     - **Magnitude**:
>         
>         ac​=∣a![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)(t)∣=ω2r
>         
>     - Substituting ω=rv​:
>         
>         ac​=(rv​)2r=rv2​
>         

### Method 2: Geometric / Similar Triangles (Intuitive)

Consider a particle moving from point A to point B over a small time interval Δt, subtending an angle Δθ.

```
        Position Triangle                      Velocity Triangle
              B                                      v₂
             / \                                    / \
            /   \ Δs                               /   \ Δv
         r /     \ r                            v /     \ v
          /  Δθ   \                              /  Δθ   \
         O─────────A                            ─────────── v₁
```

> [!NOTE]
> 1. **Position Triangle**: Formed by position vectors r![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)1​, r![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)2​ and displacement chord Δs≈rΔθ.
>     
> 2. **Velocity Triangle**: Formed by tangential velocity vectors v![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)1​, v![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)2​ and velocity change vector Δv![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>).
>     
> 
> Because v![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)1​⊥r![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)1​ and v![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)2​⊥r![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)2​, the isosceles triangles formed by positions and velocities are **similar triangles**:
> 
> v∣Δv![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)∣​=rΔs​⟹∣Δv![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)∣=rv⋅Δs​
> 
> Divide both sides by Δt:
> 
> Δt∣Δv![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)∣​=rv​(ΔtΔs​)
> 
> Taking the limit as Δt→0:
> 
> ac​=Δt→0lim​Δt∣Δv![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)∣​=rv​⋅v=rv2​

## Centripetal Force (Fc​)

> [!NOTE]
> By Newton's Second Law (F![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)net​=ma![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)), an object undergoing centripetal acceleration requires a net inward radial force called the **centripetal force**:
> 
> Fc​=mac​=rmv2​=mω2r

### Key Principle

> [!NOTE]
> Centripetal force is **not a standalone physical force** (like gravity or friction); rather, it is a **net force requirement** provided by real, physical forces acting on the system:
> 
> - **Satellite orbiting Earth**: Gravitational force provides Fc​ (r2GMm​=rmv2​).
>     
> - **Car rounding a flat curve**: Static friction between tires and road provides Fc​ (μs​mg=rmv2​).
>     
> - **Ball whirled on a string**: Tension force in the string provides Fc​ (T=rmv2​).
>     
> - **Electron orbiting a nucleus**: Electrostatic attraction provides Fc​ (r2kq1​q2​​=rmv2​).