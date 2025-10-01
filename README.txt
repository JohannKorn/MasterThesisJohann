### Data Analysis scripts Johann Master Thesis

The scripts are tested and finishing without errors in visual studio Code using the jupyter plug-in
and the Python 3.12 Kernel.

Packages must be installed on your own.
Use the command

pip -install [package name]

in Windows Powershell.

In order to properly run the scripts, in the same folder as the script files, create a folder named

"Data" and within it another one named "Cell_Counts"

The folder Data is meant to contain sequencing files (.h5ad files) and the folder
Cell_Counts is meant to contain count files (.csv files)

Data files can be retrieved from the following cloud location
(this is my private drive, if access is denied, contact me)

https://drive.google.com/drive/folders/1XKtzSRmFDqy_riEPkzhWTMLjylM9tf-n?usp=sharing

All plots are automatically saved into the Plots folder.


If errors still occur try the following trouble shooting steps:

1. Restart the Python Kernel and run the notebook again
2. Make sure data files are in the proper folders
3. If Package errors, make sure the package is installed in its latest version (if in doubt, use pip -uninstall and reinstall the package)
4. Restart VS Code or the IDE of choice

DO NOT MOVE THE .IPYNB FILES OUT OF THE ROOT DIRECTORY! ALL OTHER FOLDERS ARE RELATIVE PATHS

Enjoy! :) I put a lot of work into this.


