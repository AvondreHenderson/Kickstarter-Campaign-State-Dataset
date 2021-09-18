# Kickstarter-Campaign-State-Dataset
Dataset containing 4000 Kickstarter campaigns. Data contains campaign state, overall backer number, parent and sub categories
# Explanation of Table Contents
## MainDataSet
### This is the main data set used for the spreadsheet. Displays 4000 Kickstarter campaigns with the following information: name,	blurb,	goal,	pledged amount,	state,	country,	currency,	deadline,	launched_at,	staff_pick,	backers_count,	spotlight,	Category and Sub-Category,	Percent Funded,	Average Donation,	Date Created, and Conversion	Date Ended.

#### "State" Column formatted to show certain colors if campaign is successful, failed, cancelled, or is currently live. Respective colors are blue, red, purple, green.
Used conditional formatting on entire column. 
#### "Percent Funded" Column formatted to display red from 0 to 100%, green from 101% to 200%, and anything above 200% to display blue. Conditional formatting applied to the entire column.
#### "Category and Sub Category" Column split into separate columns using a Delimeter.
The delimeter in this particular case was the "&" in between the category and sub category in the column. 
#### "Date Created" and "Date Converted" columns created from the raw data in the "deadline" and "Lauched_at" columns. 
Formatted to display the date.
## Launch Date Outcomes
### This displays a line chart that shows the relationship between what month the campaign was launched and the total of successful, failed, and cancelled campaigns. 
#### Pivot table made from the main data set. X axis set as the month of conversion. Y axis set as total number of campaigns. 
## Category Stats
### This displays a bar chart with the total amount of successful, failed, cancelled, and live campaigns by category from the main data set. 
#### Pivot table contains the total number of successful, failed, cancelled, and live campaigns by "Category"
## Sub Category Stats
### This displays a bar chart with the total amount of successful, failed, cancelled, and live campaigns by sub category from the main data set. 
#### Pivot table contains total number of successful, failed, cancelled, and live campaigns by "sub category" type
## Bonus Goal Outcomes
### This displays a line chart with the percentage of successful, failed, and cancelled campaigns relative to a particular goal range ($)
## Bonus Backers Analysis
### This displays the mean, median, minimum, maximum, and standard deviation of the total number of backers per successful and failed campaigns. 






