# ChemGauss4 docking score predictor based on molecular features
Based on results of a virtual screen against an integrin homology model

Takes input in the form:

> [Polar surface area (ang^2), Hydrogen bond acceptor groups, hydrogen bond donor groups, largest ring size, molecular weight (gmol^-1), number of ring systems, number of rotatable bonds]

#### Limitations / ToDO:
- Use a xray structure to acquire docking data
- Save more than 200 ligands per ZINC15 tranche for representative sample of scores
- Optimize network geometry
