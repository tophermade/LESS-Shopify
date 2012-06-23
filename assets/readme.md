# [SPR-LESS](http://sprresponsive.com/less-css-kit/)

SPR-LESS is basic framework using [LESSCSS](http://lesscss.org) for writing CSS faster and more effeciently, especially for responsive sites.

The framework designed to provide nothing you don't need, and only the bare essentials to get you building a responsive layout more quaickly and easier. 

**important** SPR-LESS uses the JS implementation of LESS. If you are using Chrome & you are developing on a machine without localhost, you will need to diable web security in Chrome by adding --disable-web-security to the launcher.


## SPR-LESS is not
* a markup framework
* interested in controlling your markup with nonsemantic classes (gutter, col12, etc)
* ever going to suggest how you write your markup

## SPR-LESS is
* nothing without the really awesome [LESSCSS](http://lesscss.org) 
* designed to let you start writing CSS faster with LESS and an optomized file strcutre
* complete with a number of handy mixins and shortcuts
* expective of 3 major stops or breakpoints for responsiveness; phone, tablet, desk/laptop

### SPR-LESS is licensed under MIT & GPL v2 - take your pick


### Getting started

1. Download or clone on github
2. Begin styling. 

### Mixins & shortcuts
Mixins are store in /less/mixins.less, shorcuts in /less/shortcuts.less
Mix them in by including their classname, for example .round; . You may extend the default values of many mixins, for example .round(5px 0 5px 0);
Documentation for the mixins is coming, but looking over them should give you a good handle on their usage.


### Styling
As noted, SPR-LESS expects 3 major breakpoints. Begin styling in the LESS file of the device class you are first targeting, and then build up.
Queries are currently seperating all the styles from each breakpoint/device class. To flow up from phone to tablet & desktop, for example, simply remove the media query from phone.less, and override styles as needed.

