---
{"dg-publish":true,"permalink":"/week-5-week-6/","dg-note-properties":{}}
---

# WEEK 5
**Thermodynamics** is the branch of physical science that deals with heat, work, temperature, and their relationship to energy, radiation, and physical properties of matter.

## 1. Thermodynamic Systems and Types

A **system** is a defined quantity of matter or region in space chosen for study. Everything outside the system is the **surroundings**, separated from the system by a real or imaginary **boundary**.

Plaintext

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

- **Open System (Control Volume)**: Both mass and energy can cross the boundary (e.g., pumps, turbines, internal combustion engines, human bodies).
    
- **Closed System (Control Mass)**: Energy can cross the boundary, but mass cannot cross (e.g., a sealed piston-cylinder assembly).
    
- **Isolated System**: Neither mass nor energy can cross the boundary (e.g., a perfectly insulated thermos flask, or the Universe as a whole).
    

## 2. Thermodynamic Properties

A property is any measurable characteristic of a system in equilibrium.

|**Property Type**|**Definition**|**Key Characteristics**|**Examples**|
|---|---|---|---|
|**Intensive**|Independent of the mass or size of the system.|Value remains unchanged if the system is divided in half.|Temperature ($T$), Pressure ($P$), Density ($\rho$), Specific Volume ($v$).|
|**Extensive**|Depends on the total mass or size of the system.|Values are additive; dividing the system halves the value.|Total Mass ($m$), Total Volume ($V$), Internal Energy ($U$), Enthalpy ($H$).|

_Note: Any extensive property divided by mass becomes an **intensive (specific)** property (e.g., Specific Volume $v = \frac{V}{m}$)._

## 3. Types of Pressure

Pressure ($P$) is the normal force exerted by a fluid per unit area:

$$P = \frac{F}{A}$$

- **Atmospheric Pressure ($P_{\text{atm}}$)**: Pressure exerted by the weight of the Earth's atmosphere. At sea level, standard atmospheric pressure is $1\text{ atm} = 101.325\text{ kPa} = 1.01325\text{ bar} = 760\text{ mmHg}$.
    
- **Absolute Pressure ($P_{\text{abs}}$)**: The actual total pressure relative to absolute zero pressure (perfect vacuum).
    
- **Gauge Pressure ($P_{\text{gauge}}$)**: Pressure measured relative to local atmospheric pressure (when $P_{\text{abs}} > P_{\text{atm}}$).
    
    $$P_{\text{abs}} = P_{\text{atm}} + P_{\text{gauge}}$$
    
- **Vacuum Pressure ($P_{\text{vac}}$)**: Pressure measured below local atmospheric pressure (when $P_{\text{abs}} < P_{\text{atm}}$).
    
    $$P_{\text{abs}} = P_{\text{atm}} - P_{\text{vac}}$$
    

## 4. Standard Conditions: STP vs. NTP

|**Parameter**|**STP (Standard Temperature & Pressure)**|**NTP (Normal Temperature & Pressure)**|
|---|---|---|
|**Standardizing Body**|IUPAC|NIST / Standard Engineering|
|**Temperature**|$0^\circ\text{C}$ ($273.15\text{ K}$)|$20^\circ\text{C}$ ($293.15\text{ K}$)|
|**Pressure**|$1\text{ bar}$ ($100\text{ kPa}$) or $1\text{ atm}$ ($101.325\text{ kPa}$)|$1\text{ atm}$ ($101.325\text{ kPa}$)|
|**Molar Volume of Ideal Gas**|$22.71\text{ L/mol}$ (at $1\text{ bar}$) / $22.414\text{ L/mol}$ (at $1\text{ atm}$)|$24.05\text{ L/mol}$|

## 5. Point Functions vs. Path Functions

|**Feature**|**Point Functions (State Functions)**|**Path Functions**|
|---|---|---|
|**Dependence**|Depend **only on the state** of the system, not how it arrived there.|Depend on the **specific path or process** taken between states.|
|**Differential**|Exact differentials (written as $dP, dT$).|Inexact differentials (written as $\delta Q, \delta W$).|
|**Cyclic Integral**|$\oint dX = 0$ over a closed cycle.|$\oint \delta X \neq 0$ over a closed cycle.|
|**Examples**|Pressure ($P$), Temperature ($T$), Volume ($V$), Internal Energy ($U$), Entropy ($S$).|Heat transfer ($Q$), Work done ($W$).|

