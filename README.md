# SOCCOM-Pre-Cruise


Use the following in your computers terminal for downloadind the necessary python packages:
* pip install numpy
* pip install pandas
* pip install scipy
* pip install matplotlib
* pip install cmocean
* pip install xarray
* pip install nbformat
* pip install Pillow==2.2.1
* pip install cartopy
* pip install os

Once you have downloaded all the packages listed above and the contents of this repository, you need to edit the precruise.py script to reflect the cruise you are looking to produce plots for. Within the MetaInfo function, edit the variables there to be specific to your cruise. Then create a folder with the same name as your cruise.

Within your terminal, cd to the appropriate folder containing all the contents of this repository. Then, type: python precruise.py

Once prompted, type in the name of the cruise that you designated in the MetaInfo subfunction. The code will create the following plots and save them into that folder with the cruise name:

* bathymetry
* chlorophyll
* CO2 flux
....
