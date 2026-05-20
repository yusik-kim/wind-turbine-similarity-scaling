# Wind Turbine Similarity Scaling for OpenFAST Retrofit Studies

This repository contains:
- similarity scaling derivation
- public turbine datasets
- tower mass scaling validation

## Similarity scaling for tower

For geometrically similar tubular towers:
m ~ P^(2/3) H
where m=tower mass, P=rated power, H=tower height

I verified this scaling against multiple public wind turbine datasets, as shown in the figure below.

Key takeaways:
• The relation suggests that tower mass scales linearly with tower base moment, P^(2/3)H.
• Despite tower masses spanning nearly 30×, this simple scaling provides a  good first-order estimate.
• Only rated power and hub height are required — parameters that are almost always available.
• Small to mid-sized turbines (<3 MW) follow the scaling very well.
• Larger turbines show increasing deviation, potentially due to stronger influence from frequency constraints, offshore design drivers, or idling/extreme load requirements.

See derivation here [Scaling derivation PDF](Docs/Derivation%20of%20tower%20scaling.pdf)


## Tower mass scaling validation

![Tower scaling](Figure/tower_mass_scaling_plot.png)


