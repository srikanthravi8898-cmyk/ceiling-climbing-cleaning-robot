# Design Calculations

## 1. Design Requirements

The robot is being designed to climb and clean ceiling surfaces using a motor-driven suction mechanism.

Initial design assumptions:

- Target robot mass: Less than 1 kg
- BLDC motor: RS2205 2300KV
- Battery: 3S LiPo, 11.1V nominal
- Suction mechanism: Fan or impeller driven by a BLDC motor
- Operating surface: Ceiling or overhead test surface

These are preliminary design targets and must be updated using measured values.

## 2. Gravitational Force

The gravitational force acting on the robot is:

F = m × g

Where:

- F = gravitational force in newtons (N)
- m = total robot mass in kilograms (kg)
- g = gravitational acceleration, approximately 9.81 m/s²

For a preliminary mass of 1 kg:

F = 1 × 9.81 = 9.81 N

Therefore, the robot experiences approximately 9.81 N of gravitational force.

## 3. Required Suction Force

The suction mechanism must generate sufficient normal adhesion force to prevent the robot from detaching from the ceiling.

For a simplified static model:

F_adhesion = ΔP × A_eff

Where:

- F_adhesion = effective adhesion force (N)
- ΔP = pressure difference across the sealed area (Pa)
- A_eff = effective sealed area (m²)

The actual required force depends on the robot's weight, leakage, surface condition, acceleration, and safety factor.

## 4. Safety Factor

The adhesion system should be designed with a suitable safety factor.

Safety Factor = Available Adhesion Force / Required Load

A preliminary target of at least 2 may be considered for initial engineering analysis. The final value must account for dynamic loads, leakage, surface irregularities, and the consequences of detachment.

## 5. Battery Voltage

For a 3S lithium-polymer battery:

- Number of cells: 3
- Nominal cell voltage: 3.7 V
- Nominal pack voltage: 3 × 3.7 = 11.1 V
- Fully charged pack voltage: 3 × 4.2 = 12.6 V

The motor and ESC must be compatible with the battery voltage and current capability.

## 6. Electrical Power

Electrical input power can be estimated using:

P = V × I

Where:

- P = electrical power (W)
- V = supply voltage (V)
- I = current (A)

Measure the actual motor current under the intended impeller load before estimating power consumption.

## 7. Estimated Battery Runtime

A first-order runtime estimate is:

Runtime (hours) = Usable Battery Capacity (Ah) / Average Current (A)

Runtime (minutes) = Runtime (hours) × 60

Actual runtime will be lower or different depending on battery condition, load variation, voltage limits, and system efficiency.

## 8. Testing Plan

- Measure the complete robot mass.
- Measure pressure difference and airflow.
- Measure adhesion force using a secured test fixture.
- Record motor current at different operating speeds.
- Measure battery voltage under load.
- Determine usable runtime under representative conditions.
- Verify adhesion and safety margins before overhead operation.

## 9. Current Status

All calculations are preliminary until supported by measured prototype data.

## Future Updates

This document will be updated with actual measurements, fan specifications, test results, and validated design calculations.
