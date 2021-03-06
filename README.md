<p align="center">
<img src="./pokemodal.png" width="400" style="text-align:center" />
</p>

## Simple modal view inspired by Pokémon GO

[![CI Status](http://img.shields.io/travis/Leonardo Borges Avelino/PokeModal.svg?style=flat)](https://travis-ci.org/Leonardo Borges Avelino/PokeModal)
[![Version](https://img.shields.io/cocoapods/v/PokeModal.svg?style=flat)](http://cocoapods.org/pods/PokeModal)
[![License](https://img.shields.io/cocoapods/l/PokeModal.svg?style=flat)](http://cocoapods.org/pods/PokeModal)
[![Platform](https://img.shields.io/cocoapods/p/PokeModal.svg?style=flat)](http://cocoapods.org/pods/PokeModal)

## Screenshots
<img src="./Screenshots/screenshots.png" width="600" />

## Example

To run the example project, clone the repo, and run `pod install` from the Example directory first.

## Requirements

- iOS 8.0+ / Mac OS X 10.9+
- Xcode 6.3

## Installation

PokeModal is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
source 'https://github.com/CocoaPods/Specs.git'
platform :ios, '8.0'
use_frameworks!

pod 'PokeModal'
```

Then, run the following command:

```bash
$ pod install
```
## Usage

Inside a UIViewController subclass:

```swift
let modal = PokeModal(view: self.view)
modal!.titleText = "HI ASH"
modal!.contentText = "I wanna be the very best. Like no one ever was. To catch them is my real test. To train them is my cause"
```

## Author

Leonardo Borges Avelino, lborgav@gmail.com

## License

PokeModal is available under the MIT license. See the LICENSE file for more info.
