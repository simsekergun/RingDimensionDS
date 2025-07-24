# Ring Dimension Prediction from Integrated Dispersion Data
The goal of this project is to predict the dimensions of a ring (width and height) from the integrated dispersion datasets. The datasets can be found at https://github.com/simsekergun/RingDimensionDS/. In all datasets, the first two columns represent the dimensions (Y), and the subsequent columns contain the integrated dispersion values computed at 171 wavelengths ranging from 750 nm to 1600 nm.

Integrated dispersion calculations were made using 4 different Sellmeier Eq. coefficients. The dataset file names contain "SM1" means that they are calculated using the first set of coefficients, "SM2" means that they are calculated using the second set of coefficients, etc. 

Integrated dispersion calculations were made for the first two modes. So Dint1 means the first mode, Dint2 means the second mode.

The dataset files that have 50 at the end of their names: We add random noise of 50 MHz to the integrated dispersion values.

The dataset files that have 200 at the end of their names: We add random noise of 200 MHz to the integrated dispersion values.
