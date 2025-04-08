The code is used to understand the nature of the transients as observed by the Rubin Observatory. 
Input: Lightcurve with luminosity vs time (MJD)
Working: Converts luminosity into magnitude, subsamples with RubinSIM and produces a simulated "observed" light curve in the ugrizy bands with errors
Model used to generate initial light curves: TiDEpy (https://github.com/stermzsofi/TiDE/blob/main/docs/tutorials/GetingStarted.ipynb)
Flexibility of the code: Can use any other model to generate initial light curves
