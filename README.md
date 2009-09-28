# Getting Started with a new website

One way to use the Anatomy template is to simply use a copy as the basis of a new project. It's easy. Just clone the git repo, remove the git folder, and start a new one. This is the basic idea of Anatomy. Just grab a copy and get going!

    git clone git://github.com/thrashr888/Anatomy.git

    git submodule init

    git submodule pull

    rm -rf .git

    rm .gitmodules

    git init

    git add *

    git commit -m "initial checkin"


# Included CSS and JS libraries

I've included the most popular open source CSS and JS libraries already. jQuery and 960 are the defaults but they're easy to swich by simply uncommenting the provided code and removing what's unneeded. The idea of this HTML Framework is that the basics are taken care of so you don't have to start from scratch for every new project.

## CSS Frameworks Provided

- 960 Grid system, plus reset and text [http://960.gs] (Default)
- Blueprint CSS Framework [http://blueprintcss.org]
- YUI CSS Foundation [http://developer.yahoo.com/yui/base/]
- Free CSS Drop-Down Menu Framework [http://www.lwis.net/free-css-drop-down-menu]

## JS Frameworks Provided

The JS libraries that I've added are hosted by Google Ajax Libraries API [http://code.google.com/apis/ajaxlibs/]. These include:

- jQuery [http://jquery.com/] (Default)
- jQueryUI [http://jqueryui.com/]
- Prototype JS [http://prototypejs.org/]
- Scriptaculous [http://script.aculo.us/]
- Mootools [http://mootools.net/]
- Dojo [http://www.dojotoolkit.org/]
- SWFObject [http://code.google.com/p/swfobject/]
- YUI [http://developer.yahoo.com/yui/]
- Ext Core [http://www.extjs.com/products/extcore/]
