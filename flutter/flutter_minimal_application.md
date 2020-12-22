# Flutter minimal application

```dart
import 'package:flutter/material.dart';

void main() {
  runApp(
    Center(
      child: Text(
        'Hello, world!',
        textDirection: TextDirection.ltr,
      ),
    ),
  );
}
```

### Minimal material app
```dart
import 'package:flutter/material.dart';

void main() {
  runApp(MaterialApp(
    home: Text('hey ninjas!')
  ));
}
```