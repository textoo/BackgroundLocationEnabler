BackgroundLocationEnabler
=========================

A simple Phonegap Plugin to enable background location update on iOS

IMPORTANT
=========================

There is a bug in cordova that makes this plugin crashing the app.

https://issues.apache.org/jira/browse/CB-5262

When modifying a key in .plist file with config-file tag in plugin.xml some white spaces are added in some other keys (NSMainNibFile and NSMainNibFile~ipad)

As Cordova & Phonegap teams do not fix this, it's needed to erase those white spaces manualy :/


