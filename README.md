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
      ref: v1.12.0 # specify version here
```

2. Include `choco_lints/app.yaml` or `choco_lints/package.yaml` in your `analysis_options.yaml` file:

```yaml
include: package:choco_lints/app.yaml
```

or

```yaml
include: package:choco_lints/package.yaml
```

## Excluding files from analysis

To skip paths during static analysis, add an `analyzer.exclude` list. Entries
can be individual files or glob patterns, relative to the directory that
contains `analysis_options.yaml`.

## Configuring `dart format`

A `formatter` section configures `dart format`. `page_width` is the preferred
line length (default 80). `trailing_commas` is `automate` (default: add or
remove commas based on whether a construct splits) or `preserve` (a trailing
comma forces a split; the formatter will not remove one).

## Example

```yaml
include: package:choco_lints/app.yaml

analyzer:
  exclude:
    - build/**
    - android/**
    - ios/**
    - web/**
    - windows/**
    - macos/**
    - linux/**

formatter:
  page_width: 120
  trailing_commas: preserve
```
