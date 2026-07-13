# Changelog

All notable changes to this project will be documented in this file.
New entries are generated automatically by [Release Please](https://github.com/googleapis/release-please)
from [Conventional Commits](https://www.conventionalcommits.org/); this project
adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.1.0](https://github.com/eiserv/easySFTP/compare/v1.0.0...v1.1.0) (2026-07-13)


### Features

* enhance configuration management with YAML support ([60e8655](https://github.com/eiserv/easySFTP/commit/60e8655048af799553a81ec1677baf5a7b1ffae9))
* enhance file upload with atomic rename and error handling ([9669ad0](https://github.com/eiserv/easySFTP/commit/9669ad005fccdf80e0f7f489e436d4fb863b1d1e))

## [1.0.0] - 2026-07-13

### Added

- Initial release
- Recursive directory and single-file uploads via `local => remote` mappings
- Password and private-key authentication (with optional passphrase)
- Optional host key pinning via SHA256 fingerprint
- Gitignore-style exclude patterns (`ignore` input and `ignore-from` file)
- Delete mode for clean deploys
- Dry-run mode
- Parallel uploads (`concurrency`) and per-file retries with backoff (`retries`)
- Step outputs (`files-uploaded`, `files-deleted`, `bytes-uploaded`, `duration-ms`) and a job summary
- Support for Linux, macOS and Windows runners

[1.0.0]: https://github.com/eiserv/easySFTP/releases/tag/v1.0.0
