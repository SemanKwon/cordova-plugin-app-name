# Cordova AppName plugin

Reads the name of your app from the target build settings.

## Installation

### With cordova-cli

If you are using [cordova-cli](https://github.com/apache/cordova-cli), install
with:

    cordova plugin add https://github.com/whiteoctober/cordova-plugin-app-version.git

## Use from Javascript

If you are using jQuery, use:

    cordova.getAppName().then(function (name) {
        $('.version').text(name);
    });

If not:

    cordova.getAppName(function (name) {
        alert(name);
    });

## Credits

Written by [Nick Chistyakov](https://github.com/kolach) at
[AssuredLabor](http://assuredlabor.com/)

Code based on the following posts:

* [AppVersion](https://github.com/whiteoctober/cordova-plugin-app-version)
* [Android](http://stackoverflow.com/questions/17406793/phonegap-how-to-get-name-of-app-within-app)
