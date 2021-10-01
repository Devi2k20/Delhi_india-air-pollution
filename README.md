# india-air-pollution
## Delhi air pollution 2018 analysis
This repo contains the data used for "Closed Pattern mining and Causal analysis of Pollution Data"
The pm2.5 air pollution data of various stations in delhi is transactionised as per the seasons (files saved in .csv extensions).
### Pattern finding
Each seasons data are transformed into txt file that is supported by the SPMF tool.The closed patterns are found using the CloFAST algorithm.
### Causal analysis 
The patterns obtained are given as input along with the pm2.5 data to FCI tool. The resulting output are a set of causal pattern.

For more information checkout my paper and cite it as:
S.Sharmiladevi , S.Siva Sathya, "Closed Pattern Mining And Causal Analysis Of Pollution Data" , Indian Journal of Environmental Protection,January 2021, Vol. 41 ,No. 01, pp 42-49 
