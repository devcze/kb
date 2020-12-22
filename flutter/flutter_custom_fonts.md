# Flutter Custom fonts

* download ttf font
* create fonts folder
* put ttf font into font folder
* put font into pubspec.yaml

```yaml
  fonts:
    - family: Langar
      fonts:
        - asset: fonts/Langar-Regular.ttf
```
* pub get to update dependencies
* use font
```dart
style: TextStyle(
  fontFamily: 'Langar'
  )
```