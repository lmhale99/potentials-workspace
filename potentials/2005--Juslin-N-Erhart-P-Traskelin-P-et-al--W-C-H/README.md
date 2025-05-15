# 2005--Juslin-N--W-C-H

## Implementations

- WC.tersoff taken from https://github.com/houzf/ABOP_lammps
- WC_abop.tersoff generated here from WC.abop

Agreement seen between the two versions, with some values rounded in WC.tersoff to a lower precision.

## Status

With agreement seen in W-C parameterization, tests should be ran to validate the potential against published results.

Implementing the full W-C-H potential requires more work and investigation.  The Table of ABOP parameters in the source publication list columns for both H-C and C-H interactions.  Not sure if this is a typo or needs to be treated in a unique way.  The C-H interactions were taken from D. W. Brenner, Phys. Rev. B 42, 9458 (1990) and D. W. Brenner, Phys. Rev. B 46, 1948 (1992) where the parameters and equations were represented in a substantially different way.  Verification would probably require re-converting the Brenner parameters into ABOP parameters or performing a direct conversion into LAMMPS parameters.
