# Flutter Widgets
Basic building blocks

### Basic Structure (Widget Tree)
* Root Widget
  * App Bar Widget
    * Text Widget
  * Container Widget
    * Text Widget
    
### Widget Examples
* Text Widget
* Button Widget
* Row Widget
* Column Widget
* Image Widget

### Widget Properties
Text Widget
* style, textAlign, overflow, maxLines, etc.

Button Widget
* color, elevation, disabledColor, enabled, etc.

Scaffold Widget 
* wrapper to few basic layout widgets (appBar, body, floatingActionButton)
```dart
import 'package:flutter/material.dart';

void main() {
  runApp(MaterialApp(
    home: Scaffold(
      appBar: AppBar(
        title: Text('App'),
        centerTitle: true,
      ),
      body: Center(child: Text('Body text')),
      floatingActionButton: FloatingActionButton(
        child: Text('Click')
      ),
    ),
  ));
}
```

Styled 
```dart
void main() {
  runApp(MaterialApp(
    home: Scaffold(
      backgroundColor: Colors.black,
      appBar: AppBar(
        title: Text('App'),
        centerTitle: true,
        backgroundColor: Colors.green,
      ),
      body: Center(child: Text('Body text')),
      floatingActionButton: FloatingActionButton(
        child: Text('Click'),
        backgroundColor: Colors.green,
      ),
    ),
  ));
}
```
