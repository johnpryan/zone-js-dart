# zone_js_dart

An experimental package:js facade for zone.js

Includes the latest zone.js release available on 12/21/2016

## Usage

experimental.

## Generating

```
dart_js_facade_gen lib/zone.js.d.ts > lib/zone_js.dart
```

modifications need to be made to work with the analyzer.  `Zone` is both a class
and a getter as defined in the .d.ts file

## Features and bugs

Please file feature requests and bugs at the [issue tracker][tracker].

[tracker]: https://github.com/johnpryan/zone-js-dart/issues
