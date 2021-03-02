# hugo-book-project
Book publishing project with Hugo

This example is being set up primarily for [Tarot.io](https://www.tarot.io/) for its upcoming free online library of experimental books.

This example is useful for implementing the webnovel publishing format where typically single chapters are published online for free one chapter at a time.

This example supports multiple books being published on the same Hugo setup at once.

Note: I'm not actually going to republish classic books (only publishing new books) but some chapters of public domain books are included for the example.

Date timestamps are got from here https://timestampnow.com/ manually but you can use any date format Hugo supports.

Things to change/add/fix:

* If the book detects final page say so in a nice way?
* For breadcrumbs, if it is the final page, loop back for the front for the "next"
* Maybe define cover images in sections so they can be used in list / featured
* Cover images could also be used to be displayed next to chapter updates on the main page / section page to theme them
* Add a +- UI which increases or decreases the zoom of post-content, use the same JS as theme toggle uses in header.html / footer.html
* ^ Maybe add a settings drawer, allow for changing more themes, font, zoom, line height, full frame, no line break


Resolved

* Only chapters from a single book are showing up on the front page
* For example, instead of Draculas in the breadcrumbs it should say Dracula, stop adding the extra s (just noticed this seems to be fixed simply by adding an _index.html with the title Dracula so may not be an actual issue)
* Tags are not working fully properly (actually with this project they appear to be working proplery so ??? for now, I must have something wrong set in my other project)
* Add way to disable breadcrumbs on a page (just set ShowBreadCrumbs: false in the frontmatter of a page)
* Maybe swap the left/right of the "next page / previous page" widget so it's more logical to reading a book, might be other moving parts related to that which are going to require special changes to work cleanly
* Disable the chapter blurb, some people may view it as a spoiler trap
* Add a link to jump to the book chapter 1 and book front from the section page of a book
* Featured can be static
* List should be a list of books, it can also be static
* Add and enable this webfont https://fonts.google.com/specimen/Poppins?preview.text_type=custom