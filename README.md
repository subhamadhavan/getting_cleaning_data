
This is how the script works

Download the data source and put into a folder on your local drive. This will create a UCI HAR Dataset folder.
Place run_analysis.R and UCI HAR Dataset in teh same folder, then set it as your working directory using setwd() function in RStudio.
Run source("run_analysis.R"), then it will generate a new file tiny_data.txt in your working directory.

Dependencies

run_analysis.R file will help you to install the dependencies automatically. Dependencies include reshape2 and data.table.
