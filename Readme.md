## Monolith
Monlith is a framework to build iOS tweaks. This repository holds the Monolith framework as well as source code for example tweaks.

## Beta Status
### Please note that Monolith is currently in beta. There's debug logging that you'll see when you hook things, and the API may change.

## Features
* **Xcode Integration:** Projects are built straight from Xcode. No modification of Xcode's internal files are required, everything is native.
* **Simple:** Monolith takes the complication out of building tweaks.
* **Toolset:** More than just a tweak development framework, Monolith includes tools to conduct research on apps you're targetting.

## Built With Monolith - Open Source

* [Safari Inline Videos](//github.com/johncoates/SafariInlineVideos) Plays videos within the page, instead of going to full screen.
* [No Tab Labels](//github.com/johncoates/NoTabLabels) Removes tab labels from tab bars.

## Documentation

Documentation is being worked on, please check back soon. Watch this project on Github for update notifications.

## Community

- **Find a bug?** [Open an issue](https://github.com/johncoates/Monolith/issues/new). Try to be as specific as possible.
- **Have a feature request** [Open an issue](https://github.com/johncoates/Monolith/issues/new). Tell me why this feature would be useful, and why you and others would want it.

## Building Tweaks

Prerequisites:

* Building Monolith tweaks requires Xcode 6+
* Architectures supported are ARM-64, ARM, and x86-64
* Please note that building for the iOS Simulator requires that you build for the 5s simulator or later, as 32-bit x86 builds aren't supported
* The Monolith framework must be installed on your device. Either download [monolith.deb](http://getdelta.co/debs/monolith_0.01.deb) or install with Cydia by adding [getdelta.co](http://getdelta.co) to your sources and installing the Monolith Beta through that.

Here are the steps for building the starter project:

* Run **MonolithStaterProject/buildTweak**, and follow the prompts.
* In the future, you can build in Xcode by opening **Monolith Tweak.xcodeproj** and using the **Install Tweak** target.

## Other Things to Check Out

* [Xcode Template by @iMokhles](//github.com/iMokhles/Monolith-Xcode-Template)

## License

Monolith's license is found at [Monolith.framework/LICENSE.txt](//github.com/johncoates/Monolith/blob/master/MonolithStarterProject/Monolith.framework/LICENSE.txt). Basically you can use Monolith for free as long as your product is free. If you're selling a tweak, then 15% of your sales go to fund the development of Monolith.

## Changelog
### 0.10 - March 30th, 2016
* Building a Monolith tweak is much simpler now.

### 0.1 - 2015
* First release
