# Code and Data associated w/ "Making inference w/ messy (citizen science) data: when are data accurate enough and how can they be improved?
  
## Files and descriptions
FullData.csv -- the full dataset used to estimate baseline rates of accurracy and specific error rates.  
Full_Model_Data.csv -- the dataset used to evaluate categorical variability in error and for specific modeling excercises.
TrainPartition.csv -- a portion of Full_Model_Data.csv used to fit glmm screening models.  
TestPartition.csv -- a portion of Full_Model_Data.csv withheld from model fitting, and used to estimate varied metrics to characterize out of sample predictive performance.
Other test.csv files -- partitions within specific categories of interest used for more specific out-of-sample model testing
CitSCI_sim.RMD -- markdown file including code for executing simulation component of the manuscript: includes simulation functions, and JAGS code for model fitting.
Workflow.RMD --markdown file that roughly outlines the data and functions used to execute specific empirical analyses within the manuscript.
