# Change Log

The change log describes what is "Added", "Removed", "Changed" or "Fixed" between each release.

## 0.4.0

### Changed

- Skip creation of translations that are the same as their key 
- Bumped version of php-translation/symfony-storage

## 0.3.1

### Fixed

- Fixed bug when Translation not found. `Loco::get` should not throw exception.

## 0.3.0

### Changed

- Only export translated strings

## 0.2.1

### Added

- Add the translation parameters as "Notes" in Loco.

## 0.2.0

### Added

- Added support for `TransferableStorage`

### Changed

- `Loco::getApiKey()` is now private

## 0.1.0

Init release
