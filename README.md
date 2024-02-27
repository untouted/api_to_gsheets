# api_to_gsheets
Example of using a jupyter notebook to pull data from an API and insert into a google sheet. We pull all games for the 2023 season and insert them into a google sheet.  

Python and jupyter notebooks can be installed from https://www.anaconda.com/download.

This example uses the python library gspread to access google sheets API.  First step is to create Service Account credentials following the steps provided here:

https://docs.gspread.org/en/latest/oauth2.html

For the example to work, an API key from https://collegefootballdata.com/ is needed as well.
