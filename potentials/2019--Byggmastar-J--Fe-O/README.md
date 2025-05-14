# 2019--Byggmastar-J--Fe-O

## Implementations

- [2019--Byggmastar-J--Fe-O--LAMMPS--ipr1](https://www.ctcms.nist.gov/potentials/entry/2019--Byggmastar-J-Nagel-M-Albe-K-et-al--Fe-O/2019--Byggmastar-J--Fe-O--LAMMPS--ipr1.html) in NIST Interatomic Potentials Repository
- FeO.tersoff taken from https://github.com/houzf/ABOP_lammps
- FeO_abop.tersoff.zbl generated here from FeO.abop

Agreement seen between 2019--Byggmastar-J--Fe-O--LAMMPS--ipr1 and FeO_abop.tersoff.zbl except for some precision differences.  FeO_abop.tersoff.zbl *does not* agree as it has incorrect values for gamma for the Fe-O-Fe and O-Fe-O interactions (and is missing ZBL terms)

## Status

Use 2019--Byggmastar-J--Fe-O--LAMMPS--ipr1 as its parameter file was obtained from the developers.

Do a pull request to https://github.com/houzf/ABOP_lammps with the correct parameters.