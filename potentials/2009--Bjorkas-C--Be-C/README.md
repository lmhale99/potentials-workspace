# 2009--Bjorkas-C--Be-C-H

## Implementations

- BeC.tersoff taken from https://github.com/houzf/ABOP_lammps
- BeC_abop.tersoff.zbl generated here from BeC.abop

Agreement seen between BeC.tersoff and BeC_abop.tersoff.zbl, but BeC.tersoff has lower precision for some values and is missing the ZBL terms.

## Status

Be-C ineraction seems consistent.

Paper contains Be-Be I and II models, with II better suited for Be-C interactions.  Alternate potentials should be built for the other interaction models.

Full Be-C-H potentials use the Brenner C-H interactions, which is not fully clear how to port to ABOP or Tersoff yet...
