# Change Log
All notable changes to this project will be documented in this file.

## master - unreleased
### Changed
- Introduced `ConfigFor.load_config!` that raises exception when environment is missing
- Both integrations will raise exception when environment is missing

## 0.1.2 - 2014-10-29

### Changed
- Loading config for unknown env does not raise exception but returns an empty hash

## 0.1.1 - 2014-10-29

### Changed
- Passing a Symbol as env works
- Loads indifferent_access core extension

## 0.1.0 - 2014-10-03

### Added
- Rails integration
- Sinatra Integration
- Capistrano Integration
