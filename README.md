# write-Time-Series-Analyzer-data-to-csv-files

This is a set of Python functions that automate:
1) finding all video files (.fits or .tif) in a directory (my_path)
2) writing a custom Fiji macro to run Time Series Analyzer (ImageJ plugin) on those vidoes 
   and save the results (Time Traces) as a csv file
   
These functions pre-suppose that you have Fiji installed on your computer and ROIs predefined (with
the same name as the relevant video) in Time Series Analyzer and saved in your video directory. It
also makes use of the excellent IJ robot plugin (https://imagej.net/IJ_Robot).

Fiji (an image processing package distribution of ImageJ) comes preinstalled with the Time Series Analyzer plugin

