# GrowthAssay

This is a Jupyter Notebook I made to process growth assay data from an automation platform. The automation platform measures the optical density of a 96-well plate every hour. The built-in software from the platform produces a .csv file every hour for x hours.

This code "GrowthAssay.ipynb" compiles the .csv files obtained for n hours and produces an .xlsx file which sorts the 96-well plate in descending order of growth rate. It also outputs the growth rate graph for the top 5 wells.

An example of raw data from 1 time point can be seen at "GrowthAssaySampleRawData.csv".

Hope this code can be useful, and please let me know if you have advice or suggestions.
