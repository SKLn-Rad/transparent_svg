# transparent_svg

This is to be used with the flutter_svg package seen here: https://pub.dev/packages/flutter_svg  
It performs the same as https://pub.dev/packages/transparent_image but for SVG images!  

This way you can ternary new SVG images in as you load them from memory.  

For example:
```dart
FlutterSvg.memory(isLoaded ? kActualImage : kTransparentSvg)
```

Just call kTransparentSvg where you need it!
