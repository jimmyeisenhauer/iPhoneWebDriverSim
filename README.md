iPhoneWebDriverSim
=============

Selenium2 iPhone webdriver wrapped in iPhone simulator app using Simlaunch

Launches iWebDriver app in iPhone simulator.

Command Line
=============
open app
```
open iPhoneWebDriverSim.app/
```
close app
```
osascript -e 'tell app "iPhone Simulator" to quit'
```

Requirements
=============
Must have xcode installed with 5.1

Hooking it up to a Selenium Grid2
=============
Launch the app. Go to the iOS Settings app. Near the bottom there will be an "iWebDriver" settings area. Going into that you should see settings for Server port and Grid Host/Port. Fill in the details as desired.

Resources
=============
[Selenium WebDriver](https://github.com/Selenium2/Selenium2)

[Selenium iPhone Driver](http://code.google.com/p/selenium/wiki/IPhoneDriver)

[Simlaunch](https://github.com/landonf/simlaunch)