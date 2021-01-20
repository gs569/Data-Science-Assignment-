# Data-Science-Assignment - Elementary analysis of Flourescent Cross Correlation Spectroscopy data

This program is written in Python and provides fast elementary analysis of Flourescent Cross Correlation Spectroscopy (FCCS) data. The program can be used to analyse any FCCS data of any two molecules tagged with dual-coloured fluorophores measured from either in vitro or in vivo systems. The program enables the user to calculate the dissociation coefficient, KD, of two molecules, and summarises the the concentrations and rates of diffusion of ligand, receptor and the ligand-receptor complex (known as cross). The program creates ready-to-use figures which the user can save and use for other purposes, such as presentations and publications.

The example data provided (FCCS_run1.csv, FCCS_run2.csv and FCCS_run3.csv) was taken from 3 FCCS experiments analysing the interaction of wnt8a-mCherry ligand and Frizzled7a-YFP receptor in zebrafish. The example data contains measurements for the concentration of the ligand, receptor and cross, labelled as ligand_conc, receptor_conc and cross_conc, respectively. The diffusion rates of the ligand, receptor and cross are labelled as ligand_D2, receptor_D2 and cross_D2, respectively. If the user requires the code for analysis of their own FCCS data, the column headings in the original dataframe should match those in the example data.

To run:

1. Download python scipts and example data files (FCCS_run1.csv, FCCS_run2.csv and FCCS_run3.csv) into a single directory.

2. Run the script and check the dataframe format. The RUN column indicating each observation number during the experiment should be the first column in the dataframe that is suitable as an index column. 

3. The data is used to calculate the KD and then summary of concentrations and diffusion rates of the receptor, ligand and cross. The program creates figures with the data which the user can choose to save, simply by removing the # as indicated in the script.
