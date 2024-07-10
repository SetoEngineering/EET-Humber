# Principles of Electric Circuits Cheat Sheet

## Table of Contents
1. [Quantities and Units](#chapter-1-quantities-and-units)
2. [Voltage, Current, and Resistance](#chapter-2-voltage-current-and-resistance)
3. [Ohm's Law](#chapter-3-ohms-law)
4. [Energy and Power](#chapter-4-energy-and-power)
5. [Series Circuits](#chapter-5-series-circuits)
6. [Parallel Circuits](#chapter-6-parallel-circuits)
7. [Series-Parallel Circuits](#chapter-7-series-parallel-circuits)
8. [Circuit Theorems and Conversions](#chapter-8-circuit-theorems-and-conversions)
9. [Branch, Loop, and Node Analyses](#chapter-9-branch-loop-and-node-analyses)
10. [Magnetism and Electromagnetism](#chapter-10-magnetism-and-electromagnetism)
11. [Introduction to Alternating Current and Voltage](#chapter-11-introduction-to-alternating-current-and-voltage)
12. [Capacitors](#chapter-12-capacitors)
13. [Inductors](#chapter-13-inductors)
14. [Transformers](#chapter-14-transformers)
15. [RC Circuits](#chapter-15-rc-circuits)
16. [RL Circuits](#chapter-16-rl-circuits)
17. [RLC Circuits and Resonance](#chapter-17-rlc-circuits-and-resonance)
18. [Passive Filters](#chapter-18-passive-filters)
19. [Circuit Theorems in AC Analysis](#chapter-19-circuit-theorems-in-ac-analysis)
20. [Time Response of Reactive Circuits](#chapter-20-time-response-of-reactive-circuits)
21. [Three-Phase Systems in Power Applications](#chapter-21-three-phase-systems-in-power-applications)

---

## Chapter 1: Quantities and Units
### SI Units
- **Base Units**: 
  - Meter (m): Unit of length.
  - Kilogram (kg): Unit of mass.
  - Second (s): Unit of time.
  - Ampere (A): Unit of electric current.
  - Kelvin (K): Unit of temperature.
  - Candela (cd): Unit of luminous intensity.
  - Mole (mol): Unit of substance.
- **Supplementary Units**:
  - Radian (rad): Plane angle.
  - Steradian (sr): Solid angle.

### Scientific Notation
- Represents large/small numbers as a × 10^n.
- Example: 150,000 as 1.5 × 10^5, 0.00022 as 2.2 × 10^-4.

### Engineering Notation
- Similar to scientific notation but with exponents in multiples of three.
- Example: 33,000 as 33 × 10^3.

### Metric Prefixes
- Kilo- (k) 10^3
- Mega- (M) 10^6
- Giga- (G) 10^9
- Tera- (T) 10^12
- Milli- (m) 10^-3
- Micro- (μ) 10^-6
- Nano- (n) 10^-9
- Pico- (p) 10^-12

## Chapter 2: Voltage, Current, and Resistance
### Atomic Structure
- **Protons**: Positively charged particles in the nucleus.
- **Neutrons**: Neutral particles in the nucleus.
- **Electrons**: Negatively charged particles orbiting the nucleus.

### Voltage (V)
- **Definition**: Electrical potential difference.
- **Unit**: Volt (V).
- **Formula**: V = W/Q, where W is energy in joules and Q is charge in coulombs.

### Current (I)
- **Definition**: Flow of electric charge.
- **Unit**: Ampere (A).
- **Formula**: I = Q/t, where Q is charge in coulombs and t is time in seconds.

### Resistance (R)
- **Definition**: Opposition to current.
- **Unit**: Ohm (Ω).
- **Formula**: R = ρ (L/A), where ρ is resistivity, L is length, and A is cross-sectional area.

### Basic Circuit Measurements
- **Voltmeter**: Measures voltage.
- **Ammeter**: Measures current.
- **Ohmmeter**: Measures resistance.

## Chapter 3: Ohm's Law
### Formula
- **Ohm's Law**: V = IR
  - Voltage (V) = Current (I) × Resistance (R)
- **Rearranged**:
  - Current: I = V/R
  - Resistance: R = V/I

### Examples
- **Example 1**: If V = 10V and R = 5Ω, find I.
  - I = 10V / 5Ω = 2A
- **Example 2**: If I = 3A and V = 12V, find R.
  - R = 12V / 3A = 4Ω

## Chapter 4: Energy and Power
### Power (P)
- **Formula**: P = VI
  - Alternate Forms:
    - P = I^2R
    - P = V^2/R
- **Unit**: Watt (W).

### Energy (W)
- **Formula**: W = Pt
- **Unit**: Joule (J) or Watt-hour (Wh).

### Examples
- **Example 1**: Find power if V = 10V and I = 2A.
  - P = 10V × 2A = 20W
- **Example 2**: Find energy used in 2 hours if P = 100W.
  - W = 100W × 2h = 200Wh

## Chapter 5: Series Circuits
### Total Resistance
- **Formula**: R_total = R_1 + R_2 + ... + R_n
- **Example**: R_1 = 5Ω, R_2 = 10Ω, R_total = 15Ω.

### Current
- **Concept**: Same through each series resistor.
- **Example**: If V = 12V and R_total = 6Ω, I = 2A.

### Voltage Drop
- **Formula**: V = IR
- **Example**: If I = 2A and R = 5Ω, V = 10V.

### Kirchhoff’s Voltage Law (KVL)
- **Concept**: Sum of all voltages around a loop is zero.
- **Example**: V_total = V_1 + V_2 + V_3.

### Voltage Divider
- **Formula**: V_out = V_in × (R_2 / (R_1 + R_2))
- **Example**: If V_in = 12V, R_1 = 2kΩ, R_2 = 3kΩ, V_out = 7.2V.

### Power
- **Formula**: P = I^2R
- **Example**: If I = 2A and R = 10Ω, P = 40W.

## Chapter 6: Parallel Circuits
### Total Resistance
- **Formula**: 1/R_total = 1/R_1 + 1/R_2 + ... + 1/R_n
- **Example**: R_1 = 10Ω, R_2 = 20Ω, R_total = 1 / (1/10 + 1/20) = 6.67Ω.

### Voltage
- **Concept**: Same across each parallel resistor.
- **Example**: If V = 12V, V is the same across each branch.

### Current
- **Formula**: I = V/R
- **Example**: If V = 12V and R = 6Ω, I = 2A.

### Kirchhoff’s Current Law (KCL)
- **Concept**: Sum of currents entering a junction equals the sum of currents leaving.
- **Example**: I_total = I_1 + I_2 + I_3.

## Chapter 7: Series-Parallel Circuits
### Identify Relationships
- **Concept**: Combination of series and parallel resistors.
- **Example**: A circuit with R_1 and R_2 in series, and R_3 in parallel with the series combination.

### Total Resistance
- **Method**: Calculate series and parallel sections separately.
- **Example**: R_series = R_1 + R_2, R_total = 1 / (1/R_series + 1/R_3).

### Voltage Dividers
- **Concept**: Used in series-parallel circuits.
- **Example**: Voltage divider formula can be applied to find the voltage across resistors.

### Loading Effect
- **Concept**: Voltmeter impact on circuit measurements.
- **Example**: A high-resistance voltmeter minimizes loading effect.

### Ladder Networks
- **Concept**: Networks used in digital-to-analog conversions.
- **Example**: Calculate equivalent resistance in ladder networks.

### Wheatstone Bridge
- **Concept**: Used for precise measurement of resistance.
  - **Balanced**: No current through the galvanometer.
  - **Unbalanced**: Current through the galvanometer.

### Troubleshooting
- **Concept**: Identifying and fixing open and short circuits.
- **Example**: Use multimeter to find faults in circuits.

## Chapter 8: Circuit Theorems and Conversions
### Thevenin’s Theorem
- **Concept**: Replace a linear circuit with an equivalent circuit with a single voltage source and series resistance.
- **Example**: Find V_th and R_th to create the Thevenin equivalent circuit.

### Norton’s Theorem
- **Concept**: Similar to Thevenin’s but with a current source in parallel with a resistance.
- **Example**: Find I_no and R_no to create the Norton equivalent circuit.

### Superposition Theorem
- **Concept**: Total response in a linear circuit with multiple sources is the sum of the responses from each source acting alone.
- **Example**: Calculate voltages/currents with each source acting alone and sum the effects.

### Maximum Power Transfer Theorem
- **Concept**: Maximum power is transferred when the load resistance equals the source resistance.
- **Example**: R_load = R_source for maximum power transfer.

### Source Conversions
- **Concept**: Conversion between voltage and current sources.
- **Example**: V_s = I_s × R_s, I_s = V_s / R_s.

### Delta-to-Wye and Wye-to-Delta Conversions
- **Concept**: Transformations for simplifying complex resistor networks.
- **Example**: Use conversion formulas to simplify circuit analysis.

## Chapter 9: Branch, Loop, and Node Analyses
### Branch Current Method
- **Concept**: Assign currents to individual branches.
- **Example**: Solve simultaneous equations for branch currents.

### Loop Current Method
- **Concept**: Use Kirchhoff’s Voltage Law (KVL) for loops in the circuit.
- **Example**: Write KVL equations for each loop and solve.

### Node Voltage Method
- **Concept**: Use Kirchhoff’s Current Law (KCL) for nodes in the circuit.
- **Example**: Write KCL equations for each node and solve.

## Chapter 10: Magnetism and Electromagnetism
### Magnetic Fields
- **Concept**: Created by moving electric charges.
- **Example**: Magnetic field around a current-carrying conductor.

### Electromagnetism
- **Concept**: Relationship between electricity and magnetism.
- **Example**: Right-hand rule for direction of magnetic field.

### Electromagnetic Devices
- **Examples**: Transformers, inductors, motors.

### Electromagnetic Induction
- **Concept**: Generation of electromotive force (EMF) by changing magnetic fields.
- **Example**: Faraday’s Law of Induction.

### DC Generators and Motors
- **Concept**: Basic operation and characteristics.
- **Example**: DC motor speed control using varying voltage.

## Chapter 11: Introduction to Alternating Current and Voltage
### Sinusoidal Waveform
- **Characteristics**: Amplitude, frequency, phase.
- **Example**: AC voltage described by V(t) = V_max sin(ωt + φ).

### Phasors
- **Concept**: Represent AC quantities.
- **Example**: V = V_max ∠ θ in phasor form.

### AC Circuit Analysis
- **Impedance (Z)**: Z = R + jX.
- **Reactance (X)**: X_L = ωL, X_C = 1/ωC.

### Alternators and AC Motors
- **Concept**: Basic operation.
- **Example**: AC motor types and their applications.

## Chapter 12: Capacitors
### Capacitance (C)
- **Concept**: Ability to store charge.
- **Unit**: Farad (F).
- **Formula**: C = Q/V.

### Types of Capacitors
- **Examples**: Electrolytic, ceramic, film, etc.

### Series and Parallel Capacitors
- **Series**: 1/C_total = 1/C_1 + 1/C_2 + ... + 1/C_n.
- **Parallel**: C_total = C_1 + C_2 + ... + C_n.

### Capacitors in DC and AC Circuits
- **DC Circuits**: Charging and discharging.
- **AC Circuits**: Capacitive reactance X_C = 1/ωC.

## Chapter 13: Inductors
### Inductance (L)
- **Concept**: Ability to store energy in a magnetic field.
- **Unit**: Henry (H).
- **Formula**: V = L (dI/dt).

### Types of Inductors
- **Examples**: Air-core, iron-core, ferrite-core, etc.

### Series and Parallel Inductors
- **Series**: L_total = L_1 + L_2 + ... + L_n.
- **Parallel**: 1/L_total = 1/L_1 + 1/L_2 + ... + 1/L_n.

### Inductors in DC and AC Circuits
- **DC Circuits**: Time constant τ = L/R.
- **AC Circuits**: Inductive reactance X_L = ωL.

## Chapter 14: Transformers
### Mutual Inductance
- **Concept**: Principle of operation.
- **Formula**: M = k √(L_1 L_2).

### Step-Up and Step-Down Transformers
- **Concept**: Voltage transformation.
- **Formulas**: V_s = (N_s/N_p) V_p, I_s = (N_p/N_s) I_p.

### Impedance Matching
- **Concept**: Ensuring maximum power transfer.
- **Example**: Z_in = Z_out.

### Transformer Ratings and Characteristics
- **Ratings**: Power, voltage, current.
- **Characteristics**: Efficiency, regulation.

## Chapter 15: RC Circuits
### Complex Numbers
- **Representation**: Impedance Z = R + jX.

### Series RC Circuits
- **Impedance**: Z = R + jX_C.
- **Phase Angle**: θ = tan^-1(X_C/R).

### Parallel RC Circuits
- **Analysis**: Using admittance Y.
- **Applications**: Filters, timing circuits.

### RC Filters
- **Low-Pass Filter**: Allows low frequencies.
- **High-Pass Filter**: Allows high frequencies.

## Chapter 16: RL Circuits
### Series RL Circuits
- **Impedance**: Z = R + jX_L.
- **Phase Angle**: θ = tan^-1(X_L/R).

### Parallel RL Circuits
- **Analysis**: Using admittance Y.
- **Applications**: Filters, timing circuits.

### RL Filters
- **Low-Pass Filter**: Allows low frequencies.
- **High-Pass Filter**: Allows high frequencies.

## Chapter 17: RLC Circuits and Resonance
### Series and Parallel RLC Circuits
- **Impedance**: Z = R + j(X_L - X_C).

### Resonance
- **Concept**: Condition where X_L = X_C.
- **Frequency**: f_r = 1 / (2π√(LC)).

### Applications
- **Examples**: Tuned circuits, filters.

## Chapter 18: Passive Filters
### Low-Pass Filters
- **Concept**: Allow low frequencies.
- **Cutoff Frequency**: f_c = 1 / (2πRC).

### High-Pass Filters
- **Concept**: Allow high frequencies.
- **Cutoff Frequency**: f_c = 1 / (2πRC).

### Band-Pass Filters
- **Concept**: Allow a range of frequencies.
- **Bandwidth**: BW = f_2 - f_1.

### Band-Stop Filters
- **Concept**: Block a range of frequencies.
- **Bandwidth**: BW = f_2 - f_1.

## Chapter 19: Circuit Theorems in AC Analysis
### AC Superposition Theorem
- **Concept**: Application to AC circuits.
- **Example**: Calculate voltages/currents with each source acting alone and sum the effects.

### Thevenin’s and Norton’s Theorems
- **Concept**: Application to AC circuits.
- **Example**: Find V_th, I_no, R_th, and R_no for AC circuits.

### Maximum Power Transfer Theorem
- **Concept**: Application to AC circuits.
- **Example**: R_load = R_source for maximum power transfer in AC circuits.

## Chapter 20: Time Response of Reactive Circuits
### RC and RL Integrators
- **Concept**: Response to pulse inputs.
- **Example**: Calculate voltage/current responses in integrator circuits.

### Differentiators
- **Concept**: Response to pulse inputs.
- **Example**: Calculate voltage/current responses in differentiator circuits.

### Time and Frequency Response
- **Concept**: Relationship between time-domain and frequency-domain responses.
- **Example**: Use Fourier transforms to analyze circuit behavior.

## Chapter 21: Three-Phase Systems in Power Applications
### Three-Phase Generators
- **Concept**: Operation and types.
- **Example**: Analyze three-phase generator output.

### Three-Phase Source/Load Analysis
- **Concept**: Calculations and applications.
- **Example**: Use phasor diagrams to analyze three-phase systems.

### Three-Phase Power
- **Concept**: Power calculations in three-phase systems.
- **Example**: P = √3 V_line I_line cos(θ).
