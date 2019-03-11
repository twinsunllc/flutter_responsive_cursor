# Flutter Responsive Cursor

## About

A replacement for Flutter's EditableText with native-like cursor behavior.
The cursor stays on while typing and fades in and out rather than blinking.

## Usage

```dart
import 'package:flutter_responsive_cursor/flutter_responsive_cursor.dart';

var _controller = TextEditingController();

ResponsiveCursorEditableText(
    controller: _controller,
    cursorColor: Colors.lightBlue,
    focusNode: FocusNode(),
    style: Theme.of(context).textTheme.body1,
);

ResponsiveCursorTextField(
    cursorColor: Colors.lightBlue,
    style: Theme.of(context).textTheme.body1,
);
```
