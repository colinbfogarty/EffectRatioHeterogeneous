# EffectRatioHeterogeneous

The follow code implements the methodology described in Fogarty et al. (2021+), ``Biased Encouragements and Heterogeneous Effects in an Instrumental Variable Study of Emergency General Surgical Outcomes." It further provides a simulated data set for illustrating the method

-IV_Sens_Match_ER.R -- In this script, we conduct the near-far match and save the matched data. We exactly matched on hospitals and sepsis status.
-Balance_Statistics.r -- In this script, we measured balance before and after the near-far match.
-IV_Sens_Outcome.R -- In this script, we estimate the ITT and IV estimates after matching. We save point estimates and confidence intervals.
-IV_Sens.R -- In this script, we conduct the sensitivity analyses that do not account for possible effect modification.
-IV_Sens_Eff_Mod.R -- In this script, we conduct the sensitivity analyses that account for possible effect modification.

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
./routput - Empty directory, we are unable to share analysis output
./tables - R script which generates the tables in the paper.
