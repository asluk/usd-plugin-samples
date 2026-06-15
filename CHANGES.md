# Changelog

## 5.0.0

- Deprecated repository; preserved as a conceptual reference only,
  no longer actively maintained against current OpenUSD or Kit versions
- Removed `src/kit-extension` (targeted an outdated Kit version)
- Removed Kit/Omniverse-specific packaging instructions from build docs

## 4.0.0

- Simplified build infrastructure such that standard tooling is used
  everywhere except pulling down packman packages
- Eliminated repo-tooling based generators

## 3.0.0

- Added several examples for Hydra 2 scene index plugins
- Fixed issue in build plugInfo.json file configuration for debug builds
- Updated dependencies to stock USD 23.05
- Updated openssl and libcurl dependencies

## 2.0.0

- Added support for general USD plugins beyond schemas
- Updated repo_usd to support flexible build files
- Updated dependencies to USD 22.11 and Python 3.10
- Added sample for dynamic payloads and file format plugins

## 1.0.0

- Initial open source release