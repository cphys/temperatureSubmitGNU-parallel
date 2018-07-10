# Finding the temperatrue of many job files in parallel

When run in the same directory as /dataFull directory this script will use gnu-parallel  
to perform a peak broadening to each file in each direcory. 

## Instructions
* the program will go through all of the subdirectories within /dataFull and apply  
  peak broadening to each array.
  - each input file should be a 1d array of numbers saved as a .txt file.
  - The the input arrays should be saved within a folder labeled /noTemp.  

* The output will be identically named arrays but now in a subfolder indicating the Temperature  
  - for example: an input file /dataFull/foo/noTemp/muVal1234.txt would have an output  
    of /dataFull/foo/Temp20meV/muVal1234.txt.

## Acknowledgments
* parts of this code are based on code found on the Palmetto Cluster Home page  
  https://www.palmetto.clemson.edu/palmetto/
