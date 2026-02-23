# Changelog
All notable changes to this project will be documented in this file.

The format is based on
[Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to
[Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added
### Changed
### Deprecated
### Removed
### Fixed
### Security


## [1.1.0] - 2026-02-23

### Changed
- `CHANGES.md` renamed to `CHANGELOG.md` following https://keepachangelog.com/en/1.1.0/
- The initial values of `currency` and `didec/currency-negative` are now set to `euro`.
  Previously, no currency symbol was used (in contrast to the tutorial and examples).
- The styles `german`, `english`, `french`, and `float`, which set `decimal-separator` 
  and `grouping-separator`, no longer modify currency settings.
  Previously, they removed currency settings, which was not obvious.
- Some stylistic revisions in the documentation.

### Fixed
- Documentation produced with `minted2` instead of `minted` (currently not compatible to Python>=3.14)
- Obsolete (and now faulty) package loading of `l3benchmark` removed from the documentation 
    (it is part of l3kernel since June 2025)



## [1.0.0] - 2024-02-28

### Added
- Initial public release


## [-.-.-]
- Not public releases
