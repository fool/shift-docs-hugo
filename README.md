## Overview

a fool's attempt to extract the useful information from the existing https://shift2bikes.org website

## Software

built using:
- [hugo v0.30.2](https://gohugo.io) 
- && the theme ["learn"](https://learn.netlify.com)
- && the content from [the legacy shift website](https://shift2bikes.org)

## Contributing

- [pull requests](https://help.github.com/articles/creating-a-pull-request/) welcome, 
- or [contact fool](mailto:gently@gmail.com) for an invitation to the CMS so you can edit it in your browser.

## Local development
1. clone repo: `git clone https://github.com/fool/shift-docs-hugo.git`
2. `cd shift-docs-hugo`
3. clone theme:  `git submodule update --init --recursive`
4. [install hugo](http://gohugo.io/getting-started/quick-start/#step-1-install-hugo)
5. build site: `hugo`
6. browse site created in public/ (OSX: `cd public && open index.html`)
