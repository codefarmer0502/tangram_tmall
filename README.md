# Attention. This project is not maintained any more !!!

# Tangram for Android

[中文文档](README-ch.md)

## Projects of Tangram

### Android

+ [Tangram-Android](https://github.com/alibaba/Tangram-Android)
+ [Virtualview-Android](https://github.com/alibaba/Virtualview-Android)
+ [vlayout](https://github.com/alibaba/vlayout)
+ [UltraViewPager](https://github.com/alibaba/UltraViewPager)

### iOS

+ [Tangram-iOS](https://github.com/alibaba/Tangram-iOS)
+ [Virtualview-iOS](https://github.com/alibaba/VirtualView-iOS)
+ [LazyScrollView](https://github.com/alibaba/lazyscrollview)

Tangram is a modular UI solution for building native page dynamically including Tangram for Android, Tangram for iOS and even backend CMS. This project provides the sdk on Android which is based on [vlayout](https://github.com/alibaba/vlayout) and [UltraViewPager](https://github.com/alibaba/UltraViewPager).

# Features
Warning please not use class under tangram3 package!
Tangram 3.0 is developing, we add tangram3 package and reserve tangram package for compatible. Tangram3 is on beta and use on official app is not recommend.

- Two platform support (iOS & Android, See [Tangram-iOS](https://github.com/alibaba/Tangram-iOS) in Github for iOS Version)
- Fast Generate View by JSON Data , provide default parser.
- Easily control the reuseability of views
- Provide multiple Built-in layouts
- Custom layout style (by JSON Data or code)
- High performance (Base on [vlayout](https://github.com/alibaba/vlayout))
- Extendable API

# demo

![](docs/images/tangramdemo.gif)

# Basic Concepts
+ Card, a group of cells, is responsible for layouting child cells.
+ Cell, smallest business UI element, like an item in RecyclerView.

# Default cards
* Flow Card（like grid）
* Linear Card
* Fix Card
* Scroll Fix Card
* Sticky Card
* One drag N Card
* Page Scroll Card
* Water Flow Card
* Dragable Card

# Get started
See details at [Tutorial](docs/Tutorial.md).

# Tangram Documents

See complete [documents](http://tangram.pingguohe.net/) here.

# Contributing

Before you open an issue or create a pull request, please read [Contributing Guide](CONTRIBUTING.md) first.

# LICENSE
Tangram is available under the MIT license.

# WeChatGroup

![](https://img.alicdn.com/tfs/TB11_2_kbSYBuNjSspiXXXNzpXa-167-167.png)

Search `tangram_` or scan the QR code above to be invited in WeChat.
