# template-ios
Clean project for iOs with CocoaPods and Swift

## Important

Open template-ios.xcworkspace, not *.xcproject through XCode. xcworkspace contains rules to build 
CocoaPods dependencies, they won't compile otherwise and your code wont work

## Preparations

It's good to have brew preconfigured. For this project it's unnecessary, but may come handy in the future.

### [CocoaPods](https://cocoapods.org/)

First you need to install rvm, to isolate ruby environments. Check instructions [here](https://rvm.io/).

```bash

curl -sSL https://get.rvm.io | bash -s stable

```

Then install ruby

```bash
rvm get stable
rvm list  # NOTE: to see available rubies 
rvm use ruby-X.X.X  # NOTE: to activate ruby environment
```

Then install CocoaPods

```bash
gem install cocoapods
```

To install dependencies use: 

```bash
pod install  # IMPORTANT: in the same directory with Podsfile
```

in the same directory with Podsfile

### Pods preinstalled:

[ModelRocket](https://github.com/ovenbits/ModelRocket) - JSON parsing library with nice declarative syntax.

[AlamoFire](http://cocoadocs.org/docsets/Alamofire/3.1.5/) - Networking for IOs written wih swift

## What I've done so far?

Just created an singlePage application, then run:

```bash
pod init && pod install
```

in apps folder.

Edited the Podsfile.
