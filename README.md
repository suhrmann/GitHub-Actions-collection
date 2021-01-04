# GitHub-Actions-collection
Here I collect GitHub Action workflows for various projects and use cases.

# Table of content
1. [Web](#web)
    1. [Electron](#electron)

-----

# Web
All web related workflows (fullstack, front-end, etc.)

## Electron
**Electron to GitHub Releases and Website to GitHub Pages**

I use this workflow for Vue.js based [Anno-1800-Calculator](https://github.com/suhrmann/Anno-1800-Calculator). This project has no tests. 
The 3 workflows: 
 - [build.yml](https://github.com/suhrmann/Anno-1800-Calculator/blob/master/.github/workflows/build.yml) CI all pushs and tags
 - [release-electron.yml](https://github.com/suhrmann/Anno-1800-Calculator/blob/master/.github/workflows/release-electron.yml) Build a tagged commit publish it on GitHub Releases using with [``electron-builder``](https://www.electron.build/configuration/publish).
 - [release-gh-pages.yml](https://github.com/suhrmann/Anno-1800-Calculator/blob/master/.github/workflows/release-gh-pages.yml) Build the website and publish it on GitHub Pages.
