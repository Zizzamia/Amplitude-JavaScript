Amplitude-JavaScript
====================

A JavaScript SDK for tracking events and revenue to [Amplitude](https://www.amplitude.com).

# Setup #
Please see our [installation guide](https://amplitude.zendesk.com/hc/en-us/articles/115001361248-JavaScript-SDK-Installation) for instructions on installing and using our JavaScript SDK.

# Latest Version #
[![Circle CI](https://circleci.com/gh/amplitude/Amplitude-JavaScript.svg?style=shield&circle-token=80de0dbb7632b2db13f76ccb20a79bbdfc50c215)](https://circleci.com/gh/amplitude/Amplitude-JavaScript)
[![npm version](https://badge.fury.io/js/amplitude-js.svg)](https://badge.fury.io/js/amplitude-js)
[![Bower version](https://badge.fury.io/bo/amplitude-js.svg)](https://badge.fury.io/bo/amplitude-js)

[5.6.0 - Released on October 21, 2019](https://github.com/amplitude/Amplitude-JavaScript/releases/latest)


# JavaScript SDK Reference #
See our [JavaScript SDK Reference](https://amplitude.zendesk.com/hc/en-us/articles/115002889587-JavaScript-SDK-Reference) for a list and description of all available SDK methods.

# Demo Pages #
* A [demo page](https://github.com/amplitude/Amplitude-JavaScript/blob/master/test/browser/amplitudejs.html) showing a simple integration on a web page.
* A [demo page](https://github.com/amplitude/Amplitude-JavaScript/blob/master/test/browser/amplitudejs-requirejs.html) showing an integration using RequireJS.
* A [demo page](https://github.com/amplitude/GTM-Web-Demo) demonstrating a potential integration with Google Tag Manager.

# Changelog #
Click [here](https://github.com/amplitude/Amplitude-JavaScript/blob/master/CHANGELOG.md) to view the JavaScript SDK Changelog.

# React Native #

This library now supports react-native. It has two dependencies on react-native modules you will have to install yourself:

* [react-native-device-info](https://www.npmjs.com/package/react-native-device-info)
* [@react-native-community/async-storage](https://www.npmjs.com/package/@react-native-community/async-storage)

# Upgrading Major Versions and Breaking Changes #

## 5.0

We stopped committing the generated amplitude.min.js and amplitude.js files to
the repository. This should only affect you if you load amplitude via github.
You should use `npm` or `yarn` instead.

We dropped our custom symbian and blackberry user agent parsing to simply match
what the ua-parser-js library does.

## 4.0

The library now defaults to sending requests to https://api.amplitude.com
instead of //api.amplitude.com. This should only affect you if your site does
not use https and you use a Content Security Policy.


# Questions? #
If you have questions about using or installing our JavaScript SDK, you can send an email to [Amplitude Support](mailto:platform@amplitude.com).

# License #
```text
Amplitude

The MIT License (MIT)

Copyright (c) 2014 Amplitude

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```
