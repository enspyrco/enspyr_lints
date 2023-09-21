# enspyr_lints

This package contains a recommended set of lints for Enspyr projects (apps/packages/plugins). Selected lints have been added to [lints] for Dart projects and [flutter_lints] for Flutter projects.

Discussion of the selection of lints can be found in [enspyr_lints].

## Usage

### pubspec

In `pubspec.yaml` replace

```yaml
flutter_lints: ^x.y.z # Flutter
# or
lints: ^x.y.z # Dart
```

with

```yaml
enspyr_lints: ^0.0.0-a1
```

### analysis_options

Replace the contents of `analysis_options.yaml` file with:

```yaml
include: package:enspyr_lints/flutter.yaml # Flutter
# or
include: package:enspyr_lints/dart.yaml # Dart
```

[lints]: https://pub.dev/packages/lints
[flutter_lints]: https://github.com/flutter/packages/tree/master/packages/flutter_lints
[enspyr_lints]: https://www.notion.so/enspyrco/enspyr_lints-f98509874a044800805fc6869e00877d
