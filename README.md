# BlinkingLabel

[![Version](https://img.shields.io/cocoapods/v/BlinkingLabel.svg?style=flat)](http://cocoapods.org/pods/BlinkingLabel)
[![License](https://img.shields.io/cocoapods/l/BlinkingLabel.svg?style=flat)](http://cocoapods.org/pods/BlinkingLabel)
[![Platform](https://img.shields.io/cocoapods/p/BlinkingLabel.svg?style=flat)](http://cocoapods.org/pods/BlinkingLabel)

## Overview

BlinkingLabel is a subclass of UILabel, written in Swift, that enables the UILabel to blink.

![](blinkinglabel.gif?raw=true "Blinking Label screenshot")

## Requirements
* ARC
* iOS8

## Installation with CocoaPods

BlinkingLabel is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod "BlinkingLabel"
```

## Usage

```Swift
import BlinkingLabel

let labelThatBlinks = BlinkingLabel()
labelThatBlinks.startBlinking()
labelThatBlinks.stopBlinking()

```

## Example Project

An example project is included with this repo.  To run the example project, clone the repo, and run `pod install` from the Example directory first.

## Author

Andy Obusek

## License

BlinkingLabel is available under the MIT license. See the LICENSE file for more info.
