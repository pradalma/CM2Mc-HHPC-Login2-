# CM2Mc-HHPC-Login2-

Tested in February 2017, on the current supported HHPC of JHU, the "script_to_run_on_login_2" is the only file a user should need to download and edit (for initCond) get a run started. This scripts points to an executable. This executable has been tested for bitwise reproducibility on login2 and found to reproduce. It has also been tested for climate reproducibility across platforms (old hhpc v2 vs new hhpc login2), by running a 100year simulation and analysing the averaged fields.

Scripts shown here are

script_to_run_on_login2: Base script

newCO2_2000oc_800_ag: Branched version of run with organic carbon set to 2000 levels (J. McCurry senior thesis).

newCO2_nofedep: Branched version with iron deposition set to zero.
