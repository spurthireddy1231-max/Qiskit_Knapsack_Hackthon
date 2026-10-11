
# Qiskit Knapsack Optimization — Phase 1 Report

## 1. Problem Statement
The 0/1 Knapsack problem selects items to maximize total value without exceeding the given capacity.

## 2. Official Problem Input
- Values: [10, 4, 7, 5, 8]
- Weights: [5, 3, 4, 2, 6]
- Capacity: 15

## 3. Classical Baseline
- Method: Brute-force search
- Optimal objective value: 26
- Selected items: [1, 2, 3, 4]
- Total weight: 14
- Capacity: 15

## 4. QAOA Simulation
- Method: Quantum Approximate Optimization Algorithm (QAOA)
- Reported objective value: 26
- Status: SUCCESS

## 5. Processor A/B Benchmark
### 5. Processor A/B Benchmark

A sample-circuit transpilation test was performed using the configured Processor A and Processor B connectivity maps.

| Metric | Processor A | Processor B |
|---|---:|---:|
| Circuit Depth | 13 | 5 |
| CX Gates | 7 | 4 |
| SWAP Gates | 0 | 0 |

These measurements are for the sample test circuit only and are not actual QAOA benchmark results. The classical baseline and QAOA simulation both reported an objective value of 26 for the official knapsack input. Further validation is required to compare Processor A and Processor B using the actual QAOA circuit.

## 6. Conclusion
The classical baseline and QAOA simulation both reported an objective value of 26 for the official input. Processor A/B performance conclusions require measured benchmark results.
