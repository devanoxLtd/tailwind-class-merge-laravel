# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## v1.2.0 (2024-01-01)
### Fixed
- `withoutForAttributes` only removes `for` attribute eg. `icon:class` will remove `for` attribute but not remove `:class`

## v1.1.1 (2023-12-27)
### Changed
- Update forAttributes now you can use attributes like `icon:class`

## v1.1.0 (2023-12-26)
### Added
- Add `forAttributes` and `withoutForAttributes` on the ComponentAttributesBag to allow merging of attributes with and without `for` attribute
### Removed
- Remove `tailwindClassFor` and `withoutTailwindMergeClasses` from the ComponentAttributesBag

## v1.0.1 (2023-12-09)
### Fixed
- `tailwindClass` not working sometimes

## v1.0.0 (2023-12-09)
### Added
- Add cache support
- Add `tailwindClassFor` and `withoutTailwindMergeClasses` on the ComponentAttributesBag

### Changed
- Add empty `classGroups` configuration

### Docs
- Add documentation for configuration
- Add documentation for `tailwindClassFor()`

### Fixed
- Revert the behaviour of `tailwindClass`
- Remove DeferrableProvider - fixes

## v0.0.1 (2023-08-07)
### Added
- First version
