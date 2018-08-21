This is a repository for building an experiment suite using MOM6.

This is meant to be simple and minimalist in its design, for maximum
portability and minimum headache.

NOTES:

git rm src/land_lad2 prior to (git submodule init;git submodule update)
if you are outside of GFDL firewall

. activate <your environment with netCDF/HDF and MPICH pre-compiled>
. build/env/linux-gnu
make compile_MOM6_solo
