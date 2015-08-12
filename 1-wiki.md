# Converting PKP Wiki Documentation

Conversion from PKP Wiki is broken up into two major steps. 

1. Converting Mediawiki formatted text in the Wiki to Markdown.
2. Building the GitBook. 

A PKP Wiki document is organized differently than a GitBook because they are usually one discrete document with a Table of Contents at the top of the page. Any individual Wiki document is really just one page, whereas a GitBook is a collection of pages organized into a document. 

## Converting Mediawiki-Formatted text in the Wiki to Markdown

**Step 1** // Login to the Wiki find the document you want to migrate to GitBook.

**Step 2** // Click on "Edit" to pull up the Mediawiki text. 

![Click on "Edit"](https://github.com/AhemNason/pkp-wiki-to-gitbook-migration-documentation/blob/master/images/migration01.png?raw=true)

**Step 3** // Copy whatever portion of the mediawiki text you're converting to Markdown and save it in a text editor as a plain .txt file. 

**Step 4** // Use Pandoc to convert mediawiki to Markdown. 

**Step 5** // Put that Markdown in the GitBook, assuming you've already made the GitBook and know where you want to put it. 

**Step 6** // Remember that patience is a virtue, supposedly. Everything will be ok. 

## Building the GitBook

