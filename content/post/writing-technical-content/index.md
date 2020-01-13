---
date: "2020-01-13"
diagram: true
image:
  caption: 'Image credit: [**John Moeses Bauan**](https://unsplash.com/photos/OGZtQF8iC0g)'
  placement: 3
markup: mmark
math: true
title: My Favorite Shortcuts and Tricks in RStudio
---

One of my favorite things about R is the plethora of add-ons and extras that can make organizing, editing, and running code easier. Of course, that can come with drawbacks - a friend commented that they didn't like R "because there's always 20 ways to do the same thing!" Of course, that's exactly WHY I like it, so here's a short list of my favorite extras/functions/tips and tricks that will make your life easier. Note that these are all **WINDOWS** shortcuts, Mac OS has different options.

### Finding, Replacing, and Navigating.<br>

Just like in Word, PDFs, or webpages, you can search and locate specific instances of text with **Ctrl-F**. If you already have a piece of text highlighted when you do this, the 'find' will autopopulate with that piece, saving you the trouble of retyping. You can also choose to limit your search to text in the same case, or search by regular expressions. 

Replace comes up in the same 'find' taskbar. If you've highlighted a portion of code, you can easily replace all instances just in that snippet by checking 'in selection' and then then hitting the 'all' button. This can be really handy if you're doing the same set of tasks on many objects with different names and need to be sure you've changed all the named instances.

Another useful way to organize code is using **Ctrl-Shift-M**. This will bring up a dialog box in which you can type the main purpose of the code or part of the document you're working on, like 'Import Data' or 'Run Logistic Regression'. Then, use **Ctrl-PgUp** or **Ctrl-PgDn** to easily navigate directly to previous or later sections.

One more: navigating the cursor to the beginning (**Home**) or end (**End**) of line.

### Selection<br>

To highlight the entire current line: **Ctrl-Shift-L**.
To highlight all code to a matching parenthes or bracket, use **Ctrl-Shift-Alt-E**.
To select all code from current to start/end, use **Ctrl+Shift+Home/End** or **Shift+Alt+Up/Down**	

### Running Code<br>

 To run current line (or whatever is in your highlight snippet), **Ctrl-Enter**. You can also go up to the 'code' tab, then select 'run selected line' but I find it's faster to do via keyboard. To run the whole document up to your current cursor, use **Ctrl-Alt-B**, or from current line to then end use **Ctrl-Alt-E**.


### Commenting<br>
I comment out lines frequently. **Ctrl-Shift-C** will comment out the current line or selection.

### Knitting<br>
If using RMarkdown, knit the document with **Ctrl-Shift-K**.


### Inserting Helpful Operators<br>
The pipe operator, %>%, is a useful function built in the magittr package. Insert one with **Ctrl-Shift-M**. Also, in R the assignment operator, <- , can be inserted with **Alt- -** (that's alt and the minus key).


These are NOT the only available shortcuts, for a more complete list see this [cheatsheet](https://rstudio.com/wp-content/uploads/2016/01/rstudio-IDE-cheatsheet.pdf) . You can also create/customize your own personal shortcuts by going to 'Tools' --> 'Modify Keyboard Shortcuts'.

### Did you find this page helpful? Consider sharing it 🙌
