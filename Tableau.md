**To Set Up Tableau in a Computer Lab**
- open browser > public.tableau.com
- enter email address > download the app (10-0-1) > 30 seconds
- in download bar, find Tableau 10-0-1.dmg in Finder > double click
- Tableau verifies for 1 minute
- drag Tableau icon to Application folder > requires Authenticate
- Enter UserName Journalism Admin > wait for password from prof
- Tableau is copied to Applications for i minute
- Doubleclick Tableau Public in Applications > Tableau Desktop opens
- Students can look at Discover videos in right grey bar out of class

**Tutorial**

Data
- Under Resources in right grey bar, click Sample Data Sets
- Scroll to Lifestyle > Top Baby Names > click Dataset (csv versus xls files) > TopBabyNamesbyState.csv downloads
- double click csv file > enter first name for Office Mac, if required > Excel opens > double click csv file again
- inspect csv data: column names and 10507 rows! > close Excel
- in Tableau Public, in left blue column, Connect **not* to Excel but to a text file > double click TopBabyNamesbyState.csv
- inspect column headings and Tableau Public Symbols in column headings
- in lower left, click Sheet 1, beneath Go to Worksheet

Worksheet
- inspect Dimensions and Measures
- Definitions
  Measure: A variable from the dataset that is meant to be aggregated. This means it should be a number that it makes sense to do math with: sum, average, etc. In this dataset, the only measure is “Occurrences”
  Dimension: A categorical variable from the dataset that is used to slice and dice the data into different categories. State, year, gender, and name are all dimensions in this dataset.
  Sheet: A sheet is a singular chart or map in Tableau.
  Dashboard: A dashboard is a canvas for displaying multiple sheets at a time and allowing them
to interact with each other
  Workbook: A workbook is the entire Tableau file containing your sheets and dashboards.
  Filter: A filter is used to limit what data is being displayed on the sheet. Visible controls for a
filter on a sheet or dashboard is called a Quick Filter.
  Pages: Pages are used to quickly flip between different views of a sheet. The most common use
of pages is to show data for particular points in time.
  Legend: A legend box shows the color or size scale. In Tableau, legends can also be clicked on to
highlight certain values.
  Tooltip: Tooltips are text boxes that appear when hovering over a mark on a sheet that give
more information. The text and text formatting in them are easily edited through the Marks
card.
  Marks card: The marks card is the tool when creating a sheet that controls most of the visual
elements (a.k.a. Marks). Using the marks card, you can switch between different chart types
       
(bar, line, symbol, filled map, etc), change the colors, change sizes, add labels, change the level
of detail, and edit the tool tips.
  Rows and Columns Shelves: The rows shelf and the columns shelf is where you determine which
variables will go on what axis. Put data you want displayed along the X‐axis on the columns shelf and data you want displayed on the Y‐axis on the rows shelf

Creating the Map
- Because we want to make a map, drag states to Marks > blue dots appear in each state
- Because we want to make a map with filled colors, not dots, click the drop down menu under Marks/Automatic, select Filled Map; the states are now filled with blue
- We want to start studying top names per state: drag Top Name to Color and drag Top Name again to Label (it is a big file but Add all members if asked) > the map now has names and colors in each state
- We want to filter by names of boys and girls; drag gender to filers > in the popup box choose M
- We also want to filter by year; drag year to filter > Tableau sees the range of values from 1910 to 2012 > click OK
- On Year, right click drop down menu and click show filter so viewer can see slider

