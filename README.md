# metadata-guidelines

This repo hosts the [hugo](https://gohugo.io/) project that the Lafayette Digital Repository Metadata Dictionary & Creative Guidelines are derived from.
The dictionary is divided into two main sections: "descriptive metadata" and "administrative metadata." The Markdown files can be accessed in the "content" directory.
This site uses a fork of the "hugo-book" theme as a submodule. Within it, the favicon has been changed as well as content in "content-before.html" to create the header
on each page of the dictionary that displays a metadata field's definition, if it is required, and if it is repeatable.

## How to Deploy
This repo includes the GitHub workflow needed to host this site using GitHub Pages. To create an environment for this site on your local machine, type the 
following command after navigating to the "ldr-metadata-guidelines" directory:

```
hugo server --minify
```

Any pushes made to the master branch will automatically build the site for GitHub pages. To make the site available to the wider web,
go to "Settings"&rarr;"GitHub Pages." Under "Source," select the gh-pages branch. You should then get a notice that the site has been published.
