# get_data_BDE
Get data from ORCA and Gaussian output file for SMD(H2O)/DLPNO-CCSD(T)/CBS//(U)B3LYP-D3/6-31+G(d,p) level of theory

data extraction tool used in https://doi.org/10.1002/cbic.202100420

- can be used after modification for the extraction of data from Gaussian .log and ORCA .out output files
- DLPNO-CCSD(T)/CBS extrapolation included
- optimization in gasphase, single points in solution phase
- contains geometric centroid analysis to exclude doublet structures
- includes a old version of Bobby Patons (https://github.com/patonlab/GoodVibes) quasi-harmonic approximation (can read only Goodvibes_output.dat with _gv.log files)

If you have questions feel free to contact me!
