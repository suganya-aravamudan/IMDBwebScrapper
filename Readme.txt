**********************Simple Web Scrapper****************

1. Install Requests and Beautifulsoup using 
   -pip install requests
   -pip install bs4
These are the two packages which are important for executing any webscrapping application in python

Please do read about the uses of these packages for better understanding.
I have used simple string operations for extracting text from the website.

2. I have also used Openpyxl which is a package used for loading our output data to excel format.
  - sheetname.active is a method to get the sheet which is active.
  - sheetname.title is used to set title to our sheets default value      is 'Sheets'
  - sheet.append to add values to our active sheet,
  - excel.save method should be used without fail or else your data  
    will not be saved.

Once you execute this program an excel file will be generated in the same folder as your python file.
I have attached that also for better understanding.

******************HAPPY CODING************************