# ThreeSixtyPlayer


:construction: This is very much a work in progress :construction:

### Overview

This is a 360 video viewer for iOS, implemented using [SceneKit](https://developer.apple.com/library/ios/documentation/SceneKit/Reference/SceneKit_Framework/).

SceneKit is probably the highest level iOS API that can be used for this sort of thing. I chose this approach to refamiliarize myself with the ins and outs of graphics programming. I plan to move on to a lower level implementation next.

Currently, the player supports:

- Spherical equirectangular monoscopic video
- Spherical equirectangular stereoscopic top/bottom video (note: much work still to do on stereo configuration) 

### Usage

#### To build the demo

Clone the repo: 

`git clone git@github.com:alfiehanssen/ThreeSixtyPlayer.git`

Prepare pods: 

`pod install && pod update`

Open the `ThreeSixtyPlayer.xcworkspace` and build the `Demo-iOS` target.

💥💥💥 

#### To consume as a Cocoapod

Add this to your podfile: 

`pod 'ThreeSixtyPlayer', '0.0.1'`

🌱🌱🌱 
