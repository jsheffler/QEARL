# QEARL
QEARL is a python code that takes the orbital parameters of an exoplanet and the spherical harmonics that describe the albedo map of the planet, and outputs the light curve that planet would generate.

To Setup QEARL: (only runs on MAC IOS not Windows)

	Download Anaconda Navigator:
	See documentation here: https://docs.anaconda.com/anaconda/install/

	Download Quaternion and Spherical Functions packages:
	Open the terminal and run the conda install command to download the packages. 
	quaternion:
	conda install -c conda-forge quaternion

	To see the full documentation for this package:
	https://github.com/moble/quaternion/blob/master/README.md
	spherical_functions:
	conda install -c moble spherical_functions

	To see the full documentation for this package:
	https://github.com/moble/spherical_functions/blob/master/README.md

	Download QEARL
		Download QEARL. Should come as a .ipynb file.

To Run QEARL:

	Open Anaconda, Click on Jupyter notebook which will launch in a new window.
	Find the downloaded QEARL Code and open. Shift enter to run the code.

	To change orbital parameters change the values in the array called Inputs.
	Note the code does not yet take into account special cases like edge-on or face on orbits.
