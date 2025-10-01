# Symmetry-reduction-utilization-for-near-stabilizers
This depositary contains jupiter notebooks with code that calculates orbits of symmetry reduced near stabilizer multy-copy systems, and some additional parameters

There 3 files, they all share thre same 1st block of code that defines most of the functions that count orbits, convert matrices, set workflow for symmetry constraint mappin, solve convex problems .
Then they are followed by ssubject specific code part: 
  -workhorse orbits contais wrapper that calculates orbits for different t for specific n; 
  -workhorse Sweeps, calculates selecrted directional sweeps, and sweeps ower selected 2-witness planes for different t and n;
  -workhorse metric has a lot of additional functions to calculate metrics: trace distance or robustness, unfortunately dense mesh for present number of wtabilizer directions is unseasible excepf for n=1. 
