# node-on-ios

**This project needs an iOS developer to help out!**. Open an issue if you're interested in contributing.

Here's the plan:

We want to match the features of `node-on-android`:

- Compile Node as a C++ shared library
- Load the shared library in an iOS Application
- Allow the application to run user supplied node code
- Create a webview and allow the user code to require the special module `require('node-on-mobile')` which allows them to control the webview over a simple IPC bridge (e.g. window.loadURL)
- Provide a simple CLI workflow to build and sign a packaged application

Open Questions:

- Can the ["Node.js meets iOS"](https://github.com/janeasystems/node-mobile-react-demo) framework be used here? ([issue](https://github.com/node-on-mobile/node-on-ios/issues/1))
- Can the above framework be compiled as a static library and loaded in Objective-C? ([issue](https://github.com/node-on-mobile/node-on-ios/issues/2))
- Can the packaging be done using only CLI tools? ([issue](https://github.com/node-on-mobile/node-on-ios/issues/3))
