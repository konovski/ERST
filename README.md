# ERST
ERST - Evolutionary Reconstructions over Species Trees

The package is developed for Windows and tested with the latest versions of 
Windows and Java Runtime Environment. The minimal version of JRE is 1.8.xx.

How to download:
The download page is 'https://github.com/konovski/ERST', from the subdirectory 
marked with the date of the upload.
The executable package consists of a single 'jar' file, situated in the
subdirectory 'Executable'. 
The 'Source' subdirectory contains the source from which the executable has 
been generated. It is a copy of the relevant Eclipse directories.
The 'Examples' subdirectory contains additional datasets, on which
the package has been tested.
 
ERST needs a single working directory, with rights to write in it.

Ways to start ERST:
1. With "File Explorer": When already deployed in the working directory, 
   double-click on the file. In some cases, because of inappropriate configuration
   of Windows, this approach does not work.
2. Command line: When already deployed in the working directory, 
   make that tirectory current and start the package  
   with the command 'java -jar ERST.jar'

How to get help for ERST:
1. ERST contains a help menu with glossary of the terms, descriptions of the file
   formats and a tutorial about the basic proceedings.
2. Write to the corresponding author: p.konovski@bbk.ac.uk.

During the execution, ERST creates two directories:
1. 'resources', which contains the starting example and the initial settings
   for the starting example. If the user changes the settings, their last state 
   is saved in that directory too.
2. 'output', which contains working and output files of which the following 
   are of interest for the end user:
   a) 'shortReport.txt' contains a concize summary of the latest run of the package;
   b) 'hgTransferFile.txt' contains text output of the Horizontal Gene Transfers found;
   c) 'poEquilFile.txt' contains text output of the Points of Equilibrium found;
