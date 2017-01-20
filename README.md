# cordova-plugin-simple-android-url-intent-filter
A simple Cordova plugin for Android that redirects a website URL to an App.

This was designed to work with the Intel XDK, but should work for any Cordova App.

Include the plugin, and specify the variable DOMAIN_NAME as the top level domain you wish to direct to your app, and optionally the variable PATH_PREFIX.

The plugin will add an Android Intent Filter to the App that redirects the following URLs to your App.
 * http[s]://DOMAIN_NAME
 * http[s]://DOMAIN_NAME/
 * http[s]://DOMAIN_NAME/PATH_PREFIX*
 
The association occurs after the App has been run for the first time.
