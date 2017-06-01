# Welcome to Jade's GitHub Pages portal

This repo uses Github's built in pages (jekyll) feature to build a visual portal for all the other github projects.

Check it out at [https://jadef.github.io/](https://jadef.github.io/)

## Local Development

[Github pages setup](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/) for a local jekyll build.

Once in place `bundle exec jekyll serve` will start it up and the scroll back should include a line similar to `Server address: http://127.0.0.1:4000/` to view in your browser.

### Content

the primary page uses the root level `index.html` file as the content.

Individual projects have their own unique html file in the `projects` folder.

Any associated assets can be stored in the `assets` folder.

### Theme

Global aspects use jekyll templating found in the `_includes` and `_layouts` folders.

Based on the premade `architect` jekyll theme, custom style over rides can be found in the `_sass` folder, which are actually gathered through the `assets/css/styles.scss` build file.

## Deployment

Thanks to github's integrated aspects, deployment is a no brainer. Push to the master branch, and it's live (after a little behind the scenes compilation by jekyll).