# Eye-Tracking-on-Brain-MRI

Spatial and time domain analysis of eye-tracking data during screening of brain magnetic resonance images

This code should accompany the paper by the same name and is tested on Python 3.6.9 and R 4.1.1. Three analyses are referenced in the paper and steps to reproduce their findings are below.

# Data
Brain Stimuli Folder: contains experimental stimuli.
Eye Tracking Data Folder: contains raw eye tracking data and participants' demographics file, the file names are reffered as BE (Brain experts), C (Naives), E (Extra), OE (Other expetrs) as mentioned in the paper. 
Results for Statistical Analysis Folder: contains the results for Fractal Dimension (FD), Re-scaled range (R/S) and detrended fluctuation analysis (DFA) for using in statistical analysis.

# FD, R/S and DFA Calculation
The VisualTracking.py file is required to get the FD, R/S and DFA values which are saved in the Results for Statistical Analysis Folder.

# Statistical Analysis
The Statistical_Analysis.R file is required to get values for our statistical analysis.
Please note: The p values are calculated initially using the Statistical_Analysis.R without adjustment which are used to get adjusted values by using the code snippet inside the  Statistical_Analysis.R.
