# Current Division - Parallel Resistors

## Objective

To understand how current divides between parallel resistors with different resistance values and verify the results using Tinkercad simulation.

## Circuit

An 8V supply is connected to two parallel resistor branches:

- Branch 1: 1kΩ resistor
- Branch 2: 2kΩ resistor

Both branches are connected across the same 8V supply.

## Concept

In a parallel circuit:

- The voltage across each branch is the same.
- The total current divides between the branches.
- The branch with lower resistance carries more current.

## Design Calculation

### 1. Equivalent Resistance

Rₜ = (R₁ × R₂) / (R₁ + R₂)

Rₜ = (1kΩ × 2kΩ) / (1kΩ + 2kΩ)

Rₜ = 0.6667kΩ

Rₜ ≈ 667Ω

### 2. Total Current

Iₜ = V / Rₜ

Iₜ = 8V / 667Ω

Iₜ ≈ 12mA

### 3. Branch Currents

For the 1kΩ branch:

I₁ = 8V / 1kΩ

I₁ = 8mA

For the 2kΩ branch:

I₂ = 8V / 2kΩ

I₂ = 4mA

### 4. Current Check

Iₜ = I₁ + I₂

Iₜ = 8mA + 4mA

Iₜ = 12mA

## Simulation Results

| Quantity | Calculated | Tinkercad |
|---|---:|---:|
| Total current | 12mA | 12mA |
| 1kΩ branch current | 8mA | 8mA |
| 2kΩ branch current | 4mA | 4mA |

## Observation

The 1kΩ resistor carries twice the current of the 2kΩ resistor.

This happens because both branches have the same voltage, while the 1kΩ resistor has lower resistance.

## What I Learned

- Current divides between parallel branches.
- Parallel branches have the same voltage.
- Lower resistance carries more current.
- Total current is the sum of the branch currents.
- Current division can be predicted using circuit calculations.

## Engineering Lesson

Current division is important when analyzing parallel paths in electronic circuits. Understanding how current distributes between different resistance values helps in circuit design and troubleshooting.

## Tools Used

- Tinkercad Circuits
- 8V DC supply
- 1kΩ resistor
- 2kΩ resistor
