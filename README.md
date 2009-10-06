# Anatomy - An HTML Framework

Anatomy includes the basics of a modern HTML template so you don't have to start your HTML from scratch. It's a glue framework that brings together the best web dev frameworks into one spot.

  - XHTML 1.0 Transitional
  - Smart defaults including jQuery, 960 and Google Ajax API
  - Layout basics: header with nav bar, content and footer DIVs
  - CSS Frameworks (960, Blueprint, YUI, meyerweb reset, Dropdown Menu)
  - JS Frameworks (jQuery, Prototype + Scriptaculous, MooTools, Dojo, YUI, Ext)
  - Google Analytics tags
  - Text to be replaced is marked by "REPLACE"
  - Hosted at GitHub, of course!

## Getting Started

One way to use the Anatomy template is to simply use a copy as the basis of a new project. It's easy. Just clone the git repo, remove the git folder, and start your project. This is the basic idea of Anatomy. Just grab a copy and get going!

Here's how to use Anatomy to start a new project:

    $> git clone git://github.com/thrashr888/Anatomy.git
    $> rm -rf .git

Or, if you don’t have git, you can just download the latest source as a tarball:

    $> curl -L http://github.com/thrashr888/Anatomy/tarball/master -o Anatomy.tar.gz
    $> tar xzvf Anatomy.tar.gz

## CSS Frameworks Included

- [960 Grid System](http://960.gs) (Default)
- [Blueprint CSS Framework](http://blueprintcss.org)
- [YUI CSS Foundation](http://developer.yahoo.com/yui/base/)
- [meyerweb reset](http://meyerweb.com/eric/tools/css/reset/index.html)
- [Free CSS Drop-Down Menu Framework](http://www.lwis.net/free-css-drop-down-menu)
- A main.css file with empty selectors to get you started.

## JavaScript Frameworks Included

- [jQuery](http://jquery.com/) (Default)
- [jQueryUI](http://jqueryui.com/)
- [Prototype JS](http://prototypejs.org/)
- [Scriptaculous](http://script.aculo.us/)
- [MooTools](http://mootools.net/)
- [Dojo](http://www.dojotoolkit.org/)
- [SWFObject](http://code.google.com/p/swfobject/)
- [YUI](http://developer.yahoo.com/yui/)
- [Ext Core](http://www.extjs.com/products/extcore/)
- A main.js file with an empty document.onready handler to get you started.

## Layouts Included

### Basic
- index.html (Default)
- XHTML 1.0 Transitional
- 1 column
- header, nav, content, footer
- 960 and jQuery defaults

### HTML5 (*experimental work in progress*)
- html5.html
- HTML 5
- 1 column
- header, nav, content, footer
- 960 and jQuery defaults

### 2 Column
- 2_column.html
- XHTML 1.0 Transitional
- 2 column
- header, nav, content, sidebar, footer
- 960 and jQuery defaults

### 3 Column
- 3_column.html
- XHTML 1.0 Transitional
- 3 column
- header, nav, column 1, column 2, column 3, footer
- 960 and jQuery defaults

## TODO

- make sure all CSS and JS files are combined and compressed where possible
- add more layout styles (fluid/fixed, etc.)
- finish HTML5 version, use Modernizer? or 
- base.js file loader for each JS framework
- add icon sets?
- add custom framework for image buttons using sliding doors method from Dogster.com
- add in a 960 grid overlay option

## License & Credit

MIT License
Copyright (c) 2009 Paul Thrasher

Inspired by Federico Maggi's awesome [iWebSkel](http://iwebskel.com/). All JavaScript frameworks are hosted by [Google Ajax Libraries API](http://code.google.com/apis/ajaxlibs/).