# cordova-plugin-audio-background-mode

# Cordova/Phonegap Audio background mode plugin

for iOS, by [Phuong To](https://github.com/phuongwd)

1. [Description](https://github.com/phuongwd/cordova-plugin-audio-background-mode#1-description)
2. [Installation](https://github.com/phuongwd/cordova-plugin-audio-background-mode#2-installation)
    2.1 [Automatically](https://github.com/phuongwd/cordova-plugin-audio-background-mode#automatically)
    2.2 [Manually](https://github.com/phuongwd/cordova-plugin-audio-background-mode#manually)
3. [License](https://github.com/phuongwd/cordova-plugin-audio-background-mode#4-license)

## 1. Description

The app is able to run in background through audio mode

## 2. Installation

### Automatically
Latest release on npm:
```
$ cordova plugin add cordova-plugin-audio-background-mode
```

Bleeding edge, from github:
```
$ cordova plugin add https://github.com/phuongwd/cordova-plugin-audio-background-mode.git
```
Remove:
```
$ cordova plugin rm cordova-plugin-audio-background-mode
or
$ cordova plugin rm https://github.com/phuongwd/cordova-plugin-audio-background-mode.git
```

### Manually

#### iOS

1\. Add the following xml to your `*-Info.plist`:
```xml
<!-- for iOS -->
<key>UIBackgroundModes</key>
<array>
  <string>audio</string>
</array>
```

## 3. License

[The MIT License (MIT)](http://www.opensource.org/licenses/mit-license.html)

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