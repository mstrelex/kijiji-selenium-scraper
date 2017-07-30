# Changelog
All notable changes to this project will be documented in this file.

## [Unreleased]

## [0.3.1] - 2017-07-30
### Fixed
- Driver init via Selenium server return null and break flow
- Maximizing window in headless mode causes a failure

## [0.3] - 2017-07-30
### Added
- Added support for multi-execution

## [0.2.2] - 2017-07-26
### Added
- Optional argument to select driver

## [0.2.1] - 2017-07-22
### Added
- Optional argument to ignore ads with zero or no visits

### Fixed
- Exception thrown when no header is found

## [0.2] - 2017-07-21
### Added
- Selenium Server support
- Visitors converted to integer, removing all other chars

### Changed
- Fixed typos

## [0.1.1] - 2017-07-20

### Changed
- Driver is restarted every 20 ads
- Timeout lowered to 60 seconds

## [0.1] - 2017-07-19

Initial release.

Main features:

- Scrap Kijiji Ads building dynamic fields
- Save extracted data in Excel
- Send excel file by email