# XYDebugView
XYDebugView is debug tool to draw the all view's frame in device screen and show it by 2d/3d style like reveal did.

## Use

```objective-c
// prepare debug function
[XYDebugViewManager sharedInstance].isDebugging = YES;

// close debug function
[XYDebugViewManager sharedInstance].isDebugging = NO;
```
**normal state**

![normal_image](https://github.com/ZhipingYang/XYDebugView/raw/master/picture/normal.jpg)

**debug 2d**

![debug_image](https://github.com/ZhipingYang/XYDebugView/raw/master/picture/debug.jpg)

**debug 3d**

![untitled](https://cloud.githubusercontent.com/assets/9360037/26644677/1df50532-4668-11e7-8423-27f3c9d1960a.gif)


## Installation

XYDebugView is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod "XYDebugView"
```

## Author

XcodeYang, xcodeyang@gmail.com

## License

XYDebugView is available under the MIT license. See the LICENSE file for more info.
