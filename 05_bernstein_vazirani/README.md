# Bernstein-Vazirani

This folder demonstrates how the Bernstein-Vazirani algorithm recovers a hidden binary string with a single oracle query in the idealized case.

## Notebooks

- [hidden_string_0110.ipynb](hidden_string_0110.ipynb) uses a fixed secret string and shows the recovery circuit and its result.
- [dynamic_string_generator.ipynb](dynamic_string_generator.ipynb) builds the same style of circuit from a secret that is generated dynamically.

## What to Expect

- Oracle construction from a hidden bit string
- Circuit preparation and measurement of the answer register
- Output that reveals the secret string directly in the ideal case

## Suggested Use

Open the fixed-string notebook first to see the algorithm in a concrete example, then use the dynamic version to see how the same pattern generalizes.