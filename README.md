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
		Once in the repository jsheffler/QEARL click code and download zip. This should download a folder with the .ipynb 
		file inside.
		Note: You cannot run the code by opening it from this folder on the desktop. You must first open 
		Jupyter Notebook via Anaconda. See "To Run QEARL"

To Run QEARL:

	Open Anaconda, Click on Jupyter notebook which will launch in a new window.
	Find the downloaded folder and open the QEARL.ipynb from here. Pressing shift enter should run the code.

	To change orbital parameters change the values in the array called Inputs.
	Note the code does not yet take into account special cases like edge-on or face on orbits.
