# 🚀 Cordova App Version Plugin (Maintenance Release)

This is a **maintained fork** of the original [cordova-plugin-app-version](https://github.com/sampart/cordova-plugin-app-version).

### ⚠️ Why this fork?
The original package has been unmaintained for a long time. 

The primary reason for this release is simple: **several critical bug fixes have already been pushed to various GitHub forks by the community, but they were never published to the official npm registry**. 

I am not claiming to provide major feature updates or specific support for the latest OS versions. I have simply consolidated existing bug fixes from GitHub and published them to npm so they can be easily used in production projects without manual installation.

## ✨ Key Improvements

*   **npm Release of Existing Fixes**: Published stable bug fixes that were sitting in GitHub repositories but unavailable via npm.
*   **Production Readiness**: Ensures that you can install a version with known bugs resolved via a standard `npm install` or `cordova plugin add` command.
*   **Full Compatibility**: The API remains **100% compatible** with the original plugin. No code changes are required in your project.

## Installation

### With cordova-cli

To avoid version conflicts, please remove the original unmaintained package first:

    cordova plugin remove cordova-plugin-app-version

Then, install this version:

    cordova plugin add @sishin/cordova-plugin-app-version


## Credits

Written by [Robert (Jamie) Munro](http://twitter.com/rjmunro) at
[White October](http://whiteoctober.co.uk/)

Bug fixes and improvements integrated from sampart's fork.

This version is maintained by sishin1209.

## Legal & License

This project is a fork of the original [cordova-plugin-app-version](https://github.com/sampart/cordova-plugin-app-version).

Original code is licensed under the MIT License.

Bug fixes were integrated from sampart's repository.

All original copyright notices and license terms are preserved in the LICENSE file.