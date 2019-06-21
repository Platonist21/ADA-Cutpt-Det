Two R functions related to the Olsson Rootzen calculations are included.
The main function is LOHR(). The main input is a dataframe with a variable "sample" for sample ID, and a variable "obs" for data.
The second function qF() is to calculate percentile estimate by simple linear interpolation.
load("OlssonRootzen.RData") would load these two functions.
'package:stats' may be needed to run these two functions.