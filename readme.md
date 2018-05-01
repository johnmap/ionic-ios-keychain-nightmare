Affected platform: iOS 11.3

Issue: keychain/login form autocomplete bar appears when it shouldn't. Specifically,
it appears when focusing any text input, if a login form or password input has previously
been focused in the same session.

Repro: build this app, run on device or sim (iOS 11.3), follow steps in app

#```$ionic info``` output

cli packages: (/usr/local/lib/node_modules)

    @ionic/cli-utils  : 1.19.2
    ionic (Ionic CLI) : 3.20.0

global packages:

    cordova (Cordova CLI) : 8.0.0 

local packages:

    @ionic/app-scripts : 3.1.9
    Cordova Platforms  : ios 4.5.4
    Ionic Framework    : ionic-angular 3.9.2

System:

    ios-deploy : 1.9.2 
    Node       : v9.11.1
    npm        : 5.6.0 
    OS         : macOS High Sierra
    Xcode      : Xcode 9.3 Build version 9E145 

Environment Variables:

    ANDROID_HOME : not set

Misc:

    backend : pro
