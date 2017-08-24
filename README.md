CIF models for the waterway lock described in the CCTA paper

Compatible with CIF version r9682, downloaded from http://cif.se.wtb.tue.nl/

Input files:
[1_Plant_requirements.cif] Code for automata plant model, and state-based requirements

[2_Simulation.cif]         Code for hybrid plant model, imports [3_Visualisation.cif] 

[3_Visualisation.cif]      Code for link between hybrid plant model and SVG visualisation 

[4_Lock.svg]               SVG visualisation of Lock III

Output files:
[5_Supervisor.cif]         Synthesized supervisor using [Synthesis.tooldef2]
[6_Supervisor_Hybrid.cif]  Merge of [2_Simulation.cif] and [5_Supervisor.cif], using [Simulation.tooldef2]

Executable files:
[Synthesis.tooldef2]       Execute to synthesise [5_Supervisor.cif] from [1_Plant_requirements.cif]
[Simulation.tooldef2]      Execute to generate and simulate [6_Supervisor_Hybrid.cif]

For any questions related to the code please contact F.F.H.Reijnen@tue.nl
