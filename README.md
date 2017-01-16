# reactNativeTodoDemo

It's a test application made by tutorial (from egghead.io) to try React Native

All info is from [Getting started guide](http://facebook.github.io/react-native/releases/0.40/docs/getting-started.html)

## Installing Dependencies
You will need Node.js, Watchman, the React Native command line interface, and Xcode.

### Node, Watchman
We recommend installing Node and Watchman using Homebrew. Run the following commands in a Terminal after installing Homebrew:

```
brew install node
brew install watchman
```

### The React Native CLI
Node.js comes with npm, which lets you install the React Native command line interface.

Run the following command in a Terminal:

```
npm install -g react-native-cli
```

If you get an error like Cannot find module 'npmlog', try installing npm directly:

```
curl -0 -L http://npmjs.org/install.sh | sudo sh
```

### Xcode
The easiest way to install Xcode is via the Mac App Store. Installing Xcode will also install the iOS Simulator and all the necessary tools to build your iOS app.

## Testing your React Native Installation
Use the React Native command line interface to generate a new React Native project called "AwesomeProject", then run react-native run-ios inside the newly created folder.

```
react-native init AwesomeProject
cd AwesomeProject
react-native run-ios
```

You should see your new app running in the iOS Simulator shortly.

`react-native run-ios` is just one way to run your app. You can also run it directly from within Xcode or Nuclide.

### Modifying your app
Now that you have successfully run the app, let's modify it.

Open `index.ios.js` in your text editor of choice and edit some lines.
Hit `Command⌘ + R` in your iOS Simulator to reload the app and see your change!

### That's it!
