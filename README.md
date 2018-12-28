Appium iOS Inspector
====================

[![Inspector Screenshot](https://raw.githubusercontent.com/mykola-mokhnach/Appium-iOS-Inspector/master/screenshot.png)](#Inspector Screenshot)

The tool for iOS elements location. It is based on the original source of [Selendroid Inspector](https://github.com/selendroid/selendroid)

[Here](http://appium.io) you can find more information about Appium automation tool.

Usage
-----

Execute your iOS test using [Appium](http://appium.io) (by default it is expected to listen on http://localhost:4723) and set a breakpoint where you want to investigate the UI tree. Open/refresh iOS Inspector.html web page in your favourite web browser, wait for a while until the data is loaded and you are ready to go. The inspector currently supports showing of element attributes, element location by XPath, dynamic setting of retina scale factor and, naturally, two-way visual elements location using a screenshot and the UI tree.

Note: The Accessibility Id property can be presented as @name attribute in XPath expessions.

Customizations
--------------

Change the default Appium server address using query parameter `port` e.g.
        ```<path to Appium-iOS-Inspector>/iOS Inspector.html?host=127.0.0.1&port=1234```

Known Issues
------------

If the inspector fails load the page source even though Appium session is running on localhost and you observe a CORS error in Chrome console then it might happen because of a known [bug](https://bugs.chromium.org/p/chromium/issues/detail?id=67743). Visit the issue link to get more information on possible workarounds.

License
-------

[The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0)
