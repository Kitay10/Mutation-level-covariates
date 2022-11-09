This code was used in the analysis presented in the work "A mutation-level covariate model for mutational signatures"
4 Folders are availabe:
1) MCSM vs LDA - providing the implementation of those two models, and a script that may be used two test them.
The script file name here is MCSM_NEW_2fold_CV_Main uses the replication strand as the feature.
The script file name here is MCSM_NEW_2fold_CV_Main_Genomic uses the replication strand as the feature.
2) JMCSM vs gLDA -providing the implementation of those two models, and a script that may be used two test them.
The script file name here is JMCSM_NEW_2fold_CV_Main uses the replication strand as the feature.
The script file name here is JMCSM_NEW_2fold_CV_Main_Genomic uses the replication strand as the feature.
5) data - providing the raw data that is used in the research (BRCA, MALY and CLLE + Cosmic signatures V2).
To use the code, the data files should be placed in the folder of interest before running the script. To use the replication strand, only the JSON 
files should be used. To use the genomic strand, the tsv files should also be placed in the folder.
6) Results - this folder contains 12 files that were generated using the code described above. 
The names of the files follow the following format: strand_database_model.

We also provide 4 more file that can be used to generate data and relearn the signatures:
1) Generate_Then_Relearn_JMCSM
2) Generate_Then_Relearn_MCSM
Simply put it in the respective folder and run it.
3) get_sig_bias - used to generate figure 5

For further information, please contact itay10kahane@gmail.com



