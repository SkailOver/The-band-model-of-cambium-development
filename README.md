# The-band-model-of-cambium-development
A program for calculating the band model of cambium development: opportunities and prospects, the theory of providing in the article "A band model of cambium development: opportunities and prospects"
Good afternoon, you are reading the instructions on how to use the beta version of "The band model of cambium development". 
cWith an EXE file, you had to download 3 spreadsheets that are samples for filling in,
 we strongly recommend filling in these tables, since they are formatted in the format necessary for the program.
The main provisions for filling out spreadsheets in CSV format:
1) the column header in row " 1 " must be unchanged
2)the separator of the integer part from the fractional part is a dot
There are 3 spreadsheets at your disposal.
The file "D_and_Trend.csv" stores 3 columns:
1) the year of measurements (year), measured in years
2) cell production (d), measured in microns
3) The time trend of cellular production (Trend), measured in microns
There are 3 columns in the "Grow_rates.csv" file:
1) the year of measurements (year), measured in years
2) a day in the year (t), measured in days
3) Grow rates (Gr), measured in relative units
There are 15 columns in the "Season_info.csv" file, but we only need the ones described below, 
the rest are other information that is not used in the program at the moment:
1) The year of measurements (year), measured in years
2) The day of the beginning of the growth season (SOS), measured in the ordinal number of the day in the year
2) The day of the end of the growth season (SOS), measured in the ordinal number of the day in the year

After filling in the data in the tables, put them in the same folder with the executable program, 
without changing the names of the spreadsheets.
After starting the program, it will process the received tables for some time, after which it will ask you to enter the year 
from which you want to start the calculation and the year in which you want to finish the calculation,!they should be filled in with a space!, 
as well as when filling in non-existent data in tables with data from calculated years,
 the program will output very small data that is not comparable with reality.
After entering the years for processing, the program will find all the variables,
 put them in the "Output_file" and finish its work by closing the console window, 
after that you can open the output file, analyze and use the data obtained from it.

In the resulting file, you will have 5 columns, the first column will contain the selected best value of the Bet variable, 
the second column will contain the values of the new Bet variable for calculations,
with the help of it you will be able to make all calculations according to the formulas provided in the article yourself.
The remaining columns contain the coefficients that were necessary for calculating the new Bet variable ( according to formula 5 from the article) 
b0=a0, b1=a1, b2=a2.
B(𝑦) = 𝑎0 +𝑎1𝑉𝑒𝑥𝑡 (𝑦)+ 𝑎2𝑇𝑟𝑒𝑛𝑑𝐶𝑃(𝑦
