# Cepheus
A collection of tools used for processing fits data on variable stars.

Currently has the capability of processing the fits images in a directory, and using a reference star,
will calculate calibrated magnitudes for a target variable star.

Future implementations:

1. Period folding techniques to calculate period(s) of variable stars.

2. Automatically use AAVSO data to call in reference stars and calibrated magnitudes
   that may be contained in the field of view of your star. Likely using the BeautifulSoup
   library. 
   
3. Ability to cut out images from the data set that have overexposed or too out of focus variables in them,
   using PSF photometry.

4. Ability to create a timelapse video of the variable in an HR diagram. (probably won't happen!)

5. Linking Simbad/Vizier database to include other astronomical measurements for the variable star.


