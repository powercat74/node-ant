node-ant
===

Introduction
------------
Node.js implementation of ANT+ protocol. See [http://www.thisisant.com/](http://www.thisisant.com/) for more info regarding ANT+.

This is a node module for connecting to ANT+ capable devices through a USB ANT stick.

This project was formed out of a need to communicate with ANT+ devices in real time while relaying data over web sockets.  Node.js allowed a reduction of required technologies to accomplish this goal.  Since initiating this project, other combinations of Node.js and ANT+ have presented themselves. For that reason I decided to open this project up.


Requirements
-------
Install libusb

```
brew install libusb
```

Install
-------
npm install node-ant


Documentation
-------------
Currently there is very little documentation.  What isDocumentation will be created as the project is expanded upon.


License
-------
Released under the MIT/X11 license. See LICENSE for details.


Credits
-------
Some snippets and inspiration was derived from the #python-ant library developed by @mvillalba.  This library served as a starting point as it serves a similar purpose.