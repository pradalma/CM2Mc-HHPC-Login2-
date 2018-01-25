# CM2Mc-HHPC-Login2-

Tested in February 2017, on the current supported HHPC of JHU, the "script_to_run_on_login_2" is the only file a user should need to download and edit (for initCond) get a run started. This scripts points to an executable. This executable has been tested for bitwise reproducibility on login2 and found to reproduce. It has also been tested for climate reproducibility across platforms (old hhpc v2 vs new hhpc login2), by running a 100year simulation and analysing the averaged fields.

Scripts shown here are

script_to_run_on_login2: Base script

newCO2_2000oc_800_ag: Branched version of run with organic carbon set to 2000 levels (J. McCurry senior thesis).

newCO2_nofedep: Branched version with iron deposition set to zero.

January 25 2018: in exec_hpc:
root = /home/pradalma/test_compile/Riga_Grace_acdm
cd /home/pradalma/test_compile/CM2M_compile/exec-hpcs
module load openmpi/gcc/64/1.8.1
module: Command not found.
module load openmpi/intel/1.8.4
module: Command not found.
module load nco/4.5.2
module: Command not found.
module load gcc
module: Command not found.
module load slurm
module: Command not found.
module load netcdf/intel/4.3.3.1
module: Command not found.
module load netcdf-fortran/intel/4.4.2
module: Command not found.
module load netcdf/gcc/64/4.3.1.1
module: Command not found.
module load hdf5/intel
module: Command not found.
module load udunits2
module: Command not found.
module load zlib
module: Command not found.
module load libjpeg
module: Command not found.
module load libpng
module: Command not found.
module load jasper
module: Command not found.
setenv NC_BLKSZ 64K
setenv MPI_COREDUMP_DEBUGGER `which idb`
which idb
set TEMPLATE = /home/pradalma/fre3/sit
