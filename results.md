
# Benchmark Results

This folder stores measured results for the official O3 Knapsack problem.

## Official Problem
- Values: [10, 4, 7, 5, 8]
- Weights: [5, 3, 4, 2, 6]
- Capacity: 15

## Current Verified Results
- Classical brute-force objective: 26
- QAOA simulation objective: 26
- Classical selected items: [1, 2, 3, 4]
- Classical total weight: 14

## Processor A/B Comparison
**Note:** The Processor A/B depth, CX gate, and SWAP gate values are from the sample-circuit transpilation test only. They are not actual QAOA benchmark results. The classical brute-force and QAOA simulation both reported an objective value of 26 for the official knapsack input. Processor A/B performance conclusions should be based on measurements from the actual QAOA circuit.
