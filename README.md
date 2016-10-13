# Multi-level endogeneity test for explanatory variables of econometric models

#A process to find endogeneity in explanatory variables of the econometric models using Hausman algorithm.
If only one endogenous variable is detected then that variable will be removed from the model for further analysis.
However if more than one endogenous variables are detected then the multi-level endogeneity test process mentioned
in the decriptive file is used to find out the simultaneity error between the detected endogenous variables. 

#Simultaneity error is checked in between the explanatory variables recursively. Potentially reducing the number of endogenous variables. 
