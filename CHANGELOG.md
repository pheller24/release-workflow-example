# Changelog

All notable changes to this SDK will be documented in this file.

Only major releases are expected and allowed to break backward compatibility. Minor releases may introduce new features,
but must do so without breaking the existing API. We also provide deprecation message triggered in the code base to help
you with the migration process across major releases.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [43.0.0] - 2022-11-14

## [23.0.22] - 2020-02-02

### Added

-   Deprecated methods now triggers deprecations (via symfony/deprecation-contracts) with #48
-   RenderResponse allows to get Response HTTP Status Code with #47

### Changed

-   MagicClassWidgetDataProvider is deprecated and will be removed with v25.x

### Fixed

-

## [23.0.1] - 2022-08-01

### Fixed

-   <https://digistore.atlassian.net/browse/PGB-2991>

## [23.0.0] - 2022-07-26

### Added

-   OCB-7125: provide version hash to parent application by @pheller24 in #36
-   Allow to pass any context to render\_ methods that can be used in \_DataProviders

### Changed

-   PGB-2976: improve sdk rendering by @pheller24 in #35
-   render method is split to different methods
-   Mode-Configuration has moved to seperate \*Config classes
-   The interface Locale was changed to be usable with PHP8 enums

### Removed

-   locales was removed from RenderMode
    -   This was used for editor only, and now is part of EditorConfig::\_\_construct(...)
-   Disabled method chaining

[Unreleased]: https://github.com/workflow-playground/release-workflow-example/compare/43.0.0...HEAD

[43.0.0]: https://github.com/workflow-playground/release-workflow-example/compare/23.0.22...43.0.0

[23.0.22]: https://github.com/workflow-playground/release-workflow-example/compare/23.0.1...23.0.22