## 6. Heat and Work

Both heat and work are **transient forms of energy** that exist only while crossing system boundaries (path functions).

### Heat ($Q$)

Energy transfer caused solely by a **temperature difference** between the system and its surroundings.

- **Sign Convention**:
    
    - $+Q$: Heat absorbed **by** the system (from surroundings).
        
    - $-Q$: Heat rejected **by** the system (to surroundings).
        

### Work ($W$)

Energy transfer associated with a force acting through a distance, or any interaction whose sole effect could be reduced to raising a weight.

- **Boundary Work** ($P$-$V$ work for a reversible process):
    
    $$W = \int_{V_1}^{V_2} P \, dV$$
    
- **Sign Convention**:
    
    - $+W$: Work done **by** the system (on surroundings).
        
    - $-W$: Work done **on** the system (by surroundings).
        

## 7. Thermodynamic Equilibrium & Zeroth Law

### Thermodynamic Equilibrium

A system is in **thermodynamic equilibrium** if it simultaneously satisfies three forms of equilibrium:

1. **Thermal Equilibrium**: Uniform temperature throughout the system (no heat flux).
    
2. **Mechanical Equilibrium**: No unbalanced forces or pressure gradients within the system or at boundaries.
    
3. **Chemical Equilibrium**: No net chemical reactions occur, and chemical composition remains constant over time.
    

### Zeroth Law of Thermodynamics

> **Statement**: If two bodies ($A$ and $B$) are each in thermal equilibrium with a third body ($C$), then they are also in thermal equilibrium with each other.

Plaintext

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

## 8. Summary of the Four Laws of Thermodynamics

1. **Zeroth Law**: Defines temperature and thermal equilibrium.
    
2. **First Law (Conservation of Energy)**: Energy cannot be created or destroyed, only transformed.
    
    $$\Delta U = Q - W$$
    
3. **Second Law (Direction of Processes)**: Heat cannot spontaneously flow from a colder body to a hotter body without external work; entropy of an isolated system always increases over time ($\Delta S_{\text{univ}} \ge 0$).
    
4. **Third Law (Absolute Zero)**: As the absolute temperature of a pure crystalline substance approaches zero ($0\text{ K}$), its entropy approaches zero.

# WEEK 6

**Uniform Circular Motion (UCM)** occurs when an object travels along a circular path of radius r at a **constant speed** v. Although the speed remains constant, the velocity vector continuously changes direction, meaning the object undergoes continuous acceleration directed toward the center of the circle.

## 1. Key Variables and Parameters

|Parameter|Symbol|Formula|SI Unit|Description|
|---|---|---|---|---|
|**Period**|T|T=f1​=v2πr​|Seconds (s)|Time taken to complete one full revolution.|
|**Frequency**|f|f=T1​=2πω​|Hertz (Hz or s−1)|Number of complete revolutions per unit time.|
|**Angular Velocity**|ω|ω=ΔtΔθ​=T2π​=2πf|Radians per second (rad/s)|Rate of change of angular displacement.|
|**Linear Velocity**|v|v=ωr=T2πr​|Meters per second (m/s)|Tangential speed along the circular path.|

## 2. Centripetal Acceleration (ac​)

Because velocity is a vector quantity (having both magnitude and direction), a change in direction constitutes acceleration. In UCM, this acceleration points toward the center of the rotation axis and is called **centripetal acceleration**.

ac​=rv2​=ω2r

## 3. Derivations of Centripetal Acceleration

### Method 1: Calculus and Vector Differentiation (Rigorous)

Let a particle move counterclockwise in a circle of radius r centered at the origin, with constant angular velocity ω.

Plaintext

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

1. **Position Vector r![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)(t)**:
    
    r![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)(t)=rcos(ωt)i^+rsin(ωt)j^​
    
