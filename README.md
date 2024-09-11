# Calibration_process
This repository contains the codes to reproduce the calibration and validation presented in the manuscript: Calibrating streamflow and hydrological processes in the geological regions using a combined soft and hard calibration approach

The repository have 3 scripts:

1_Soft-Hard: This scrip contains the code implemented in the calibration of the model (soft-calibration and hard-calibration) with the subsequent processing of the variables to make the aggregation of results in sub-catchment on a daily and annual sub-catchments.

2_Evaluation: This scrip contains the code for the extraction of the scatter plots results of the soft-calibration and for the estimation of the hard-calibration performance metrics for each sub-catchment. Additionally, code is included to determine the selection of the best performing simulations in the simulated sub-catchments.

3_Validation: This scrip contains the code used in the validation to run the best performing simulations and perform the aggregation and evaluation of the results this time at the catchment level of Entrepeñas and Buendia. At the end the code to run the final simulation and evaluate the results in the monthly inflows to the reservoirs.

As additional material to implement the codes, files such as those shown in the data folder are needed. Reference data for the aggregation of the results into sub-catchments (aquifer_subbasin , Data_lsus) and observed data for the evaluation of the performance metrics (Obs_flo11_20 , CHT_res_month_11_19).
