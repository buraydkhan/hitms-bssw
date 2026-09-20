# WEEK 1

## LAB 1

> [!NOTE] Basics
> ## Unit Conversion 
> - For any conversion, we need the conversion factor, ex : pounds,kilogram.
> - 1 kg = how many lbs. 
> 
> Numerator : Multiplication 
> - When converting to a smaller unit, there will be more of then. The math resolves to multiplication.
> - Problem: 4 feet to inches. Since foot 12 inches, you have 12 inches four times over.
> - 4 ft x (12 in/1 ft) = 48 in
> - The ft cancels out each other.
> 
> Denominator : Division
> - When converting to a larger unit, there will be fewer of them. The math inherenty resolves to division.
> - Problem : 96 inches to feet. Since it takes 12 inches to make a single foot, you must divide the total.
> - 96 in x (1 ft/12 in) = 8 ft

> [!question] Makes Sense ?
> Does the answer makes sense ? (Distance) 
> - Evaluate the relationship b/w the units.
> - Scenario : converting 14 miles to kilometers.
> - km is shorter than mile (1 km = 1.609 mi), it takes more km to cover the same physical distance. Our final answer must be larger than 14.
> - 14 mi x (1.609 km/1 mi) = 22.5 km. Result 22.5 > 14, the logic holds.
> 
> Does the answer makes sense ? (Mass)
> - Applying the same logic to weight.
> - 53.5 pounds (lbs) to kg
> - We know that 1 kg is heavier than 1 lb, kg is a larger unit, we should end up with a numerically smaller answer than what we should have started with.
> - 53.5 lbs x (1 lb/2.2 lbs) = 24.3 kg. Result : 24.3 < 53.5, the logic holds
> 
> TO CONVERT FROM SMALL UNIT TO BIG UNIT, WE DIVIDE
> TO CONVERT FROM BIG UNIT TO SMALL UNIT, WE MULTIPLE

> [!NOTE] Chain Link Method
> When a direct conversion factor is unavaible, multiple conversions factors can be multiplied together in a single continuous row. Unwanted units systematically cancel out to isolate the target unit.
> 1. Time and DIstance conversions. 
> - Path : Hours->Minutes->Seconds
> - 4 hr x (60 min/1 hr) x (60 sec/1 min) = 14,400 sec
> 1. Volume conversion
> - Problem : Convert 350 tablespoons into liters
> - Path : Tablespoons->Cups->Gallons->LIters
> - 16 tbsp = 1 cup, 16 cup = 1 gallon, 1 gallon = 3.785 L 
> - 350 tpsp x 1 cup/16 tsps x 1 gal/16 cup x 3.785 L/1 gal = 5.2 L

> [!NOTE] Derived Units
> When converting derived units, the starting value contains both a numerator & denomenator. Expand these units completely before applying conversion factor. 
> Rates & Densities : Ex : speed, convert 105 km/h into mi/h. hours remained unchanged.
> 105 km/1 hr x 1 mi/1.609 km = 65.3 mi/hr
> Complex Rate Conversion : Ex : mi/hr into m/s. mi->km->m, hour->min->sec
> 25 mi/1 hr x 1.609 km/1 mi x 1000 m/1 km x 1 hr/60 min x 1 min/60 sec = 11 m/s

> [!question] QUESTIONS
> Q1 : How many seconds are there in 7.5 hours ?
> - Conversion Factors : 1 hour = 60 min, 1 min = 60 sec, 1 hour =3600 sec
> - 7.5 hours  x 3600 seconds/hour = 27,000 sec
> 
> Q2 : How many miles is 315,000 inches ?
> - Conversion Factors : 1 ft = 12 inch, 1 mi = 5,280 ft, 1 mi = 12 x 5,280 = 63,360 inch
> - 315,000 inches/63,360 inches/miles = 4.97 miles

## LAB 2

> [!NOTE] MEASURING TOOLS
> ### Vernier Caliper Principles 
> 
> Mechanism: Utilizes a stationary main scale and a sliding Vernier scale to measure internal/external dimensions and depth with extreme precision. 
> Least Count (LC): The smallest measurable value. It is found by dividing the smallest division on the main scale by the total number of divisions on the Vernier scale. 
> Zero Error: Before taking readings, the jaws must be closed. If the zeros do not align, a zero error must be recorded and algebraically applied to the result.
> 
> ### Micrometer Screw Guage 
> 
> Instrument Design: Employs precisely machined screw mechanism specifically designed for measuring extremely small dimensions, like wire thickness.  
> Dual Scales: Features a linear pitch scale on the sleeve and a rotating circular scale on the thimble 
> Extreme Precision: Offers a finer Least Count (typically 0.01 mm) compared to the Vernier caliper, minimizing systemic error during delicate diameter measurements.
> 

