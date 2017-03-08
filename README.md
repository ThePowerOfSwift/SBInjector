# SBInjector

This framework is a minimal dependency injection framework for macOS and iOS. It injects properties into (NS|UI)ViewControllers loaded from a storyboard.

Both [Typhoon](http://typhoonframework.org) and [Swinject](https://github.com/Swinject/Swinject) are way more complicated than what I needed. Also, Swinject can't inject into subclasses, and it would require a pretty massive rewrite to support that.

This project was developed on macOS 10.12 using Xcode 8.3. It is written in Swift 3, using Objective-C only for the swizzling the view controllers.

