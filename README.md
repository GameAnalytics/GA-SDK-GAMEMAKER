GA-SDK-GAMEMAKER
================

GameAnalytics GameMaker SDK for Gamaker Studio v1.4+ and v2

Documentation can be found [here](https://gameanalytics.com/docs/gamemaker-sdk).

If you have any issues or feedback regarding the SDK, please contact our friendly support team [here](https://gameanalytics.com/contact).

Supported platforms:

* Mac OS X
* Winddows
* Linux
* UWP
* Android
* iOS
* HTML5


> :information_source:   
> **Build size:**   
> Note that download size differ from the actual build size.   
>   
> **Android:**   
> The SDK build size in a native Android app is only around **49Kb** and the dependecies take up to **820Kb** depending if your app already uses some of the same dependencies.   
>   
> **iOS:**   
> The SDK build size in a native iOS app is only around **242Kb** (armv7) / **259Kb** (armv8).

Changelog
---------
<!--(CHANGELOG_TOP)-->
**3.0.8**
* fixed progression events with scores (android)

**3.0.7**
* cryptojs bug fix (html5)

**3.0.6**
* removed facebook, gender and birthyear methods

**3.0.5**
* A/B testing fixes

**3.0.4**
* fixed getRemoteConfigsValueAsString bug

**3.0.3**
* remote configs fixes

**3.0.2**
* fixed events bug (ios, html5)

**3.0.1**
* corrected naming of function

**3.0.0**
* Remote Config calls have been updated and the old calls have deprecated. Please see GA documentation for the new SDK calls and migration guide
* A/B testing support added

**2.1.4**
* fixed android bugs

**2.1.3**
* added check if log files and database can't be created

**2.1.2**
* fixed hanging background thread when closing application for desktop platforms

**2.1.1**
* added ga_onQuit method

**2.1.0**
* added enable/disable event submission function

**2.0.4**
* fixed business event validation

**2.0.3**
* ios compile fixes

**2.0.2**
* compile eror fixes for android and ios

**2.0.1**
* fixed thread hanging on shutdown for desktop platforms

**2.0.0**
* added command center functionality

**1.1.9**
* added custom dimensions to design and error events

**1.1.8**
* fixed session length bug
* fixed not allowing to add events when session is not started

**1.1.7**
* progression event fix for ios (ios)

**1.1.6**
* missing to update Gamemaker Studio 1.4 package

**1.1.5**
* bug fixes import crash for Gamemaker Studio 2

**1.1.1**
* bug fixes for building for various platforms

**1.1.0**
* added Gamemaker Studio 2 support
* fixed bug for certain events on desktop platforms not being called

**1.0.5**
* fixed html5 wrapper to use correct namespace (html5)

**1.0.4**
* bug fix for end session when using manual session handling

**1.0.3**
* bug fix for sending events straight after initializing sdk (html5)

**1.0.2**
* session length precision improvement

**1.0.1**
* added missing .gml files

**1.0.0**
* public release
