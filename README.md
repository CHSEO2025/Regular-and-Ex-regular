# Regular-and-Ex-regular
Aim:
Finding Regular and Ex-regular students from the input file. 

Requirement List:
1.Code language ------> Python version(3.12.7).
2.libraries     ------> * Pandas version(2.2.2),
                        * NumPy version(1.26.4).
3.Input File    ------> **********.

Steps:
* Import the required libraries.
* Reading the Excel File, Load data from the Excel file into a Data Frame called df.
* Create a new column Course Type based on the 6th and 7th characters of REGN_NO.
* If the 6th char is '2' and 7th char is '3', it's classified as 'Regular'.
* Otherwise, it is 'Ex_Regular'.
* Counting Each Course Type, show how many entries fall under 'Regular' vs. 'Ex_Regular'. 
* Create two separate Data Frames:
 ---> df_regular for only 'Regular' students.
 ---> df_Ex_regular for only 'Ex_Regular' students.
* Display the top few rows from each of the filtered Data Frames to verify the filtering.
* Save the filtered Data Frames to Excel files without including the index column.
* Save the filtered data into CSV format as an alternative to Excel.
 
