These are the necessary files to replicate the results reported in Takahashi (2026).

Takahashi, M. (2026). Multiple imputation based on the support vector machine for high-dimensional data with general missing patterns in causal inference. Journal of Statistical Computation and Simulation.

First, download "00miceSVM.R" on your computer. This is the file that the author created as multiple imputation based on the support vector machine using multivariate imputation by chained equations (mice). After downloding this file, you can use miceSVM in conjunction with R package mice.

Second, download the files (01Tbale1, 02Table1). These files allow you to replicate the results reported in Table 3a and Table 3b in the main text. Also, by changing p1 <- 496, then you can replicate Table A4a and TableA4b in the appendix. Set the directory where you saved 00miceSVM.R. For example, source("C://Users//...//00miceSVM.R"). Copy and paste the entire code into R.

Third, download the files (03Tbale2, 04Table2, 05Table2). These files allow you to replicate the results reported in Table 4a, Table 4b, and Table 4c in the main text. Also, by changing p1 <- 496, then you can replicate Table A5a, Table A5b, and TableA5c in the appendix. Set the directory where you saved 00miceSVM.R. For example, source("C://Users//...//00miceSVM.R"). Copy and paste the entire code into R.

Fourth, download the files (06Tbale3, 07Table3). Also, download the EVS data from the GESIS Data Archive. These files allow you to replicate the results reported in Table A2 in the appendix. Set the directory where you saved 00miceSVM.R. For example, source("C://Users//...//00miceSVM.R"). Copy and paste the entire code into R. The window pops up, so choose EVS1.csv for 06Table3, or EVS2.csv for 07Table3. Note that the EVS data are openly and freely available from the GESIS Data Archive and should be downloaded from https://doi.org/10.4232/1.13897. The code to prepare the EVS data is available from the GitHub page of Costantini et al. (2025, p.492).
