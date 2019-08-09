# write-Time-Series-Analyzer-data-to-csv-files

This is a set of Python functions that automate:
1) finding all video files (.fits or .tif) in a directory (my_path)
2) write a custom ImageJ macro to run Time Series Analyzer (ImageJ plugin) on those vidoes 
   and save the results (Time Traces) as a csv file
   
These functions pre-suppose that you have ImageJ installed on your computer and ROIs predefined in
time series analyzer and saved in your video directory. It also makes use of the excellent IJ robot
plugin (https://imagej.net/IJ_Robot)

Custom script can be run in ImageJ but probably better to use Fiji as it comes preinstalled with 
the Time Series Analyzer plugin
