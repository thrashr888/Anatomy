# Anatomy - An HTML Framework

Anatomy includes the basics of a modern HTML template.

  - XHTML 1.0 Transitional
  - Hosted at GitHub
  - Smart defaults including jQuery, 960 and Google Ajax API
  - Header, content and footer DIVs
  - CSS Dropdown Menu
  - CSS Frameworks (960, Blueprint, YUI)
  - JS Frameworks (jQuery, Prototype + Scriptaculous, MooTools, Dojo, YUI, Ext)
  - Google Analytics Tag
  - Text to be replaced is marked by "REPLACE"

## Getting Started

One way to use the Anatomy template is to simply use a copy as the basis of a new project. It's easy. Just clone the git repo, remove the git folder, and start a new one. This is the basic idea of Anatomy. Just grab a copy and get going!

Here's how to use Anatomy to start a new project:

    git clone git://github.com/thrashr888/Anatomy.git

    rm -rf .git


## CSS and JavaScript Frameworks Included

The most popular open source CSS and JS frameworks are provided for you. jQuery and 960 are setup by default but they're easy to swich by simply un-commenting the provided code and removing what's unneeded. The idea of this HTML framework is that the basics are taken care of so you don't have to start from scratch for every new web project.

### CSS Frameworks

At first I linked 960 and Blueprint to their respective repos on GitHub as submodules. I've decided against this to cut down on having too many unneeded files in the folder structure. I also combined 960's files to cut down on HTTP requests.

- [960 Grid System](http://960.gs) (Default)
- [Blueprint CSS Framework](http://blueprintcss.org)
- [YUI CSS Foundation](http://developer.yahoo.com/yui/base/)
- [Free CSS Drop-Down Menu Framework](http://www.lwis.net/free-css-drop-down-menu)

### JavaScript Frameworks

All JavaScript frameworks are hosted by [Google Ajax Libraries API](http://code.google.com/apis/ajaxlibs/).

- [jQuery](http://jquery.com/) (Default)
- [jQueryUI](http://jqueryui.com/)
- [Prototype JS](http://prototypejs.org/)
- [Scriptaculous](http://script.aculo.us/)
- [MooTools](http://mootools.net/)
- [Dojo](http://www.dojotoolkit.org/)
- [SWFObject](http://code.google.com/p/swfobject/)
- [YUI](http://developer.yahoo.com/yui/)
- [Ext Core](http://www.extjs.com/products/extcore/)


## TODO

- make sure all CSS and JS files are combined and compressed
- add a basic sidebar
- add a few basic layout styles (right sidebar, left sidebar, etc.)
- HTML5 version
- base.js file loader for each JS framework
- add icon sets?

# License

MIT License

Copyright (c) 2009 Paul Thrasher
