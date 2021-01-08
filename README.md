# SOCCOM-Pre-Cruise

import numpy as np
import pandas as pd

from scipy.io import loadmat
import matplotlib.pyplot as plt
from matplotlib import cm
import cmocean

import xarray as xr

from nbformat import read

from PIL import Image
import matplotlib.pyplot as plt
import cartopy.crs as ccrs
import cartopy.feature as cfeature
from matplotlib.offsetbox import AnchoredText

from cartopy.mpl.gridliner import LONGITUDE_FORMATTER, LATITUDE_FORMATTER

import os

download:
pip install numpy
pip install pandas
pip install scipy
pip install matplotlib
pip install cmocean
pip install xarray
pip install nbformat
pip install Pillow==2.2.1
pip install cartopy
pip install os
