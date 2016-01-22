# template-ios
Clean project for iOs with cocoapods

## Important

Open template-ios.xcworkspace through XCode

## Preparations

### Cocoapods

First you need to install rvm, to isolate ruby environments. Check instructions [here](https://rvm.io/).

```bash

curl -sSL https://get.rvm.io | bash -s stable

```

Then install ruby

```bash
rvm get stable
rvm list # to see available rubies 
rvm use ruby-X.X.X # to activate ruby environment
```

Then install cocoapods

``` bash
gem install ruby
```

To install dependencies use: 

``` bash
pod install
```

in the same directory with Podsfile

## CocoaPods preconfigured:

[ModelRocket](https://github.com/ovenbits/ModelRocket) - JSON parsing library with nice declarative syntax.
[AlamoFire](http://cocoadocs.org/docsets/Alamofire/3.1.5/) - Networking for IOs written wih swift
