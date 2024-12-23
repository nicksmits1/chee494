- `si_c2h6`: structure I with ethane
- `si_ch4`: structure I with methane
- `si_co2`: structure I with carbon dioxide
- `si_eo`: structure I with ethylene oxide
- `si_hcn`: structire I with hydrogen cyanide
- `sii_is`: structure II with isobutane
- `sii_nb`: structure II with n-butane
- `sii_pr`: structure II with propane
- `sii_pr_me`: structure II with propane and methane
- `si_ref_centers.xyz`: structure I from reference with small and large cages labelled
- `sii_ref_centers.xyz`: structure II from reference with the small and large cages labelled
- `sh_ref_centers.xyz`: structure H from reference with small and large cages labelled
- `.vasp` files come from density functional theory (VASP)
    - first line after comment is a scaling factor
    - next three lines are the three vectors (one per line) for the lattice
    - then atom counts
    - then Direct or Cartesian: direct means the they are provided in fractional coordinates of the lattice parameters, Cartesian means they are directly provided in a cartesian coordinate system.
- files labelled with `POSCAR` are from VASP
- `POSCAR` files should be readily convertible to `.data` files with Ovito
    - `File` > `Export File` > select `LAMMPS Data File (*)` in `Files of type:`
    - default `Export Settings` are fine