# Data Analysis Skills
## Parsing Data From Excel

Data cleaning skills using a .csv containing geotechnical data from ‘EMerald Geomodelling AS’.

EMerald’s internal data structures are built around the Swedish geotechnical format – They have an open source library called libsgfdata (installable via pip or by cloning the github repo and following the README.me).

You can see an excel sheet named SP_TRO-TEL_88.xlsx in the folder. A spreadsheet and the corresponding parsed sgf file SP_TRO-TEL_94.sgf / .xlsx has been given as sample. As you can see this SGF file does not contain all the data from the excel sheet, but only the subset that we’re interested in.

The task is to extract a similar dataset, or as much data as you can out of SP_TRO-TEL_88.xlsx and write an SGF file using the method outlined in the libsgfdata documentation.
