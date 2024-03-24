# Risk Process and Fractional Brownian Motion

The report provides a detailed description and implementation of the following topics:

### Part 1 - Risk Process
It concerns fitting a classical risk model to data. The provided data includes one trajectory of the process, a time horizon - T, a time step - h, and a parameter of premium level - theta. This part of the report includes:

a) Estimation of parameters using the maximum likelihood method and comparison of the provided trajectory with data to simulated trajectories of the fitted risk process.

b) Estimation of ruin probability in finite (T=100 and T=200) and infinite time.

c) Parisian Ruin - bankruptcy of the company occurs when its capital falls below 0 for a period of at least q consecutive time units. This part covers topics such as:
- how the ruin probability changes depending on q,
- the impact of the chosen value of q on the initial capital,
- how the average time to ruin changes depending on q on the interval [0, 100].

### Part 2 - Fractional Brownian Motion
It concerns the implementation of a generator for trajectories of fractional Brownian motion and testing it by comparing theoretical quantile lines with those determined empirically.
