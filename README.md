# USGS-data-analysis
Using PHREEQC to analyze groundwater samples to calculate Saturation indices for minerals 


Steps - 
1. Use parsing_code_final.ipynb with "NAWQA_GLACM&M_AsMn_SIss.200914_abbreviated for email to Chen Zhu" as input to generate full_input1.txt (change extension to pqi)
2. Temp 0 replaced as 0.01 to avoid some data points from crashing in parsing_code_final
3. Run full_input1.pqi in Phreeqc to generate full_output.csv
4. Use Visualization_subplot.ipynb with full_output.csv as input to generate the final plots. 
