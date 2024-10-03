# CHO_screeningV2
This is an updated version of CHO_screening algorithm:
1. changed from Perl script to R script;
2. avoid of paramter txt files;
3. efficiency updated

Usage:
In script.R file, add "dir" and "pdb_name

dir = "/home/XXX/"
pdb_name = "test.pdb"  ####input pdb name

run through the whole script, and the output file will be created in the same folder "test.pdb.out"


Paramters used:
TRP: r_cutoff = 2.7; h_cutoff = 6.7; d_cutoff = 12.6; 
PHE: r_cutoff = 2.9; h_cutoff = 6.7; d_cutoff = 11.5; 
TYR: r_cutoff = 3.0; h_cutoff = 5.9; d_cutoff = 11.6; 

2024-09-02
