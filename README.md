Codes for Bachelor's thesis (R)
Author: Linda Ruchti

During the thesis data from Lac Sentinelles Network was used. Bottom oxygen was investigated. Visually three types of oxygen dynamic were determined.
In further analysis parameters relevant for distinguishing those typologies were investigated with statistical analysis.

Workflow and Order of codes

Data preparation:
clear extreme values
->exterem values of raw data were deleted (O2 sat, O2 conc, Temp)
change data from long to broad format
->change format of data
qc_scatterplots raw vs clear
->quality control raw data versus cleaned up data
plot DO over year
->for visual analysis and determining which lake belonged in which typology

Creating datafile for Analysis
modeling wavelet making model_df
->modleing metabolism values using LakeMetabolizer and checking with Wavelet Analysis
model_df to complete_df
->extracting modeling values and creating final datafile used for analysis, adding further paramters to it
make zmix and secchi relative values
->data for secchi and zmix was through complete lake depth, had to be relatove to be comparable between lakes
qc_boxplots showing added parameters before statistics
->quality control of final datafile before analysis
separation of complete df
->

Analysis
pca
->PCA of all lakes and all parameters
statistical testing and boxplots
->tetsing for  statistical relevance of parameter differences between typologies
temporal analysis
->plots of parameters over the years per year to see if there is pattern when parameters and typologies change
	
