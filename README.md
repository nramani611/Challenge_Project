# Challenge_Project
## Pipeline Description
The pipeline (pipeline.py) needs two inputs: all directories containing excel sheets of curves to be ranked and the desired name of the output excel file.
The output is an excel sheet with two columns: the first one is the filename and location, and the second one is the rank of the file (a value 1-4). 

## What you need from this repository to run the pipeline
Only three files are needed to run the pipeline: pipeline.py, ClusterValues.txt, and AllFeatures_Nate.xls.

## How to use the pipeline
From the command line, type the followng: python3 pipeline.py directory1 directory2 directory3 outputfile.xls. It is important to note that the pipeline can take in
as many directories as needed, and the output filename needs to be the last argument. 
