# LUHNY.DART :iphone: :lock: :dart:

[![GitHub CI](https://github.com/angeldollface/luhny.dart/actions/workflows/dart.yml/badge.svg)](https://github.com/angeldollface/luhny.dart/actions)

***A Dart package to validate IMEI numbers of mobile devices. :iphone: :lock: :dart:***

## ABOUT :books:

I implemented some libraries to validate IMEI numbers using the Luhn algorithm in Javascript and Rust recently. This implementation is the Dart implementation of the Luhn algorithm. Enjoy. :heart:

## LINKS :earth_americas:

- Library implementation in ECMA Script: [VIEW](https://github.com/angeldollface/luhny)
- Library implementation in Rust: [VIEW](https://github.com/angeldollface/luhny.rs)
- Web app implementation in Vue.js: [VIEW](https://github.com/angeldollface/ceramic)
- Web app implementation in Yew.rs: [VIEW](https://github.com/angeldollface/ceramic.rs)

## INSTALLATION :inbox_tray:

### Adding to your project

To add Harpo to your project's dependencies, add this to your project's `pubspec.yml`:

```YAML
dependencies:
  ...
  harpo:
    git: git://github.com/angeldollface/luhny.dart.git
```

The three dots represent anything else that you might have in the `dependencies` section.
Having done that, re-fetch your project's dependencies by running this in the project's root directory:

```bash
$ dart pub get
```

## USAGE :hammer:

### Importing

Import all functions like this:

```dart
import 'package:harpo/luhny.dart';
```

### APIs

To inspect the available APIs, read the source code, please. I've split everything by subject so it should be easy to understand.

## NOTE :scroll:

- *Luhny.dart :iphone: :lock: :dart:* by Alexander Abraham :black_heart: a.k.a. *"Angel Dollface" :dolls: :ribbon:*
- Licensed under the MIT license.