# Part 5 Code and formulas used in this project
# Code for internal file export from Athena (SQL Query) - 
select title, state, country
from public_contact limit 50000

Excel and Sheets formulas used for this project - 
=proper()
=lower()
ctrl+shift+down arrow - to select full data set on page to copy to full/main data set
copy lower title fields, paste – values option to title column (creating the table from the pivot table - for better formatting in report)
=LEFT(A26,FIND(" at ",A26)-1) - this was used to find all the job titles with company information included, which was then deleted, I also used this for the " a " variation
used column search bar to sort for junk data lines (ex. job title or location with just "---" in the cell)
Select Data - Data cleanup - trim whitespace
Select Data - Data cleanup - remove duplicates (for the assembled contact ID # column, this column was deleted once the duplicate rows were deleted - each contact has a unique ID# so a duplicate row was duplicate data)

Project title - How Do We Increase Positive Responses To Emails?
Team Members - Dana Leenheer
