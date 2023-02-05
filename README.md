# "Biocontrol impacts on wheat physiology and Fusarium head blight outcomes are bacterial endophyte strain- and cultivar specific"
### Whitaker, B.K., Vaughan, M.M., McCormick, S.P.

DOI here

This repository includes the R code, data files, and small scripts to supplement the manuscript by Whitaker et al. "Biocontrol impacts on wheat physiology and Fusarium head blight outcomes are bacterial endophyte strain- and cultivar specific".

The Rmd file ("dataOrg.Rmd") details the organization of original data input (from qPCR, DON-Chemical analysis, visual disease symptoms, physiology data, and treatment information) and includes details on organized and summarized comma-separated outputs. Definitions for the physiology variables are also included. The Rmd file ("diseasePhys.Rmd") details the univariate and MANOVA analysis of all disease response and physiology data. The Rmd file ("diseasePhys_multivariate.Rmd") details the multivariate PCA approach to summarize and test the indirect effect of the plant physiology traits on wheat disease response. 

They should be run in this order: dataOrg.Rmd > diseasePhys.Rmd > diseasePhys_multivariate.Rmd.

The /code folder contains the batch and R scripts necessary to run small codes inside R. Data necessary to run the analyses can be found in /data folder.

Please see the manuscript for details and full reference information.