2. **Velocity Vector v![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)(t)** (First derivative with respect to time t):
    
    v![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)(t)=dtdr![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)​=−rωsin(ωt)i^+rωcos(ωt)j^​
    
3. **Acceleration Vector a![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)(t)** (Second derivative with respect to time t):
    
    a![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)(t)=dtdv![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)​=−rω2cos(ωt)i^−rω2sin(ωt)j^​
    
4. **Simplify using Position Vector**:
    
    a![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)(t)=−ω2[rcos(ωt)i^+rsin(ωt)j^​]=−ω2r![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)(t)
    
5. **Magnitude and Direction**:
    
    - **Direction**: The negative sign indicates a![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)(t) points directly opposite to the position vector r![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)(t) (toward the origin/center).
        
    - **Magnitude**:
        
        ac​=∣a![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)(t)∣=ω2r
        
    - Substituting ω=rv​:
        
        ac​=(rv​)2r=rv2​
        

### Method 2: Geometric / Similar Triangles (Intuitive)

Consider a particle moving from point A to point B over a small time interval Δt, subtending an angle Δθ.

Plaintext

```
        Position Triangle                      Velocity Triangle
              B                                      v₂
             / \                                    / \
            /   \ Δs                               /   \ Δv
         r /     \ r                            v /     \ v
          /  Δθ   \                              /  Δθ   \
         O─────────A                            ─────────── v₁
```

1. **Position Triangle**: Formed by position vectors r![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)1​, r![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)2​ and displacement chord Δs≈rΔθ.
    
2. **Velocity Triangle**: Formed by tangential velocity vectors v![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)1​, v![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)2​ and velocity change vector Δv![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>).
    

Because v![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)1​⊥r![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)1​ and v![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)2​⊥r![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)2​, the isosceles triangles formed by positions and velocities are **similar triangles**:

v∣Δv![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)∣​=rΔs​⟹∣Δv![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)∣=rv⋅Δs​

Divide both sides by Δt:

Δt∣Δv![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)∣​=rv​(ΔtΔs​)

Taking the limit as Δt→0:

ac​=Δt→0lim​Δt∣Δv![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)∣​=rv​⋅v=rv2​

## 4. Centripetal Force (Fc​)

By Newton's Second Law (F![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)net​=ma![](data:image/svg+xml;utf8,<svg%20xmlns="http://www.w3.org/2000/svg"%20width="0.471em"%20height="0.714em"%20style="width:0.471em"%20viewBox="0%200%20471%20714"%20preserveAspectRatio="xMinYMin"><path%20d="M377%2020c0-5.333%201.833-10%205.5-14S391%200%20397%200c4.667%200%208.667%201.667%2012%205%0A3.333%202.667%206.667%209%2010%2019%206.667%2024.667%2020.333%2043.667%2041%2057%207.333%204.667%2011%0A10.667%2011%2018%200%206-1%2010-3%2012s-6.667%205-14%209c-28.667%2014.667-53.667%2035.667-75%2063%0A-1.333%201.333-3.167%203.5-5.5%206.5s-4%204.833-5%205.5c-1%20.667-2.5%201.333-4.5%202s-4.333%201%0A-7%201c-4.667%200-9.167-1.833-13.5-5.5S337%20184%20337%20178c0-12.667%2015.667-32.333%2047-59%0AH213l-171-1c-8.667-6-13-12.333-13-19%200-4.667%204.333-11.333%2013-20h359%0Ac-16-25.333-24-45-24-59z"></path></svg>)), an object undergoing centripetal acceleration requires a net inward radial force called the **centripetal force**:

Fc​=mac​=rmv2​=mω2r

### Key Principle

Centripetal force is **not a standalone physical force** (like gravity or friction); rather, it is a **net force requirement** provided by real, physical forces acting on the system:

- **Satellite orbiting Earth**: Gravitational force provides Fc​ (r2GMm​=rmv2​).
    
- **Car rounding a flat curve**: Static friction between tires and road provides Fc​ (μs​mg=rmv2​).
    
- **Ball whirled on a string**: Tension force in the string provides Fc​ (T=rmv2​).
    
- **Electron orbiting a nucleus**: Electrostatic attraction provides Fc​ (r2kq1​q2​​=rmv2​).