# Changelog

## [1.11.0] - 2026-08-14

### Added

- [`async_return_with_no_await`]
- [`empty_container_bodies`]
- [`initialize_in_field_declaration`]
- [`migrate_design_widgets`]
- [`no_dynamic_casts`]
- [`no_raw_types`]
- [`unnecessary_const_in_enum_constructor`]
- [`unnecessary_primary_constructor_body`]
- [`unnecessary_type_name_in_constructor`]
- [`use_declaring_parameters`]

### Changed

- Bump minimum Dart SDK to 3.13.0.

### Removed

- `strict-casts` analyzer option, replaced by [`no_dynamic_casts`].
- `strict-raw-types` analyzer option, replaced by [`no_raw_types`].
- Deprecated [`avoid_private_typedef_functions`].
- Deprecated [`one_member_abstracts`].
- Deprecated [`unnecessary_await_in_return`].

## [1.10.0] - 2026-05-21

### Added

- [`simple_directive_paths`]
- [`var_with_no_type_annotation`]

### Changed

- Bump minimum Dart SDK to 3.12.0.

## [1.9.1] - 2026-03-03

### Fixed

- Remove the non-existing `non_nullable_equals_parameter` lint.

## [1.9.0] - 2026-02-19

### Added

- [`simplify_variable_pattern`]

### Changed

- Bump minimum Dart SDK to 3.11.0.

### Removed

- Deprecated [`avoid_null_checks_in_equality_operators`].
- Deprecated [`prefer_final_parameters`].
- Deprecated [`use_if_null_to_convert_nulls_to_bools`].

## [1.8.0] - 2025-11-14

### Added

- [`remove_deprecations_in_breaking_versions`].

### Changed

- Bump minimum Dart SDK to 3.10.0.

### Removed

- Analyzer `errors` and `exclude` sections from the lint configuration.

## [1.7.0] - 2025-08-15

### Added

- [`switch_on_type`]
- [`unnecessary_unawaited`]

### Changed

- Bump minimum Dart SDK to 3.9.0.

## [1.6.0] - 2025-05-23

### Added

- [`use_null_aware_elements`]
- [`unnecessary_ignore`]

### Changed

- Bump minimum Dart SDK to 3.8.0.

## [1.5.0] - 2025-02-14

### Added

- [`strict_top_level_inference`]
- [`unnecessary_async`]
- [`unnecessary_underscores`]

### Changed

- Bump minimum Dart SDK to 3.7.0.

### Removed

- [`package_api_docs`]

## [1.4.0] - 2024-12-15

### Added

- [`avoid_futureor_void`]
- [`omit_obvious_local_variable_types`]
- [`use_truncating_division`]

### Changed

- Bump minimum Dart SDK to 3.6.0.

### Removed

- [`unsafe_html`]

## [1.3.0] - 2024-12-15

### Added

- [`document_ignores`]
- [`invalid_runtime_check_with_js_interop_types`]
- [`unintended_html_in_doc_comment`]

### Changed

- Bump minimum Dart SDK to 3.5.0.

## [1.2.0] - 2024-07-04

### Added

- [`unnecessary_library_name`]
- [`missing_code_block_language_in_doc_comment`]

### Changed

- Bump minimum Dart SDK to 3.4.0.
- Disable [`prefer_int_literals`].

## [1.1.0] - 2023-11-23

### Added

- [`annotate_redeclares`]

### Changed

- Bump minimum Dart SDK to 3.2.0.

## [1.0.0] - 2023-09-10

### Added

- Initial release.

