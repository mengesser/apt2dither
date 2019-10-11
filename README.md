# apt2dither

This repository contains a Jupyter notebook and a .py script designed to convert APT pointing files into MIRIsim readable dither files.

To use from Jupyter notebook, either import the module via `import apt2dither` or by launching the notebook provided. Importing will print the current distortion solution to stdout. Use the 'make_dither_file' function with input and output file paths as the first two parameters. The third parameter is the distortion solution, which uses the default value unless overridden by the user. The notebook also has a function allowing selection of the three test case files included in the directory.  Select a file by calling get_test_file(fnum) where fnum is 1, 2, or 3. These correspond to:

1 = 'untitled.pointing'
2 = 'test.pointing'
3 = 'sub.pointing'
        
You may also run the code via command line using ./apt2dither.py. It will prompt for input and output file names. 

There is also code built in to change distortion solution version by giving it as a string in the third parameter of `make_dither_file`. This code is commented out and not available by default. 
