# EffectRatioHeterogeneous

The follow code implements the methodology described in Fogarty et al. (2021+), ``Biased Encouragements and Heterogeneous Effects in an Instrumental Variable Study of Emergency General Surgical Outcomes." It further provides a simulated data set for illustrating the method

/Analysis - Example Data 

-IV_Sens_Example.R -- In this script, we conduct a self-contained analysis based on simulated data. The simulated data has a matched pair structure.
In the script, we estimate the IV effect using the effect ratio, conduct a sensitivity analysis that does not account for possible effect modification,
and a second sensitivity analysis that accounts for effect modification. It uses the same functions used in the main analysis 

/Simulation - R scripts for both simulations in the paper. These are labeled by which table is produced in the paper.

./data - contains simulated data only.  Does not contain actual data used in the analysis.

Description of Simulated Data: ExampleData.csv

Sample Size - 5000

Z - Binary IV 

D - Binary Treatment Variable

Y - Outcome

X.1 - X.10 - Baseline Covariates Drawn from Uniform Distributions.

Pair - Matched Pair IDs

./rfunctions - all R functions used in the analysis

