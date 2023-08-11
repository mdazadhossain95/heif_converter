# HEIF Converter

Flutter plugin to convert HEIC/HEIF file to PNG/JPEG image.

## Installation

Add the Package

```yaml
dependencies:
  heif_converter: ^lastVersion
```

## How to use

Import the package in your dart file

```dart
import 'package:heif_converter/heif_converter.dart';
```

And call convert method with local HEIC/HEIF image file path.

```dart
final _heifConverterPlugin = HeifConverter();
String jpgPath = await _heifConverterPlugin.convert(heicPath, output: jpgPath);
String pngPath = await _heifConverterPlugin.convert(heicPath, format: 'png');
```
