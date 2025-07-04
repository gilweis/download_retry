# Changelog

All notable changes to this project will be documented in this file.

## [0.1.0] - 2025-07-04
### Added
- Initial release of `download_retry.py` tool
- Supports retry downloading binary file with configurable retry interval and timeout
- Default skips SSL certificate verification with optional `--insecure` flag
- Command line interface with arguments for URL, delta_t, max_t, output file
- Returns exit codes 0 (success) and 1 (failure)
- Included tests and packaging files
- README and LICENSE added
