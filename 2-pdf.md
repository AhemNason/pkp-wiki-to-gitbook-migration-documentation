#Converting PDFs and Other Formats

##Not all Formats are Created Equal

Pandoc has support to convert a number of formats to Markdown. While it's worth noting that not all formats will convert as easily as Mediawiki might, the list of supported input formats is fairly substantial and a great place to start. Pandoc supports:

- **docx**
- **html**
- **mediawiki**
- docbook
- haddock
- twiki
- t2t
- epub
- commonmark
- json
- latex
- markdown (github, strict, mmd, standard)
- native
- opml
- rst
- textile

If the document format you are converting is *some other thing*, you'll be on the hook for converting it twice. 

##PDF Conversion

Converting a PDF to Markdown can be a fairly *involved process*. PDFs are primarily about preserving the book-like view/structure of a document but aren't really all that great at preserving the content of the document itself. As someone tasked with converting a PDF document to just about any other format, there are going to be some obstacles in the way. 

There are a number of different tools out there that advertise conversion of PDF to other formats. Adobe's Acrobat Pro is pretty reasonable at converting PDF to HTML or Word Doc, for example. The most important thing to remember, though, is that **you will need to convert PDF to some other format *before converting to Markdown*.** 

Because PDF is about the look of the content instead of the content itself, though, you're more likely to run into issues like incorrect text formatting (your italicized text might not be italicized, for example) or spacing issues. You should expect any document with more than just plain text to require some effort to clean up. 

