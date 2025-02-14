# THIS IS A FORK FROM [Flutter Crop](https://github.com/xclud/flutter_crop)!
# THIS PROJECT IS NO LONGER MAINTAINED. USE [Flutter Crop](https://github.com/xclud/flutter_crop)!

# cropper
[![pub package](https://img.shields.io/pub/v/crop.svg)](https://pub.dartlang.org/packages/crop)

A Flutter package for cropping any widget, not only images. This package is entirely written in Dart and supports Android, iOS, Web and Desktop. Also, because of being independent from native platform, it does not increase size of your apps output (e.g. apk).

## Supported platforms

* Flutter Android
* Flutter iOS
* Flutter Web (as of 2020 Nov 24)*
* Flutter Desktop

> \* In order to run Crop on web correctly, flutter version
> `1.24.0-8.0.pre.359` or above is needed (master channel) and you need
> to enable CanvasKit/Skia when compiling: `flutter build web
> --dart-define=FLUTTER_WEB_USE_SKIA=true`

[Web Demo](https://xclud.github.io/flutter_crop/) | [Install from Google Play](https://play.google.com/store/apps/details?id=dev.pub.crop.app)

![Screenshot](doc/screenshot01.png)

## Getting Started

In your `pubspec.yaml` file add:

```dart
dependencies:
  cropper: any
```
Then, in your code import:
```dart
import 'package:cropper/cropper.dart';
```
Now in build function, put a `Crop` widget in the widget tree and you are done. Please don't forget to check ```/example``` folder, there is much more.
