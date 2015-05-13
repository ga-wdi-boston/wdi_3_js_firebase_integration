![General Assembly Logo](http://i.imgur.com/ke8USTq.png)

# Integrating a JavaScript app into Firebase

## Objectives

By the end of this, students should be able to:

- Describe the JavaScript event model
- Describe a turn based Firebase app

## Instructions

### Fork and clone this repository, then

```bash
$ cd wdi_3_js_firebase_integration
$ npm install
$ bower install
```

### What we talk about when we talk about events

**[Philip Roberts: What the heck is the event loop anyway?](https://www.youtube.com/watch?v=8aGhZQkoFbQ)**

### Turn based game code walk through and demo

Walk through of the code and concepts in the turn based app

### Set up the turn based game example.

**[Firebase Hosting Quickstart](https://www.firebase.com/docs/hosting/quickstart.html)** _(Firebase documentation)_

First, edit *wdi_3_js_firebase_integration/app/js/index.js*, and replace `<Firebase App>` with a Firebase App URL, then

```bash
$ cd wdi_3_js_firebase_intro
$ firebase init
```

You'll be prompted for the Firebase app you want to be able to deploy.

## Lab

Break up into groups and ensure that each of you can run the example app locally using `$ grunt serve`.  Run the app from two different browsers (or two different browser sessions) and explore its behavior.  Use the Firebase **[Dashboard](https://www.firebase.com/account/)** to get to the apps data to see how it changes.

### Optional

- Deploy the app to Firebase
- Modify the app to store and retrieve more data used by the "game"
