# MOSFET Amplifiers using LTspice

This repository contains LTspice simulations of MOSFET common source amplifiers.

## Projects

### Single-Stage Common Source Amplifier
- Single MOSFET common source configuration
- Voltage Gain ≈ 24 mV/ 1 mV = 24

### Two-Stage Common Source Amplifier
- Two cascaded common source stages
- Voltage Gain ≈ 450 mV/ 1 mV = 450

## Key Observation

The two-stage common source amplifier achieves significantly higher voltage gain than the single-stage amplifier.

|    Amplifier    | Approximate Voltage Gain |
|-----------------|--------------------------|
| Single-Stage CS | 24 V/V |
| Two-Stage CS    | 450 V/V |

This demonstrates the principle of cascading amplifier stages to achieve higher overall gain in analog circuit design.

## Conclusion

By cascading two common-source MOSFET stages, the overall voltage gain increased from approximately 24 V/V to 450 V/V, illustrating the effectiveness of multistage amplification techniques in analog circuit design.

## Software Used
- LTspice XVII

## Concepts Covered
- MOSFET Biasing
- Common Source Amplifier
- Multi-stage Amplifiers
- AC Sweep Analysis
- Voltage Gain Analysis
