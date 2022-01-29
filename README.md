# SCP-dataset

The file dataset.mat file contains sets of data from the Solar Cooling Plant (SCP) at the University of Seville. This data is used to train machine learning algorithm for the fault detection and prediction in the plant. The sets are the following:

SIMULATED DATA		DATE: D/M/A;
D1_05_07_2016 % TRAIN	%05/07/2016;
D2_25_08_2016 % CHECK	%25/07/2016\\
D3_31_08_2016 % TRAIN	%31/07/2016\\
D4_07_08_2016 % CHECK	%07/08/2016
D5_12_08_2016 % VALID	%12/08/2016
D6_15_08_2016 % CHECK	%15/08/2016
D7_27_08_2016 % TRAIN	%27/08/2016
D8_27_08_2016 % TRAIN	%31/08/2016

REAL DATA
R1_16_06_2009 % TRAIN	%16/06/2009
R2_29_06_2009 % CHECK	%29/06/2009
R3_06_07_2009 % TRAIN	%06/07/2009
R4_10_07_2009 % TRAIN	%10/07/2009
R5_17_08_2009 % VALID	%17/08/2009
R6_22_08_2009 % CHECK	%22/08/2009

Each set contains samples per minute of the following variables:

%column 1 Local Hour
%column 2 Inlet Temperature
%column 3 Outlet Temperature 
%column 4 Thermic Jump
%column 5 Ambient Temperature
%column 6 Irradiance W/m2
%column 7 Effective Irradiance 
%column 8 Flow [m3/h]
