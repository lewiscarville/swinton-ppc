# Swinton PPC

Static files templated using [Hugo](https://gohugo.io/)

## Prerequisites

+ Hugo
+ Gulp


## Developing Locally

To run the local server:

    hugo server
 
To build production files you can run:

    hugo


To compile front end resources:

@lewis you need to move the files here and adjust the process so the files get outputted to the correct place

    gulp

## Structure

The site content lives in Markdown files in the content directory.

At the top of the file sits a YAML defined structure of the components that we want on the given page.

Each component has its own parameters which define the content for it.


## Compiling for production

To build the static site to the 'build' directory run:

    hugo

In theory this site could then be served directly or more likely the html extracted and inserted in the CMS


