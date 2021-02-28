# hugo-book-project
Book publishing project with Hugo

Note: I'm not actually going to republish classic books (only publishing new books) but some chapters of public domain books are included for the example.

Things to change/add/fix:

* Featured can be static
* List should be a list of books, it can also be static
* Maybe swap the left/right of the "next page / previous page" widget so it's more logical to reading a book, might be other moving parts related to that which are going to require special changes to work cleanly
* If the book detects final page say so in a nice way?
* Add and enable this webfont https://fonts.google.com/specimen/Poppins?preview.text_type=custom


Resolved

* Only chapters from a single book are showing up on the front page
* For example, instead of Draculas in the breadcrumbs it should say Dracula, stop adding the extra s (just noticed this seems to be fixed simply by adding an _index.html with the title Dracula so may not be an actual issue)
* Tags are not working fully properly (actually with this project they appear to be working proplery so ??? for now, I must have something wrong set in my other project)
* Add way to disable breadcrumbs on a page (just set ShowBreadCrumbs: false in the frontmatter of a page)