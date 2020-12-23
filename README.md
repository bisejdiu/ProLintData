# ProLintData

Sample files to test the ProLint webserver (www.prolint.ca). You can also access the same files on the following [Dropbox](https://www.dropbox.com/sh/uluh54ye5sevv0q/AAAqpvZ_OO6iWjAcjaHIpAXSa?dl=0) folder.

Each folder contains results for a different system or protein. Within each folder, files are separated according to their size. If you only want to test the functionality of the webserver, you may want to choose files within the *small* folders, but please note that results won't be as accurate compared to the larger files. Once you decide on a system, download the files to your machine.

## Testing
* Open the webserver (www.prolint.ca) and then head over to the Submit page. 
* On the form, provide a title and name for the protein (write whatever you want - this won't affect the results).
* Upload the trajectory and coordinate files in the appropriate fields. 
* Check the Grouping box. 
* Select a cutoff value of 0.7 (nm) - (leave the Lipids field blank). 
* Click Submit. 

And that's it! If you choose the big trajectory files, then uploading them will take a couple of minutes (depending on your network speed). Calculation of results will also take some time so please write down the ID that will be given to you so that you can access your results. 

## Notes on the included files and file requirements
The test files in this repository represent the most common types of simulation setups in lipid-protein interaction studies. Integral membrane proteins and peripheral membrane proteins in simple and complex lipid environment and in different number of copies/replicates. A few things to note are the following: 
* Simulations use the Martini model (support for atomistic simulations will be added shortly) 
* Make sure to remove water and ions (this requirement is strictly enforced to reduce file sizes)
