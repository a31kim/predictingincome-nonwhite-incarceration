# Excel Step-By-Step Description
1. Downloaded .csv files from Opportunity Atlas, converted to .xlsx files (located in original_data folder)
2. Copied and pasted datasets into compiled_data.xlsx (main Excel workbook)
3. Used text-to-columns and filters to isolate data specific to Baltimore and D.C. for all data sets
4. Within compiled_data.xlsx, used VLOOKUP function to combine separate datasets into one sheet (see "balti_vlookup", "dc_vlookup")
5. Removed all blanks and #N/A values using filter function
6. Copied and pasted compiled data into separate sheet ("balti_compiled_data", "dc_compiled_data")
7. Used Data Analysis Toolpack to complete regression analysis for both datasets, placed side-by-side on one sheet (see "regression")
8. Went through regression data to determine significant values, created simplified chart on "important_values" sheet
