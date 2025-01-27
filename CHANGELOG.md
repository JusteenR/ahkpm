# Changelog

## 0.5.0

- ahkpm now supports version ranges such as `1.x.x`.
- `ahkpm install` now makes the smallest possible change to the dependency tree
- Added a new `ahkpm version` command to bump package version
- `ahkpm install` now supports specifying multiple dependencies
- Added support for `gh:` shorthand for GitHub dependencies in `ahkpm install` and `ahkpm update`
- Added `ahkpm list` to display table of top level dependencies
- The command to get the version of ahkpm has moved. Now use `ahkpm --version` instead of `ahkpm version`

## 0.4.0

- Added `ahkpm update` to update package(s) to latest allowed version
- Fixed a bug where the local package cache was taking precedence over the remote
- `ahkpm version` now also attempts to display the version of AutoHotkey installed
- Set up a new documentation site at [ahkpm.dev][https://ahkpm.dev].

## 0.3.0

- Resolve transitive dependencies
- Add `ahkpm.lock` to prevent unexpected code changes in dependencies
- Validate dependency arguments passed to `ahkpm install`

## 0.2.0

- Remove some unnecessary binary bloat
- Add `ahkpm version` command
- Make ahkpm available with a Windows installer
- Fix GitHub url validation
- Add friendly error messages if package or version can't be found

## 0.1.0

- Initial version