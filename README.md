

The model reproduces FIG 11A and FIG 11B of the paper. However, please note
that FIG 11B is a plot of normalised amounts versus time. The "stoichiometry"
field has been used to convert fluxes from membrane species to volume species.
The value of 0.0009967 is a product of (Surface to Volume_M*(1/Avagadro's
number)*1E21. 0.6 is the surface to volume ratio of the plasma membrane, 1E21
is required for a unit surface to volume ratio and the Avagadro's number is
present in the denominator to convert molecules to moles. The model was
successfully tested using MathSBML and SBML ODESolver.  
All the kinetic laws have the unit _items per second_ , which requires the one
reaction taking place in the cytoplasm - _IP3Phosphatase_ \- to include an
explicit conversion factor both in the kinetic law and the stoichiometry of
_IP3_C_ . The kinetic law is multiplied and the stoichiometry divided by the
number of molecules per micro-mole. This conversion factor is only required
for correct units and can be replaced by 1, if it should lead to numerical
problems.

  

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not.

  

To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)

