# cordova-plugin-swift-support

![swift-128x128](https://cloud.githubusercontent.com/assets/579922/15999501/79196b48-3146-11e6-836e-061a7ef53571.png)

This [Cordova plugin](https://www.npmjs.com/package/cordova-plugin-add-swift-support) adds Swift 3 support to your iOS project.

## Installation

You can add this plugin directly to your project:

`cordova plugin add cordova-plugin-swift-support --save`

Or add it as a dependency into your own plugin:

`<dependency id="cordova-plugin-swift-support" version="1.3.2"/>`

If needed, add a prefixed `Bridging-Header` file in your plugin in order to import frameworks (`MyPlugin-Bridging-Header.h`, for instance).
As an example you can have a look at this [plugin](https://github.com/akofman/cordova-plugin-permissionScope).

If the `cordova-plugin-swift-support` plugin is already installed to your project, then you can add your own Swift plugin as usual, its prefixed `Bridging-Header` will be automatically found and merged.

## License

Developed and originally licensed under the Apache-2.0 license by [Alexis Kofman](http://twitter.com/alexiskofman). This fork is maintained by [Jason Dreyzehner](http://twitter.com/bitjson) under the MIT license.
