# Portfolio Page

This is Bryan Yunis's portfolio page, his first attempt at creating a Vue App. 

## About
This page was originally created using Vue Router, however the entire site was composed on a single, scrollable page. The functionality still exists, though the routes array in the index.js file is currently empty. Links simply link to anchors contained in the page. 

It was laid out by having several components added to the root vue instance, and each component was contained within its own file (each was a single file component). This is absolutely overkill for such a simple page, but I wanted to experiement with the encapsulation provided by SFCs. I will probably refactor the site to have multiple components composed within the root page. 

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
