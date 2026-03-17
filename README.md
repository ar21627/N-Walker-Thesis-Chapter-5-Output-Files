This repository holds output files for the DFT optimisations discussed in Chapter 5 of Nicholas Walker's PhD thesis: Turning Data into Knowledge - Data-Led Catalyst Optimisation. There are two types of files included: files with the .out extension, which contain optimisation details, and files with the .01.in which contain the cartesian coordinates for the final geometry of each optimisation.

There are eight directories of files in this repository: one for each of the eight ligands whose catalytic cycles were studied, and one for the reagents and byproducts common to each catalytic cycle. The directory for each ligand is labelled by their LKB-P unique identifiers. These correspond to ligands as follows:

PL139 is JohnPhos

PL145 is SPhos

PL146 is XPhos

PL154 is <sup>_t_</sup>BuMePhos

PL274 is <sup>_t_</sup>BuXPhos

PL344 is BrettPhos

PL747 is vBRIDP

Each ligand folder except PL344 contains 19 of each file type. The naming convention for these files corresponds to steps in the theoretical catalytic cycle as follows:

PLXXX - Free ligand

L1_PLXXX - PdL

L2_PLXXX - PdL2

L1_NaOtBu_PLXXX - NaO<sup>_t_</sup>BuPdL

enc_comp_L1_PLXXX - Int 1

ox_add_TS_L1_PLXXX - TS 1

ox_add_(Ar/L/Br)_L1_PLXXX - Int 2, three different conformations of ligands about the metal tested for each

L_Ar_NaOtBu_Br_O_trans_PLXXX - Dep A.1

L_Ar_OtBu_PLXXX - Dep A.2

L_Ar_OtBu_N_Ar_trans_PLXXX - Dep A.3

L_Ar_Br_N_N_trans_PLXXX - Dep B.1

L_Ar_Br_N_Na_N_trans_PLXXX - Dep B.2

red_elim_(Ar/L/N)_trans_L1_PLXXX - Int 3, three different conformations of ligands about the metal tested for each

red_elim_TS_L1_PLXXX - TS 2

red_elim_complex_L1_PLXXX - Int 4

In the PL344 directory, there are additionally three conformers of Dep A.1 without the sodium counterion (L*Ar_OtBu_Br*(Ar/Br/O)\_trans_PL344).

Numbers are present after the 'PLXXX' section of files names in instances where more than one attempt was made to converge the structure.
