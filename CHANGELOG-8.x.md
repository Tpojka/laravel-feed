# Change log


## v8.0.2 (2026-08-21)


### Fixed

- Restored the `add()` convenience method (dropped in v8.0.1), used directly by
  packages such as `WebDevEtc\BlogEtc`. It now delegates to `addItem()` instead
  of duplicating its shortening/sanitization logic.


## v8.0.1 (2020-09-12)


### Added

- Added support for Laravel 8
- Added new branch for development ``8.x-dev``
