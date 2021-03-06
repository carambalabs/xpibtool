xpibtool
================

[![Build Status](https://travis-ci.org/carambalabs/xpibtool.svg?branch=master)](https://travis-ci.org/carambalabs/xpibtool)

### Why this tool?
If you are building cross-platform frameworks, you can use macros in code to conditionally select the code you want to include depending on the platform. However, that's not possible with IB files. If you add a iOS Storyboard and you try to compile your framework for macOS, your framework **won't compile**. Thanks to this tool you can solve this issue. It'll copy and link only the `.xib` and `.storyboard` that match the platform you are building for.


### Setup
1. Install Swift if you didn't have it installed.
2. Git clone the repository `git clone git@github.com:carambalabs/xpibtool.git`
3. Build it using `swift build`
4. Voila :tada:

### References

- [ibtool](https://developer.apple.com/legacy/library/documentation/Darwin/Reference/ManPages/man1/ibtool.1.html)
- [Xcode & cross-platform frameworks](http://ilya.puchka.me/xcode-cross-platform-frameworks/)
- [Output](https://gist.github.com/fabiopelosin/4560417)
- [xcbuild compiler](https://github.com/facebook/xcbuild/tree/master/Specifications/Compiler)


### Thanks

- [Files](https://github.com/JohnSundell/Files) from [John Sundell](https://github.com/JohnSundell)
- [Commander](https://github.com/kylef/Commander) from [Kyle Fuller](https://github.com/kylef)
- [SwiftShell](https://github.com/kareman/SwiftShell) from [Kare Morstol](https://github.com/kareman)

## About

<img src="https://github.com/carambalabs/Foundation/blob/master/ASSETS/avatar_rounded.png?raw=true" width="70" />

This project is funded and maintained by [Caramba](http://caramba.io). We 💛 open source software!

Check out our other [open source projects](https://github.com/carambalabs/), read our [blog](http://blog.caramba.io) or say :wave: on twitter [@carambalabs](http://twitter.com/carambalabs).

## Contribute

Contributions are welcome :metal: We encourage developers like you to help us improve the projects we've shared with the community. Please see the [Contributing Guide](https://github.com/carambalabs/Foundation/blob/master/CONTRIBUTING.md) and the [Code of Conduct](https://github.com/carambalabs/Foundation/blob/master/CONDUCT.md).

## License

```
The MIT License (MIT)

Copyright (c) <2017> Caramba

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