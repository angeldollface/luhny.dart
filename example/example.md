# EXAMPLE FOR HARPO

Here is the example's `pubspec.yml`:
```YAML
name: test
description: A test app for Luhny.dart!
version: 1.0.0
homepage: https://github.com/angeldollface/luhny
publish_to: none
environment:
  sdk: '>=2.12.0 <3.0.0'
dependencies:
  harpo:
    git: git://github.com/angeldollface/luhny.dart.git
```

Here is the example itself:

```dart
/*
LUHNY.DART by Alexander Abraham, a.k.a. "Angel Dollface".
Licensed under the MIT license.
*/

// You could also just copy and paste any of the functions
// from the docs and use Luhny.dart like this:
import 'package:luhny/luhny.dart';

void main() {
  String testIMEI = '353879234252633';
  print(validateIMEI(testIMEI));
}

// Run it with "dart myprogram.dart".
```