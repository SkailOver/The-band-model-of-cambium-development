ReadMe (How to run the Band Model of Cambium Development)
1. Introduction 
This is an instruction on how to use the beta version of the Band Model of Cambium Development. 
With an EXE file, you will download 3 spreadsheets that are samples of the format used.
We strongly recommend following this spreadsheets formats which are using in the beta version (software). To use the software, you do not need to install it or download additional packages, in addition to the mandatory executable file and tables (spreadsheets) with data for processing.
The main requirements to the spreadsheets in CSV format are:
1) The column header in row " 1 " must be unchanged
2)The separator of the integer part from the fractional part is a dot
2. Model description
There are 3 spreadsheets in your disposal:
1)	"D_and_Trend.csv"
2)	"Grow_rates.csv"
3)	"Season_info.csv"
These files are obtained by using VS Oscilloscope (http://vs-genn.ru/), but for subsequent use in the new program, you will need to transfer the format of original files to the ".csv " format and set the names that will be described below, in accordance with the information stored in the files. All transformed files with source data must be placed in the same folder with the executable file (Fig.1).
 
Fig.1 Example of the location of the program and file
2.2 Format of input files
The file "D_and_Trend.csv" contains 3 columns (Fig.2):
1) The year of measurements (year) - column A; 
2) Cell production (d) (in microns) - column B;
3) Temporal nonlinear trend of cellular production (trend) (in microns) column C. 
 
Fig.2 "D_and_Trend.csv" columns

There are 3 columns in the "Grow_rates.csv" file (Fig. 3):
1) The year of measurements (year);
2) A day of the year (t);
3) Grow rates (Gr) (in relative units)  , where “Gr” is an integral tree-ring growth rates obtained by the VS-Oscilloscope .
 
Fig.3 "Grow_rates.csv" columns

There are 15 columns in the "Season_info.csv" file, but only three of them are using in the beta version, namely:
1) The year of measurements (year);
2) The day of the start of growing season (SOS);
2) The day of the end of the growing season (SOS).
 
Fig.4 "Season_info.csv" columns
3. Running program 
After running the software, it processes the input files during some time and will ask to enter a start and end years of analysis (Fig.5). 
 
Fig.5 Example of entering calculation years
During the program progress a new output file "Output_file” will be formed in the root folder(Fig.6), 
 
Fig.6 Example of the root folder

4. Output file format
The output CSV file contains 6 columns (Fig.7):
1.	The year of analysis.
2.	The best fit beta (Beta_fit);
3.	Estimated Beta (Beta) by the linear regression approach used in the paper (Shishov et al., 2021), namely:
Beta(𝑦) = b0 +b1*𝑉𝑒𝑥𝑡 (𝑦)+ b2*𝑇𝑟𝑒𝑛𝑑(𝑦)
The other three columns correspond to the regression coefficients.
 
Fig.7 Output file format
