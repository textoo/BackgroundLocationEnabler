BackgroundLocationEnabler
=========================

A simple Phonegap Plugin to enable background location update on iOS

Has to be used in conjunction with :

    geolocation.watchPosition()


Unlimited background location
-------------------------
If your device is not moving, iOS will suspend background location after 10 minutes.

To go beyond this limit, use the following method :

    BackgroundLocationEnabler.enableUnlimited()
    
note: Since Phonegap 3.1.0 it seems that the use of this method is not needed anymore.    
    


IMPORTANT
=========================

There is a bug in cordova that makes this plugin crashing the app.

https://issues.apache.org/jira/browse/CB-5262

When modifying a key in .plist file with config-file tag in plugin.xml some white spaces are added in some other keys (NSMainNibFile and NSMainNibFile~ipad)

As Cordova & Phonegap teams do not fix this, it's needed to erase those white spaces manualy :/


