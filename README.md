# Choco Lints

Custom lint rules for Dart and Flutter.

## Usage

To use `choco_lints` in your project, follow these steps:

1. Add `choco_lints` as a dev dependency in your `pubspec.yaml` file:

```yaml
dev_dependencies:
  choco_lints:
    git:
      url: https://github.com/charlescyt/choco_lints.git
      ref: 1.6.0 # specify version here
```

2. Include `choco_lints/app.yaml` or `choco_lints/package.yaml` in your `analysis_options.yaml` file:

```yaml
include: package:choco_lints/app.yaml
or
include: package:choco_lints/package.yaml
```
