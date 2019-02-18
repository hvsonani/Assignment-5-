# Assignment-5-
Importing Multiple tabs from Multiple Excel Files and performing Logs and Validation Table

Foreach Loop container was used to loop through pipeline created for importing multiple tabs from excel files by creating inputfolder and Filename variables. After importing files, row count transformation was performed to count rows imported into destination table. Rowcount variables were created to create log Table using SQL script Task in SSIS. Validation was performed by using Lookup Task in SSIS.

The Zip file contains following files

1) assignment-5 ssis Folder contains SSIS package.

2) Excel_Files folder contains Excel files used to load data through pipelines created in SSIS.

3) Assignment-5.docx contains documentation for all tasks performed in SSIS.

4) SQLQuery1 contains sql scripts used to create log tables, validation tables and dimension tables.
