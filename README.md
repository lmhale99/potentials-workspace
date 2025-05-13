# Potentials Workspace

This repository provides a workspace for preparing and testing of interatomic potential parameter files for use with the LAMMPS software.  Primarily, it focuses on attempting to implement existing potentials in LAMMPS-compatible formats when such implementations are not available from the original developers.  This repository was created to serve as a consolidated location for such work and share progress and information.

***WARNING!!!***  Please carefully read the status notes associated with each potential to check its level of development and testing!

***WARNING!!!***  Many of the parameter files hosted here are untested or untrusted and may not behave consistent to the original publications!

***WARNING!!!***  Due to the developmental nature of this repository, any contained parameter files may change over time without much notice!

See the NIST Interatomic Potentials Repository for tested, trusted, and traceable interatomic potentials.

## Code suggestions/requirements

Most of the developmental work done in this repository uses the Python packages created by the NIST Interatomic Potentials Repository project.  In particular,
- potentials contains tools for generating and analyzing LAMMPS parameter files in a variety of formats.
- iprPy collects a number of standard property evaluation methods that can be used to test the behavior of the parameter files.