> [!NOTE] Mathematical Computations (Volume)
> Volume of a Cylinder
> Using the Vernier caliper to measure the height (h) and
> radius (r):
> 
> Where π ≈ 3.14159
> 
> Volume of a Cube
> Measuring the length of one uniform side (s) of the cube:
> Where all sides (length, width, height) are equal.
> 

Diameter Derivation & Applications

Wire Diameter Formula The micrometer reading combines the Main Scale Reading (MSR) and Circular Scale Reading multiplied by the Least Count (LC) :
d = MSR+ (CSR x LC)

> [!NOTE] Engineering Applications
> Automotive Manufacturing: Engineers use Vernier calipers to measure exact cylinder volumes in engine blocks (pictured right) to ensure correct combustion ratios. 
> 
> Telecommunications: Technicians use micrometers to measure copper are diameters, as thickness strictly dictates electrical resistance and signal load capacity.

## LAB 3 : To Calculate Moment of Inertia Using Flywheel

> [!NOTE] Theoretical Aspect
> Defintion :
> The property of a body that resists any
> change in its rotational motion about an axis.
> 
> I = Σ m r2
> Sum over all particles of mass × (distance from the axis)2
> SI unit: kg·m2
> Depends upon total mass, how the mass is spread
> out, and the chosen axis
> 
> | Linear motion         | Rotational motion      |
> | --------------------- | ---------------------- |
> | Mass m                | Moment of inertia I    |
> | Velocity v            | Angular velocity ω     |
> | Acceleration a        | Angular acceleration a |
> | Force F               | Torque τ               |
> | F = ma                | τ = Iα                 |
> | Kinetic energy 1⁄2mv2 | Kinetic energy 1⁄2Iω2  |
> 

> [!NOTE] FLYWHEEL 
> The Flywheel
> • A heavy wheel mounted on an axle with ball bearings
> • Stores energy as rotational kinetic energy, 1⁄2Iω2
> • A larger I means more stored energy and steadier
> rotation
> 
> Thin rim (ring) -> MR2
> All mass at radius -> R
> Solid disc -> 1⁄2MR2
> Mass spread toward the centre

> [!NOTE] APPARATUS REQUIRED 
> Flywheel -> Heavy wheel on an axle
> Slotted masses -> With a hanger, to drive the wheel
> Thin string -> Wound around the axle
> Stopwatch -> Times the wheel until it stops
> Metre scale -> Measures the height h
> Vernier callipers -> Measure the axle diameter

> [!NOTE] SETUP
> Experimental
> 
> Floor
> Flywheel -> Axle, radius r
> String -> Mass m
> 
> Symbols used
> 
> m falling mass (kg)
> r radius of the axle (m)
> h height above the floor, h = 2πrn (m)
> n turns of the wheel while the mass falls
> N turns after the string slips off, until rest
> t time taken for those N turns (s)

> [!NOTE] Principle: Conservation of Energy
> PHASE 1 · Mass falls (n turns)
> 
> mgh = 1⁄2mv2 + 1⁄2Iω2 + n·Wf
> Potential energy lost by the mass becomes kinetic
> energy of the mass, kinetic energy of the flywheel and
> work done against friction. Here v = ωr.
> 
> PHASE 2 · String slips off (N turns)
> 
> 1⁄2Iω2 = N·Wf
> With the mass gone, all the kinetic energy of the
> flywheel is used up against friction until it stops. Wf is
> the friction work per turn.

> [!NOTE] DERIVATION
> Deriving the Working Formula
> 1. Phase 2 gives the friction work per turn: Wf = Iω2 / 2N
> 
> 2. Put Wf and v = ωr into Phase 1:
> 	mgh = 1⁄2mω2r2 + 1⁄2Iω2(1 + n/N)
> 
> 3. Rearrange for I to get the working formula (right)
> 
> 4. Average angular velocity = ω/2 = 2πN/t, so ω = 4πN/t.
> 	The height is h = 2πrn.
> 

> [!NOTE] FORMULA
> I = N m / (N + n)× ( 2gh / ω2 − r2 )
> Where:
> ω = 4πN / t
> h = 2πrn
> g = 9.8 m/s2
> I is in kg·m2
> 

> [!NOTE] Procedure
> 1. Check and measure
> 	Make sure the wheel turns freely. Measure the axle
> 	diameter with vernier callipers to get r.
> 
> 2. Set the string
> 	Place a mass m on the hanger. Adjust the string so it
> 	slips off as the mass touches the floor.
> 
> 3. Wind the string
> 	Wind n turns around the axle without overlap.
> 	Measure the height h of the mass.
> 
> 4. Release
> 	Let the mass fall so the wheel spins. Count the n
> 	turns made while the mass descends.
> 
> 5. Time the stop
> 	Start the stopwatch as the mass lands. Count N
> 	turns until rest and note t.
> 
> 6. Repeat and calculate
> 	Change m and n, repeat, calculate I each time and
> 	take the mean.

