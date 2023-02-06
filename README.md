![Screenshot 2023-02-06 184905](https://user-images.githubusercontent.com/93249038/216981955-0446ddee-409d-4379-b433-07d5506c9728.png)




![Screenshot_2023-02-06-18-44-50-64_7441a990aaa174fbb591de199bcb07fe](https://user-images.githubusercontent.com/93249038/216984030-6355dee5-2827-44a7-b4d6-a9dfad9dc160.gif)

React NativeScript is A React renderer for NativeScript, allowing you to write a NativeScript app using the familiar React style.

I'm always hanging out in the #react chat of the NativeScript Slack if you'd like to talk about this project.

## Setup
# Make sure that you have `tns` (the NativeScript CLI) installed:
#   https://docs.nativescript.org/start/quick-setup

tns create myApp --react

cd myApp

npm install

# The Preview and Playground apps are awaiting an update from

# RNS v0 to v1, so the `tns preview` workflow isn't supported

# yet. We're working on it. – 18th July 2020

# tns preview

# or

tns run ios

# or

tns run android

## Documentation
React NativeScript docs
NativeScript docs


## Example real-world app
See the Apps showcase in the docs to see various apps built with React NativeScript.

One example is my rpstrackerrns issue-tracking example app, which demonstrates how you can make fully native, professional-looking UIs with RNS:

## Features		
1) Login Page

2) Backlog Page

3) Detail Page

## Plugins
Although NativeScript lets you write native code inline as JavaScript, you can also write modules purely using native code (e.g. Objective-C and Java), and access the code directly in NativeScript via JavaScript. When a common, cross-platform JavaScript API is provided for such modules, it is called a "plugin", and can be thought of as equivalent to a React Native "native module". NativeScript has a rich ecosystem of these plugins – see the NativeScript Marketplace.

React NativeScript uses the same plugins API as NativeScript Vue and NativeScript Angular, so all those plugins should be compatible (although generally needing to be consumed with any type, as most plugins are only typed for NativeScript Core). Instructions on how to integrate plugins, and provide typings for React, can be found in the React NativeScript plugins documentation.

## Why not just use React Native?

# Is it production-ready?

It's based on React, NativeScript Core, and NativeScript Vue, which are each individually production-ready. Make of that what you will.
