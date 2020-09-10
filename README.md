# Modeling-EF-inactivation-peanuts-2020

Files labeled "ind.trt#" include data for each temperature curve that corresponds to a microbial inactivation point. The number after trt corresponds to the condition coding below:

Conditions are labeled 1-6 and vary according to process temperature and air velocity
Condition 1 = 121C and 1 m/s
Condition 2 = 149C and 1 m/s
Condition 3 = 177C and 1 m/s
Condition 4 = 121C and 1.3 m/s
Condition 5 = 149C and 1.3 m/s
Condition 6 = 177C and 1.3 m/s

Within the ind.trt files are several tabs. Each tab is labeled with the treatment time and replicate. So, for example, in ind.trt1, the tab 18-1 is the time-temperature curve for the first replicate of sample treated for 18 minutes at oven conditions 121C and 1 m/s.

Moisture and aw curves can be obtained using the curve fits found in the "moisture_data.xlsx" file. Each tab corresponds to one of the 6 treatments, coded according to the above key, and data collected for each sample (represented as an end-point value) are presented.

Microbial inactivation data are contained in the "micro.trt#" files. The number after trt corresponds to the condition coding as above. The file contains columns corresponding to the replicate, air velocity, air temperature, and treatment time. Microbial inactivation data are presented as raw values (logN) or values normalized to the initial value for that replicate (logN/N0).
