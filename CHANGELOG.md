# Changelog

## [1.0.2] - 2026-09-06
### Changed
- LoginForm format to json:UTF-8 (version 483 format)
- Endpoint from /login to /auth/login (version 483 endpoint)

### Added
- Fallback to 204 no content (483 change)

## [1.0.1] - 2026-04-01
### Added
- Support for configuring the max in-memory size for the `WebClient` buffer to support fetching query JSONs larger than 256 KB. 
