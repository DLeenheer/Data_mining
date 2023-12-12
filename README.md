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

# Project title - How Do We Increase Positive Responses To Emails?
# Team Members - Dana Leenheer
# Project Description
This project was an investigation into job titles. My domain knowledge of job title selection and its impact on email sales prospecting was the driver for this project. The literature review confirmed my hypothesis that job titles have an impact.
I utilized my experience with Google Sheets, CSV files, and Excel formulas & pivot tables to prepare the data and complete the data transformations.
# Main Questions Asked and Answers
What is the most common job title (in the data set)? 

President, followed by Vice President, and then Director (these are the full titles, the department specific versions were not as popular, ex. Vice President of Engineering)

Do job titles vary by region? 

Yes but not significantly. The top 10 job titles from the United States only view were all within the top 20 most common titles in the overall view, but in different spots. 

What job titles are most frequent within different industries? 

I created drilled down views for this question of the top 20 most common job titles in the top 3 overall most common industries within the external data set.

Are general job titles more popular than department specific titles?

Yes, the four most common job titles overall are general titles with the first department title being CEO. The top 4 job titles were President, Vice President, Director, and Managing Director

# Application of Knowledge
Top 20-50 job title lists for the top 5 to 10 industries from this data set will be ultilized to provide recommendations for future client campaigns in my role at work. The trends and nuiances discovered proved the importance
of further investigations of job titles in specific industries/other criteria (ex. Manager and Entry level job title investigations). I will recommend that general titles are included in the prospecting mix along with department/role specific titles.

# Link to video - my video is over 10MB so I am blocked from adding the video link to this file. I am going to create a separate Part 6 file and try uploading there. 

# Link to presentation slide deck (linking this because of the video presentation file size issue) [Group10_HowDoWeIncreasePositiveResponsestoEmails_Part6.pdf](https://github.com/DLeenheer/CSPB_4502_project/files/13643746/Group10_HowDoWeIncreasePositiveResponsestoEmails_Part6.pdf)

# Link to final paper [Group10_HowDoWeIncreasePositiveResponsesToEmails_Part4.pdf](https://github.com/DLeenheer/CSPB_4502_project/files/13643739/Group10_HowDoWeIncreasePositiveResponsesToEmails_Part4.pdf)





