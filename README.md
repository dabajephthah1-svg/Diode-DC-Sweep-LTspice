# Diode-DC-Sweep-LTspice
# Diode DC Sweep Analysis (LTspice)

## Overview
This project analyzes the behavior of a diode circuit using LTspice. The same circuit is simulated using two diode models: an ideal diode and a practical silicon diode (1N4148). A DC sweep analysis is performed to compare their electrical characteristics.

## Turn-On Voltage Difference
The ideal diode turns on at 0 V, meaning it begins conducting current immediately when a forward voltage is applied. In contrast, the 1N4148 diode requires a forward voltage of approximately 0.6–0.7 V before significant current flows. This voltage drop is due to the physical properties of the PN junction in real diodes.

## Current Behavior Difference
For the ideal diode, the current increases sharply once the voltage becomes positive, showing no gradual transition. The real diode exhibits a nonlinear exponential increase in current after its turn-on voltage. At lower voltages, the current is very small due to the diode’s internal barrier potential.

## Why Ideal Models Are Used
Ideal diode models are useful for learning, quick calculations, and simplifying circuit analysis. They help engineers understand circuit operation without the complexity of real-world effects.

## When Ideal Models Become Inaccurate
Ideal models become inaccurate when precise voltage levels, power dissipation, or current behavior are important. In real circuits, diode voltage drops, leakage currents, and temperature effects must be considered, making practical diode models necessary.
