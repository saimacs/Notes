# Creating an ebook

* Use pandoc to convert markdown (.md) file to ebook (.epub)

pandoc yourfilename.md -o mybook.epub

* Add a cover to your ebook

pandoc yourfilename.md -o --epub-cover-image=cover.jpg myebook.epub

* Convert to amazon's .mobi format:

kindlegen mybook.epub 


