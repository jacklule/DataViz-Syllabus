**To Set Up Tableau in a Computer Lab**
- open browser > public.tableau.com
- enter email address > download the app (10-0-1) > 30 seconds
- in download bar, find Tableau 10-0-1.dmg in Finder > double click
- Tableau verifies for 1 minute
- drag Tableau icon to Application folder > requires Authenticate
- Enter UserName Journalism Admin > wait for password from prof
- Tableau is copied to Applications for 1 minute
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
Definitions
  Definitions
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
- We want to filter by names of boys and girls; drag gender to filters > in the popup box, choose M and F and Select All
- In gender drop down menu select show filter > a box appears with gender choices for the viewer
- We also want to filter by year; drag year to filter > Tableau sees the range of values from 1910 to 2012 > click OK
- On Year, right click drop down menu and click show filter so viewer can see slider
 
Separate Maps for Alaska and Hawaii
1. In order to make the dashboard more space efficient, we are going to create Hawaii and Alaska as separate maps.
2. In top tool bar find icon and select “Duplicate Sheet”
3. Use the bottom zoom control with the square and magnifying glass to focus just on Hawaii.
4. Right click on bottom tab for Sheet 2 and rename Hawaii
4. Repeat steps for Alaska.
5. On the main map, zoom into the continental US.

Create the Dashboard
- Click on top or bottom toolbar for Create New Dashboard
- In left grey sidebar, change size to Automatic
- At the bottom of the sidebar, under Objects, change Tiled to Floating
- drag 48 States to Dashboard. It comes with the year slider, gender filter and list of names, which is not necessary. Drag and separate the slider and gender filter from the list of top names. Click on drop down men for Top Names and select Remove from Dashboard.
- reposition and make larger the year slider and the gender filter
- drag Alaska and Hawaii to Dashboard. Remove top names but keep the slider and gender filter
- Drag and resize until the maps seem right to you

Adding a title
1. From the left pane, where the sheets are listed, click on text.
2. Drag text out into the dashboard. Place it at the very top.
3. In the text editor box, write “Baby Name Trends in the US, 1910‐2012”
4. Make the text 18pt, bold, and centered.
5. Hit OK.

Saving and Publishing to the Web
Save Dialog
We are all done and it looks great! Let’s save it and share it with the world!
Naming Schemes
Whenever you build a dashboard in Tableau Public, the naming conventions will come up with an address like: public.tableausoftware.com/views/Filename/Dashboard name. Because of this, it’s important to name your dashboard (the same way you name a sheet) and your workbook something you are happy with.
Sheets as Tabs
There will be a checkbox that says “Show Sheets as Tabs”. What this does is makes all your sheets able for viewing. In this case, we will not want that, so make sure it is unchecked.
URL and Embed Codes
  
Once your dashboard is saved to the web you will get a preview screen. You’ll see a URL that was generated to take the viewer directly to the dashboard. There is also an embed code for the dashboard. If you switch which view you are looking at by clicking on a different sheet on the far left, the embed code and URL will change. Tableau automatically makes a unique code and URL for every view in your workbook.
Embedding on your website
To embed your dashboard, copy the embed code and paste it anywhere that allows for HTML input.


