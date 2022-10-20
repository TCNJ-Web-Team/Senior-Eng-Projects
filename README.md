# Senior Engineering Projects | Add list of sites to matrix

## Creating a new matrix page and prep matrix for content (for web team)

1. Login to [engineering site](https://engineering.tcnj.edu/). 
2. Create new page based on the year and title Engineering Senior Projects 'year'. Use year URL "2022-2023" as an example.
3. In the WP dashboard custom field group, Senior Projects Grid, under Year add latest year in format, "23 : 2022-2023" and click "Update"
4. Open the new page in headway and import the page formatting from the previous year's page.
5. In the lower custom block change the 'meta_value' to match the first number in the previous custom field 
> 'meta_value'	=> array('23')
6. Publish the page.

## Importing list of sites for new year (for web team and Terry)
### A. Edit and download spreadsheet data
[Access formatted spreadsheet](https://docs.google.com/spreadsheets/d/13s5IzXsWPuQcfOKXzJPZt8qJz58W-EaM7A67pk5FcVI/edit?usp=sharing)
> To be used for storing and formatting data. Please contact web team if additional users need access to the sheet

1. Create a new spreadsheet tab titled with the current year. Please be sure to **keep the existing column headers and category types.** 
2. The category type for an individual site **must** be one of the following:
- BME Senior Projects
- ECE Senior Projects
- ME Senior Projects
- CE Senior Projects
3. Add the category type, title, and URL of this year's project sites.
4. Click "File -> Download -> .csv file" to download the sheet as a .csv file. 

### B. Import spreadsheet data to website
1. Login to the [engineering site](https://engineering.tcnj.edu/) and in the dashboard navigate to "All Import" and select "New Import."
2. Click "Upload a file" and add your .csv file
3. Under "New Items," "create new," select "Eng Senior Projects" and click Continue
4. Check that the following nodes show-up in the listing then click "Continue"
- categories
- title
- _hw_seo_redirect301
5. Scroll to bottom of page. Select "Load Template" and pick "Project Import"
6. Open the Advanced Custom Fields Add-on and under "Year," select latest year
7. Unselect "Save Setting as a template"
8. Click continue
9. Click confirm and run import
10. Refresh the recently created matrix page, for example https://engineering.tcnj.edu/2021-2022/. You should see your newly added project matrix.
11. Contact webteam to add year's listing to the main projects page.

