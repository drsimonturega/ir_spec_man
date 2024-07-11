# Infrared spectral manipulation 

## A description of the project: what it does, the aim of the project, and what you learned

This project involves the devlopment of code for the storage retival and manipulation of infrared spectra for data analysis and machine learning purposes.   The core aims for this work are:

One. Converting IR spectra from manifacturer and instrument specific formats into a common, commer separated value format (*.csv) with annotation that can be used in downstream applications.

Two. Produce accessible Python algorithms for the processing and manipulation of spectra for example solvent subtraction or baseline corrections.

Three.  Produce Python scripts that allow the storage,  annotation, manipulation and retrieval of spectra from storage databases.


## Installation instructions
### Colab sheets
Use the open in Colab button to open the sheet in colab.
## Usage instructions
The scripts and algorithms will be made available in three different formats  the first is fire Jupyter notebooks run on Google collapse the second is via a bioinformatics (Galaxy) server  and the third is via a use of Python scripts.
### Colab sheets
#### Infrared spectral manipulation: *.asp to *.csv (asptocsv.ipynb)
Takes a lab book code and a single *.asp IR spectra and converts it into a long thin (yes I know its transposed) spectra in *.csv format. The orginal *.asp and long thin *.csv files are downloaded as a *.zipfile named after the lab book code.
#### Infrared multi-spectral manipulation: *.asp to *.csv (asptocsv_multi.ipynb)
Takes a lab book code and multiple *.asp IR spectra and converts it into a long thin (yes I know its transposed) set of spectra in *.csv format. The orginal *.asp files and long thin *.csv files are downloaded as a *.zipfile named after the lab book code.
## File structure of the project
## License information

This is availible through a GNU General Public License, version 3.
