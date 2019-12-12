## Night 1

Going off the tutorial on Gatsby's site to see if this would be a good option for Connor's portfolio site, while allowing Clay and Jamie to manage content/uploads.

Link to tutorial: https://www.gatsbyjs.org/docs/sourcing-from-netlify-cms/

Standard rocket emoji 🚀

Progress: Made it to deploy to Netlify section (because that's 🍰)

## Night 2

Got authentication working through Github OAuth. Pages still not creating and not showing up in routes and need to research.

Got tripped up because initially, when following the tutorial, wasn't clear that a blog directory needed to be created in order for it to show up at all. Locally, routes showing but not on build? Must be a config file issue???

[Resource] Gatsby's Markdown file tutorial: https://www.gatsbyjs.org/docs/adding-markdown-pages/

## Night 3

Page build now working from markdown files with template and `gatsby-node.js` file.

## Considerations for Future Projects

1. Is Netlify CMS worth using in client projects?

   > It's hard to answer this question. It seems relatively basic and may indeed have all the essentials, but as far as needing something simple the site needs to build from github repository and so will need to continue to maintain even after handing off.
   > Would work for clients that just want a blog to edit but if they want to be able to change design/colors/layout then it will not be a good fit.

2. Having difficulty wrapping head around the creation of pages, collections, etc. to get what you want
   > It seems like it would be worthwhile to have this down as a method, but it does seem complicated from the starter
   > Still a significant benefit for being able to utilize Gatsby and also it be static rather than a costly CMS hosted with PHP
