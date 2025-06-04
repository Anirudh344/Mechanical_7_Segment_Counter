Mechanical 7-Segment Counter
Course: ME-395 Engineering Practicum-2
Professor-in-Charge: Dr. Murshid Imam

🧑‍🤝‍🧑 Group Members
Anirudh Singh (2201ME11)

Aryan Kaushal (2201ME16)

Ashutosh Tiwari (2201ME18)

Asmit Singh (2201ME20)

Harsh Kumar (2201ME30)

📌 Objective
Design and implementation of a mechanical 7-segment counter driven by cams and gears. The counter displays digits from 0 to 9 through a push-button mechanism and automatically resets after reaching 9. All components are designed for 3D printing using PLA (Polylactic Acid).
| Part         | Quantity |
| ------------ | -------- |
| Cams         | 8        |
| Followers    | 7        |
| Segments     | 7        |
| Screws       | 4        |
| Springs      | 2        |
| Gears        | 4        |
| Plates       | 3        |
| Shaft        | 1        |
| Pushbutton   | 1        |
| Rubber Bands | 2        |
📖 Theory
The mechanism uses a ratchet and pawl system to enforce unidirectional motion. It:

Converts continuous button presses into intermittent camshaft rotation.

Ensures one-way counting (0 to 9), and automatic reset to 0 after 9.

Minimizes component wear and stress for improved longevity.

⚙️ Working Principle
1. Seven-Segment Mechanism
Each segment has two states: ON or OFF.

A camshaft with 8 cams controls the states.

Springs retract segments to OFF; cams push them ON.

2. Camshaft Design
Camshaft rotates in 10 steps (36° per step).

Each cam profile corresponds to one digit (0–9).

Varying lift and dwell angles ensure correct segment combinations.

3. Gear and Key Mechanism
A gear train rotates the camshaft.

A ratchet and pawl mechanism ensures precise 36° step increments per push.

4. Reset Mechanism
After the 9th position, camshaft automatically resets to 0.

Achieved by full 360° rotation across 10 button presses.

5. Segment Control
Each segment is a lever actuated by cams.

Springs/rubber bands bring segments back to OFF state.

📐 Calculations
Rotation per digit = 360° / 10 = 36°

Cam positions determined based on required ON/OFF segments per digit.

3D CAD Models designed in SolidWorks.

🧪 Innovation and Applications
Sensor Integration:

Replace push button with electric, thermal, or proximity sensors.

Allows use in automated or hostile environments.

Application Scenarios:

Industrial impact monitoring (hammering, punching, etc.)

Deep-sea equipment counters.

Radiation monitoring in nuclear or fusion reactors.

📏 Optimization
Compact design for space efficiency.

Fewer moving parts to simplify mechanics.

Use of rubber bands instead of multiple springs for easier assembly.

🎯 Future Goals
Integrate sensors for hands-free operation.

Enable multi-digit display counters.

Explore commercialization of the product.

🖼️ CAD Designs and Prints
✅ Cam profiles and followers modeled in SolidWorks.

✅ 2D and 3D assemblies prepared for 3D printing.

✅ Fully functional prototype tested and validated.
