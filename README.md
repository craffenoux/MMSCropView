# MMSCropView

[![CI Status](http://img.shields.io/travis/miller-ms/MMSCropView.svg?style=flat)](https://travis-ci.org/miller-ms/MMSCropView)
[![Version](https://img.shields.io/cocoapods/v/MMSCropView.svg?style=flat)](http://cocoapods.org/pods/MMSCropView)
[![License](https://img.shields.io/cocoapods/l/MMSCropView.svg?style=flat)](http://cocoapods.org/pods/MMSCropView)
[![Platform](https://img.shields.io/cocoapods/p/MMSCropView.svg?style=flat)](http://cocoapods.org/pods/MMSCropView)
[![Readme Score](http://readme-score-api.herokuapp.com/score.svg?url=miller-ms/MMSCropView)](http://clayallsopp.github.io/readme-score?url=miller-ms/MMSCropView)

This class provides the feature to draw a rectangle over an image by dragging a finger over it, move it, and extract the covered region into a UIImage.

<p align="center">
<img src="screenshot.png" alt="Sample">
</p>

A simple image cropper.

## Usage

To run the example project, clone the repo, and run `pod install` from the Example directory first.

In your storyboard select the custom class MMSCropImageView for the Image View widget.

Import the class header.

``` objective-c
#import <MMSCropImageView.h>
```

Add an event handler to initiate the crop action and call the crop method on the image view.

``` objective-c
- (IBAction)crop:(UIButton *)sender {

UIImage* croppedImage; // = self.imageView.image;

croppedImage =  [self.imageView crop];

self.croppedView.image = croppedImage;
}
```

## Requirements

*MMSCropImageView requires iOS 9.0 or later.*

## Installation

MMSCropView is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod "MMSCropView"
```

## Author

William Miller, support@millermobilesoft.com

## Article

An article describing the implementation of the class:  [A View Class for Cropping Images](http://www.codeproject.com/Articles/1066191/A-View-Class-for-Cropping-Images).

## Contact

William Miller


<a href="https://github.com/miller-ms">
<img src="https://cloud.githubusercontent.com/assets/1567433/6521218/9c7e2502-c378-11e4-9431-c7255cf39577.png" height="44" hspace="2"/>
</a>
<a href="https://twitter.com/a_grebenyuk">
<img src="https://cloud.githubusercontent.com/assets/1567433/6521243/fb085da4-c378-11e4-973e-1eeeac4b5ba5.png" height="44" hspace="2"/>
</a>
<a href="https://www.linkedin.com/pub/alexander-grebenyuk/83/b43/3a0">
<img src="https://cloud.githubusercontent.com/assets/1567433/6521256/20247bc2-c379-11e4-8e9e-417123debb8c.png" height="44" hspace="2"/>
</a>

- http://github.com/miller-ms
- support@millermobilesoft.com

## License

This project is is available under the MIT license. See the LICENSE file for more info. Attribution by linking to the [project page](https://github.com/miller-ms/MMSCropView) is appreciated.

------------------

## MMSCropImageView
This class provides the feature to draw a rectangle over an image by dragging a finger over it, move it, and extract the covered region into a UIImage.

<p align="center">
<img src="Screenshot.png" alt="Sample">
</p>

A simple image cropper.

## Installation
*MMSCropImageView requires iOS 9.0 or later.*

## Basic Usage

In your storyboard select the custom class MMSCropImageView for the Image View widget.

Import the class header.

``` objective-c
#import <MMSCropImageView.h>
```

Add an event handler to initiate the crop action and call the crop method on the image view.

``` objective-c
- (IBAction)crop:(UIButton *)sender {

UIImage* croppedImage; // = self.imageView.image;

croppedImage =  [self.imageView crop];

self.croppedView.image = croppedImage;
}
```

## Demo

Build and run the `CropDemo` project in Xcode to see `MMSCropImageView` in action.

## Article

An article describing the implementation of the class:  [A View Class for Cropping Images](http://www.codeproject.com/Articles/1066191/A-View-Class-for-Cropping-Images).

## Contact

William Miller

- http://github.com/miller-ms
- support@millermobilesoft.com

## License

This project is is available under the MIT license. See the LICENSE file for more info. Attribution by linking to the [project page](https://github.com/miller-ms/MMSCropImageView) is appreciated.