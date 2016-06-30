Appium iOS Inspector
====================

The tool for iOS elements location. It is based on the original source of [Selendroid Inspector](https://github.com/selendroid/selendroid)
[Here](http://appium.io) you can find more information about Appium automation tool.

Usage
-----

Execute your iOS test using Appium (by default it is expected to listen on localhost:4723) and set a breakpoint where you want to investigate UI tree. Open/refresh iOS Inspector.html web page in your favourite web browser, wait for a while until the data is loaded and you are free to go. The inspector currently supports showing of element attributes, elements location by XPath and, naturally, two-way visual elements location using a screenshot and UI tree.
Note: The Accessibility Id property can be presented as @name attribute in XPath expessions.

Customizations
-------------

Change the default Appium server address if needed inside inspector.js, APPIUM_ROOT constant.

License
-----------
[The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0)