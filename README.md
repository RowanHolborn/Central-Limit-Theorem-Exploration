# Central Limit Theorem Simulation

This project provides a modular Python simulation that visually demonstrates the **Central Limit Theorem (CLT)**. It allows you to:

- Generate synthetic data from a chosen population distribution.
- Visualize the underlying population.
- Simulate the distribution of sample means across different sample sizes.
- Observe how sample means tend toward a normal distribution as sample size increases - even when the population is not normally distributed.

---

## 🔧 Configuration

You can configure the simulation by editing the constants in the central_limit_theorem_simulation.ipynb:

```python
DIST_TYPE = 'exponential'     # Options: 'exponential', 'normal', 'uniform'
DIST_PARAMS = {'scale': 2}    # Distribution-specific parameters
POPULATION_SIZE = 100_000     # Number of data points in the population
SAMPLE_SIZES = [1, 5, 30, 100] # Sample sizes to test
NUM_SAMPLES = 1000            # Number of repeated samples per sample size
```
