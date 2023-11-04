# Map_Automation
This is a brief outline of the steps needed to obtain live data for inflation from the World Bank, including how to upload the data, parse the JSON data to Python, and filter the data. The following steps should be taken:

1. Create a makefile.py to upload the data from the World Bank.
2. Create imf_csv.py to parse the JSON data to Python and combine countries with inflation.
3. Create clean_data to filter the data, correcting any incorrect rows and changing country names to be recognized by Datawrapper.
