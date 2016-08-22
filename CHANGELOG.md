# Change Log

All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]
### Changed
- [SPEC] add "exec" and "http" log types.

## [1.1.0] - 2016-08-22
### Changed
- `Logger.Writer`: fixed a minor bug.
- "id" log field is renamed to "request_id" (API is not changed).

## [1.0.1] - 2016-08-20
### Changed
- [Logger.Writer](https://godoc.org/github.com/cybozu-go/log#Logger.Writer) is rewritten for better performance.

[Unreleased]: https://github.com/cybozu-go/log/compare/v1.1.0...HEAD
[1.1.0]: https://github.com/cybozu-go/log/compare/v1.0.1...v1.1.0
[1.0.1]: https://github.com/cybozu-go/log/compare/v1.0.0...v1.0.1