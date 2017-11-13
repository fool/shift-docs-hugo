## Overview

a fool's attempt to extract the useful information from the existing https://shift2bikes.org website

## Software

built using:
- [hugo v0.30.2](https://gohugo.io) 
- && the theme ["learn"](https://learn.netlify.com)
- && the content from [the legacy shift website](https://shift2bikes.org)
- && [Netlify web hosting](https://www.netlify.com) to serve the content

You can browse the current state here:  https://shift-docs.netlify.com

## Contributing

- [pull requests](https://help.github.com/articles/creating-a-pull-request/) welcome.  You can check out [a link to the build status and log and a preview of your site](https://app.netlify.com/sites/shift-docs/deploys)
- or [contact fool](mailto:gently@gmail.com) for an invitation to the CMS so you can edit it in your browser.

## Local development
1. clone repo: `git clone https://github.com/fool/shift-docs-hugo.git`
2. `cd shift-docs-hugo`
3. clone theme:  `git submodule update --init --recursive`
4. [install hugo](http://gohugo.io/getting-started/quick-start/#step-1-install-hugo)
5. build site: `hugo`
6. start server for site: `hugo serve`
7. browse at [http://localhost:1313](http://localhost:1313) in your browser

