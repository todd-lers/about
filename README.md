# About the Todd Group
We are a group of scientists interested in chemistry, biology and drug discovery. We can be found mostly at University College London in the School of Pharmacy, 29-39 Brunswick Square, London WC1N 1AX, UK. There are still some group members at Mat's previous institution, the University of Sydney, Australia.

The group website can be found here: https://todd-lers.github.io/about/

# How to edit/update the website pages
All the files used to create the group website can be found in the Code tab above. Each page of the website is contained within the respective markdown (.md) file. They are as follows:
- Home page = [index.md](https://github.com/todd-lers/about/blob/master/index.md)
- Research page = [research.md](https://github.com/todd-lers/about/blob/master/research.md)
- Current Members page = [current.md](https://github.com/todd-lers/about/blob/master/current.md)
- Past Members page = [past.md](https://github.com/todd-lers/about/blob/master/past.md)
- Publications = [publications.md](https://github.com/todd-lers/about/blob/master/publications.md)
- News = [news.md](https://github.com/todd-lers/about/blob/master/news.md)
- Internal = [internal.md](https://github.com/todd-lers/about/blob/master/internal.md)

In general, each page can be edited directly by opening the pages .md file and clicking the edit button (pencil icon in the top right). Once the desired edits are made, click the "Commit changes" button. You may need to refresh the website to see the changes (the site updated date should change to reflect this).

The majority of text in the .md files is written in markdown, however certain pages also contain HTML code that enable design elements on those pages.

Please contact @edwintse if you encounter any issues or need any help.

# Linking to files and documents and inserting images

All files and documents should be uploaded to the docs folder above and put in the relevant subfolder. You can use one of the following bits of code to create a hyperlink to the to the file from the group website:

- Use `[hyperlinked text](URL)` to create a link that goes directly to the GitHub page were the file is located (standard markdown way of hyperlinking)
- Use `<a href="./docs/###" download>hyperlinked text</a>` to create a link that downloads the file to your computer when clicked (### = file path to the document including the file extension; e.g. "./docs/Onboarding/COSHH Form.doc")
- Use `<a href="./docs/###.pdf" rel="noopener noreferrer" target="_blank">hyperlinked text</a>` if you want a PDF to be opened in a new tab in your internet browser (### = file path to the document)

Any photos/images should be uploaded to the pics folder above and put in the relevant subfolder. You can use the following code to insert an image on the group website:

- Use `<center><img src="./pics/###" width="90%"></center>` to insert an image (### = file path to the image including the file extension; e.g. "./pics/research/OSTB Summary.png")

# Page specific instructions
The .md files for the following pages contain code that is important for the design elements on the page. This should make more sense once you read these instructions then look at the code in the actual .md files.

In case you are not familiar with it, HTML code is written between containers such as `<div>` and `</div>` (first bit starts the code, the second bit with the forward slash ends the code). For every `<div>` there will always be a matching `</div>`.

_**Please make sure you are aware of these bits of code before editing these pages to make sure it continues to look as intended.**_

## Current Members page

This page contains "cards" that displays the info for each current group member.

There are 3 cards per row contained between `<div class="row">` and its matching `</div>`.

Within each row, each card is represented with the following code (3 of these can be placed in each row environment):

```
<div class="column">
  <div class="card">
    <img src="./pics/people/###" class="myimg">
    <h4>@@@</h4>
    <p class="title">$$$ (UCL) <br>%%%-present</p>
    <p></p>
    <div style="margin: 15px 0;">
      <a href="&&&"><i class="fa fa-linkedin"></i></a>
      <a href="&&&"><i class="fa fa-twitter"></i></a>
    </div>
  </div>
</div>
```
\### = file name of the photo including the file extension (e.g. Ed_Tse.jpeg). Photos should be uploaded to the pics => people folder ([shortcut here](https://github.com/todd-lers/about/tree/master/pics/people)).  
@@@ = persons name  
$$$ = position (e.g. postdoc/PhD/etc.)  
%%% = year joined group (e.g. 2019-present)  
&&& = URL to LinkedIn and Twitter (can delete these lines if no accounts)

## Internal page

This page contains "accordians" that expand and collapse when clicked. This is done to minimise the number of separate pages (and .md files) needed to create the site and allows for more info to be put in a single page.

Each group of connected accordians is contained between `<div id="accordion">` and its matching `</div>`.

> n.b. each group of connected accordions must have a unique id (e.g. accordion1, accordion2, etc.). To add a new group of connected accordions to the page you must go to [this file](https://github.com/todd-lers/about/blob/master/_layouts/collapsible.html) and add a new accordion id between `<script>` and `</script>`. Copy and paste the following code in a new line of the script environment (replace "accordion4" with the new id):

```
$( "#accordion4" ).accordion({
      active: false,collapsible: true,heightStyle: "content"
    });
```

Within a group, each separate accordian is represented with the following code (you can have as many of these in each accordion group as you'd like):

```
<h3>###</h3>
  <div id="link" markdown="1">
$$$
  </div>
```
\### = text that appears on the accordian bar (i.e. description of the contents)
$$$ = text that appears when expanding the accordion (use markdown for this text)
