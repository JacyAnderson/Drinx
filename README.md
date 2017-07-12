#  Drinx
[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat)](http://standardjs.com/)

A happy hour finding app to help you quench your thirst during the happiest time of day.

* Standard compliant React Native App Utilizing [Ignite](https://github.com/infinitered/ignite)

## Potential Features
* Google Maps API integration
* Show timers for start/end times of happy hours
* Show Happy Hour location on map
* Easy access to Happy Hour Menus
* Happy Hours can be filtered by distance
* Establishments will be able to set up accounts to update their Happy Hour menus (Pending approval of business)
* Uber/Lyft integration for safe traveling
* Pub Crawl Coordination: Choose your times, and choose your pubs! Share the crawl with your friends (invite via code?)
* Bar search feature
* Facebook/Social Integration
* User Profiles/Favorite Spots/Crawls
* Rate Pubs/Happy Hours
* Filter by bar type

## Tech Stack
* React Native
* Ignite
* Sass
* HTML
* Axios (API Requests)
* Node
* Firebase
* Yarn

## :arrow_up: How to Setup

**Step 1:** git clone this repo:

**Step 2:** cd to the cloned repo:

**Step 3:** Install the Application with `yarn` or `npm i`


## :arrow_forward: How to Run App

1. cd to the repo
2. Run Build for either OS
  * for iOS
    * run `react-native run-ios`
  * for Android
    * Run Genymotion
    * run `react-native run-android`

## :no_entry_sign: Standard Compliant

[![js-standard-style](https://cdn.rawgit.com/feross/standard/master/badge.svg)](https://github.com/feross/standard)
This project adheres to Standard.  Our CI enforces this, so we suggest you enable linting to keep your project compliant during development.

**To Lint on Commit**

This is implemented using [husky](https://github.com/typicode/husky). There is no additional setup needed.

**Bypass Lint**

If you have to bypass lint for a special commit that you will come back and clean (pushing something to a branch etc.) then you can bypass git hooks with adding `--no-verify` to your commit command.

**Understanding Linting Errors**

The linting rules are from JS Standard and React-Standard.  [Regular JS errors can be found with descriptions here](http://eslint.org/docs/rules/), while [React errors and descriptions can be found here](https://github.com/yannickcr/eslint-plugin-react).

## :closed_lock_with_key: Secrets

This project uses [react-native-config](https://github.com/luggit/react-native-config) to expose config variables to your javascript code in React Native. You can store API keys
and other sensitive information in a `.env` file:

```
API_URL=https://myapi.com
GOOGLE_MAPS_API_KEY=abcdefgh
```

and access them from React Native like so:

```
import Secrets from 'react-native-config'

Secrets.API_URL  // 'https://myapi.com'
Secrets.GOOGLE_MAPS_API_KEY  // 'abcdefgh'
```

The `.env` file is ignored by git keeping those secrets out of your repo.

