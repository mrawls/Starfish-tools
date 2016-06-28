# Starfish-tools
Programs I wrote to help me use the Starfish spectral inference code.

`fits2hdf.ipynb` - I knew how to use `astropy` to access the data in 1D FITS spectra, but I had no idea how HDF5 files worked. Since Starfish essentially requires HDF5, this is an exercise I wrote to take the wavelength and flux data from a FITS spectrum file and put it into a new HDF5 spectrum file.
