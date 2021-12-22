The emission spectra are formated as follows:

MELT/VAPORISATION/
	BB/planet.dat
	EMPTY/planet.dat
	FLUX/planet.dat
	STAR/planet.dat
	

# VAPORISATION: F00 - 0%; F20 - 20%; F60 - 60%; F80 - 80%
# BB: Fplanet/Fstar assuming planet is a blackbody with analytical surface temperature and no absorbers.
# EMPTY: Fplanet/Fstar assuming computed radiative-transfer (R-T) TP profile but no present absorbers.
# FLUX: Fplanet, not divided by star flux (10^-6 erg/cm^2/s/Hz).
# STAR: The one you want. Fplanet/Fstar including all absorbers with R-T temperature profiles.
# Wavelength units are in micron.