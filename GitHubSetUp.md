#GitHub Set Up
I have attempted to make this guide as simple and clear as possible for those without any GitHub experience. It is written for Macs but can be adapted to PCs. If you have questions, please do let me know so I can continue to improve the document.

Found below are instructions for:
- [Getting Set Up at GitHub.com](#Getting-Set-Up-at-GitHub.com)
- [Getting Set Up at GitHub.io](#Getting-Set-Up-at-GitHub.io)
- [To Edit an html page in TextEdit](#To-edit-an-html-page-in-TextEdit)
- [To Set Up TextEdit to Create html Pages](#To-Set-Up-TextEdit-to-Create-html-Pages)
- [To Customize the GitHub.io Page](#To-Customize-the-Github.io-Page)
- [To Publish Other Work at GitHub.io](#To-Publish-Other-Work-at-GitHub.io)
- [To Create and Manage Files and Folders](#To-Create-and-Manage-Files-and-Folders)
- [Working with GitHub in a Computer Lab](#Working-with-GitHub-in-a-computer-lab)
- [Resources](#Resources)


<a id="Getting-Set-Up-at-GitHub.com"></a>
##Getting Set Up at GitHub.com <a id="Getting-Set-Up-at-GitHub.com"></a>

<p>Students of course first need to set up an account. It is easy at <a href="https://github.com">GitHub.com.</a> 
<p>We will follow along with the <a href="https://guides.github.com/activities/hello-world/">Git Hub setup guide, "Hello World."</a></p>

My **annotations** for Hello World:
- for **Signup**, students should use their first and last name: for example, jacklule
- before Create a Repository, follow tip to open up Hello World guide in **separate tab** and work in another tab
- also before repository, GitHub will ask, **Please verify email address**; will need to open email
- for repository, no need to name, "Hello World;" can **name Data Viz**
- click Public, click Initialize with ReadMe; notice **ReadMe is md file**
- do Issue and Create Branch, notice **working in branch, not master**; not use often, will work in master, but good practice
- click to access ReadMe (**notice we are in branch**);
- click pencil icon in top right to **edit ReadMe**; practice md and preview as go along
- -write a Commit title or message (**grey default can be written over**)
- can check ReadMe in branch and master to see difference; **master is still unedited; changes have not been pulled in**
- **request a pull**; (you will not usually make a request of yourself and just work on master) New Pull Request
- as creator of the master branch, you **compare change**; either in grey base box, master>branch; or click on edit link; notice changes in green and red
- click **confirm merge** and **delete branch** to keep things clean
- check your repository; changes made and the branch has been deleted; though we will not use much can see the advantage of collaborative work flow; check the **GitHub work flow** link

<p>For homework, students should edit their ReadMe page with more information about themselves and their education. They should also add a photo and more information to their profile, all the while gaining experience with markdown.</p>
<a id="Getting-Set-Up-at-GitHub.io"></a>
##Getting Set Up at GitHub.io 

<p> The following class, the students then should follow the <a href="https://pages.github.com/">GitHub Pages guide</a>, using "User or organization" site and "GitHub for Mac" to set up their .io repository page, which will serve as a Portfolio of their work for the class and for future employers.</p>

My **annotations** for GitHub Pages Guide:
- GitHub for Mac should already be installed on local computer
- Go to the [GitHub Pages Guide](https://pages.github.com/) and follow steps, using GitHub for Mac
- "Head over to GitHub" means go to **github.com/username** and create a new repository named **username.github.io**
- Step 2: Clone the Repository **may** be accomplished by merely clicking Set Up in Desktop. Students will need to know, however, where the local repo is being stored on the computer.
- If the cloning does not work, here are [GitHub instructions for cloning](https://help.github.com/articles/cloning-a-repository/); desktop instructions are near the bottom: Go to repo's main page; click on clipboard to copy the URL for the rep; go to GitHub Desktop, verify name and location of where the file should be; click Clone.
- GitHub then says, **grab your favorite text editor**: not so simple; next step:

<a id="To-Set-Up-TextEdit-to-Create-html-Pages"></a>
##To Set Up TextEdit to Create html Pages
- Students must **set up their text editor to create html pages**. For the Mac, this means to edit Preferences in Apple TextEdit. [Apple Support: How to Set Up TextEdit](https://support.apple.com/kb/ta20406?locale=en_US). In sum: Under Preferences, Click the Plain Text radio button for New Document Format; Under Saving, click the checkbox to turn off "Append '.txt' extension to plain text files."
- Also see [Creating an html page](http://www.w3schools.com/html/html_intro.asp)
- Students can then take the next step in the Pages Guide and create an index.html page
- Opening up the Mac's TextEdit, students will follow the html directions at the Guide to create the html page
- Students then save that page to their GitHub repository on the local computer
- GitHub will recognize a change has been made to the repository. Students then commit the changes and sync with their GitHub site
- The sync will add the html page to name.github.com
- Students can view the html page through any browser

Students thus have learned to code and create a new html page to embed and publish each assignment thus doubling the value of each lesson. 

<a id="To-edit-an-html-page-in-TextEdit"></a>
##To Edit an html Page in TextEdit
TextEdit will open a previously created html page as an html file, not in text edit. To edit an html page in TextEdit:
- Under TextEdit, find Preferences
- Go to the “Open and Save” tab, check the box, “Display HTML files as HTML code instead of formatted text” 
- Under "New Document," make TextEdit default to "plain text" (instead of "rich text")

<a id="To-Customize-the-Github.io-Page"></a>
##To Customize the GitHub.io Page
Remembering that the page eventually will be their GitHub portfolio, students should follow these steps:
- Students should have already **set up their repo site at github.io**, using the directions above and at [Git Hub Pages guide above](https://pages.github.com/)
- After creating username.github.io, students can personalize that page;
- They should go to page --- username.github.io -- and find the **setting** link to the top right;
- Scroll down to Update site and click on Automatic Page Generator;
- provide a straightforward page name: name.github.io
- provide a brief tagline of description;
- scroll past generic text and continue to Layout; 
- I chose Minimal but students can pick from other styles;
- the repo/portfolio page is now customized;
- Students can then go to their index page, remove the generic GitHug text and begin providing their own content;
- Here is the result for me at [my GitHub Page](http://jacklule.github.io/)

<a id="To-Publish-Other-Work-at-GitHub.io"></a>
##To Publish Other Work at GitHub.io
To publish other work, such as charts, Tableau files and YouTube videos to GitHub.io:

- **To publish work saved on the local computer**, such as svg files produced by Chartbuilder: 1) Students would complete the assignment at Chartbuilder; 2) download the svg file to their local computer (the other option, png files, do not render consistently); 3) create an html page for the assignment; 4) insert the svg file into the html page; 5) upload the html page to their github.io site. Here are examples of a Chartbuilder assignment in svg and png format: [Chartbuilder svg test](http://jacklule.github.io/pages/SVGtest.html) and [Chartbuilder png test](http://jacklule.github.io/pages/PNGtest.html)
- **To embed and publish work hosted on sites**, such as Tableau or YouTube: 1) Students would complete the assignment on Tableau; 2) get the embed code at Tableau; 3) create an html page for the assignment; 4) embed the Tableau work into the html page; 5) upload the html page to their github.io site. Here are examples: [You Tube Embed Test](http://jacklule.github.io/pages/YouTubeEmbedTest.html) and [Tableau Embed Test](http://jacklule.github.io/pages/embed-test-Tableau.html)
- **To "hand in" the assignment**, students would: 1) Copy the file path --"copy path" -- for the assignment page and paste that link into their "Portfolio" page, name.github.io; 2) The students may need to add http:// in front of the assigment file path name on their Portfolio page for the pasted url to work; 3) Students would then notfiy me that the assignment was completed and send me the url for the Portfolio page.
- Again, name.github.io will be **The Portfolio** page, a collection of Data Viz work that can be shared with future employers.

<a id="To-Create-and-Manage-Files-and-Folders"></a>
##To Create and Manage Files and Folders
**Creating folders within GitHub**:
- go to the folder inside which you want to create another folder
- click on New file
- on the text field for creatng the file name, after the /, type the *folder* name you want to create and hit Enter
- on the next text field to the right, after the /, type the *file* name (type .md if you want that style) and hit Enter
- this creates a folder.
- [Here is GitHub help on Moving Files](https://help.github.com/articles/moving-a-file-to-a-new-location/)

<a id="Working-with-GitHub-in-a-computer-lab"></a>
##Working with GitHub in a Computer Lab
Students likely will not have administrative access to download and install GitHub for Mac in a computer lab. The instructor would do so with JournalismAdmin access, for example, with its password. 

For students then to set up GitHub.io pages, follow the four-step process at [GitHub Pages](https://pages.github.com/) or see above but also follow these annotations:

1. Create a repository at github.com: 
  - name.github.io
  - select GitHub for Mac as client
2. Clone the repository: 
  - GitHub.com might give “Setup in Desktop” as an option. That should clone the repository on the local computer.
  - If that option does not appear: Instructions say to “launch the local app.” That means, find GitHub on the local Mac and open. At top bar, go to File>Clone Repository. Defaults say: “clone as name.github.io” and where (GitHub folder): press okay
  - The repository should now be cloned (copied) onto local computer.
  - But **where is GitHub stored locally?**
  - Outside of a lab, GitHub on a Mac is stored under Home, with Documents, Downloads etc. In a computer lab, GitHub will be stored under Users, for example: Mac3>Users>DataViz>GitHub>name.github.io
  - To access: Finder>top bar> Go> Home(opens as DataViz)> GitHub folder. Inside that folder should be another folder name.github.io
3. Create an Index file
  - The local Mac’s text edit needs to have been adjusted so it can create and save an html page. See instructions above. 
  - Save the html file. It should automatically save without prompting to local folder: name.github.io. Can check using instructions above, "Where is GitHub stored locally?"
4. Commit and Sync
  - Go back to GitHub desktop. You should see “1 uncommitted page.”
  - Click and see the new html page.
  - Provide a summary and description and then “commit to master.”
  - Page is now on the local GitHub master.
  - Click sync. The local and GitHub.com repositories are now synced.
  - To check online: Go to the io repository at name.github.com. The index.html file should be now in the github.com repository.

<a id="Resources"></a>
###Resources
- [Nice intro to first steps with GitHub to add to a list](https://18f.gsa.gov/2015/03/03/how-to-use-github-and-the-terminal-a-guide/)
- [A good, clear introduction to using Terminal/the Command Line and GitHub](https://18f.gsa.gov/2015/03/03/how-to-use-github-and-the-terminal-a-guide/)
