# [AllYourTexts](http://allyourtexts.com) Source Code

This is the source code of AllYourTexts.com, a website dedicated to providing a knowledgebase for the AllYourTexts application.  The website for the application is built using [Jekyll](http://jekyllrb.com) and utilizing [GitHub Pages](https://pages.github.com/) to publish and host the site.

Current Build Status is: [![Build Status](https://secure.travis-ci.org/AllYourTexts/AllYourTexts.github.io.png?branch=master)](http://travis-ci.org/AllYourTexts/AllYourTexts.github.io)

## Local Development

1. Install dependencies `bundle install`
2. Run Jekyll server to preview in development mode `jekyll serve`.  To regenerate the site automatically use the watcher option `-w`.

## Site Structure

#### _includes 
Contains several partials that are common to several generated pages.

#### _layouts 
Contains the templates that are used to generate the commonality of the pages (default is the main one that all the pages use.

#### _pages 
Contains all the individual pages of the site.  The numbering system used for the individual pages corresponds to the main navigational menu and shows them in order from smallest to largest if they have the `menu-item:true` frontmatter field set. 

#### css 
Contains the css for the project.

#### download
Contains the executable that can be downloaded and installed by an end user.

#### images 
Contains all the image files broken out by month.

#### js
Contains all of the javascript files used by the website.
