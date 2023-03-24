# Surface roughness in CNC machining

Data source: 
L.C. Moreira, W.D. Li, X. Lu, M.E. Fitzpatrick "Supervision controller for real-time surface quality assurance in CNC machining using artificial intelligence" in Computers & Industrial Engineering, Volume 127, January 2019, Pages 158-168

DOI: https://doi.org/10.1016/j.cie.2018.12.016

## Data dictionary
```
S : Spindle speed [rpm]
F: Tool feed-rate [mm/min]
MMR: Material removal rate [mm^3/min]
Ra: Surface roughness [Ra]
```

Work-piece material was: BS EN24T Alloy (AISI 4340)

The material removal rate (MMR) is computed based on F*ap*ae where ap (depth of cut) and ae (width of cut) which were constant (32 mm and 4 mm).