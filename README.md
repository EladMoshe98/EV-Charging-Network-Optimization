# EV Charging Network Optimization

**1st place** at the IE Business School Datathon. The challenge, proposed by **Iberdrola**, was to design the optimal electric vehicle charging network for Spain's interurban routes for a **2027 operational horizon**, subject to electrical grid capacity constraints.

## Problem

Spain's interurban road network needs a strategically placed EV charging infrastructure to support mass EV adoption by 2027. The placement must respect:
- Existing electrical grid capacity at candidate locations
- Driver range anxiety (maximum distance between chargers)
- Budget and installation constraints

## Approach

1. **Data collection** – road network topology, traffic flow data, grid capacity at candidate sites
2. **Optimization model** – formulated as a facility location / set cover problem
3. **Solver** – mixed-integer linear programming (MILP) with coverage and capacity constraints
4. **Validation** – simulated EV trips across major Spanish corridors

## Results

- Achieved optimal coverage of interurban routes within grid constraints
- Solution selected as best among all competing teams

## Tech Stack

Python · PuLP / OR-Tools · pandas · geopandas · matplotlib
