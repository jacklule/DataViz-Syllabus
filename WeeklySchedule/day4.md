# Day 4
## Telling Stories of Change Over Time

## Timelines

## Principles: Before Class

- Read: Lena Groeger of ProPublica on Making Timelines. Her [2013 presentation to NICAR](http://lenagroeger.s3.amazonaws.com/timelines/timelines.html), the National Institute for Computer-Assisted Reporting, and her [2015 NICAR presentation](http://lenagroeger.s3.amazonaws.com/talks/nicar-2015/timelines-nicar/timelines.html)
- View: [Examples of TimelineJS](https://timeline.knightlab.com/index.html#examples), noting the combination of image, text and time, such as [How Wine Colonized the World](http://vinepair.com/wine-colonized-world-wine-history/#1)
- Read this wiki about [how to organize a timeline](http://www.wikihow.com/Make-a-Timeline)

## Principles: In Class

- Time is at the core of journalism. The linguistic roots of the word "journalism" are tied to the word, "day." 
- Timelines are natural ways to tell stories, especially about changes over time, from the history of a university to the story of someone's life.
- Timelines are also effective for telling the story of an incident, from a terrorist attack to the Olympics opening ceremony.
- Timelines had been difficult to construct. But the Knight Lab created a beautiful tool: TimelineJS. It continues to be improved and we will work with TimelineJS 3.

## Practice: In Class

- In-Class Exercises
  - **Review again**: [Examples of TimelineJS](https://timeline.knightlab.com/index.html#examples), noting the combination of image, text and time
  - Next: we will study the spreadsheet at the heart of the Timeline and most data visualizations. The [Timeline spreadsheet](https://drive.google.com/a/lehigh.edu/previewtemplate?id=1pHBvXN7nmGkiG8uQSUB82eNlnL8xHu6kydzH_-eguHQ&mode=public#) is based in Google Drive. 
  - You will need to be signed up at Google Drive. The timeline is quite specific in its structure. Here is a [discussion of the spreadsheet](https://timeline.knightlab.com/docs/using-spreadsheets.html).
  - **Create your own timeline**
  - We will use links to photos and add our own brief text to complete the [4-step TimelineJS tutorial](https://timeline.knightlab.com/index.html#make), including the Optional Settings in Step 3. We will want to pay attention to photo credits. Our timeline will be about opening night of the 2016 Olympics in Rio, August 5, 8 p.m.
  - **Step 1** Fill in the spreadsheet with information from links below.
    - [Rio 2016](https://1.bp.blogspot.com/-gpgFkYiFS0k/V2PgaYiIIWI/AAAAAAAAAGg/iP_5APptn2Yoy-irza5E4unZTHJSPIg9QCLcB/s1600/Rio%2B2016%2BOlympics%2BOpening%2BCeremony.jpeg). Text to state that 2016 Summer Olympics were held in Rio de Janeiro, Brazil. Date this August 1.
    - [Concern that Rio would be ready](https://i.ytimg.com/vi/9qPPxnOlrlo/maxresdefault.jpg). Text focuses on some of the concerns. Date this August 2.
    - [Athletes march in](http://wpmedia.news.nationalpost.com/2016/08/rio_olympics_opening_ceremony-12.jpg). Text states that the Games started on time, with the familiar parade of nations. Date this August 5, 8 p.m.
    - [Rio opening ceremony](http://images.indianexpress.com/2016/08/maracana-main.jpg). Text states the opening ceremony was a celebration of Brazilian history and culture. Date this August 5, 10 p.m.
    - [2016 takes its place in history](). Text states that the 2016 opening ceremony thus took its place in the long history of Olympic ceremonies. Date this August 6.
  - **Step 2** says: Under File, click Publish to the Web. Click grey Embed. Asked "Are You Sure," press ok. 
      - NOTE: The following has changed as of 21 November 2016!
      - Close the 'Publish to the web' window. It no longer works. Instead, copy the URL for your Timeline from the browser's address bar. 
      - It should look something like this: https://docs.google.com/spreadsheets/d/1xuY4upIooEeszZ_lCmeNx24eSFWe0rHe9ZdqH2xqVNk/edit#gid=0
    - **Important**: This is the link to the spreadsheet NOT to the timeline. You still need to return to TimelineJS and Step 3.
  - **Step 3** Return to TimelineJS Make a Timeline site and under Step 3, paste the link to the spreadseet into the box on Step 3, next to Google Spreadsheet URL.
  - **Step 4** The final iframe embed link should now appear in the grey box in Step 4 (it should begin with <iframe src="https://cdn.knightlab.com). Copy the iframe embed code from Step 4 and proceed to directions on creating an html page for it.
  - **Create html page for timeline**
    - With the iframe embed code copied, go to github.com, create a New File, title it Rio.html, use standard html coding to create an html page and paste in the iframe embed code:
    - (enter < and > before and after each line where needed so it will appear as html)
    - !DOCTYPE HTML>
    - html>
    - body>
    - h1> Rio Opening Ceremony</h1>
    - h2>Your Name</h2>
    - iframe src="https://cdn.knightlab.com. . . . .>
    - /body>
    - /html>

Commit

## Practice: Out of Class Assignment

- Find a topic you care about and construct your own TimelineJS, using 5-8 photos or videos with 2-3 lines of text for each.
- Publish the TimelineJS on an html page.
- Send me a link to that page.
- Eventually put the link on your page at name.github.io

## Resources
- [What Are Time Series Graphs](http://statistics.about.com/od/Descriptive-Statistics/a/Time-Series-Graphs.htm)
