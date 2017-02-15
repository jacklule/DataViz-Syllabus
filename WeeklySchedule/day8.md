# Day 8

## Telling Stories of Places

## Maps

## Principles: Before Class
- Quiz over Days 7 and 8
- [Axis Maps has an excellent Thematic Cartography Guide on GitHub](http://axismaps.github.io/thematic-cartography/), read General Map Making Topics
- Google Fusion Map sample: [Birthplaces of American Singers](https://www.google.com/fusiontables/embedviz?q=select+col2+from+18KeGgJBuUr36eWPkcIbfAow998liGL-OGqdh27Tg&viz=MAP&h=false&lat=42.38378713996336&lng=-76.28461759999999&t=1&z=4&l=col2&y=2&tmplt=3&hml=GEOCODABLE). Here is the [Google Fusion data and cards](https://www.google.com/fusiontables/DataSource?docid=18KeGgJBuUr36eWPkcIbfAow998liGL-OGqdh27Tg) for Birthplaces of American Singers

## Practice: In-Class

- Google Fusion exercise with local data
- Demonstrate how to get URLs of images from Google: Search>Images>View Image (get photo credit)
- Open [spreadsheet on local arts centers](https://docs.google.com/spreadsheets/d/1IuaZxQf0zKPVXZZbs7VJKQWG4ePLbf-utVQ8ueN7Eg0/edit?usp=sharing), created at Google Sheets
- Note column -- Icon -- with arts entered into each cell.
- Click grey folder next to name J 24 Google Fusion Data Sample. Click Make a Copy (not Add to Drive) to add to your Google Drive and rename.
- Add information to a fifth establishment to practice finding and adding data. Find address, URL and image for ArtsQuest in Bethlehem and create new row on spreadsheet. 
- go to Google Drive, open Google Fusion; Import J24 Table from Google Spreadsheet
- Under Change Info Window, edit card to remove unecessary boldfaced titles: Name, URL, Address, Description, Image, Icon

**Troubleshoot**
- If student has two Google drives (Lehigh and Gmail), spreadsheet may not open; student should then download the spreadsheet to the local computer and then have Google Fusion select from there.

- Go to Map of Location to assure maps displays (if not, troubleshoot below)

**Troubleshoot**
- When spreadsheet first opened in Google Fusion, the tab said Map of Name, not Map of Location; the map did not work. The dots were all over the world.
- It turns out that Google Fusion was trying to map by Names, rather than Location.
- In the fusiontables, click on the Rows tab and hover over the Location cell until a dropdown menu appears. Click Change. Change Type from Text to Location. Repeat steps with Name cell: Change from Location to Text. Map should now say Map of Location and should work.

- **Challenge**: under Configure, [Change Type of Icon](https://support.google.com/fusiontables/answer/2679986?hl=en&ref_topic=2592806) if "arts" icon does not display (Change Map > Feature Style > Icon > Column > Icon).

**Troubleshoot**
- It is possible to add different icons to Google Fusion, rather than the spreadsheet. 
- To enter a new column in Google Fusion, Select Edit > Change Columns > New > Icon. Then add "arts" to each card.

**To Publish**
- Click Done on Map.
- Must make map accessible (the default is private).
- Click the Share button.
- You'll see a list of who has access to the table. Find "Private" and click Change.
- Select the Public or "Anyone with the link" radio button under Visibility options.
- Click Save. The change is effective immediately.
- Click Done. The maps is now accessible.
- Go to Tools > Publish and get iframe html code to embed.
- Create map.html page at github.com to embed the iframe code for the map.
- **Challenge**: The map is small on the html page. Go into the code on your html page and double the size.

## Practice: Out of Class
## Graded Assignment

- Create your own spreadsheet and Google Fusion map with at least five locations.
- Be sure to take out unnecessary bold titles on your cards
- Publish to an html page at github.com, with the size of the map doubled, and send me the link

## Resources

- [Telling Stories with Google Maps](https://sites.google.com/site/geomedialab/exercise-1)
- [Mapping where English is not the language at home](http://www.washingtonpost.com/wp-srv/special/national/us-language-map/), by Dan Keating and Darla Cameron, 2013
- Ken Schwencke gave a two-hour tutorial to ONA, [Getting Started with Mapping](http://forjournalism.github.io/courses/mapping/) that gets into django and other tools.
- ArtsQuest: 101 Founders Way, Bethlehem, PA, 18015	ArtsQuest	http://www.artsquest.org	Two indy movie theaters and restaurants	http://www.artsquest.org/wp-content/uploads/sites/5/2014/11/story-aq.jpg

## Other Mapping Tools

**OpenStreetMap**
- [OpenStreetMap](https://www.openstreetmap.org/about) provides data and maps

**BatchGeo**
- Insert a spreadsheet and get a Google Map at [BatchGeo](https://batchgeo.com/)

**ESRI and ArcGIS**
  - [ESRI Mapping Basics](http://www.esri.com/connected#Mapping%20Our%20World), very possible to use this in classes as well as Google Fusion
  - [Journalists Embrace ESRI Story Maps](https://blogs.esri.com/esri/esri-insider/2015/07/06/journalists-embrace-story-maps/)
  - [ESRI Story Maps](http://storymaps.arcgis.com/en/)
  - Brief [instructions for an ESRI Story Map](http://www.esri.com/esri-news/arcwatch/0513/make-a-map-tour-story-map)
  - My example of a [South Side Story Map](http://jacklule.github.io/pages/ESRIMapStory.html)

**Carto**
  - [The Map Academy: Online Mapping for Beginners -- 5 Lessons](http://academy.cartodb.com/courses/beginners-course/), a steeper learning curve than ESRI and Google Fusion
  - [The Map Academy: Introduction to Map Design -- 4 Lessons](http://academy.cartodb.com/courses/design-for-beginners/)

**StorymapJS**
- [StorymapJS](https://storymap.knightlab.com/), track events across a map; not as powerful as Google Fusion, Carto or ESRI
 
**Stately**
-[Stately](https://intridea.github.io/stately/), U.S. state mapping