[unreleased]: https://github.com/charlescyt/choco_lints/compare/v1.11.0...HEAD
[1.11.0]: https://github.com/charlescyt/choco_lints/compare/v1.10.0...v1.11.0
[1.10.0]: https://github.com/charlescyt/choco_lints/compare/v1.9.1...v1.10.0
[1.9.1]: https://github.com/charlescyt/choco_lints/compare/v1.9.0...v1.9.1
[1.9.0]: https://github.com/charlescyt/choco_lints/compare/v1.8.0...v1.9.0
[1.8.0]: https://github.com/charlescyt/choco_lints/compare/v1.7.0...v1.8.0
[1.7.0]: https://github.com/charlescyt/choco_lints/compare/v1.6.0...v1.7.0
[1.6.0]: https://github.com/charlescyt/choco_lints/compare/v1.5.0...v1.6.0
[1.5.0]: https://github.com/charlescyt/choco_lints/compare/v1.4.0...v1.5.0
[1.4.0]: https://github.com/charlescyt/choco_lints/compare/v1.3.0...v1.4.0
[1.3.0]: https://github.com/charlescyt/choco_lints/compare/v1.2.0...v1.3.0
[1.2.0]: https://github.com/charlescyt/choco_lints/compare/v1.1.0...v1.2.0
[1.1.0]: https://github.com/charlescyt/choco_lints/compare/v1.0.0...v1.1.0
[1.0.0]: https://github.com/charlescyt/choco_lints/releases/tag/v1.0.0
[`annotate_redeclares`]: https://dart.dev/lints/annotate_redeclares
[`async_return_with_no_await`]: https://dart.dev/lints/async_return_with_no_await
[`avoid_futureor_void`]: https://dart.dev/lints/avoid_futureor_void
[`avoid_null_checks_in_equality_operators`]: https://dart.dev/lints/avoid_null_checks_in_equality_operators
[`avoid_private_typedef_functions`]: https://dart.dev/lints/avoid_private_typedef_functions
[`document_ignores`]: https://dart.dev/lints/document_ignores
[`empty_container_bodies`]: https://dart.dev/lints/empty_container_bodies
[`initialize_in_field_declaration`]: https://dart.dev/lints/initialize_in_field_declaration
[`invalid_runtime_check_with_js_interop_types`]: https://dart.dev/lints/invalid_runtime_check_with_js_interop_types
[`migrate_design_widgets`]: https://dart.dev/lints/migrate_design_widgets
[`missing_code_block_language_in_doc_comment`]: https://dart.dev/lints/missing_code_block_language_in_doc_comment
[`no_dynamic_casts`]: https://dart.dev/lints/no_dynamic_casts
[`no_raw_types`]: https://dart.dev/lints/no_raw_types
[`omit_obvious_local_variable_types`]: https://dart.dev/lints/omit_obvious_local_variable_types
[`one_member_abstracts`]: https://dart.dev/lints/one_member_abstracts
[`package_api_docs`]: https://dart.dev/lints/package_api_docs
[`prefer_final_parameters`]: https://dart.dev/lints/prefer_final_parameters
[`prefer_int_literals`]: https://dart.dev/lints/prefer_int_literals
[`remove_deprecations_in_breaking_versions`]: https://dart.dev/lints/remove_deprecations_in_breaking_versions
[`simple_directive_paths`]: https://dart.dev/lints/simple_directive_paths
[`simplify_variable_pattern`]: https://dart.dev/lints/simplify_variable_pattern
[`strict_top_level_inference`]: https://dart.dev/lints/strict_top_level_inference
[`switch_on_type`]: https://dart.dev/lints/switch_on_type
[`unintended_html_in_doc_comment`]: https://dart.dev/lints/unintended_html_in_doc_comment
[`unnecessary_async`]: https://dart.dev/lints/unnecessary_async
[`unnecessary_await_in_return`]: https://dart.dev/lints/unnecessary_await_in_return
[`unnecessary_const_in_enum_constructor`]: https://dart.dev/lints/unnecessary_const_in_enum_constructor
[`unnecessary_ignore`]: https://dart.dev/lints/unnecessary_ignore
[`unnecessary_library_name`]: https://dart.dev/lints/unnecessary_library_name
[`unnecessary_primary_constructor_body`]: https://dart.dev/lints/unnecessary_primary_constructor_body
[`unnecessary_type_name_in_constructor`]: https://dart.dev/lints/unnecessary_type_name_in_constructor
[`unnecessary_unawaited`]: https://dart.dev/lints/unnecessary_unawaited
[`unnecessary_underscores`]: https://dart.dev/lints/unnecessary_underscores
[`unsafe_html`]: https://dart.dev/lints/unsafe_html
[`use_declaring_parameters`]: https://dart.dev/lints/use_declaring_parameters
[`use_if_null_to_convert_nulls_to_bools`]: https://dart.dev/lints/use_if_null_to_convert_nulls_to_bools
[`use_null_aware_elements`]: https://dart.dev/lints/use_null_aware_elements
[`use_truncating_division`]: https://dart.dev/lints/use_truncating_division
[`var_with_no_type_annotation`]: https://dart.dev/lints/var_with_no_type_annotation
