# Creating an ebook

Use any texteditor to write ebook text in markdown format. Use [katib](http://katibapp.com) for multilingual editing. 
Use command line tools pandoc and kindlegen for format conversions.

Use pandoc to convert markdown (.md) file to ebook (.epub)

    pandoc yourfilename.md -o mybook.epub

Convert to amazon's .mobi format:

    kindlegen mybook.epub 
    
### Cover Image for the ebook

    pandoc yourfilename.md -o --epub-cover-image=cover.jpg myebook.epub


### CSS to style the ebook


### Metadata for the ebook

### References
http://pandoc.org/epub.html

http://garyhall.org.uk/create-ebook-command-line.html

https://rachelandrew.co.uk/archives/2014/01/07/html-epub-mobi-pdf-wtf-creating-an-ebook/



