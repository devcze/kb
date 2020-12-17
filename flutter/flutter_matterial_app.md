# Flutter Material app
Application uses material design

```dart
import 'package:flutter/material.dart';

void main() {

  runApp(MaterialApp(
    routes: <String, WidgetBuilder>{
      '/': (BuildContext context) {
        return Scaffold(
          appBar: AppBar(
            title: const Text('Home Route'),
          ),
        );
      },
      '/about': (BuildContext context) {
        return Scaffold(
          appBar: AppBar(
            title: const Text('About Route'),
          ),
        );
      }
    },
  ));
}
```

