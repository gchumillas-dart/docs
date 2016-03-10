# docs
Docs

## Imports

```dart
// imports native library
import 'dart:<library>';
// imports project library
import 'package:<project-name>/path/to/file.dart';
```

Notes:

1. `project-name` is defined in `pubspac.yaml`.
2. `pub get` creates a `.packages` file. Remove it and execute `pub get` again if you have changed `pubspec.yaml`.
3. `package:<project-name>/path/to/file.dart` refers to `lib/path/to/file.dart`.
