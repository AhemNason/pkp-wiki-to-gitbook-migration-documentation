# Converting PKP Wiki Documentation

Conversion from PKP Wiki is broken up into four major steps. 

1. Converting Mediawiki formatted text in the Wiki to Markdown.
2. Building the GitBook. 
3. Clean up text. 
4. Update as Necessary. 

A PKP Wiki document is organized differently than a GitBook because they are usually one discrete document with a Table of Contents at the top of the page. Any individual Wiki document is really just one page, whereas a GitBook is a collection of pages organized into a document. 

## Converting Mediawiki-Formatted text in the Wiki to Markdown

**Step 1** // Login to the Wiki find the document you want to migrate to GitBook.

**Step 2** // Click on "Edit" to pull up the Mediawiki text. 

![Click on "Edit"](https://github.com/AhemNason/pkp-wiki-to-gitbook-migration-documentation/blob/master/images/migration01.png?raw=true)

**Step 3** // Copy whatever portion of the mediawiki text you're converting to Markdown and save it in a text editor as a plain .txt file. 

**Step 4** // Use Pandoc to convert mediawiki to Markdown. 

![Pandoc conversion"](https://github.com/AhemNason/pkp-wiki-to-gitbook-migration-documentation/blob/master/images/migration02.png?raw=true)

**Step 5** // Put that Markdown in the GitBook, assuming you've already made the GitBook and know where you want to put it. 

**Step 6** // Remember that patience is a virtue, supposedly. Everything will be ok. 

## Building the GitBook

It is highly recommended that you read through the [GitBook help](http://help.gitbook.com/). The guide is fairly extensive. What's important in the process of building the GitBook is that you have some idea of what the structure of the book will be before you get started. Moving content around after-the-fact can be somewhat cumbersome. 

The most important thing here, however, is that you know where you'll want to paste your Markdown that you've converted from mediawiki. You could paste it all in one large document and part it out, or you could paste each section as you go. It's really up to you. Listen to your heart. 

**Courage**. 

## Cleaning Up the Text 

It's likely that the migration from mediawiki to GitBook Markdown might produce text that isn't a direct 1:1 match. Things like discrete line length might end up requiring quite a bit of clean up. You're likely to be on the hook for a little bit of the following:

- 

