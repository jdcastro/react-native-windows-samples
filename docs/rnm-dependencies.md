---
id: rnm-dependencies
title: System Requirements
---

You can run React Native for macOS apps on Mac devices with versions [Mojave (10.14.6)](https://support.apple.com/en-us/HT209149#macos10146) or newer.

The development dependencies for React Native for macOS are identical to the development dependencies for React Native for iOS. You can follow the steps at [Setting up the development environment](https://reactnative.dev/docs/environment-setup) in the **"React Native CLI Quickstart"** section, or follow the paraphrased steps below:

### macOS Development Dependencies
- A Mac device is required to build projects with native code for macOS.
- Install [Xcode](https://apps.apple.com/us/app/xcode/id497799835?mt=12) version 11.3.1 or newer.
- Ensure to install Xcode Command Line Tools. Open Xcode, then choose "Preferences..." from the Xcode menu. Go to the Locations panel and install the tools by selecting the most recent version in the Command Line Tools dropdown.
- Install [CocoaPods](https://guides.cocoapods.org/using/getting-started.html)
   ```bash
   sudo gem install cocoapods
   ```

### React Native Development Dependencies
- Install the [standard React Native dependencies](https://reactnative.dev/docs/getting-started#node-python2-jdk)
- Install [Node.js](https://nodejs.org) version 12 LTS or newer via [HomeBrew](https://brew.sh/)
   ```bash
   brew install node
   ```
- Install [Watchman](https://facebook.github.io/watchman)
   ``` bash
   brew install watchman
   ```
