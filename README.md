# ADA-Cutpt-Det
Olsson Rootzen algorithm for cut point calculation

Two R functions related to the Olsson Rootzen algorithm are included.
The main function is JOHR.ADA(). The main input is a dataframe with a variable "sample" for sample ID, and a variable "obs" for data.
The second function qF() is to calculate quantile estimate by simple linear interpolation.
load("OlssonRootzen.RData") would load these two functions.
'package:stats' may be needed to run these two functions.

27Nov2019 by Charles Tan
