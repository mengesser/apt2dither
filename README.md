# apt2dither

This repository contains a Jupyter notebook and a .py script designed to convert APT pointing files into MIRIsim readable dither files.

To use from Jupyter notebook, either import the module via `import apt2dither` or by launching the notebook provided. Call the `make_dither_file` function with input and output file paths as parameters. The included notebook has hard-coded filepaths from my local machine. These files are included, but will need to be edited to reflect where they are on your local machine. 

You may also run the code via command line using ./apt2dither.py. It will prompt for input and output file names. 
